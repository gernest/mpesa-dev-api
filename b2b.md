> *B2C API Specification*

# Approvals

> This document needs below approvals for implementation.

<table>
<tbody>
<tr class="odd">
<td align="left"><blockquote>
<p><strong>Author(s)</strong></p>
</blockquote></td>
<td align="left"><blockquote>
<p><strong>Name</strong></p>
</blockquote></td>
<td align="left"><blockquote>
<p><strong>Signature</strong></p>
</blockquote></td>
<td align="left"><blockquote>
<p><strong>Date</strong></p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>Service Development Engineer</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Eneth Kubai</p>
</blockquote></td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p><strong>Reviewers</strong></p>
</blockquote></td>
<td align="left"><blockquote>
<p><strong>Name</strong></p>
</blockquote></td>
<td align="left"><blockquote>
<p><strong>Signature</strong></p>
</blockquote></td>
<td align="left"><blockquote>
<p><strong>Date</strong></p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>Senior Manager Service Development</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Reginald Tole</p>
</blockquote></td>
<td align="left"></td>
<td align="left"></td>
</tr>
</tbody>
</table>

# Revision Log

<table>
<thead>
<tr class="header">
<th align="left"><blockquote>
<p><strong>Revision Number</strong></p>
</blockquote></th>
<th align="left"><blockquote>
<p><strong>Revision Date</strong></p>
</blockquote></th>
<th align="left"><blockquote>
<p><strong>Revision</strong></p>
</blockquote></th>
<th align="left"><blockquote>
<p><strong>Revision made by</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><blockquote>
<p>1.0</p>
</blockquote></td>
<td align="left"><blockquote>
<p>18th June, 2013</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Initial Draft</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Eneth Kubai</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>1.1</p>
</blockquote></td>
<td align="left"><blockquote>
<p>9<sup>th</sup> July, 2013</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Added section 3.8.1: Password Encryption</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Eric Mokaya</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>1.2</p>
</blockquote></td>
<td align="left"><blockquote>
<p>29<sup>th</sup> July 2013</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Added Result codes</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Eneth Kubai</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>1.3</p>
</blockquote></td>
<td align="left"><blockquote>
<p>13<sup>th</sup> Jan 2014</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Added Result code explanations</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Eneth Kubai</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>1.4</p>
</blockquote></td>
<td align="left"><blockquote>
<p>7<sup>th</sup> Sept 2014</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Added changePassword interface, edited queryTransaction Interface, edited OriginatorConversationId field restrictions. Removed encrypted parameter tag. Edited the genericAPI request, response and result, added result and response codes</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Eneth Kubai</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>1.5</p>
</blockquote></td>
<td align="left"><blockquote>
<p>11<sup>th</sup> Nov 2014</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Attached SSL Guide</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Eneth Kubai</p>
</blockquote></td>
</tr>
</tbody>
</table>

# References

<table>
<thead>
<tr class="header">
<th align="left"><strong>Document</strong></th>
<th align="left"><strong>Author</strong></th>
<th align="left"><strong>Name</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"></td>
<td align="left">Eneth Kubai</td>
<td align="left">Response and Result Codes V1.0</td>
</tr>
<tr class="even">
<td align="left"></td>
<td align="left">John Barii</td>
<td align="left">SSL Guide</td>
</tr>
</tbody>
</table>

# Abbreviations

<table>
<thead>
<tr class="header">
<th align="left"><blockquote>
<p><strong>Term</strong></p>
</blockquote></th>
<th align="left"><blockquote>
<p><strong>Definition</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><blockquote>
<p>API</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Application Programming Interface</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>B2C</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Business to Customer</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>Broker</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Service Access Gateway</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>SP</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Service Provider</p>
</blockquote></td>
</tr>
</tbody>
</table>

1.  # Introduction
    
    1.  ## Scope

> The present document specifies the real time B2C Web Service aspects
> of the interface. All aspects of B2C Web Service are defined here,
> these being:

* > Message Flow Description

* > Data Type Definition

* > Web Service Interface Definition

* > WSDL for this specification

* > Example


1.  # Message Flow Description

2.  # Data Type Definition
    
    1.  ## IdentityType enumeration

> List of IdentityType values.

<table>
<thead>
<tr class="header">
<th align="left"><blockquote>
<p>Enumeration</p>
</blockquote></th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><blockquote>
<p>1000</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Customer</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>2000</p>
</blockquote></td>
<td align="left"><blockquote>
<p>SPOperator</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>3000</p>
</blockquote></td>
<td align="left"><blockquote>
<p>OrganizationOperator</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>5000</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Organization</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>6000</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Till</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>8000</p>
</blockquote></td>
<td align="left"><blockquote>
<p>SP</p>
</blockquote></td>
</tr>
</tbody>
</table>

## IdentifierType enumeration

> List of IdentityType values.

<table>
<thead>
<tr class="header">
<th align="left"><blockquote>
<p>Enumeration</p>
</blockquote></th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><blockquote>
<p>1</p>
</blockquote></td>
<td align="left"><blockquote>
<p>MSISDN</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>2</p>
</blockquote></td>
<td align="left"><blockquote>
<p>TillNumber</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>3</p>
</blockquote></td>
<td align="left"><blockquote>
<p>SPShortCode</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>4</p>
</blockquote></td>
<td align="left"><blockquote>
<p>OrganizationShortCode</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>5</p>
</blockquote></td>
<td align="left"><blockquote>
<p>IdentityID</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>6</p>
</blockquote></td>
<td align="left"><blockquote>
<p>O2CLink</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>9</p>
</blockquote></td>
<td align="left"><blockquote>
<p>SPOperatorCode</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>10</p>
</blockquote></td>
<td align="left"><blockquote>
<p>POSNumber</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>11</p>
</blockquote></td>
<td align="left"><blockquote>
<p>OrganizationOperatorUserName</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>12</p>
</blockquote></td>
<td align="left"><blockquote>
<p>OrganizationOperatorCode</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>13</p>
</blockquote></td>
<td align="left"><blockquote>
<p>VoucherCode</p>
</blockquote></td>
</tr>
</tbody>
</table>

## ParameterType structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Key</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>It indicates a parameter name.</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left">Value</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>It indicates a parameter value.</p>
</blockquote></td>
</tr>
</tbody>
</table>

## Parameters structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left"><blockquote>
<p>Element type</p>
</blockquote></th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Parameter</td>
<td align="left"><blockquote>
<p>ParameterType[1..unbounded]</p>
</blockquote></td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>It is used to carry specific parameters for specific transaction or business operation.</p>
</blockquote></td>
</tr>
</tbody>
</table>

## ReferenceData structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">ReferenceItem</td>
<td align="left">ParameterType[1..unbounded]</td>
<td align="left">No</td>
<td align="left">It is used carry some reference data that MM need not analyze but need to record it into transaction log..</td>
</tr>
</tbody>
</table>

## Transaction structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">CommandID</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left"><p>The unique identifier of transaction/business operation. Max length is 64.eg</p>
<ul>
<li><blockquote>
<p><em>SalaryPayment </em></p>
</blockquote></li>
<li><blockquote>
<p><em>BusinessPayment</em></p>
</blockquote></li>
<li><blockquote>
<p><em>BusinessPaymentWithWithdrawalChargePaid</em></p>
</blockquote></li>
<li><blockquote>
<p><em>SalaryPaymentWithWithdrawalChargePaid</em></p>
</blockquote></li>
<li><blockquote>
<p><em>PromotionPayment</em></p>
</blockquote></li>
<li><blockquote>
<p><em>TransferFromBankToCustomer</em></p>
</blockquote></li>
</ul></td>
</tr>
<tr class="even">
<td align="left">LanguageCode</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left">It indicates language. It’s reserved.</td>
</tr>
<tr class="odd">
<td align="left">OriginatorConversationID</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left"><p>The unique identifier of the request message generated by third party. It is used to identify a request between the third party and MM. Max length is 128.</p>
<p>Field must start with the B2C organisation short and name of organisation. Eg.</p>
<p>232323_KCBOrg_XXXXXX</p>
<p>XXXXX must be unique for every transaction.</p></td>
</tr>
<tr class="even">
<td align="left">ConversationID</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left">The unique identifier generated by MM for a previous request message. It is used to support communication multi-times between the third party and MM for one operation/transaction.</td>
</tr>
<tr class="odd">
<td align="left">Remark</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left">The remark information about this operation. Max length is 255</td>
</tr>
<tr class="even">
<td align="left">EncryptedParameters</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left">It is used to carry the value for the element Parameters which are encrypted.<br />
The value for this parameter should be a CDATA and encode with base64</td>
</tr>
<tr class="odd">
<td align="left">Parameters</td>
<td align="left">Parameters</td>
<td align="left">Yes</td>
<td align="left">It is used to carry specific parameters for specific transaction or business operation.<br />
If the element EncryptedParameters presents, this parameter should not present.</td>
</tr>
<tr class="even">
<td align="left">ReferenceData</td>
<td align="left">ReferenceData</td>
<td align="left">Yes</td>
<td align="left">It is used carry some reference data that MM need not analyze but need to record it into transaction log.</td>
</tr>
<tr class="odd">
<td align="left">Timestamp</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left">The timestamp generated by the third party.</td>
</tr>
</tbody>
</table>

## Caller structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">CallerType</td>
<td align="left">xsd:integer</td>
<td align="left">No</td>
<td align="left">Indicates the type of the caller:<br />
2-APICaller<br />
3-Other(Reserved)</td>
</tr>
<tr class="even">
<td align="left">ThirdPartyID</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left">The unique identifier of a third party system defined in MM. It indicates the third party which initiates the request. Max length is 20</td>
</tr>
<tr class="odd">
<td align="left">Password</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left">This security credential of the ThirdPartyID defined in MM. If the password feature for third party is used in MM, then this parameter must be presented in the request message.</td>
</tr>
<tr class="even">
<td align="left">CheckSum</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left">Currently it is unused. It is reserved for API security.</td>
</tr>
<tr class="odd">
<td align="left">ResultURL</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left">It indicates the destination URL where Broker should send the result message to.</td>
</tr>
</tbody>
</table>

## Initiator structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">IdentifierType</td>
<td align="left">IdentifierType</td>
<td align="left">No</td>
<td align="left">It indicates the identifier type of the initiator. The value of this parameter must be a valid identifier type supported by MM.</td>
</tr>
<tr class="even">
<td align="left">Identifier</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left">It indicates the identifier of the initiator. Its value must match the inputted value of the parameter IdentifierType.</td>
</tr>
<tr class="odd">
<td align="left">SecurityCredential</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left">It indicates the security credential of the initiator. Its value must match the inputted value of the parameter IdentifierType.</td>
</tr>
<tr class="even">
<td align="left">ShortCode</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left">When the initiator is an organization operator, this parameter must be present in the request to indicate which organization the operator belongs to.<br />
If the initiator is not an organization operator, this parameter should not be present.</td>
</tr>
</tbody>
</table>

### Password Encryption

The Caller will be required to confirm its authority to act on behalf of
the Initiator (in other words, a specific B2C organisation) by
presenting the user name and password for the Initiator, the latter
encrypted with the public key from an X509 certificate issued to the
Initiator specifically for this purpose.

The following algorithm must be followed by the Initiator to encrypt
passwords:

First, create the block of data to be encrypted:

* > Write the unencrypted password value.

* > Then, encrypt the block of data created in step 1 with the public
  > portion of the password key certificate. Use the RSA algorithm, and
  > use PKCS \#1\.5 padding (not OAEP), and add the result to the
  > encrypted stream – this becomes the encrypted password which is
  > submitted via the API.

* > Convert the resulting encrypted byte array into a string using
  > base64 encoding. Present this base64 encoded string in the API
  > request as the initiator SecurityCredential value.
  
  1.  ## PrimaryParty structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left"><blockquote>
<p>Element type</p>
</blockquote></th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><em>IdentifierType</em></td>
<td align="left"><blockquote>
<p><em>IdentifierType</em></p>
</blockquote></td>
<td align="left"><em>No</em></td>
<td align="left"><em>It indicates the identifier type of the primary party. The value of this parameter must be a valid identifier type supported by MM and must match the inputted value of the parameter IdentityType.</em></td>
</tr>
<tr class="even">
<td align="left"><em>Identifier</em></td>
<td align="left"><blockquote>
<p><em>xsd:string</em></p>
</blockquote></td>
<td align="left"><em>No</em></td>
<td align="left"><em>It indicates a parameter value.</em></td>
</tr>
<tr class="odd">
<td align="left"><em>ShortCode</em></td>
<td align="left"><blockquote>
<p><em>xsd:string</em></p>
</blockquote></td>
<td align="left"><em>Yes</em></td>
<td align="left"><em>It is reserved</em></td>
</tr>
</tbody>
</table>

## ReceiverParty structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">IdentifierType</td>
<td align="left">IdentifierType</td>
<td align="left">No</td>
<td align="left">It indicates the identifier type of the recipient party. The value of this parameter must be a valid identifier type supported by MM.</td>
</tr>
<tr class="even">
<td align="left">Identifier</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left">It indicates the identifier of the recipient party. Its value must match the inputted value of the parameter IdentifierType.</td>
</tr>
<tr class="odd">
<td align="left">ShortCode</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left">When the receiver party is an organization operator or a Till, this parameter must be present in the request to indicate which organization the receiver party belongs to.<br />
If the receiver party is not an organization operator or a Till, this parameter should not be present.</td>
</tr>
</tbody>
</table>

## AccessDevice structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left"><blockquote>
<p>Element type</p>
</blockquote></th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">IdentifierType</td>
<td align="left"><blockquote>
<p>IdentifierType</p>
</blockquote></td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>It indicates the identifier type of the access device.</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left">Identifier</td>
<td align="left"><blockquote>
<p>xsd:string</p>
</blockquote></td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>It indicates the identifier of the access device. Its value must match the inputted value of parameter IdentifierType</p>
</blockquote></td>
</tr>
</tbody>
</table>

## Identity structure

<table>
<thead>
<tr class="header">
<th align="left"><blockquote>
<p>Element name</p>
</blockquote></th>
<th align="left"><blockquote>
<p>Element type</p>
</blockquote></th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Caller</td>
<td align="left">Caller</td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>It indicates the third party which initiates the request</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left">Initiator</td>
<td align="left">Initiator</td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>It indicates the identity who makes the request</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left">PrimaryParty</td>
<td align="left">PrimaryParty</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>If business operation/action, this element is not present; if transaction, this can be either the debit party or the credit party according to the transaction type.</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left">ReceiverParty</td>
<td align="left">ReceiverParty</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>If business operation/action, this is the affected party; if transaction, it is the opposite party to the PrimaryParty</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left">AccessDevice</td>
<td align="left">AccessDevice</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>It indicates the access device which the initiator uses to initiate the request.</p>
</blockquote></td>
</tr>
</tbody>
</table>

## Request structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left"><blockquote>
<p>Element type</p>
</blockquote></th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Transaction</td>
<td align="left"><blockquote>
<p>Transaction</p>
</blockquote></td>
<td align="left">No</td>
<td align="left">It indicates a transaction.</td>
</tr>
<tr class="even">
<td align="left">Identity</td>
<td align="left"><blockquote>
<p>Identity</p>
</blockquote></td>
<td align="left">No</td>
<td align="left">This section is used to specify all identities involved in the request</td>
</tr>
<tr class="odd">
<td align="left">KeyOwner</td>
<td align="left"><blockquote>
<p>xsd:integer</p>
</blockquote></td>
<td align="left">No</td>
<td align="left">It indicates which Key is used to encrypt the elements Initator.SecurityCredential and the EncryptedParameters.<br />
Its value are enumerated as follows:<br />
1:the API Caller's Key<br />
2:the Initiator's Key</td>
</tr>
</tbody>
</table>

## Response structure

<table>
<thead>
<tr class="header">
<th align="left"><blockquote>
<p>Element name</p>
</blockquote></th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">ResponseCode</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>It indicates whether MM accepts the request or not.</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left">ResponseDesc</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>Its value is a description for the parameter ResultCode.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left">ConversationID</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>The unique identifier generated by M-Pesa for the request message.</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left">OriginatorConversationID</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>The unique identifier generated by the third party for the request message.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left">ServiceStatus</td>
<td align="left">xsd: integer</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>It indicates the MM service status.</p>
</blockquote></td>
</tr>
</tbody>
</table>

## ResultParameters structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">ResultParameter</td>
<td align="left">ParameterType[0…unbounded]</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>It is used to carry specific parameters for specific transaction or business operation.</p>
</blockquote></td>
</tr>
</tbody>
</table>

## Result structure

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">ResultType</td>
<td align="left">xsd:integer</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>0: completed 1: waiting for further messages</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left">ResultCode</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>It indicates whether MM processes the request successfully or not. Max length is 10</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left">ResultDesc</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>Its value is a description for the parameter ResultCode.Max length is 1024</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left">OriginatorConversationID</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>The unique identifier of the request message generated by third party. Its value comes from the request message.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left">ConversationID</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>The unique identifier generated by MM for a request</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left">TransactionID</td>
<td align="left">xsd:string</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>It’s only for transaction. When the request is a transaction request, MM will generate a unique identifier for the transaction.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left">ResultParameters</td>
<td align="left">ResultParameters</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>It is used to carry specific parameters for specific transaction or business operation.</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left">ReferenceData</td>
<td align="left">ReferenceData</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>It comes from the request message</p>
</blockquote></td>
</tr>
</tbody>
</table>

## Result code

<table>
<thead>
<tr class="header">
<th align="left">Error code</th>
<th align="left">Error Description</th>
<th align="left"></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"></td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">0</td>
<td align="left">Success</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">1</td>
<td align="left">Insufficient Funds</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">2</td>
<td align="left">Less Than Minimum Transaction Value</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">3</td>
<td align="left">More Than Maximum Transaction Value</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">4</td>
<td align="left">Would Exceed Daily Transfer Limit</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">5</td>
<td align="left">Would Exceed Minimum Balance</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">6</td>
<td align="left">Unresolved Primary Party</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">7</td>
<td align="left">Unresolved Receiver Party</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">8</td>
<td align="left">Would Exceed Maxiumum Balance</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">11</td>
<td align="left">Debit Account Invalid</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">12</td>
<td align="left">Credit Account Invaliud</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">13</td>
<td align="left">Unresolved Debit Account</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">14</td>
<td align="left">Unresolved Credit Account</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">15</td>
<td align="left">Duplicate Detected</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">17</td>
<td align="left">Internal Failure</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">18</td>
<td align="left">Initiator Credential Check Failure</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">19</td>
<td align="left">Message Sequencing Failure</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">20</td>
<td align="left">Unresolved Initiator</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">21</td>
<td align="left">Initiator to Primary Party Permission Failure</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">22</td>
<td align="left">Initiator to Receiver Party Permission Failure</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">23</td>
<td align="left">Request schema validation error</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">24</td>
<td align="left">MissingRequestParameters</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="even">
<td align="left">25</td>
<td align="left">InvalidRequestParameters</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">26</td>
<td align="left">SystemTooBusy</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="even">
<td align="left">0</td>
<td align="left">Success</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">100000000</td>
<td align="left">Request was cached, waiting for resending</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="even">
<td align="left">100000001</td>
<td align="left">The system is overload</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">100000002</td>
<td align="left">Throttling error</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="even">
<td align="left">100000003</td>
<td align="left">Exceed the limitation of the LICENSE</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">100000004</td>
<td align="left">Internal Server Error</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="even">
<td align="left">100000005</td>
<td align="left"><p>Invalid input value:%1</p>
<p>%1 indicates the parameter’s name.</p></td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">100000006</td>
<td align="left">SP’s status is abnormal</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="even">
<td align="left">100000007</td>
<td align="left">Authentication failed</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">100000008</td>
<td align="left">Service’s status is abnormal</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="even">
<td align="left">100000009</td>
<td align="left">API’s status is abnormal</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">100000010</td>
<td align="left">Insufficient permissions</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="even">
<td align="left">100000011</td>
<td align="left">Exceed the limitation of request rate</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">100000012</td>
<td align="left">Insufficient balance</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="even">
<td align="left">100000013</td>
<td align="left">No route</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">100000014</td>
<td align="left"><p>Missing mandatory parameter:%1</p>
<p>%1 indicates the parameter’s name.</p></td>
<td align="left">ApiResponse</td>
</tr>
<tr class="even">
<td align="left">28</td>
<td align="left">InitiatorAllowedOperationCheckFailure</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">29</td>
<td align="left">InvalidCommand</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">30</td>
<td align="left">ErrorSerializingRequest</td>
<td align="left">ApiResponse</td>
</tr>
<tr class="odd">
<td align="left">31</td>
<td align="left">InitiatorNotSpecified</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">32</td>
<td align="left">ErrorSerializingRequest</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">33</td>
<td align="left">PrimaryPartyNotSpecified</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">34</td>
<td align="left">PrimaryPartyIdentifierInvalid</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">35</td>
<td align="left">ReceiverPartyNotSpecified</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">36</td>
<td align="left">ReceiverPartyIdentifierInvalid</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">37</td>
<td align="left">MissingApiCommand</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">38</td>
<td align="left">InvalidConversationId</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">39</td>
<td align="left">UnknownConversationId</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">40</td>
<td align="left">InvalidParameterDefinition</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">41</td>
<td align="left">DuplicateConversationDetected</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">42</td>
<td align="left">DuplicateStageMessageDetected</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">43</td>
<td align="left">AwaitingConfirmation</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">44</td>
<td align="left">InitiatorToReceiverPartyPermissionFailure</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">45</td>
<td align="left">InternalErrorDuringFinancialTransaction</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">46</td>
<td align="left">ConfirmationReceived</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">47</td>
<td align="left">RejectionReceived</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">48</td>
<td align="left">OperationPermissionFailure</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">49</td>
<td align="left">NoTransactionFound</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">50</td>
<td align="left">InitiatorOrgIdentityStatusFailure</td>
<td align="left">ApiResult</td>
</tr>
<tr class="odd">
<td align="left">51</td>
<td align="left">DebitChargeAccountInvalid</td>
<td align="left">ApiResult</td>
</tr>
<tr class="even">
<td align="left">52</td>
<td align="left">WouldExceedMaximumSingleAirtimePurchase</td>
<td align="left">ApiResult</td>
</tr>
</tbody>
</table>

The following table lists result codes and result descriptions which are
provided to the caller. These may be commincated either in the
synchronous *ApiResponse* message, or in the asynchronous *ApiResult*
message.

1.  **Success **
    
    This is indicated for both ApiResponse and ApiResult messages. An
    ApiResponse value of 0 indicates that the request has passed basic
    validation tests and been passed on to the core system for further
    processing. An ApiResult value of 0 means that the requested
    financial transaction has been completed successfully. In case of
    multi staged transaction the response code will be 43 for initiation
    stage and 46 for confirmation.

2.  **InsufficientFunds**
    
    Typically indicates that the primary party does not have enough
    money to complete the requested financial transaction. In the case
    of the B2C API, this means that the business organisation does not
    have enough money in its utility account.
    
    This is returned by the *ApiResult* and represented internally as a
    transaction reason.

3.  **LessThanMinimumTransactionValue**

4.  **MoreThanMaximumTransactionValue**
    
    Each of these potential failures derive from the rules which govern
    MPesa financial transactions. In the case of the B2C API, these are
    taken from *DefaultBusinessUtilityAccount* rules, which specify a
    lower bound of 10 KE shillings and an upper bound of 70000\. For
    promotion payments and salary payments to unregistered users, the
    upper limit is lower: 35000\. Likewise, the lower bound for these 2
    transactions is also different: 101 rather than 10\.
    
    These are both returned by the *ApiResult* and represented
    internally as a transaction reason.

5.  **WouldExceedDailyTransferLimit**

> This is a limit on daily activity. For the business organisation, this
> is very high: 100000000 KE shillings. It is much more likely that this
> rule will apply to the customer, where the limit is 140000 KE
> shillings.
> 
> This is returned by the *ApiResult* and represented internally as a
> transaction reason.

1.  **WouldExceedMinimumBalance**
    
    This rule is rather confusingly named – it actually means that a
    transaction would bring the business organisations utility account
    bellow the required minimum – which is currently 0\.
    
    This is returned by the *ApiResult* and represented internally as a
    transaction reason. It is computed during execution of the financial
    transaction.

2.  **UnresolvedPrimaryParty**

3.  **UnresolvedReceiverParty**
    
    The primary party or receiver party cannot be associated with an
    MPesa identity. For transactions (such as promotion payment and
    salary payment) which are supported for unregistered users, the
    unresolved receiver party rule is not applied.
    
    These are returned in the *ApiResult* and checked before the linked
    financial transaction is created.

4.  **WouldExceedMaximumBalance**
    
    For the B2C API, this applies to the recipient MMF customer – the
    limit here is 100,000 KE shillings.
    
    This is returned by the *ApiResult* and represented internally as a
    transaction reason. It is computed during execution of the financial
    transaction.

5.  **LessThanMinAirtimeValue**

6.  **MoreThanMaxAirtimeValue**

> Neither of these apply to B2C API operations.

1.  **DebitAccountInvalid**

2.  **CreditAccountInvalid**

3.  **UnresolvedDebitAccount**

4.  **UnresolvedCreditAccount**

> These are all existing failure transaction reasons for B2C financial
> transactions – they would be issued to the caller in the *ApiResult*
> message. The latter 2 in particular are unlikely to occur, as the
> request would be rejected by Core API specific checks before the
> request reached the accounting engine.

1.  **DuplicateDetected**

> Currently, any requests which presents an originator conversation id
> which has been seen before will be rejected. This rule will need to be
> reconsidered in contexts which require multi-stage conversations or
> multiple Callers. This check (along with the message expiry check) is
> the first thing done by the transaction processor when handling an API
> request. The outcome is reported in the *ApiResult* message.

1.  **PayUtilityInvalidAccountNumberFormat**

> Does not apply to the B2C API operations.

1.  **InternalFailure**

> A catch all for failures which are not identified more specifically –
> this can occur in either the *ApiResponse* or *ApiResult* – although
> the intent is to replace any such error with a more precise message.

1.  **InitiatorCredentialCheckFailure**

> The password check for the initiator failed, either because the
> presented password is wrong, or something has gone wrong in the
> encryption or decryption steps. This is issued in the *ApiResult*
> before the creation of a financial transaction.

1.  **ApiRequestMessageExpiryFailure**

> Initiators have the option to specify a request timestamp. If the gap
> between this value and the time at which the message is received by
> the transaction processor is too great, then the request is rejected.
> The specific interval is configured separately for each API operation
> (and indeed, for each API operation stage). This is the first check
> performed on an API request arriving at the transaction processor, and
> as such is included in the *ApiResult* message.

1.  **UnresolvedInitiator**
    
    The initiator username presented with the request cannot be found.
    This is included in the *ApiResult*.

2.  **InitiatorToPrimaryPartyPermissionFailure**

> The initiator presented does not have the right to issue requests for
> the specified primary party (as established during creation of the
> initiator on the admin web site). The is part of the *ApiResult*, and
> computed prior to issuing a financial transaction.

1.  **InitiatorStatusCheckFailure**

> The presented initiator username can be received, but the initiator is
> not currently active. This fact is returned in the *ApiResult*.

1.  **RequestSchemaValidationError**

> Incoming API requests are validated against the schema defined in
> *CPSInterface\_Request.xsd*. This is part of the *ApiResponse* message
> – the details of the validation error are included in the response.

1.  **MissingRequestParameters**

> Required input parameters are defined for each type of API operation.
> If these are missing, then this is issued in the *ApiResult* message.
> The names of the missing parameters are included in the result
> parameters field.

1.  **InvalidRequestParameters**

> If all required parameters are presented, then validation checks are
> performed. Specifically, the parameter is checked to see if it can be
> converted to the intended type, and then checked against (optional)
> configuration regular expression based validation rules. For the B2C
> API, only the type check (i.e the amount specified is a valid decimal)
> is performed. Failures are indicated in the *ApiResult* message, with
> the details included in the result parameters.

1.  **SystemTooBusy**

> Included in the *ApiResponse* message if a traffic blocking condition
> is in place. See section 5\.1 for more detail.

28. **InitiatorAllowedOperationCheckFailure**

> Upon creation, initiators are assigned permissions for specific API
> operations – if the operation specified in the request message is not
> included in this list, then this *ApiResult* message is received.

28. **InvalidCommand**
    
    The command specified in the request is not defined – this is part
    of the *ApiResult*.

29. **ErrorSerializingRequest**
    
    After XML schema validation, the API attempts to convert the XML
    request into an internal *ApiRequest* object – any failures result
    in this *ApiResponse* message. The details of the exception are
    included.

30. **InitiatorNotSpecified**

> The initiator username is not specified, or not specified in a way
> that can be parsed.

28. **ErrorSerializingRequest**

> The presented identifier for the initiator is not a username.

28. **PrimaryPartyNotSpecified**

29. **PrimaryPartyIdentifierInvalid**

30. **ReceiverPartyNotSpecified**

31. **ReceiverPartyIdentifierInvalid**

> In all these case, one of the API parties is either missing from the
> request, or has been presented with the wrong identifier type., This
> kind of failure is indicated in the *ApiResult* message.,

28. **MissingApiCommand**

> No command is included in the request – in general this problem should
> be captured by the XML schema validation, but if it is not this
> *ApiResult* message is issued.

28. **InvalidConversationId**

29. **UnknownConversationId**

> Not currently checked for – this will take place for multi-stage
> conversations.

28. **InvalidParameterDefinition**
    
    Not been used.

29. **DuplicateConversationDetected**
    
    If the originatorconversationid is be reused again, the request will
    end up with duplicate error code. The request should have a unique
    originatorconversationid for every new apirequest.

30. **DuplicateStageMessageDetected**
    
    If the stage name is requested twice it will end up with duplicate
    stage. Though the occurance of this would be very rare.

31. **AwaitingConfirmation**
    
    It is applicable for multi stage transaction. Once the first stage
    of the transaction is set to authorised with will set the result
    code as AwaitingConfirmation to convey the initiator to initiate the
    confirmation stage.

32. **InitiatorToReceiverPartyPermissionFailure**
    
    The initiator presented does not have the right to issue requests
    for the specified receiver party (as established during creation of
    the initiator on the admin web site). The is part of the
    *ApiResult*, and computed prior to issuing a financial transaction.

33. **InternalErrorDuringFinancialTransaction**

34. **ConfirmationReceived**
    
    It is applicable for the multi stage transaction. The result code is
    send once the confirmation stage is processed successfully to
    confirm the financial transaction.

35. **RejectionReceived**
    
    It is applicable for the multi stage transaction. The result code is
    send once the confirmation stage is processed successfully to cancel
    the financial transaction

36. **OperationPermissionFailure**
    
    For transaction status query if the initiator presented was not the
    part of the original transaction or linked to the respective parties
    within the original request a transaction access permission failure
    result is send out. For balance query if the initiator is not linked
    to the request organisation shortcode it will return the same result
    code. As the validation is common the result code will be shared by
    both the request.

37. **NoTransactionFound**
    
    For transaction status query is the request transaction parameter is
    not found in the system it will send the transaction not found
    result code.

38. **InitiatorOrgIdentityStatusFailure**
    
    The result code is returned if the organisation status is closed.

39. **DebitChargeAccountInvalid**
    
    If the Airtime purchase account is set to inactive state the
    corresponding transaction will return an invalid debit charge
    account failure.

40. **WouldExceedMaximumSingleAirtimePurchase**
    
    If transaction amount exceeds the maximum amount configured for
    single request it will fail the transaction for rule failure.


1.  # Web Service Interface Definition
    
    1.  ## Interface: RequestMgrPortType
        
        1.  ### Operation: GenericAPIRequest

> The 3<sup>rd</sup> party invokes this operation to send a B2C request

#### 4\.1\.1\.1 Message Header: RequestSOAPHeader

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">spId</td>
<td align="left">xsd: string</td>
<td align="left"><blockquote>
<p>No</p>
</blockquote></td>
<td align="left"><p>SP ID.</p>
<p>This is the Service Provider Identifier that is allocated by the Broker to the 3<sup>rd</sup> party.</p>
<p>[Example] 000201</p></td>
</tr>
<tr class="even">
<td align="left">spPassword</td>
<td align="left">xsd: string</td>
<td align="left"><blockquote>
<p>Yes</p>
</blockquote></td>
<td align="left"><p>This is an encrypted form of the SP password issued to an SP when an account is created on the Broker.</p>
<p>The encrypted password is a Base64 encoded string of the SHA-256 hash of the concatenation of the spId, password and the timeStamp as illustrated below:</p>
<p>Given the following parameters</p>
<p>spId: 601399</p>
<p>password: spPassword</p>
<p>timestamp: 20130702212854</p>
<p>spPassword = BASE64(SHA-256(spId + Password + timeStamp)) e.g.</p>
<p>spPassword = BASE64(SHA-256(601399spPassword20130702212854)</p>
<p>[Example]</p>
<p>e6434ef249df55c7a21a0b45758a39bb</p></td>
</tr>
<tr class="odd">
<td align="left">serviceId</td>
<td align="left">xsd: string</td>
<td align="left"><blockquote>
<p>Yes</p>
</blockquote></td>
<td align="left"><p>Service ID.</p>
<p>This is the Service Identifier that is allocated by the Broker for every service created.</p>
<p>[Example]</p>
<p>3500001000012</p></td>
</tr>
<tr class="even">
<td align="left">Timestamp</td>
<td align="left">xsd: string</td>
<td align="left"><blockquote>
<p>Yes</p>
</blockquote></td>
<td align="left"><p>Time stamp (UTC time).</p>
<p>The value is required during SHA-256 encryption for <strong>spPassword</strong>.</p>
<p>NOTE</p>
<p><span id="gen-id1.4.6.4.2.3.2.6.4.4.3" class="anchor"></span>If the <strong>spPassword</strong> parameter must be set, this parameter is mandatory.</p>
<p>[Format]</p>
<p>yyyyMMddHHmmss</p>
<p>[Example]</p>
<p>20100731064245</p></td>
</tr>
</tbody>
</table>

#### 4\.1\.1\.2 Input Message: RequestMsg

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">RequestMsg</td>
<td align="left">xsd: string</td>
<td align="left">No</td>
<td align="left">Request Message from 3<sup>rd</sup> party. Its value should be an instance of Request Type and a CDATA</td>
</tr>
</tbody>
</table>

> **Note:**
> 
> 1\. If there is no configuration for notification URL on Broker side,
> which indicates the callback url for accepting notification of
> GenericAPIResult, the **ResultURL** parameter inside Identity tag must
> present.
> 
> 2\. If there is no configuration for notification URL on Broker side,
> which indicates the callback url for accepting notification of cached
> requests expired, the 3<sup>rd</sup> party must add a key-pair
> parameter into **ReferenceData** and the key is **QueueTimeoutURL**.

#### 4\.1\.1\.3 Output Message: ResponseMsg

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">ResponseMsg</td>
<td align="left">xsd: string</td>
<td align="left">No</td>
<td align="left">Response return to 3<sup>rd</sup> party. Its value should be an instance of Response Type and a CDATA.</td>
</tr>
</tbody>
</table>

**\
**

1.  ## Interface: ResultMgrPortType
    
    1.  ### Operation: GenericAPIResult

> This operation must be implemented by a Web Service at the 3rd party
> side if it requires notification of the final result for B2C request.
> It will be invoked by Broker to notify the 3<sup>rd</sup> party once
> Broker received the notification from CoreAPI.

#### 4\.2\.1\.1 Input Message: ResultMsg

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">ResultMsg</td>
<td align="left">xsd: string</td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>Request Message from Broker. Its value should be a instance of Result Type and a CDATA.</p>
</blockquote></td>
</tr>
</tbody>
</table>

#### 4\.2\.1\.2 Output Message: ResponseMsg

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">ResponseMsg</td>
<td align="left">xsd: string</td>
<td align="left">No</td>
<td align="left"><blockquote>
<p>Response return to Broker. Its value should be a instance of Response Type and a CDATA.</p>
</blockquote></td>
</tr>
</tbody>
</table>

#### 4\.2\.1\.3 Response Codes

<table>
<thead>
<tr class="header">
<th align="left"><blockquote>
<p>ResponseCode</p>
</blockquote></th>
<th align="left"><blockquote>
<p>ResponseDesc</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><blockquote>
<p>000000000</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Success</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>200000001</p>
</blockquote></td>
<td align="left"><blockquote>
<p>The system is overload</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>200000002</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Throttling error</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>200000003</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Internal Server Error</p>
</blockquote></td>
</tr>
</tbody>
</table>

The parameters in the **Result/ResultParameters** element are listed
below:

The **ResultParameters** will change to this on April 2015\.

<table>
<thead>
<tr class="header">
<th align="left">Parameter</th>
<th align="left">Data Type</th>
<th align="left">Mandatory or Optional</th>
<th align="left">Description</th>
<th align="left">Example</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><blockquote>
<p>TransactionReceipt</p>
</blockquote></td>
<td align="left">xs:string</td>
<td align="left">Mandatory</td>
<td align="left"><blockquote>
<p>Unique transaction ID for the payment transaction.</p>
</blockquote></td>
<td align="left">1234560000007031</td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>TransactionAmount</p>
</blockquote></td>
<td align="left">xs:string</td>
<td align="left">Mandatory</td>
<td align="left"><blockquote>
<p>2 fixed point decimal amount of the transaction</p>
</blockquote></td>
<td align="left">100.22</td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>TransactionCompletedDateTime</p>
</blockquote></td>
<td align="left">xs:string</td>
<td align="left">Mandatory</td>
<td align="left"><blockquote>
<p>The time when the financial transaction was completed, as recorded in the M-Pesa system.</p>
<p>Format:</p>
<p>dd.mm.yyyy HH:MM:SS</p>
</blockquote></td>
<td align="left">22.03.2012 12:20:20</td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>ReceiverPartyPublicName</p>
</blockquote></td>
<td align="left">xs:string</td>
<td align="left">Mandatory</td>
<td align="left"><blockquote>
<p>Public name of the customer who has been issued the money.</p>
<p>Format: <em>&lt;MSISDN&gt;-&lt;First Name&gt; &lt;Last Name&gt;</em></p>
<p>For unregister customer, the <em>&lt;First Name&gt; &lt;Last Name&gt;</em> will be blank.</p>
</blockquote></td>
<td align="left">254778866553868-Kip Keino</td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>B2CWorkingAccountAvailableFunds</p>
</blockquote></td>
<td align="left">xs:string</td>
<td align="left">Mandatory</td>
<td align="left"><blockquote>
<p>2 fixed point decimal amount of the Available Balance of the organization’s Working Account.</p>
<p>Note: the exact Account Type will depend on the configuration.</p>
</blockquote></td>
<td align="left">9999.88</td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>B2CUtilityAccountAvailableFunds</p>
</blockquote></td>
<td align="left">xs:string</td>
<td align="left">Mandatory</td>
<td align="left"><blockquote>
<p>2 fixed point decimal amount of the Available Balance of the organization’s Utility Account, which is the debit account of the principle transaction.</p>
<p>Note: the exact Account Type will depend on the configuration.</p>
</blockquote></td>
<td align="left">9999.88</td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>B2CChargesPaidAccountAvailableFunds</p>
</blockquote></td>
<td align="left">xs:string</td>
<td align="left">Mandatory</td>
<td align="left"><blockquote>
<p>2 fixed point decimal amount of the Available Balance of the organization’s Charge Paid Account, which is debit account of the charge.</p>
<p>Note: the exact Account Type will depend on the configuration.</p>
</blockquote></td>
<td align="left"><blockquote>
<p>9999.88</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>B2CRecipientIsRegisteredCustomer</p>
</blockquote></td>
<td align="left">xs:string</td>
<td align="left">Mandatory</td>
<td align="left"><blockquote>
<p>Indicate if the recipient is an existing Mobile Money customer, or an unregistered customer.</p>
<p>Format: Y or N</p>
<p>Note: This field is not filled by the G1 platform, but it will be filled by the G2 platform.</p>
</blockquote></td>
<td align="left">Y</td>
</tr>
</tbody>
</table>

1.  ## Interface: QueueTimeoutNotificationPort
    
    1.  ### Operation: notifyQueueTimeout

> This operation must be implemented by a Web Service at the 3rd party
> side if it requires notification of cached B2C requests are expired.
> It will be invoked by Broker to notify the 3<sup>rd</sup> party once
> cached B2C requests are expired.

#### 4\.3\.1\.1 Input Message: notifyQueueTimeout

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left"><blockquote>
<p>Optional</p>
</blockquote></th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">originatorConversationID</td>
<td align="left">xsd:string</td>
<td align="left"></td>
<td align="left">originatorConversationID from the request sent by the 3<sup>rd</sup> party</td>
</tr>
<tr class="even">
<td align="left">originRequest</td>
<td align="left">xsd:string</td>
<td align="left"><blockquote>
<p>No</p>
</blockquote></td>
<td align="left">Original request without SOAP Header sent by 3<sup>rd</sup> party. Its value is encoded with base64, when the 3rd party receive the request, it should decode it.</td>
</tr>
<tr class="odd">
<td align="left">extensionInfo</td>
<td align="left">Parameters</td>
<td align="left"><blockquote>
<p>Yes</p>
</blockquote></td>
<td align="left">Extended parameters.</td>
</tr>
</tbody>
</table>

#### 4\.3\.1\.2 Output Message: notifyQueueTimeoutResponse

<table>
<thead>
<tr class="header">
<th align="left"><blockquote>
<p>Element name</p>
</blockquote></th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left"><blockquote>
<p>Description</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><blockquote>
<p>result</p>
</blockquote></td>
<td align="left">Result</td>
<td align="left">No</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>extensionInfo</p>
</blockquote></td>
<td align="left">Parameters</td>
<td align="left">Yes</td>
<td align="left"><blockquote>
<p>Extended parameters.</p>
</blockquote></td>
</tr>
</tbody>
</table>

#### 4\.3\.1\.3 Response Code

<table>
<thead>
<tr class="header">
<th align="left"><blockquote>
<p>ResponseCode</p>
</blockquote></th>
<th align="left"><blockquote>
<p>ResponseDesc</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><blockquote>
<p>000000000</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Success</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>000000001</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Failed</p>
</blockquote></td>
</tr>
</tbody>
</table>

1.  ## Interface: QueryTransactionPort
    
    1.  ### Operation: queryTransaction

> The 3<sup>rd</sup> party invokes this operation to query transaction
> information..

#### 4\.3\.1\.1 Message Header: RequestSOAPHeader

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">spId</td>
<td align="left">xsd: string</td>
<td align="left">No</td>
<td align="left"><p>SP ID.</p>
<p>It’s allocated by the Broker to the 3<sup>rd</sup> party.</p>
<p>[Example]</p>
<p>000201</p></td>
</tr>
<tr class="even">
<td align="left">spPassword</td>
<td align="left">xsd: string</td>
<td align="left">Yes</td>
<td align="left"><p>Encrypted authentication password for partners to access the Broker.</p>
<p>The value is a character string encrypted from <strong>spId</strong> + <strong>Password</strong> + <strong>timeStamp</strong> by SHA-256. The encryption formula is as follows: spPassword =BASE64(SHA-256(spId + Password + timeStamp))</p>
<p>In the preceding formula:</p>
<ul>
<li><p><strong>timeStamp</strong>: value of <strong>timeStamp</strong>.</p></li>
<li><p><strong>Password</strong>: authentication password for 3<sup>rd</sup> parties to access the Broker. The value is allocated by the Broker.</p></li>
</ul>
<p>NOTE</p>
<p>The authentication modes include SPID&amp;Password, SPID&amp;IP&amp;Password, and SPID&amp;IP. When the authentication mode is SPID&amp;Password or SPID&amp;IP&amp;Password, this parameter is mandatory.</p>
<p>[Example]</p>
<p>e6434ef249df55c7a21a0b45758a39bb</p></td>
</tr>
<tr class="odd">
<td align="left">serviceId</td>
<td align="left">xsd: string</td>
<td align="left">Yes</td>
<td align="left"><p>Service ID.</p>
<p>The value is allocated by the Broker to the 3<sup>rd</sup> party.</p>
<p>[Example]</p>
<p>3500001000012</p></td>
</tr>
<tr class="even">
<td align="left">timeStamp</td>
<td align="left">xsd: string</td>
<td align="left">Yes</td>
<td align="left"><p>Time stamp (UTC time).</p>
<p>The value is required during SHA-256 encryption for <strong>spPassword</strong>.</p>
<p>NOTE</p>
<p>If the <strong>spPassword</strong> parameter must be set, this parameter is mandatory.</p>
<p>[Format]</p>
<p>yyyyMMddHHmmss</p>
<p>[Example]</p>
<p>20100731064245</p></td>
</tr>
</tbody>
</table>

#### 4\.3\.1\.2 Input Message: queryTransaction

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">originatorConversationID</td>
<td align="left">xsd:string</td>
<td align="left"></td>
<td align="left">The unique identifier of the request message generated by third party. It is used to identify a request between the third party and MM. Max length is 128</td>
</tr>
<tr class="even">
<td align="left">extensionInfo</td>
<td align="left">Parameters</td>
<td align="left">Yes</td>
<td align="left">Extended parameters.</td>
</tr>
</tbody>
</table>

1.  > extensionInfo Description

<table>
<thead>
<tr class="header">
<th align="left">Parameter</th>
<th align="left">Optional</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">queryDate</td>
<td align="left">Yes</td>
<td align="left">String(20)</td>
<td align="left"><p>The date of the original conversation. Format is yyyyMMddHHmmss, for example: 20131230134412</p>
<p>Note:</p>
<p>If this parameter does not present, it will cost more time to get the result.</p></td>
</tr>
</tbody>
</table>

#### 

#### 4\.3\.1\.3 Output Message: queryTransactionResponse

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">result</td>
<td align="left">Response</td>
<td align="left">No</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">submitApiRequestList</td>
<td align="left">xsd:string[0-unbounded]</td>
<td align="left">Y</td>
<td align="left">Requests sent by the 3<sup>rd</sup> party. Its value is the requests sent by the 3<sup>rd</sup> party with base64 encoded.</td>
</tr>
<tr class="odd">
<td align="left">submitApiResponseList</td>
<td align="left">xsd:string[0-unbounded]</td>
<td align="left">Y</td>
<td align="left">Responses returned from the Broker. Its value is the responses returned from the Broker with base64 encoded.</td>
</tr>
<tr class="even">
<td align="left">submitApiResultList</td>
<td align="left">xsd:string[0-unbounded]</td>
<td align="left">Y</td>
<td align="left">Results sent to the 3<sup>rd</sup> party. Its value is the requests sent by the Broker with base64 encoded.</td>
</tr>
<tr class="odd">
<td align="left">queueTimeOutList</td>
<td align="left">xsd:string[0-unbounded]</td>
<td align="left">Y</td>
<td align="left">QueueTimeout requests sent to the 3<sup>rd</sup> party. Its value is the requests sent by the Broker with base64 encoded.</td>
</tr>
<tr class="even">
<td align="left">extensionInfo</td>
<td align="left">Parameters</td>
<td align="left">Yes</td>
<td align="left">Extended parameters.</td>
</tr>
</tbody>
</table>

#### 

**\
**

#### 4\.3\.1\.4 Response Codes

<table>
<thead>
<tr class="header">
<th align="left"><blockquote>
<p>ResponseCode</p>
</blockquote></th>
<th align="left"><blockquote>
<p>ResponseDesc</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><blockquote>
<p>000000000</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Success</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>100000001</p>
</blockquote></td>
<td align="left"><blockquote>
<p>The system is overload</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>100000002</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Throttling error</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>100000003</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Exceed the limitation of the LICENSE</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>100000004</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Internal Server Error</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>100000005</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Invalid input value:%1</p>
<p>%1 indicates the parameter’s name.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>100000006</p>
</blockquote></td>
<td align="left"><blockquote>
<p>SP’s status is abnormal</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>100000007</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Authentication failed</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>100000008</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Service’s status is abnormal</p>
</blockquote></td>
</tr>
<tr class="even">
<td align="left"><blockquote>
<p>100000010</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Insufficient permissions</p>
</blockquote></td>
</tr>
<tr class="odd">
<td align="left"><blockquote>
<p>100000014</p>
</blockquote></td>
<td align="left"><blockquote>
<p>Missing mandatory parameter:%1</p>
<p>%1 indicates the parameter’s name.</p>
</blockquote></td>
</tr>
</tbody>
</table>

## 4\.5 Interface: Management

### 4\.5\.1 Operation: changePassword

The 3<sup>rd</sup> party invokes this operation to change his password.

1.  Input Message: changePassword

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">spId</td>
<td align="left">xsd: string</td>
<td align="left">No</td>
<td align="left"><p>SP ID.</p>
<p>It’s allocated by the SAG to the 3<sup>rd</sup> party.</p>
<p>[Example]</p>
<p>000201</p></td>
</tr>
<tr class="even">
<td align="left">spPassword</td>
<td align="left">xsd: string</td>
<td align="left">Yes</td>
<td align="left"><p>Encrypted authentication password for partners to access the SAG.</p>
<p>The value is a character string encrypted from <strong>spId</strong> + <strong>Password</strong> + <strong>timeStamp</strong> by SHA-256. The encryption formula is as follows: spPassword =BASE64(SHA-256(spId + Password + timeStamp))</p>
<p>In the preceding formula:</p>
<p><strong>timeStamp</strong>: value of <strong>timeStamp</strong>.</p>
<p><strong>Password</strong>: authentication password for 3<sup>rd</sup> parties to access the SAG. The value is allocated by the SAG.</p>
<p>NOTE</p>
<p>The authentication modes include SPID&amp;Password, SPID&amp;IP&amp;Password, and SPID&amp;IP. When the authentication mode is SPID&amp;Password or SPID&amp;IP&amp;Password, this parameter is mandatory.</p>
<p>[Example]</p>
<p>e6434ef249df55c7a21a0b45758a39bb</p></td>
</tr>
<tr class="odd">
<td align="left">timeStamp</td>
<td align="left">xsd: string</td>
<td align="left">Yes</td>
<td align="left"><p>Time stamp (UTC time).</p>
<p>The value is required during SHA-256 encryption for <strong>spPassword</strong>.</p>
<p>NOTE</p>
<p>If the <strong>spPassword</strong> parameter must be set, this parameter is mandatory.</p>
<p>[Format]</p>
<p>yyyyMMddHHmmss</p>
<p>[Example]</p>
<p>20100731064245</p></td>
</tr>
<tr class="even">
<td align="left">newPassword</td>
<td align="left">xsd:string</td>
<td align="left">No</td>
<td align="left"><p>New authentication password for 3<sup>rd</sup> parties to access the SAG. It should be encrypted by AES-256 and encoded with base64. Shared key and will be allocated by the SAG.</p>
<p>For example:</p>
<p>New password is !QAZ2wsx,</p>
<p>Security key is AAAabcdefghijklm,</p>
<p>Vector is abcdefghijklmnop</p>
<p>BASE64(AES(!QAZ2wsx, AAAabcdefghijklm, abcdefghijklmnop)) is wi2a7BAH0QPd2LRdmcgC9w==</p>
<p>SP should fill wi2a7BAH0QPd2LRdmcgC9w== as newPassword</p></td>
</tr>
<tr class="odd">
<td align="left">extensionInfo</td>
<td align="left">Parameters</td>
<td align="left">Yes</td>
<td align="left">Extended parameters.</td>
</tr>
</tbody>
</table>

1.  Output Message: changePasswordResponse

<table>
<thead>
<tr class="header">
<th align="left">Element name</th>
<th align="left">Element type</th>
<th align="left">Optional</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">result</td>
<td align="left">Result</td>
<td align="left">No</td>
<td align="left">Result.</td>
</tr>
<tr class="even">
<td align="left">extensionInfo</td>
<td align="left">Parameters</td>
<td align="left">Yes</td>
<td align="left">Extended parameters.</td>
</tr>
</tbody>
</table>

1.  Response Code

<table>
<thead>
<tr class="header">
<th align="left">ResponseCode</th>
<th align="left">ResponseDesc</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">000000000</td>
<td align="left">Success</td>
</tr>
<tr class="even">
<td align="left">100000001</td>
<td align="left">The system is overload</td>
</tr>
<tr class="odd">
<td align="left">100000002</td>
<td align="left">Throttling error</td>
</tr>
<tr class="even">
<td align="left">100000003</td>
<td align="left">Exceed the limitation of the LICENSE</td>
</tr>
<tr class="odd">
<td align="left">100000004</td>
<td align="left">Internal Server Error</td>
</tr>
<tr class="even">
<td align="left">100000005</td>
<td align="left"><p>Invalid input value:%1</p>
<p>%1 indicates the parameter’s name.</p></td>
</tr>
<tr class="odd">
<td align="left">100000006</td>
<td align="left">SP’s status is abnormal</td>
</tr>
<tr class="even">
<td align="left">100000007</td>
<td align="left">Authentication failed</td>
</tr>
<tr class="odd">
<td align="left">100000014</td>
<td align="left"><p>Missing mandatory parameter:%1</p>
<p>%1 indicates the parameter’s name.</p></td>
</tr>
</tbody>
</table>

1.  # Example
    
    1.  ## GenericAPIRequest
        
        1.  ### The 3rd party send B2C request to the Broker

> Example1: Request with ResultURL and QueueTimeoutURL
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:req="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>
> 
> \<soapenv:Header\>
> 
> \<tns:RequestSOAPHeader
> xmlns:tns="http://www.huawei.com.cn/schema/common/v2\_1"\>
> 
> \<tns:spId\>35000011\</tns:spId\>
> 
> \<tns:spPassword\>c5216e519a071d601bedd150f3fcd026\</tns:spPassword\>
> 
> \<tns:serviceId\>35000001000009\</tns:serviceId\>
> 
> \<tns:timeStamp\>20120101010101\</tns:timeStamp\>
> 
> \</tns:RequestSOAPHeader\>
> 
> \</soapenv:Header\>
> 
> \<soapenv:Body\>
> 
> \<req:RequestMsg\>\<\!\[CDATA\[\<?xml version="1\.0"
> encoding="UTF-8"?\>
> 
> \<request
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>
> 
> \<Transaction\>
> 
> \<CommandID\>PromotionPayment\</CommandID\>
> 
> \<LanguageCode\>\</LanguageCode\>
> 
> \<OriginatorConversationID\>4596\</OriginatorConversationID\>
> 
> \<ConversationID\> \</ConversationID\>
> 
> \<Remark\> \</Remark\>
> 
> \<Parameters\>
> 
> \<Parameter\>
> 
> \<Key\>Amount\</Key\>
> 
> \<Value\>1\</Value\>
> 
> \</Parameter\>
> 
> \<Parameter\>
> 
> \<Key\>Key1\</Key\>
> 
> \<Value\>Value1\</Value\>
> 
> \</Parameter\>
> 
> \</Parameters\>
> 
> \<ReferenceData\>
> 
> \<ReferenceItem\>
> 
> \<Key\>QueueTimeoutURL\</Key\>
> 
> \<Value\>http://10\.66\.49\.789:7888/new\</Value\>
> 
> \</ReferenceItem\>
> 
> \<ReferenceItem\>
> 
> \<Key\>Occasion\</Key\>
> 
> \<Value\>Jamuhuri\</Value\>
> 
> \</ReferenceItem\>
> 
> \</ReferenceData\>
> 
> \<Timestamp\>2013-07-29T18:50:41\.2109675Z\</Timestamp\>
> 
> \</Transaction\>
> 
> \<Identity\>
> 
> \<Caller\>
> 
> \<CallerType\>2\</CallerType\>
> 
> \<ThirdPartyID\> \</ThirdPartyID\>
> 
> \<Password\>Password0\</Password\>
> 
> \<CheckSum\>CheckSum0\</CheckSum\>
> 
> \<ResultURL\>ResultURL0\</ResultURL\>
> 
> \</Caller\>
> 
> \<Initiator\>
> 
> \<IdentifierType\>11\</IdentifierType\>
> 
> \<Identifier\>username\</Identifier\>
> 
> \<SecurityCredential\>SecurityCredential0\</SecurityCredential\>
> 
> \<ShortCode\>859636\</ShortCode\>
> 
> \</Initiator\>
> 
> \<PrimaryParty\>
> 
> \<IdentifierType\>4\</IdentifierType\>
> 
> \<Identifier\>859636\</Identifier\>
> 
> \<ShortCode\>859636\</ShortCode\>
> 
> \</PrimaryParty\>
> 
> \<ReceiverParty\>
> 
> \<IdentifierType\>1\</IdentifierType\>
> 
> \<Identifier\>2547204789659\</Identifier\>
> 
> \<ShortCode\>ShortCode1\</ShortCode\>
> 
> \</ReceiverParty\>
> 
> \<AccessDevice\>
> 
> \<IdentifierType\>1\</IdentifierType\>
> 
> \<Identifier\>Identifier3\</Identifier\>
> 
> \</AccessDevice\>
> 
> \</Identity\>
> 
> \<KeyOwner\>1\</KeyOwner\>
> 
> \</request\>\]\]\>\</req:RequestMsg\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>
> 
> Example2: Request without ResultURL and QueueTimeoutURL
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:req="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>
> 
> \<soapenv:Header\>
> 
> \<tns:RequestSOAPHeader
> xmlns:tns="http://www.huawei.com/schema/osg/common/v2\_1"\>
> 
> \<tns:spId\>35000001\</tns:spId\>
> 
> \<tns:spPassword\>c5216e519a071d601bedd150f3fcd026\</tns:spPassword\>
> 
> \<tns:timeStamp\>20080101010101\</tns:timeStamp\>
> 
> \<tns:serviceId\>35000001000009\</tns:serviceId\>
> 
> \<tns:OA\>861234567890\</tns:OA\>
> 
> \<tns:FA\>861234567890\</tns:FA\>
> 
> \</tns:RequestSOAPHeader\>
> 
> \</soapenv:Header\>
> 
> \<soapenv:Body\>
> 
> \<req:RequestMsg\>\<\!\[CDATA\[\<?xml version="1\.0"
> encoding="UTF-8"?\>
> 
> \<request
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>
> 
> \<Transaction\>
> 
> \<CommandID\>CommandID0\</CommandID\>
> 
> \<LanguageCode\>LanguageCode0\</LanguageCode\>
> 
> \<OriginatorConversationID\>OriginatorConversationID0\</OriginatorConversationID\>
> 
> \<ConversationID\>ConversationID0\</ConversationID\>
> 
> \<Remark\>Remark0\</Remark\>
> 
> \<EncryptedParameters\>EncryptedParameters0\</EncryptedParameters\>
> 
> \<Parameters\>
> 
> \<Parameter\>
> 
> \<Key\>Key0\</Key\>
> 
> \<Value\>Value0\</Value\>
> 
> \</Parameter\>
> 
> \<Parameter\>
> 
> \<Key\>Key1\</Key\>
> 
> \<Value\>Value1\</Value\>
> 
> \</Parameter\>
> 
> \</Parameters\>
> 
> \<ReferenceData\>
> 
> \<ReferenceItem\>
> 
> \<Key\>Key2\</Key\>
> 
> \<Value\>Value2\</Value\>
> 
> \</ReferenceItem\>
> 
> \</ReferenceData\>
> 
> \<Timestamp\>
> 
> \</Timestamp\>
> 
> \</Transaction\>
> 
> \<Identity\>
> 
> \<Caller\>
> 
> \<CallerType\>0\</CallerType\>
> 
> \<ThirdPartyID\>ThirdPartyID0\</ThirdPartyID\>
> 
> \<Password\>Password0\</Password\>
> 
> \<CheckSum\>CheckSum0\</CheckSum\>
> 
> \</Caller\>
> 
> \<Initiator\>
> 
> \<IdentifierType\>1\</IdentifierType\>
> 
> \<Identifier\>Identifier0\</Identifier\>
> 
> \<SecurityCredential\>SecurityCredential0\</SecurityCredential\>
> 
> \<ShortCode\>
> 
> \</ShortCode\>
> 
> \</Initiator\>
> 
> \<PrimartyParty\>
> 
> \<IdentifierType\>1\</IdentifierType\>
> 
> \<Identifier\>Identifier1\</Identifier\>
> 
> \<ShortCode\>ShortCode0\</ShortCode\>
> 
> \</PrimartyParty\>
> 
> \<ReceiverParty\>
> 
> \<IdentifierType\>1\</IdentifierType\>
> 
> \<Identifier\>Identifier2\</Identifier\>
> 
> \<ShortCode\>ShortCode1\</ShortCode\>
> 
> \</ReceiverParty\>
> 
> \<AccessDevice\>
> 
> \<IdentifierType\>1\</IdentifierType\>
> 
> \<Identifier\>Identifier3\</Identifier\>
> 
> \</AccessDevice\>
> 
> \</Identity\>
> 
> \<KeyOwner\>0\</KeyOwner\>
> 
> \</request\>\]\]\>\</req:RequestMsg\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

### The Broker return response to the 3rd party

> Example1: Forward CoreAPI response to the 3<sup>rd</sup> party
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:req="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<req:ResponseMsg\>\<\!\[CDATA\[\<?xml version="1\.0"
> encoding="UTF-8"?\>
> 
> \<response
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/response"\>
> 
> \<ResponseCode\>ResponseCode0\</ResponseCode\>
> 
> \<ResponseDesc\>ResponseDesc0\</ResponseDesc\>
> 
> \<ConversationID\>
> 
> \</ConversationID\>
> 
> \<OriginatorConversationID\>
> 
> \</OriginatorConversationID\>
> 
> \<ServiceStatus\>0\</ServiceStatus\>
> 
> \</response\>\]\]\>\</req:ResponseMsg\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

Or

> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"\>
> 
> \<soapenv:Body\>
> 
> \<req:ResponseMsg
> xmlns:req="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>\<\!\[CDATA\[\<?xml
> version="1\.0"
> encoding="UTF-8"?\>\<Response\>\<ResponseCode\>0\</ResponseCode\>\<ConversationID\>AG\_20140825\_000056ac18ccfd6a13a2\</ConversationID\>\<ResponseDesc\>Accept
> the service request
> successfully.\</ResponseDesc\>\<OriginatorConversationID\>B2C-SIT-000005
> 
> \</OriginatorConversationID\>\<ServiceStatus\>0\</ServiceStatus\>\</Response\>\]\]\>\</req:ResponseMsg\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>
> 
> Example2: Error response caused by authentication failed.
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:req="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<req:ResponseMsg\>\<\!\[CDATA\[\<?xml version="1\.0"
> encoding="UTF-8"?\>
> 
> \<response
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/response"\>
> 
> \<ResponseCode\>100000007\</ResponseCode\>
> 
> \<ResponseDesc\>Authentication failed\</ResponseDesc\>
> 
> \</response\>\]\]\>\</req:ResponseMsg\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>
> 
> Example3: Error response caused by waiting for resending.
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:req="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<req:ResponseMsg\>\<\!\[CDATA\[\<?xml version="1\.0"
> encoding="UTF-8"?\>
> 
> \<response
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/response"\>
> 
> \<ResponseCode\>100000000\</ResponseCode\>
> 
> \<ResponseDesc\>Request was cached, waiting for
> resending\</ResponseDesc\>
> 
> \</response\>\]\]\>\</req:ResponseMsg\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

1.  ## GenericAPIResult
    
    1.  ### The Broker send notification to the 3rd party

> \<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/"\>
> 
> \<s:Body xmlns:xsi="http://www.w3\.org/2001/XMLSchema-instance"
> xmlns:xsd="http://www.w3\.org/2001/XMLSchema"\>
> 
> \<ResultMsg
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/result"\>
> 
> \<\!\[CDATA\[\<Result
> xmlns:i="http://www.w3\.org/2001/XMLSchema-instance"
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/result"\>
> 
> \<ResultType\>Completed\</ResultType\>
> 
> \<ResultCode\>0\</ResultCode\>
> 
> \<ResultDesc\>Success\</ResultDesc\>
> 
> \<OriginatorConversationID\>R9-2-eq-a7cb-q277\</OriginatorConversationID\>
> 
> \<ConversationID\>61da40ad-7e96-4889-83c4-1ea77091f8ec\</ConversationID\>
> 
> \<TransactionID\>X-IO213\</TransactionID\>\<ResultParameters\>
> 
> \<Parameter\>
> 
> \<Key
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>Amount\</Key\>
> 
> \<Value
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>Ksh200\.00\</Value\>
> 
> \</Parameter\>\<Parameter\>\<Key
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>Transaction
> Datetime\</Key\>
> 
> \<Value
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>22/10/2014
> 20:55:24\</Value\>
> 
> \</Parameter\>\<Parameter\>
> 
> \<Key
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>Working
> Account Available Funds\</Key\>
> 
> \<Value
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>2338002\.5100\</Value\>
> 
> \</Parameter\>\<Parameter\>
> 
> \<Key
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>Charges
> Paid Account Available Funds\</Key\>
> 
> \<Value
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>0\.0000\</Value\>
> 
> \</Parameter\>\<Parameter\>
> 
> \<Key
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>Utility
> Account Available Funds\</Key\>
> 
> \<Value
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>461898\.0000\</Value\>
> 
> \</Parameter\>\</ResultParameters\>
> 
> \<ReferenceData\>\<ReferenceItem\>\<Key
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>QueueTimeoutURL\</Key\>\<Value
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>http://10\.66\.49\.201:8097/\</Value\>\</ReferenceItem\>\</ReferenceData\>\</Result\>\]\]\>\</ResultMsg\>
> 
> \</s:Body\>
> 
> \</s:Envelope\>

Or

> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<req:ResultMsg
> xmlns:req="http://cps.huawei.com/cpsinterface/result"\>\<\!\[CDATA\[\<?xml
> version="1\.0" encoding="UTF-8"?\>
> 
> \<Result\>
> 
> \<ResultType\>0\</ResultType\>
> 
> \<ResultCode\>0\</ResultCode\>
> 
> \<ResultDesc\>The service request is processed
> successfully.\</ResultDesc\>
> 
> \<OriginatorConversationID\>D7866050-CE7C-46B9-BE97-D9FBACC69041\</OriginatorConversationID\>
> 
> \<ConversationId\>B72AC018-86E4-477A-B4B0-9EC65AE8A2FE\</ConversationId\>
> 
> \<TransactionId\>2782728972\</TransactionId\>
> 
> \<ResultParameters\>
> 
> \<ResultParameter\>
> 
> \<Key\>TransactionReceipt\</Key\>
> 
> \<Value\>2782728972\</Value\>
> 
> \</ResultParameter\>
> 
> \<ResultParameter\>
> 
> \<Key\>TransactionAmount\</Key\>
> 
> \<Value\>100\.00\</Value\>
> 
> \</ResultParameter\>
> 
> \<ResultParameter\>
> 
> \<Key\>TransactionCompletedDateTime\</Key\>
> 
> \<Value\>22\.03\.2012 12:20:20\</Value\>
> 
> \</ResultParameter\>
> 
> \<ResultParameter\>
> 
> \<Key\>ReceiverPartyPublicName\</Key\>
> 
> \<Value\>254778866553868-Kip Keino\</Value\>
> 
> \</ResultParameter\>
> 
> \<ResultParameter\>
> 
> \<Key\>B2CWorkingAccountAvailableFunds\</Key\>
> 
> \<Value\>10000\.00\</Value\>
> 
> \</ResultParameter\>
> 
> \<ResultParameter\>
> 
> \<Key\>B2CUtilityAccountAvailableFunds\</Key\>
> 
> \<Value\>100000\.00\</Value\>
> 
> \</ResultParameter\>
> 
> \<ResultParameter\>
> 
> \<Key\>B2CChargesPaidAccountAvailableFunds\</Key\>
> 
> \<Value\>1000\.00\</Value\>
> 
> \</ResultParameter\>
> 
> \<ResultParameter\>
> 
> \<Key\>B2CRecipientIsRegisteredCustomer\</Key\>
> 
> \<Value\>Y\</Value\>
> 
> \</ResultParameter\>
> 
> \<ResultParameter\>
> 
> \<Key\>B2CWithdrawalChargeAmount\</Key\>
> 
> \<Value\>12\.00\</Value\>
> 
> \</ResultParameter\>
> 
> \</ResultParameters\>
> 
> \<ReferenceData\>
> 
> \<ReferenceItem\>
> 
> \<Key\>Occasion\</Key\>
> 
> \<Value\>Christmas\</Value\>
> 
> \</ReferenceItem\>
> 
> \</ReferenceData\>
> 
> \</Result\>\]\]\>\</req:ResultMsg\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

### The 3rd party return response to the Broker

> Example1: Success response
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:req="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<req:ResponseMsg\>\<\!\[CDATA\[\<?xml version="1\.0"
> encoding="UTF-8"?\>
> 
> \<response
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/response"\>
> 
> \<ResponseCode\>00000000\</ResponseCode\>
> 
> \<ResponseDesc\>success\</ResponseDesc\>
> 
> \</response\>\]\]\>\</req:ResponseMsg\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>
> 
> Example2: Error response
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:req="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<req:ResponseMsg\>\<\!\[CDATA\[\<?xml version="1\.0"
> encoding="UTF-8"?\>
> 
> \<response
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/response"\>
> 
> \<ResponseCode\>20000003\</ResponseCode\>
> 
> \<ResponseDesc\>Internal Server Error\</ResponseDesc\>
> 
> \</response\>\]\]\>\</req:ResponseMsg\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

1.  ## notifyQueueTimeout
    
    1.  ### The Broker send notification to the 3rd party

> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:loc="http://www.csapi.org/schema/timeoutnotification/data/v1\_0/local"
> xmlns:res="http://api-v1\.gen.mm.vodafone.com/mminterface/result"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<loc:notifyQueueTimeout\>
> 
> \<loc:originatorConversationID\>OriginatorConversationID0\</loc:originatorConversationID\>
> 
> \<loc:originRequest\>PHNvYXBlbnY6RW52ZWxvcGUgeG1sbnM6c29hcGVudj0iaHR0cDovL3NjaGVtYXMueG1sc29hcC5v
> 
> cmcvc29hcC9lbnZlbG9wZS8iIHhtbG5zOnJlcT0iaHR0cDovL2FwaS12MS5nZW4ubW0udm9kYWZv
> 
> bmUuY29tL21taW50ZXJmYWNlL3JlcXVlc3QiPgogICA8c29hcGVudjpCb2R5PgogICAgICA8cmVx
> 
> OlJlcXVlc3RNc2c+PCFbQ0RBVEFbPD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgi
> 
> Pz4KPHJlcXVlc3QgeG1sbnM9Imh0dHA6Ly9hcGktdjEuZ2VuLm1tLnZvZGFmb25lLmNvbS9tbWlu
> 
> dGVyZmFjZS9yZXF1ZXN0Ij4KICAgIDxUcmFuc2FjdGlvbj4KICAgICAgICA8Q29tbWFuZElEPkNv
> 
> bW1hbmRJRDA8L0NvbW1hbmRJRD4KICAgICAgICA8TGFuZ3VhZ2VDb2RlPkxhbmd1YWdlQ29kZTA8
> 
> L0xhbmd1YWdlQ29kZT4KICAgICAgICA8T3JpZ2luYXRvckNvbnZlcnNhdGlvbklEPk9yaWdpbmF0
> 
> b3JDb252ZXJzYXRpb25JRDA8L09yaWdpbmF0b3JDb252ZXJzYXRpb25JRD4KICAgICAgICA8Q29u
> 
> dmVyc2F0aW9uSUQ+Q29udmVyc2F0aW9uSUQwPC9Db252ZXJzYXRpb25JRD4KICAgICAgICA8UmVt
> 
> YXJrPlJlbWFyazA8L1JlbWFyaz4KICAgICAgICA8RW5jcnlwdGVkUGFyYW1ldGVycz5FbmNyeXB0
> 
> ZWRQYXJhbWV0ZXJzMDwvRW5jcnlwdGVkUGFyYW1ldGVycz4KICAgICAgICA8UGFyYW1ldGVycz4K
> 
> ICAgICAgICAgICAgPFBhcmFtZXRlcj4KICAgICAgICAgICAgICAgIDxLZXk+S2V5MDwvS2V5Pgog
> 
> ICAgICAgICAgICAgICAgPFZhbHVlPlZhbHVlMDwvVmFsdWU+CiAgICAgICAgICAgIDwvUGFyYW1l
> 
> dGVyPgogICAgICAgICAgICA8UGFyYW1ldGVyPgogICAgICAgICAgICAgICAgPEtleT5LZXkxPC9L
> 
> ZXk+CiAgICAgICAgICAgICAgICA8VmFsdWU+VmFsdWUxPC9WYWx1ZT4KICAgICAgICAgICAgPC9Q
> 
> YXJhbWV0ZXI+CiAgICAgICAgPC9QYXJhbWV0ZXJzPgogICAgICAgIDxSZWZlcmVuY2VEYXRhPgog
> 
> ICAgICAgICAgICA8UmVmZXJlbmNlSXRlbT4KICAgICAgICAgICAgICAgIDxLZXk+UXVldWVUaW1l
> 
> b3V0VVJMPC9LZXk+CiAgICAgICAgICAgICAgICA8VmFsdWU+VmFsdWUyPC9WYWx1ZT4KICAgICAg
> 
> ICAgICAgPC9SZWZlcmVuY2VJdGVtPgogICAgICAgICAgICA8UmVmZXJlbmNlSXRlbT4KICAgICAg
> 
> ICAgICAgICAgIDxLZXk+S2V5MzwvS2V5PgogICAgICAgICAgICAgICAgPFZhbHVlPlZhbHVlMzwv
> 
> VmFsdWU+CiAgICAgICAgICAgIDwvUmVmZXJlbmNlSXRlbT4KICAgICAgICA8L1JlZmVyZW5jZURh
> 
> dGE+CiAgICAgICAgPFRpbWVzdGFtcD4KICAgICAgICA8L1RpbWVzdGFtcD4KICAgIDwvVHJhbnNh
> 
> Y3Rpb24+CiAgICA8SWRlbnRpdHk+CiAgICAgICAgPENhbGxlcj4KICAgICAgICAgICAgPENhbGxl
> 
> clR5cGU+MDwvQ2FsbGVyVHlwZT4KICAgICAgICAgICAgPFRoaXJkUGFydHlJRD5UaGlyZFBhcnR5
> 
> SUQwPC9UaGlyZFBhcnR5SUQ+CiAgICAgICAgICAgIDxQYXNzd29yZD5QYXNzd29yZDA8L1Bhc3N3
> 
> b3JkPgogICAgICAgICAgICA8Q2hlY2tTdW0+Q2hlY2tTdW0wPC9DaGVja1N1bT4KICAgICAgICAg
> 
> ICAgPFJlc3VsdFVSTD5SZXN1bHRVUkwwPC9SZXN1bHRVUkw+CiAgICAgICAgPC9DYWxsZXI+CiAg
> 
> ICAgICAgPEluaXRpYXRvcj4KICAgICAgICAgICAgPElkZW50aWZpZXJUeXBlPjE8L0lkZW50aWZp
> 
> ZXJUeXBlPgogICAgICAgICAgICA8SWRlbnRpZmllcj5JZGVudGlmaWVyMDwvSWRlbnRpZmllcj4K
> 
> ICAgICAgICAgICAgPFNlY3VyaXR5Q3JlZGVudGlhbD5TZWN1cml0eUNyZWRlbnRpYWwwPC9TZWN1
> 
> cml0eUNyZWRlbnRpYWw+CiAgICAgICAgICAgIDxTaG9ydENvZGU+CiAgICAgICAgICAgIDwvU2hv
> 
> cnRDb2RlPgogICAgICAgIDwvSW5pdGlhdG9yPgogICAgICAgIDxQcmltYXJ0eVBhcnR5PgogICAg
> 
> ICAgICAgICA8SWRlbnRpZmllclR5cGU+MTwvSWRlbnRpZmllclR5cGU+CiAgICAgICAgICAgIDxJ
> 
> ZGVudGlmaWVyPklkZW50aWZpZXIxPC9JZGVudGlmaWVyPgogICAgICAgICAgICA8U2hvcnRDb2Rl
> 
> PlNob3J0Q29kZTA8L1Nob3J0Q29kZT4KICAgICAgICA8L1ByaW1hcnR5UGFydHk+CiAgICAgICAg
> 
> PFJlY2VpdmVyUGFydHk+CiAgICAgICAgICAgIDxJZGVudGlmaWVyVHlwZT4xPC9JZGVudGlmaWVy
> 
> VHlwZT4KICAgICAgICAgICAgPElkZW50aWZpZXI+SWRlbnRpZmllcjI8L0lkZW50aWZpZXI+CiAg
> 
> ICAgICAgICAgIDxTaG9ydENvZGU+U2hvcnRDb2RlMTwvU2hvcnRDb2RlPgogICAgICAgIDwvUmVj
> 
> ZWl2ZXJQYXJ0eT4KICAgICAgICA8QWNjZXNzRGV2aWNlPgogICAgICAgICAgICA8SWRlbnRpZmll
> 
> clR5cGU+MTwvSWRlbnRpZmllclR5cGU+CiAgICAgICAgICAgIDxJZGVudGlmaWVyPklkZW50aWZp
> 
> ZXIzPC9JZGVudGlmaWVyPgogICAgICAgIDwvQWNjZXNzRGV2aWNlPgogICAgPC9JZGVudGl0eT4K
> 
> ICAgIDxLZXlPd25lcj4wPC9LZXlPd25lcj4KPC9yZXF1ZXN0Pl1dPjwvcmVxOlJlcXVlc3RNc2c+
> 
> CiAgIDwvc29hcGVudjpCb2R5Pgo8L3NvYXBlbnY6RW52ZWxvcGU+Cg==\</loc:originRequest\>
> 
> \</loc:notifyQueueTimeout\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

### The 3rd party return response to the Broker

> Example1: Success response
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:loc="http://www.csapi.org/schema/timeoutnotification/data/v1\_0/local"
> xmlns:res="http://api-v1\.gen.mm.vodafone.com/mminterface/result"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<loc:notifyQueueTimeoutResponse\>
> 
> \<loc:result\>
> 
> \<res:ResultCode\>00000000\</res:ResultCode\>
> 
> \<res:ResultDesc\> success\</res:ResultDesc\>
> 
> \</loc:result\>
> 
> \</loc:notifyQueueTimeoutResponse\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>
> 
> Example2: Error response
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:loc="http://www.csapi.org/schema/timeoutnotification/data/v1\_0/local"
> xmlns:res="http://api-v1\.gen.mm.vodafone.com/mminterface/result"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<loc:notifyQueueTimeoutResponse\>
> 
> \<loc:result\>
> 
> \<res:ResultCode\>000000001\</res:ResultCode\>
> 
> \<res:ResultDesc\> failed \</res:ResultDesc\>
> 
> \</loc:result\>
> 
> \</loc:notifyQueueTimeoutResponse\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

1.  ## queryTransaction
    
    1.  ### The 3rd party sends query request to the Broker

> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:v2="http://www.huawei.com.cn/schema/common/v2\_1"
> xmlns:loc="http://www.csapi.org/schema/transaction/data/v1\_0/local"
> xmlns:res="http://api-v1\.gen.mm.vodafone.com/mminterface/result"\>
> 
> \<soapenv:Header\>
> 
> \<v2:RequestSOAPHeader\>
> 
> \<v2:spId\>151515\</v2:spId\>
> 
> \<v2:spPassword\>ODExNERCMDlCNjVDRkYxQUFCNzE5MkE1OEQyMjJDMzk1RUFCNzgwMjk2ODE4Rjk1OTE2MEFGNDU1QkRCMDkyMg==\</v2:spPassword\>
> 
> \<v2:serviceId\>151515000\</v2:serviceId\>
> 
> \<v2:timeStamp\>20140730093620\</v2:timeStamp\>
> 
> \</v2:RequestSOAPHeader\>
> 
> \</soapenv:Header\>
> 
> \<soapenv:Body\>
> 
> \<loc:queryTransaction\>
> 
> \<loc:originatorConversationID\>R9I1-0000-4225-g64153\</loc:originatorConversationID\>
> 
> \<loc:extensionInfo\>
> 
> \<loc:item\>
> 
> \<res:Key\>queryDate\</res:Key\>
> 
> \<res:Value\>20140930102022\</res:Value\>
> 
> \</loc:item\>
> 
> \</loc:extensionInfo\>
> 
> \</loc:queryTransaction\>
> 
> \</soapenv:Body\>

### The Broker return response to the 3rd party

> Example1: Success response
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:xsi="http://www.w3\.org/2001/XMLSchema-instance"\>
> 
> \<soapenv:Body\>
> 
> \<ns1:queryTransactionResponse
> xmlns:ns1="http://www.csapi.org/schema/transaction/data/v1\_0/local"\>
> 
> \<ns1:result\>
> 
> \<ns2:ResponseCode
> xmlns:ns2="http://api-v1\.gen.mm.vodafone.com/mminterface/response"\>00000000\</ns2:ResponseCode\>
> 
> \<ns3:ResponseDesc
> xmlns:ns3="http://api-v1\.gen.mm.vodafone.com/mminterface/response"\>Success\</ns3:ResponseDesc\>
> 
> \</ns1:result\>
> 
> \<ns1:submitApiRequestList\>
> 
> \<ns1:submitApiRequest\>UE9TVCAvbW1pbnRlcmZhY2UvcmVxdWVzdCBIVFRQLzEuMQ0KQWNjZXB0LUVuY29kaW5nOiBnemlwLGRlZmxhdGUNCkNvbnRlbnQtVHlwZTogdGV4dC94bWw7Y2hhcnNldD1VVEYtOA0KU09BUEFjdGlvbjogIiINClVzZXItQWdlbnQ6IEpha2FydGEgQ29tbW9ucy1IdHRwQ2xpZW50LzMuMQ0KSG9zdDogMTAuNS4zOC41MTo4MzEwDQpDb250ZW50LUxlbmd0aDogMjU1MQ0KDQo8c29hcGVudjpFbnZlbG9wZSB4bWxuczpzb2FwZW52PSJodHRwOi8vc2NoZW1hcy54bWxzb2FwLm9yZy9zb2FwL2VudmVsb3BlLyIgeG1sbnM6cmVxPSJodHRwOi8vYXBpLXYxLmdlbi5tbS52b2RhZm9uZS5jb20vbW1pbnRlcmZhY2UvcmVxdWVzdCI+CiAgIDxzb2FwZW52OkhlYWRlcj4KICAgICAgPHRuczpSZXF1ZXN0U09BUEhlYWRlciB4bWxuczp0bnM9Imh0dHA6Ly93d3cuaHVhd2VpLmNvbS9zY2hlbWEvb3NnL2NvbW1vbi92Ml8xIj4KICAgICAgICAgPHRuczpzcElkPjE1MTUxNTwvdG5zOnNwSWQ+CiAgICAgICAgIDx0bnM6c3BQYXNzd29yZD5PREV4TkVSQ01EbENOalZEUmtZeFFVRkNOekU1TWtFMU9FUXlNakpETXprMVJVRkNOemd3TWprMk9ERTRSamsxT1RFMk1FRkdORFUxUWtSQ01Ea3lNZz09PC90bnM6c3BQYXNzd29yZD4KICAgICAgICAgPHRuczp0aW1lU3RhbXA+MjAxNDA3MzAwOTM2MjA8L3Ruczp0aW1lU3RhbXA+CiAgICAgICAgIDx0bnM6c2VydmljZUlkPjE1MTUxNTAwMDwvdG5zOnNlcnZpY2VJZD4KICAgICAgPC90bnM6UmVxdWVzdFNPQVBIZWFkZXI+CiAgIDwvc29hcGVudjpIZWFkZXI+CiAgIDxzb2FwZW52OkJvZHk+CiAgICAgIDxyZXE6UmVxdWVzdE1zZz48IVtDREFUQVs8P3htbCB2ZXJzaW9uPScnMS4wJycgZW5jb2Rpbmc9JydVVEYtOCcnPz48cmVxdWVzdCB4bWxucz0nJ2h0dHA6Ly9hcGktdjEuZ2VuLm1tLnZvZGFmb25lLmNvbS9tbWludGVyZmFjZS9yZXF1ZXN0Jyc+CjxUcmFuc2FjdGlvbj4KCTxDb21tYW5kSUQ+U2FsYXJ5UGF5bWVudDwvQ29tbWFuZElEPgoJPExhbmd1YWdlQ29kZT4wPC9MYW5ndWFnZUNvZGU+Cgk8T3JpZ2luYXRvckNvbnZlcnNhdGlvbklEPlI5STEtMDAwMC00MjI1LWc2NDE1MzwvT3JpZ2luYXRvckNvbnZlcnNhdGlvbklEPgoJPENvbnZlcnNhdGlvbklEPjwvQ29udmVyc2F0aW9uSUQ+Cgk8UmVtYXJrPjA8L1JlbWFyaz4KCTxFbmNyeXB0ZWRQYXJhbWV0ZXJzPkVuY3J5cHRlZFBhcmFtZXRlcnMwPC9FbmNyeXB0ZWRQYXJhbWV0ZXJzPgo8UGFyYW1ldGVycz48UGFyYW1ldGVyPgoJPEtleT5BbW91bnQ8L0tleT4KCTxWYWx1ZT43MC4wMDwvVmFsdWU+CjwvUGFyYW1ldGVyPgoKICAgICAgICAgICAgCgo8L1BhcmFtZXRlcnM+CjxSZWZlcmVuY2VEYXRhPgoJPFJlZmVyZW5jZUl0ZW0+CgkJPEtleT5RdWV1ZVRpbWVvdXRVUkw8L0tleT4KCQk8VmFsdWU+aHR0cDovLzEwLjY2LjQ5LjIwMTo4OTg5LzwvVmFsdWU+Cgk8L1JlZmVyZW5jZUl0ZW0+PC9SZWZlcmVuY2VEYXRhPgoJPFRpbWVzdGFtcD4yMDE0LTA5LTI3VDEyOjUzOjE5LjAwMDA1MjFaPC9UaW1lc3RhbXA+CjwvVHJhbnNhY3Rpb24+CjxJZGVudGl0eT4KCTxDYWxsZXI+CgkJPENhbGxlclR5cGU+MjwvQ2FsbGVyVHlwZT4KCQk8VGhpcmRQYXJ0eUlEPjg5ODk0MTwvVGhpcmRQYXJ0eUlEPgoJCTxQYXNzd29yZD5QYXNzd29yZDA8L1Bhc3N3b3JkPgoJCTxDaGVja1N1bT5DaGVja1N1bTA8L0NoZWNrU3VtPgoJCTxSZXN1bHRVUkw+aHR0cDovLzEwLjY2LjQ5LjIwMTo4MDk3LzwvUmVzdWx0VVJMPgoJPC9DYWxsZXI+Cgk8SW5pdGlhdG9yPgoJCTxJZGVudGlmaWVyVHlwZT4xMTwvSWRlbnRpZmllclR5cGU+CgkJPElkZW50aWZpZXI+YjJjMmI8L0lkZW50aWZpZXI+CgkJPFNlY3VyaXR5Q3JlZGVudGlhbD5iSkpiQ0E0UVQvVzdwVlQ5ZyszZGN0alFJRlUyb2pTVVZlcXo1WVVCK3VVcDY2RDlVaGpqWnNoWEp5KzltRGVTcFJuRVFiczZIOHdHcmhoMjNBVnVQMi9jeURxRTZ4ZmhhU2hXM0tkdFZ0K0FxdWF0VWFCZkxiNlNQZ045ZWdrVWtuNGhzWFdrK25oZlk3UnNtZE1LeTRJUkJZVGlqTXVlUGU2eUd3MTdrZUVqWk9MNCtrNG5XYTFqVnZScFBJNnVBRkpTWTMzcEl4dUxoMlR4K2tBcmc1STRCNEpRS09pdzJtN0NQblZVMGpodnE4eHNHYXJPSW4yQ09DakV0M0cvQnIwV3Bucks3MStIenZoQUJoOVU4bG5OMjVFdlU3cmpBVHpMd2xGOE1nVnYra3UySERTNjJ4MFptVEtVWEgxc3JzU0JhS0VqaVRoY2NGcmZYVEVrRlE9PTwvU2VjdXJpdHlDcmVkZW50aWFsPgoJCTxTaG9ydENvZGU+ODk4OTQ3PC9TaG9ydENvZGU+Cgk8L0luaXRpYXRvcj4KCQk8UHJpbWFyeVBhcnR5PgoJCQk8SWRlbnRpZmllclR5cGU+NDwvSWRlbnRpZmllclR5cGU+CgkJCTxJZGVudGlmaWVyPjg5ODk0NjwvSWRlbnRpZmllcj4KCQkJPFNob3J0Q29kZT48L1Nob3J0Q29kZT4KCQk8L1ByaW1hcnlQYXJ0eT4KCTxSZWNlaXZlclBhcnR5PgoJCTxJZGVudGlmaWVyVHlwZT4xPC9JZGVudGlmaWVyVHlwZT4KCQk8SWRlbnRpZmllcj4yNTQ3MDcxNjM2MDU8L0lkZW50aWZpZXI+CgkJPFNob3J0Q29kZT48L1Nob3J0Q29kZT4KCTwvUmVjZWl2ZXJQYXJ0eT4KCTxBY2Nlc3NEZXZpY2U+CgkJPElkZW50aWZpZXJUeXBlPjE8L0lkZW50aWZpZXJUeXBlPgoJCTxJZGVudGlmaWVyPklkZW50aWZpZXIzPC9JZGVudGlmaWVyPgoJCTwvQWNjZXNzRGV2aWNlPjwvSWRlbnRpdHk+CgkJPEtleU93bmVyPjE8L0tleU93bmVyPgoJPC9yZXF1ZXN0Pl1dPjwvcmVxOlJlcXVlc3RNc2c+CiAgIDwvc29hcGVudjpCb2R5Pgo8L3NvYXBlbnY6RW52ZWxvcGU+\</ns1:submitApiRequest\>
> 
> \<ns1:submitApiRequest\>UE9TVCAvQ29yZUFwaVdlYlNlcnZpY2UvR2VuZXJpY0FwaS5zdmMgSFRUUC8xLjENCkNvbnRlbnQtVHlwZTogdGV4dC94bWwNCkhvc3Q6IDg1LjIwNS4xNjUuMTk3OjE4MjAyDQpDb25uZWN0aW9uOiBjbG9zZQ0KQ29udGVudC1MZW5ndGg6IDIxNDYNCg0KPHNvYXBlbnY6RW52ZWxvcGUgeG1sbnM6c29hcGVudj0iaHR0cDovL3NjaGVtYXMueG1sc29hcC5vcmcvc29hcC9lbnZlbG9wZS8iIHhtbG5zOnJlcT0iaHR0cDovL2FwaS12MS5nZW4ubW0udm9kYWZvbmUuY29tL21taW50ZXJmYWNlL3JlcXVlc3QiPgogICAKICAgPHNvYXBlbnY6Qm9keT4KICAgICAgPHJlcTpSZXF1ZXN0TXNnPjwhW0NEQVRBWzw/eG1sIHZlcnNpb249JycxLjAnJyBlbmNvZGluZz0nJ1VURi04Jyc/PjxyZXF1ZXN0IHhtbG5zPScnaHR0cDovL2FwaS12MS5nZW4ubW0udm9kYWZvbmUuY29tL21taW50ZXJmYWNlL3JlcXVlc3QnJz4KPFRyYW5zYWN0aW9uPgoJPENvbW1hbmRJRD5TYWxhcnlQYXltZW50PC9Db21tYW5kSUQ+Cgk8TGFuZ3VhZ2VDb2RlPjA8L0xhbmd1YWdlQ29kZT4KCTxPcmlnaW5hdG9yQ29udmVyc2F0aW9uSUQ+UjlJMS0wMDAwLTQyMjUtZzY0MTUzPC9PcmlnaW5hdG9yQ29udmVyc2F0aW9uSUQ+Cgk8Q29udmVyc2F0aW9uSUQ+PC9Db252ZXJzYXRpb25JRD4KCTxSZW1hcms+MDwvUmVtYXJrPgoJPEVuY3J5cHRlZFBhcmFtZXRlcnM+RW5jcnlwdGVkUGFyYW1ldGVyczA8L0VuY3J5cHRlZFBhcmFtZXRlcnM+CjxQYXJhbWV0ZXJzPjxQYXJhbWV0ZXI+Cgk8S2V5PkFtb3VudDwvS2V5PgoJPFZhbHVlPjcwLjAwPC9WYWx1ZT4KPC9QYXJhbWV0ZXI+CgogICAgICAgICAgICAKCjwvUGFyYW1ldGVycz4KPFJlZmVyZW5jZURhdGE+Cgk8UmVmZXJlbmNlSXRlbT4KCQk8S2V5PlF1ZXVlVGltZW91dFVSTDwvS2V5PgoJCTxWYWx1ZT5odHRwOi8vMTAuNjYuNDkuMjAxOjg5ODkvPC9WYWx1ZT4KCTwvUmVmZXJlbmNlSXRlbT48L1JlZmVyZW5jZURhdGE+Cgk8VGltZXN0YW1wPjIwMTQtMDktMjdUMTI6NTM6MTkuMDAwMDUyMVo8L1RpbWVzdGFtcD4KPC9UcmFuc2FjdGlvbj4KPElkZW50aXR5PgoJPENhbGxlcj4KCQk8Q2FsbGVyVHlwZT4yPC9DYWxsZXJUeXBlPgoJCTxUaGlyZFBhcnR5SUQ+ODk4OTQxPC9UaGlyZFBhcnR5SUQ+CgkJPFBhc3N3b3JkPlBhc3N3b3JkMDwvUGFzc3dvcmQ+CgkJPENoZWNrU3VtPkNoZWNrU3VtMDwvQ2hlY2tTdW0+CgkJPFJlc3VsdFVSTD5odHRwczovLzE5Ni4yMDEuMjE0LjEzNjoxODMyMy9tbWludGVyZmFjZS9yZXN1bHQ8L1Jlc3VsdFVSTD4KCTwvQ2FsbGVyPgoJPEluaXRpYXRvcj4KCQk8SWRlbnRpZmllclR5cGU+MTE8L0lkZW50aWZpZXJUeXBlPgoJCTxJZGVudGlmaWVyPmIyYzJiPC9JZGVudGlmaWVyPgoJCTxTZWN1cml0eUNyZWRlbnRpYWw+YkpKYkNBNFFUL1c3cFZUOWcrM2RjdGpRSUZVMm9qU1VWZXF6NVlVQit1VXA2NkQ5VWhqalpzaFhKeSs5bURlU3BSbkVRYnM2SDh3R3JoaDIzQVZ1UDIvY3lEcUU2eGZoYVNoVzNLZHRWdCtBcXVhdFVhQmZMYjZTUGdOOWVna1VrbjRoc1hXaytuaGZZN1JzbWRNS3k0SVJCWVRpak11ZVBlNnlHdzE3a2VFalpPTDQrazRuV2ExalZ2UnBQSTZ1QUZKU1kzM3BJeHVMaDJUeCtrQXJnNUk0QjRKUUtPaXcybTdDUG5WVTBqaHZxOHhzR2FyT0luMkNPQ2pFdDNHL0JyMFdwbnJLNzErSHp2aEFCaDlVOGxuTjI1RXZVN3JqQVR6THdsRjhNZ1Z2K2t1MkhEUzYyeDBabVRLVVhIMXNyc1NCYUtFamlUaGNjRnJmWFRFa0ZRPT08L1NlY3VyaXR5Q3JlZGVudGlhbD4KCQk8U2hvcnRDb2RlPjg5ODk0NzwvU2hvcnRDb2RlPgoJPC9Jbml0aWF0b3I+CgkJPFByaW1hcnlQYXJ0eT4KCQkJPElkZW50aWZpZXJUeXBlPjQ8L0lkZW50aWZpZXJUeXBlPgoJCQk8SWRlbnRpZmllcj44OTg5NDY8L0lkZW50aWZpZXI+CgkJCTxTaG9ydENvZGU+PC9TaG9ydENvZGU+CgkJPC9QcmltYXJ5UGFydHk+Cgk8UmVjZWl2ZXJQYXJ0eT4KCQk8SWRlbnRpZmllclR5cGU+MTwvSWRlbnRpZmllclR5cGU+CgkJPElkZW50aWZpZXI+MjU0NzA3MTYzNjA1PC9JZGVudGlmaWVyPgoJCTxTaG9ydENvZGU+PC9TaG9ydENvZGU+Cgk8L1JlY2VpdmVyUGFydHk+Cgk8QWNjZXNzRGV2aWNlPgoJCTxJZGVudGlmaWVyVHlwZT4xPC9JZGVudGlmaWVyVHlwZT4KCQk8SWRlbnRpZmllcj5JZGVudGlmaWVyMzwvSWRlbnRpZmllcj4KCQk8L0FjY2Vzc0RldmljZT48L0lkZW50aXR5PgoJCTxLZXlPd25lcj4xPC9LZXlPd25lcj4KCTwvcmVxdWVzdD5dXT48L3JlcTpSZXF1ZXN0TXNnPgogICA8L3NvYXBlbnY6Qm9keT4KPC9zb2FwZW52OkVudmVsb3BlPg==\</ns1:submitApiRequest\>
> 
> \</ns1:submitApiRequestList\>
> 
> \<ns1:submitApiResponseList\>
> 
> \<ns1:submitApiResponse\>SFRUUC8xLjEgMjAwIE9LDQpDb250ZW50LVR5cGU6IHRleHQveG1sOyBjaGFyc2V0PXV0Zi04DQpTZXJ2ZXI6IE1pY3Jvc29mdC1JSVMvNy4wDQpYLVBvd2VyZWQtQnk6IEFTUC5ORVQNCkRhdGU6IFR1ZSwgMzAgU2VwIDIwMTQgMTI6NTE6MzUgR01UDQpDb25uZWN0aW9uOiBjbG9zZQ0KQ29udGVudC1MZW5ndGg6IDYzNQ0KDQo8czpFbnZlbG9wZSB4bWxuczpzPSJodHRwOi8vc2NoZW1hcy54bWxzb2FwLm9yZy9zb2FwL2VudmVsb3BlLyI+PHM6Qm9keSB4bWxuczp4c2k9Imh0dHA6Ly93d3cudzMub3JnLzIwMDEvWE1MU2NoZW1hLWluc3RhbmNlIiB4bWxuczp4c2Q9Imh0dHA6Ly93d3cudzMub3JnLzIwMDEvWE1MU2NoZW1hIj48UmVzcG9uc2VNc2cgeG1sbnM9Imh0dHA6Ly9hcGktdjEuZ2VuLm1tLnZvZGFmb25lLmNvbS9tbWludGVyZmFjZS9yZXF1ZXN0Ij48IVtDREFUQVs8UmVzcG9uc2UgeG1sbnM6aT0iaHR0cDovL3d3dy53My5vcmcvMjAwMS9YTUxTY2hlbWEtaW5zdGFuY2UiIHhtbG5zPSJodHRwOi8vYXBpLXYxLmdlbi5tbS52b2RhZm9uZS5jb20vbW1pbnRlcmZhY2UvcmVzcG9uc2UiPjxSZXNwb25zZUNvZGU+MDwvUmVzcG9uc2VDb2RlPjxDb252ZXJzYXRpb25JRD5lMGU5NjhmNS04Y2VhLTQzMTMtYWFjZi0wNzljNWNhNDdkMDE8L0NvbnZlcnNhdGlvbklEPjxPcmlnaW5hdG9yQ29udmVyc2F0aW9uSUQ+UjlJMS0wMDAwLTQyMjUtZzY0MTUzPC9PcmlnaW5hdG9yQ29udmVyc2F0aW9uSUQ+PFNlcnZpY2VTdGF0dXM+MDwvU2VydmljZVN0YXR1cz48L1Jlc3BvbnNlPl1dPjwvUmVzcG9uc2VNc2c+PC9zOkJvZHk+PC9zOkVudmVsb3BlPg==\</ns1:submitApiResponse\>
> 
> \<ns1:submitApiResponse\>SFRUUC8xLjEgMjAwIE9LDQpDb250ZW50LVR5cGU6IHRleHQveG1sDQpDb25uZWN0aW9uOiBjbG9zZQ0KQ29udGVudC1MZW5ndGg6IDYzNQ0KDQo8czpFbnZlbG9wZSB4bWxuczpzPSJodHRwOi8vc2NoZW1hcy54bWxzb2FwLm9yZy9zb2FwL2VudmVsb3BlLyI+PHM6Qm9keSB4bWxuczp4c2k9Imh0dHA6Ly93d3cudzMub3JnLzIwMDEvWE1MU2NoZW1hLWluc3RhbmNlIiB4bWxuczp4c2Q9Imh0dHA6Ly93d3cudzMub3JnLzIwMDEvWE1MU2NoZW1hIj48UmVzcG9uc2VNc2cgeG1sbnM9Imh0dHA6Ly9hcGktdjEuZ2VuLm1tLnZvZGFmb25lLmNvbS9tbWludGVyZmFjZS9yZXF1ZXN0Ij48IVtDREFUQVs8UmVzcG9uc2UgeG1sbnM6aT0iaHR0cDovL3d3dy53My5vcmcvMjAwMS9YTUxTY2hlbWEtaW5zdGFuY2UiIHhtbG5zPSJodHRwOi8vYXBpLXYxLmdlbi5tbS52b2RhZm9uZS5jb20vbW1pbnRlcmZhY2UvcmVzcG9uc2UiPjxSZXNwb25zZUNvZGU+MDwvUmVzcG9uc2VDb2RlPjxDb252ZXJzYXRpb25JRD5lMGU5NjhmNS04Y2VhLTQzMTMtYWFjZi0wNzljNWNhNDdkMDE8L0NvbnZlcnNhdGlvbklEPjxPcmlnaW5hdG9yQ29udmVyc2F0aW9uSUQ+UjlJMS0wMDAwLTQyMjUtZzY0MTUzPC9PcmlnaW5hdG9yQ29udmVyc2F0aW9uSUQ+PFNlcnZpY2VTdGF0dXM+MDwvU2VydmljZVN0YXR1cz48L1Jlc3BvbnNlPl1dPjwvUmVzcG9uc2VNc2c+PC9zOkJvZHk+PC9zOkVudmVsb3BlPg==\</ns1:submitApiResponse\>
> 
> \</ns1:submitApiResponseList\>
> 
> \<ns1:submitApiResultList\>
> 
> \<ns1:submitApiResult\>UE9TVCAvIEhUVFAvMS4xDQpDb250ZW50LVR5cGU6IHRleHQveG1sDQpIb3N0OiAxMC42Ni40OS4yMDE6ODA5Nw0KQ29ubmVjdGlvbjogY2xvc2UNCkNvbnRlbnQtTGVuZ3RoOiAxMTc5DQoNCjxzOkVudmVsb3BlIHhtbG5zOnM9Imh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3NvYXAvZW52ZWxvcGUvIj48czpCb2R5IHhtbG5zOnhzaT0iaHR0cDovL3d3dy53My5vcmcvMjAwMS9YTUxTY2hlbWEtaW5zdGFuY2UiIHhtbG5zOnhzZD0iaHR0cDovL3d3dy53My5vcmcvMjAwMS9YTUxTY2hlbWEiPjxSZXN1bHRNc2cgeG1sbnM9Imh0dHA6Ly9hcGktdjEuZ2VuLm1tLnZvZGFmb25lLmNvbS9tbWludGVyZmFjZS9yZXN1bHQiPjwhW0NEQVRBWzxSZXN1bHQgeG1sbnM6aT0iaHR0cDovL3d3dy53My5vcmcvMjAwMS9YTUxTY2hlbWEtaW5zdGFuY2UiIHhtbG5zPSJodHRwOi8vYXBpLXYxLmdlbi5tbS52b2RhZm9uZS5jb20vbW1pbnRlcmZhY2UvcmVzdWx0Ij48UmVzdWx0VHlwZT5Db21wbGV0ZWQ8L1Jlc3VsdFR5cGU+PFJlc3VsdENvZGU+MTk8L1Jlc3VsdENvZGU+PFJlc3VsdERlc2M+QXBpUmVxdWVzdE1lc3NhZ2VFeHBpcnlGYWlsdXJlPC9SZXN1bHREZXNjPjxPcmlnaW5hdG9yQ29udmVyc2F0aW9uSUQ+UjlJMS0wMDAwLTQyMjUtZzY0MTUzPC9PcmlnaW5hdG9yQ29udmVyc2F0aW9uSUQ+PENvbnZlcnNhdGlvbklEPmUwZTk2OGY1LThjZWEtNDMxMy1hYWNmLTA3OWM1Y2E0N2QwMTwvQ29udmVyc2F0aW9uSUQ+PFJlc3VsdFBhcmFtZXRlcnM+PFBhcmFtZXRlcj48S2V5IHhtbG5zPSJodHRwOi8vYXBpLXYxLmdlbi5tbS52b2RhZm9uZS5jb20vbW1pbnRlcmZhY2UvcmVxdWVzdCI+VHJhbnNhY3Rpb24gRGF0ZVRpbWU8L0tleT48VmFsdWUgeG1sbnM9Imh0dHA6Ly9hcGktdjEuZ2VuLm1tLnZvZGFmb25lLmNvbS9tbWludGVyZmFjZS9yZXF1ZXN0Ij4zMC4wOS4yMDE0IDEyOjUyOjMxPC9WYWx1ZT48L1BhcmFtZXRlcj48L1Jlc3VsdFBhcmFtZXRlcnM+PFJlZmVyZW5jZURhdGE+PFJlZmVyZW5jZUl0ZW0+PEtleSB4bWxucz0iaHR0cDovL2FwaS12MS5nZW4ubW0udm9kYWZvbmUuY29tL21taW50ZXJmYWNlL3JlcXVlc3QiPlF1ZXVlVGltZW91dFVSTDwvS2V5PjxWYWx1ZSB4bWxucz0iaHR0cDovL2FwaS12MS5nZW4ubW0udm9kYWZvbmUuY29tL21taW50ZXJmYWNlL3JlcXVlc3QiPmh0dHA6Ly8xMC42Ni40OS4yMDE6ODk4OS88L1ZhbHVlPjwvUmVmZXJlbmNlSXRlbT48L1JlZmVyZW5jZURhdGE+PC9SZXN1bHQ+XV0+PC9SZXN1bHRNc2c+PC9zOkJvZHk+PC9zOkVudmVsb3BlPg==\</ns1:submitApiResult\>
> 
> \</ns1:submitApiResultList\>
> 
> \<ns1:queueTimeOutList/\>
> 
> \</ns1:queryTransactionResponse\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>Example2: Error response
> 
> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:loc="http://www.csapi.org/schema/transaction/data/v1\_0/local"
> xmlns:res="http://api-v1\.gen.mm.vodafone.com/mminterface/response"
> xmlns:res1="http://api-v1\.gen.mm.vodafone.com/mminterface/result"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<loc:queryTransactionResponse\>
> 
> \<loc:result\>
> 
> \<ResponseCode\>100000007\</ResponseCode\>
> 
> \<ResponseDesc\>Authentication failed\</ResponseDesc\>
> 
> \</loc:result\>
> 
> \</loc:queryTransactionResponse\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

1.  ## changePassword
    
    1.  ### Request example:

> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:loc="http://www.csapi.org/schema/management/data/v1\_0/local"
> xmlns:res="http://api-v1\.gen.mm.vodafone.com/mminterface/result"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<loc:changePassword\>
> 
> \<loc:spId\>3500001\</loc:spId\>
> 
> \<loc:spPassword\>c5216e519a071d601bedd150f3fcd026\</loc:spPassword\>
> 
> \<loc:timeStamp\>20120101010101\</loc:timeStamp\>
> 
> \<loc:newPassword\>wi2a7BAH0QPd2LRdmcgC9w==\</loc:newPassword\>
> 
> \</loc:changePassword\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

### Response example:

* Example1: Success response

> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:loc="http://www.csapi.org/schema/transaction/data/v1\_0/local"
> xmlns:res="http://api-v1\.gen.mm.vodafone.com/mminterface/response"
> xmlns:res1="http://api-v1\.gen.mm.vodafone.com/mminterface/result"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<loc:changePassword Response\>
> 
> \<loc:result\>
> 
> \<res:ResponseCode\>00000000\</res:ResponseCode\>
> 
> \<res:ResponseDesc\>Success\</res:ResponseDesc\>
> 
> \</loc:result\>
> 
> \<loc:changePasswordResponse\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

* Example2: Error response caused by authentication failed.

> \<soapenv:Envelope
> xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
> xmlns:req="http://api-v1\.gen.mm.vodafone.com/mminterface/request"\>
> 
> \<soapenv:Header/\>
> 
> \<soapenv:Body\>
> 
> \<req:ResponseMsg\>\<\!\[CDATA\[\<?xml version="1\.0"
> encoding="UTF-8"?\>
> 
> \<response
> xmlns="http://api-v1\.gen.mm.vodafone.com/mminterface/response"\>
> 
> \<ResponseCode\>100000007\</ResponseCode\>
> 
> \<ResponseDesc\>Authentication failed\</ResponseDesc\>
> 
> \</response\>\]\]\>\</req:ResponseMsg\>
> 
> \</soapenv:Body\>
> 
> \</soapenv:Envelope\>

