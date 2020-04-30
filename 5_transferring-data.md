---
layout: page
title: Transferring Data
permalink: /transferring-data/
nav: true
weight: 5
---

## De-identify data as needed.
Depending on the data request, the data owner may need to de-identify data in order to protect the privacy and rights of the individuals represented in the data. There are a number of ways to de-identify data, and these are summarized below.

### Removing PII and confidential data
One way to de-identify data is to remove all of the fields that could be used to identify a specific individual from the data. Examples include names, phone numbers, and birthdays. (For more information about confidential data, see the section [Document critical data elements](/data-sharing-playbook/safeguarding-data/#document-critical-data-elements).) 

### Aggregating data
Data owners can also choose to aggregate data. This is accomplished by providing counts of specific fields for a dataset. For example, sensitive fields like birthday and address can be converted to age range and zip code in order to provide the counts of each age group living in a specific area. 

When aggregating data, it’s important to ensure that groups aren’t split up so much that it’s still possible to identify individuals. For example, if you’re aggregating based on school, test scores, grade, and race and ethnicity, the counts can’t be small enough for someone to identify individual students. 

### Recommended reading 
* [Connecticut Data Aggregation Guidance](https://portal.ct.gov/CTData/Content/Agency-Guidance)
* [FERPA Data Suppression Guidelines](http://edsight.ct.gov/relatedreports/BDCRE%20Data%20Suppression%20Rules.pdf)
* [Guidance Regarding Methods for De-identification of Protected Health Information in Accordance with the Health Insurance Portability and Accountability Act (HIPAA) Privacy Rule](https://www.hhs.gov/hipaa/for-professionals/privacy/special-topics/de-identification/index.html)
* [Guidelines for Data De-Identification or Anonymization](https://www.educause.edu/focus-areas-and-initiatives/policy-and-security/cybersecurity-program/resources/information-security-guide/toolkits/guidelines-for-data-deidentification-or-anonymization)
* [De-Identification of Personal Information](https://nvlpubs.nist.gov/nistpubs/ir/2015/NIST.IR.8053.pdf)
* [Guide to Basic Data Anonymization Techniques](https://iapp.org/media/pdf/resource_center/Guide_to_Anonymisation.pdf)

## Choose the right method for transferring data.
Once the parties have agreed to share data, it’s time to consider the logistics of transferring the data. The method will vary based on the sensitivity of the data.

### Open and public data
Data that is open to the public doesn’t require a secure channel for data transfer. Some options that might be suited for file transfers are:

| **Technology** | **File size limits** | **Usage notes** | 
| ----------- | ----------- | ----------- |
| Email (ct.gov and po.state.ct.us) | 20MB, 35MB | 35MB but depends on the recipients size limit also, they could have a 20MB limit. | 
| Microsoft Office 360 OneDrive (ct.gov and po.state.ct.us) | 100GB | | 
| Approved external device | varies | Ask IT department for more information | 
| Shared network drive | varies | Ask IT department for more information | 


### Non-public data
All data that isn't open to the public should be transferred through secure channels. These data include data governed by HIPAA, FERPA, or state laws and data that are confidential, subject to misuse, or simply not authorized for public consumption due to outstanding approval.

Failure to transfer non-public data securely may result in harm to citizens, lawsuits filed against the responsible government office, and severe professional consequences for the offending employee. It’s important to pay careful attention when sharing non-public data. Secure channels include:

| **Technology** | **File size limits** | **Usage notes** | 
| ----------- | ----------- | ----------- | 
| Government-approved SFTP service |{::nomarkdown}<ul><li>1.5GB - using the web client</li><li>Unlimited - using an approved client</li></ul>{:/}|{::nomarkdown}<ul><li>The IT department/Delegated Admin will be needed to set up an SFTP connection and provide instructions on how to upload files.</li><li>Files will be removed from the system after 60 days of inactivity.</li><li>The IT department/Delegated Admin must be informed if a user is planning on uploading a file more than 5GB.</li><li>FileZilla and WinSCP are both approved FTP clients for uploading file sizes larger than 1.5GB</li></ul>{:/}| 
| Government-approved Encrypted External Drive | varies |{::nomarkdown}<ul><li>Doesn’t include encrypted personal or even all government-approved flash drives. An encrypted external drive must be approved by the IT department and be password protected to prevent misuse of data if a non-authorized person accesses the drive.</li></ul>{:/}| 


### Zipping and encryption
To accelerate secure data transfer, zip and encrypt data files before initiating a data transfer. 

To zip a file:
1. Right-click on file or folder
2. Navigate to “Send to” option
3. Click on “Compressed (zipped) folder”


To encrypt a file:
1. Right-click on the zipped folder and open Properties.
2. Under the General tab, click Advanced.
3. Check the “Encrypt contents to secure data” box.


## Enterprise Secure File Transport Services

### [Overview from BEST](https://portal.ct.gov/DAS/BEST/Planning-and-Architecture/Enterprise-Secure-File-Transport-Services)

DAS/BEST is pleased to offer Executive Branch state agencies our Enterprise Secure File Transport (SFT) Service for agencies that need to share sensitive content between other agencies, or business partners in a secure manner. This service offers the following:
* Powered by the [Axway Secure Transport](https://www.axway.com/en/enterprise-solutions/secure-transport#tablist1-tab1) solution, an industry leader in managed file transport solutions.
* Provides for the exchange of file based content that ensures protection and encryption in transit and at rest.
* Meets the federal government's strict security compliance requirements,
* Supports the use of a web-based file management environment as well as traditional secure file transport clients (e.g., FileZilla), 
* Is part of the state’s data center ecosystem, providing a secure and highly available environment.
* Leverages the data center’s virtualization and storage services to further enhance reliability.
* Is available 24 X 7 X 365, including critical incident response.
* Customer support is available from 8:00 AM to 4:00 PM, Monday through Friday.
 
### Conditions of Use:
Use of our Enterprise Secure File Transport Service has the following conditions:
* Each agency who has enrolled in this service will need to appoint a primary and alternate SFT Liaison, with whom we will work on matters associated with your agency’s use of this system. The SFT Liaison will be granted an elevated level of permissions to provide basic support to your agency (e.g., password resets, etc.)
* Content on the SFT environment is considered transitional and is automatically purged after 60 days.

See [Appendix B](/data-sharing-playbook/steps-to-use-sftp/) for a step by step guide to using SFTP.