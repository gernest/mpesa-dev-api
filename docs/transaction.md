# Transaction Interface Specifications 

**Introduction**

All Organizations on M-Pesa can get data extracts of all the transactions that occurred on a specific day from the Broker SFTP server. This is the process to follow to access the data extracts.

| **Action** | **Responsibility** |
| --- | --- |
|1. Establish connectivity the Broker SFTP server (See access IP's below) | 3rd Party and Vas Support team |
|1. Provide a list of Organisation short codes and Broker SPID. If the Organisation does not have a Broker SPID the SPID will be created. | 3rd Party |
| 1. Create Broker SPID, 3rd party SFTP profile and append the short codes to the account | Vas Support team |
| 1. Access the data extracts| 3rd Party |

# Access IP'S

**P2P Connection**

192.168.9.36

192.168.9.37

**IT VPN**

196.201.214.95

196.201.214.94

Port 15423

# Transactions Extract

**Introduction** 

This data feed includes all transactions (completed, failed, declined, cancelled, expired, excluding intermediate status) in the M-PESA system within the extraction period. This data feed is required to be extracted every day.

** File Generation Frequency and Scheduled Task**

The Mobile Money system will extract corresponding information of all transactions and send the CSV payload file every day.

A new scheduled task (based on exiting G2 platform system task plan capability) will be configured in the SP portal of Mobile Money system to perform the Organization Transaction extraction processing every day. After the process is completed, the extracted data will be packaged into a CSV payload file which is transmitted to the SFTP server within the Mobile Money system. The scheduled task can also be triggered manually when it is required to be performed immediately or the automatic task fails.

### Payload File Format

** File Name Format **

The format of the file name will be with timestamp which is the payload file generation time on SFTP server within the Mobile Money platform.

Example of File Name Format for Organization Transaction:

`_MPESA\_ShortCode\_{YYYYMMDDHh24mmss}.csv_`

Example of a file name:

`_MPESA\_000001\___20111013012608.csv_`

File name format description:

| **Field** | **Description** |
| --- | --- |
| File Prefix | Indicates the prefix of the file name and refers to the contents in the file. The file prefix is always _MPESA\_Shortcode\__. |
| YYYYMMDD | Indicates the date when the file is generated. |
| Hh24mmss | Indicates the time when the file is generated. |
| File Suffix | Indicates the type of the file. For payload file will always be .csv |

The timestamp format requirements in filename are shown in the following table:

| **Time** | **Format** | **Example** |
| --- | --- | --- |
| Year | YYYY | 2014 |
| Month | MM | 02 |
| Date | DD | 19 |
| Hour | Hh24 | 23 |
| Minute | mm | 42 |
| Second | ss | 23 |

# Content Format

A sample file of complete contents is shown as below:

```sh
_#RECEIPT\_NUMBER,DATE1,DETAILS,STATUS,WITHDRAW\_AMOUNT,PAID\_IN\_AMOUNT,BALANCE,BALANCE\_CONFIRMED,TRANSACTION\_TYPE,OTHERPARTYINFO,TRANSACTIONPARTYDETAILS,TRANSACTION\_ID,REMARK # head line_

_"JEK4FESX2M","2015-05-20 23:38:33","Business Payment to 254717267846 - FAITH NDWIGA via
API","Completed","4,029","0","5,924,891","true","B2C Payment 254717267846 – FAITHNDWIGA","","JEK4FESX2M","0"_
``` 
# The description of the CSV payload file content format is as follows:

- The file is a CSV file format.
- Each record ends with a carriage return character.
- The headline should be the title columns. The field name in the header in based on Data field but not the above example file.
- Each record occupies one line.
- Fields in the file are separated by comma (,).
- Fields' values in the file should be encapsulated by double quotes. The encapsulation will not be done on the file headers and footers where they exist.
- The values of certain fields can be blank, and these values must still be encapsulated by the double quotes, with no characters between the quotes. This is represented as the two bars with only double quotes in the file record, such as '"a","","c","d"'.
- For each segment value, the comma character (,) and double quotes are not allowed to be included in the value. If there are comma characters or double quotes in the data field which cause the third-party resolution failure, the Mobile Money system will not handle the failure.

# Data Field

The data format and field description of the Transaction Extract payload file is shown in the following table:

| **SN** | **Field Name** | **Type** | **Example value** | **Description** |
| --- | --- | --- | --- | --- |
| 1 | RECEIPT NUMBER | String | 3063400210 | The receipt number for the transaction. |
| 2 | DATE | String | _2015-05-20 23:38:33_ | Date |
| 3 | DETAILS | String | _Business Payment to 2547XXXXXXXX - Safaricom via API_ | Description of the account entry |
| 4 | STATUS | String | Completed | The status of the transaction. The value should be completed, failed, declined, cancelled, or expired. |
| 5 | WITHDRAW\_AMOUNT | String | _4,029_ | Indicate the debit amount of the account entry. Can be principal amount or charge amount. |
| 6 | PAID\_IN\_AMOUNT | String | _0_ | Indicate the credit amount of the account entry. Can be principal amount or charge amount. |
| 7 | BALANCE | String | _5,924,891_ | Available balance of the account after the transaction. |
| 8 | BALANCE\_CONFIRMED | String | _true_ ||
| 9 | TRANSACTION\_TYPE | String | _Business Payment to 2547XXXXXXXX - Safaricom via API_ | Description of the account entry |
| 10 | OTHERPARTYINFO | String | 2547XXXXXXXX - Safaricom | Transaction party info |
| 11 | TRANSACTIONPARTYDETAILS | String | ||| 12 | TRANSACTION\_ID | String | _JEK4FESX2M_ | Unique identifier of the transaction in M-PESA system. |
| 13 | REMARK | String | 0 | Indicate the remark of the transaction. | #RECEIPT\_NUMBER,DATE1,DETAILS,
