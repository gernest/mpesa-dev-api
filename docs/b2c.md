#
 B2C API Specification


# Approvals    

This document needs below approvals for implementation   


  **Author(s)**                         | **Name**         |**Signature**    |  **Date**
----------------------------------------|-----------------|------------------|-------------
 Service Development Engineer           | Eneth Kubai      |                 |
 
 
  **Reviewers**                          |  **Name**        |   **Signature**|    **Date**
  ---------------------------------------|------------------|----------------|---------------
 Senior Manager Service Development      | Reginald Tole    |                |

## Revision Log

   **Revision Number**|  **Revision Date**   | **Revision**  |**Revision made by**
-----------------------|-----------------------|--------------|--------------------
   1.0                 | 18th June, 2013      | Initial Draft  |Eneth Kubai
   1.1                 | 9^th^ July, 2013      |Added section 3.8.1: Password Encryption | Eric Mokaya
   1.2                 |   29^th^ July 2013   |  Added Result codes  | Eneth Kubai
   1.3                 | 13^th^ Jan 2014    | Added Result code explanations  | Eneth Kubai
   1.4                 |  ^th^ Sept 2014     |Added changePassword interface, edited queryTransaction Interface, edited OriginatorConversationId field restrictions. Removed encrypted parameter tag. Edited the genericAPI request, response and result, added result and response codes   | Eneth Kubai
   1.5                 |   11^th^ Nov 2014     | Attached SSL Guide       | Eneth Kubai


### References 

  **Document**  | **Author** |    **Name**
  --------------|-----------|--------------------
                |Eneth Kubai |   Response and Result Codes V1.0
                | John Barii |    SSL Guide

## Abbreviations

   **Term**    | **Definition**
-------------|------------------------------------
 API        | Application Programming Interface
 B2C        | Business to Customer
 Broker     | Service Access Gateway
 SP         | Service Provider

# Introduction

## Scope

 The present document specifies the real time B2C Web Service aspects
 of the interface. All aspects of B2C Web Service are defined here,
 these being:

- Message Flow Description

- Data Type Definition

- Web Service Interface Definition

- WSDL for this specification

- Example
