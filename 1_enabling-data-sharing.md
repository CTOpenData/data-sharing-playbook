---
layout: page
title: Enabling Data Sharing
permalink: /enabling-data-sharing/
nav: true
weight: 1
---

## Identify who plays each data-related role.

Identifying who plays each data-related role allows organizations to establish who has the responsibility of fielding external inquiries, designing sharing procedures, and executing requests. The first step in setting up a strong data governance model and maintaining institutional knowledge of the data sharing process is to establish and communicate these roles.

Although the roles below are described separately, the same person may exercise more than one role and may have a separate job title and function. For example, a single contractor may act as both the steward and custodian for the agency's data. In small agencies, the data officer may also fulfill the data owner, custodian, and steward roles. The important takeaway is that agency leadership and the team need to know who’s the go-to for each set of responsibilities in the data system.

### Agency data officer

Agency data officers serve as the main contact person for inquiries, requests, or concerns regarding access to the data of an agency. The agency data officer, in consultation with the Chief Data Officer and the executive agency head, establishes procedures to ensure that the agency complies with requests for data in an appropriate and prompt manner. [^1]

The role of agency data officer was established in Connecticut by [Public Act 18-175](https://www.cga.ct.gov/2018/ACT/pa/pdf/2018PA-00175-R00HB-05517-PA.pdf), which required executive branch agencies to designate an employee to serve as the primary contact for inquiries, requests, and concerns about access to data at their agency, and to be responsible for implementing the provisions of P.A. 18-175. [See the list of agency data officers.](https://data.ct.gov/Government/Agency-Data-Officers/ti3z-strx)

### Data owner 

The data owner is accountable for the quality and security of the data and holds the decision-making authority about data within their domain. The data owner varies by dataset, and there may be multiple data owners. For some datasets, a data officer is the data owner, and in others, it may be the program lead.

### Data steward 

The data steward is responsible for the governance of data and ensures the fitness of content and metadata. Stewards exercise established processes, policies, guidance, compliance, and rules in this effort. They are usually the subject matter experts and data analysts that work with the data on a daily basis.

### Data custodian 

A data custodian is responsible for the technology used to store and transport the data. The role can be filled by either a person or team, and data custodians are usually database administrators, data analysts, or software engineers.

### Legal counsel 

Legal counsel is a person or team that can evaluate data access and use and help craft appropriate legal agreements when needed.

### Privacy and compliance officer

This person or team develops and implements policies and procedures to protect individual rights and comply with federal and state law. The privacy and compliance officer also investigates any data incidents and breaches.

## Create and publish a data dictionary.

A publicly-available data dictionary helps requesters understand what data your agency collects and possesses. It can also help them craft requests that reference specific tables and fields, making the request easier to fulfill. The data dictionary should:
* Describe all of the datasets for which your agency is responsible
* Contain information on how each of the datasets was collected
* Define the individual fields in each of the datasets
* Indicate levels of access for each of the datasets, including which data is alreaddy open, which data is restricted, and which should not be used, or is not available

## Document metadata.

Metadata is a set of information that describes the fields in a dataset. It provides data about your data. It includes information such as when and how the data was gathered or any other information that might describe an aspect of the data. It is important to keep detailed notes on the metadata and process by which the data was collected because this information can facilitate easier and more effective use later on. 

One common misconception about metadata is that it is solely the definitions of the various fields in a dataset. However, metadata includes much more than these surface-level characteristics. Anything that gives additional information about the nature, structure, or gathering process of the dataset counts as metadata. Some examples of metadata for different types of media include:

* **Photographs / images**: date and time the photo was taken, who took the photo, location where the image was captured, and camera settings used to take the photo
* **Books / reports / documents**: title, author, publishing information, year of publication, table of contents, index, date of last update / modification, and number of pages
* **Emails / communication records**: person sending the communication, person receiving the communication, message text, date and time of correspondence, subject line, IP addresses of sender and responder, and encryption details
* **Spreadsheets / databases**: names of column fields, explanation of fields, number of users / respondents surveyed, number of missing data entries, integrity constraints, data types included in the table, and date and time the information was collected (including multiple records if gathered over a period of time)

When tracking metadata, it’s important to:
* Document as much information as you can about the higher-level aspects of a dataset: its source, update frequency, timestamps of collection, expected level of detail, explanations of tags, data quality, etc.
* Be consistent about the language you use to describe metadata
* Avoid acronyms and language that might be specific to you or your agency, since metadata can help recipients of data sharing understand what a dataset is all about


### Recommended reading
* [Metadata guidelines for publishers on data.ct.gov](https://portal.ct.gov/-/media/CT-Data/Metadata-Guidelines.docx?la=en)
 * [P20 WIN Data Dictionary](https://www.ct.edu/files/pdfs/p20win/P20WIN_Data_Dictionary.xlsx)
 * [Manually creating a data dictionary](https://data.nal.usda.gov/manually-creating-data-dictionary)
 * [Smithsonian Data Management Best Practices](https://library.si.edu/sites/default/files/pdf/rdm_best_practices.pdf) 

## Update Connecticut’s High Value Data Inventory.
[Connecticut’s High Value Data Inventory (Non GIS)](https://data.ct.gov/Government/2019-CT-Data-Catalog-Non-GIS-/f6rf-n3ke/) and [Connecticut’s High Value Data Inventory (GIS)](https://data.ct.gov/Government/2019-CT-Data-Catalog-GIS-/kr39-sdfm/) are data catalogs that highlight general information about high-value datasets possessed by state agencies. The annual maintenance of the high value data inventories is required by P.A. 18-175. At the end of each year, OPM will reach out to agencies to provide updates by December 31 of that year. By keeping your agency’s datasets up to date in the catalog, you help other agencies and the public understand what data your agency owns and who to contact for more information.

To update the inventory, email both [scott.gaul@ct.gov](mailto:scott.gaul@ct.gov) and [pauline.zaldonis@ct.gov](mailto:pauline.zaldonis@ct.gov) with the subject line “CT High Value Data Inventory Change Request.”

## Review data for implicit biases. 

As organizations become more data-driven, data experts are discovering more instances in which unaccounted biases in data perpetuate racism, sexism, and other forms of discrimination. 

The data that government agencies, academic researchers, and other organizations collect most likely contain implicit biases. These biases can be introduced due to: 

* **Whose data is collected** — Does a dataset contain a representative sample of people across different demographics and backgrounds (i.e. multiple races, ethnicities, geographic locations, ages, genders, etc.)?
* **Whose data isn’t collected** — Does the data leave out a specific demographic group that might not frequent the service where the data is collected?  
* **How the data is collected** — For example, is the data collected via interview in one area and via a form somewhere else?

Consider possible sources of bias in your agency’s data carefully. If you don’t identify possible bias, communicate it to data requesters, and work to reduce it, the decisions made based on your data may have serious unintended societal implications. 

### Here’s an example of how implicit bias can have unintended consequences:

Researchers discovered that a major health provider’s algorithm favored white patients over black patients when deciding who would benefit from extra medical care. The researchers attributed the algorithm’s bias to the data that was used to create it. Researchers noted that the health provider attempted to prevent bias by omitting the patient's race in the algorithm. Nevertheless, the algorithm amplified underlying inequities in access to healthcare. In the US, white patients incur more medical costs than black patients due to long-standing disparities in wealth and access to healthcare. Because of this difference in access to care, the algorithm perpetuated the disparity by determining that white patients would benefit more from extra medical care than sicker black patients. [^2]

## Work to eliminate possible sources of bias.

Data analysts are ultimately responsible for how they use your agency’s data; however, as the data owners and experts, you can help data analysts avoid biases in data that perpetuate racism, sexism, and other forms of discrimination. 

First, be open about the limitations of the agency’s data to reduce the likelihood that it will be used in ways that have unintended consequences. Second, work towards systemic changes to data collection practices. Finally, require data requesters to demonstrate responsible use of your agency’s data. The recommended reading below provides guidance on identifying and eliminating sources of implicit bias. 

### Recommended reading

 * [Algorithmic Justice League](https://www.ajlunited.org/)
 * [Confronting Structural Racism in Research and Policy Analysis](https://www.urban.org/sites/default/files/publication/99852/confronting_structural_racism_in_research_and_policy_analysis_0.pdf), Urban Institute, 2019
 * [Data 4 Black Lives](http://d4bl.org/conference.html), MIT, 2019
 * [How I'm Fighting Bias in Algorithms](https://www.ted.com/talks/joy_buolamwini_how_i_m_fighting_bias_in_algorithms) - Joy Buolamwini, TED Talks, 2016 
 * [Racial bias in a medical algorithm favors white patients over sicker black patients](https://www.washingtonpost.com/health/2019/10/24/racial-bias-medical-algorithm-favors-white-patients-over-sicker-black-patients/), The Washington Post, 2019
 * [The era of blind faith in big data must end](https://www.ted.com/talks/cathy_o_neil_the_era_of_blind_faith_in_big_data_must_end) - Cathy O'Neil, Ted Talks, 2017
 * [Weapons of Math Destruction](https://www.penguinrandomhouse.com/books/241363/weapons-of-math-destruction-by-cathy-oneil/), Cathy O’Neil, 2017
 * [When computers make biased health decisions, black patients pay the price, study says, Los Angeles Times](https://www.latimes.com/science/story/2019-10-24/computer-algorithm-fuels-racial-bias-in-us-healthcare), 2019

## Develop a data request process.

A clearly documented data request process can facilitate successful requests. This section covers some of the supporting documents to develop as part of a comprehensive data request process. 

Remember that the data request process must abide by the regulations and laws that apply to each dataset. For more detailed information, refer to [Establish a privacy policy](/data-sharing-playbook/safeguarding-data/#establish-a-privacy-policy) and the report on [Legal Issues in Interagency Data Sharing](https://portal.ct.gov/-/media/CT-Data/PA-19153-Legal-Issues-in-Interagency-Data-Sharing-Report-11520.pdf), including the appendices reviewing state and federal laws and regulations.

### Request form
Ensure that the data requester answers the questions below in order to evaluate the benefits and mitigate the risks of sharing data.

* What is the requester's contact information and organization?
* What is the purpose of the request?
* How does the requester plan to use the data?
* Who will have access to the data?
* What are the specific data they are requesting, and what are the specific parameters, such as individual or aggregate data and over what time period?
* How will the data be used? What methods will be used in the analysis of the data?
* How will results be reported? With whom will they be shared? How will they be disseminated? 
* How frequently will this data be needed? For example, is this a one-time need or a recurring need?
* How long is the requester seeking to keep the data? When and how will the data be destroyed? How is this reported or disseminated to the data owner?


#### Examples

 * [Vital Records Request Form for Non-confidential data](https://portal.ct.gov/-/media/Departments-and-Agencies/DPH/hisr/VR/GENERAL-VR-DATASET-REQUEST-FORM-vSep2019.docx?la=en)
 * [DCF-5101 ORE Data Request Form](https://portal.ct.gov/-/media/DCF/Policy/NEW-fillin-Forms/DCF-5101-10-31-19.pdf)

### Flow diagram or detailed narrative of the steps 

It’s important to have a way to illustrate or describe the data sharing process from start to finish. Common approaches include using a flow diagram or descriptions for each step. 

#### Examples 

 * [Vital Records Data Request Process](/assets/documents/Vital-Records-Flow.pdf)
 * [P20 WIN Data Request Process](http://www.ct.edu/p20win/request-data)

### Data dictionary

A data dictionary describes the agency’s data. (See [Create and publish a data dictionary](#create-and-publish-a-data-dictionary).)

#### Examples

 * [P20 WIN Data Dictionary](http://www.ct.edu/files/pdfs/p20win/P20WIN_Data_Dictionary.xlsx)

### Data request fees

A request fee schedule communicates the cost of requesting data. Both the Department of Public Health and P20-WIN have fee schedules, but each agency may have unique procedures for enacting request fees. We recommend that you consult your agency’s legal counsel for specific guidance on fee schedules. 

#### Examples

 * [Vital Records Request Fees](/assets/documents/SAR-Data-Request-Fee-Schedule.docx)
 * [P20 WIN Fee Schedule](http://www.ct.edu/p20win/request-data) 

### Footnotes

[^1]: [Office Of Policy And Management: General Provisions; Budget And Appropriations; State Planning](https://www.cga.ct.gov/current/pub/chap_050.htm#sec_4-67p)
[^2]: [Racial bias in a medical algorithm favors white patients over sicker black patients](https://www.washingtonpost.com/health/2019/10/24/racial-bias-medical-algorithm-favors-white-patients-over-sicker-black-patients/), The Washington Post, 2019