# Table of Contents

**[Certification Endorsements](#certification-endorsements)**<br />
**[Endorsements Page](#endorsements-page)** | [Filtering and Sorting](#filtering-and-sorting)<br />
**[Summary Report](#summary-report)** | [Data Elements View](#data-elements-view) | [Performance View](#performance-view)<br />
**[Data Dictionary Report](#data-dictionary-report)** | [Exploring the Data](#exploring-the-data)<br />
**[Web API Report](#web-api-report)**<br />
**[Other Guides](#other-guides)**

# Certification Endorsements
At this time, there are two possible endorsements that can be issued to data providers, **Data Dictionary 1.7** and **Web API Core 2.0.0**, each of which have different reports.

Endorsements are shown under their respective organizations at **[certification.reso.org](http://certification.reso.org)**.

<br />

# Endorsements Page
The **Endorsements** page includes the data elements (e.g., Data Dictionary, Web API), endorsement version, status and status date for each certified organization.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/108787f7-69a2-41c7-a454-384a347c9ec0)

<br />

## Filtering and Sorting
There are several sorting and filtering options at the top of the endorsements page.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/580cc375-7282-4280-8437-5bb803889c7c)

<br />

## Organization Name or Identifier Search
Filter by typing in an organization name or Unique Organization Identifier (UOI).

![image](https://user-images.githubusercontent.com/88680702/163901524-6390ecc4-8c79-4485-b783-84d717d86d21.png)

<br />

## Filtering by Endorsement Type
![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/3ac8af5f-aa12-4bfa-b2ee-f798c2b06b1c)

<br />

## Sorting
Sort by organization name alphabetically, ascending or descending.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/9b207c00-c936-4029-8b23-b41a2c0ff1b9)

<br />

Sort by the date/time certifications were issued, ascending or descending. This will show each endorsement individually rather than grouped by organization.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/3fbe9fc9-d350-4540-a219-720a0229acfb)

<br />

The endorsements page may also be accessed by selecting the **Endorsements** option at the top of the page. This option is hidden if you are currently on the endorsements page itself.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/3e4058c6-84a1-44c2-b889-5554799ed71e)

<br />

Selecting the RESO logo at the top left also directs back the Endorsement view.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/290846fc-8c1e-4fd0-b793-4ef8439eb66e)

<br />

# Summary Report
[BACK TO TOP](#table-of-contents)

Summary Reports show information about the resources, fields and lookups that were found during certification testing for the organization being viewed.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/842f32bf-8c84-4be4-b20c-20853e86f26f)

<br />

Summary Reports for organizations with more than one data provider contain a dropdown at the top of the report for switching between them.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/47658123-7456-4bfd-b1a5-8d2d6cae9fb3)


<br />

Each Summary Report contains two views, **Data Elements** and **Performance**, accessed from a dropdown at the top left of the report.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/744c867e-5e71-406b-8e23-64e100bc869e)


<br />


## Data Elements View
The **Data Elements** view shows the field and lookup counts found during certification testing and how they compare with the industry averages. The counts are broken down by **Advertised** and **Available** data.

<br />

* **Advertised**: the fields and lookups that were found on the server metadata during testing. <br />
* **Available**: the fields and lookups that were found in the data payload during sampling.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/c347770a-a203-497f-bc44-b836af4c64ee)

<br />

The **Availability Threshold** slider can be used to filter the field and lookup counts based on how often they were populated with data during sampling. 

For example, setting the slider to 75% will filter the field and lookup counts to those that are used more often.

The default availability threshold level shows the field and lookup counts that have an availability greater than zero.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/151c2e4a-fdf1-415e-bfb1-d0dc1723cc85)

<br />

Located below the charts, the **Resources** dropdown menu filters the  to the specific resource selected. For example, if Property is selected, chart data will only include Property fields and lookups, with data elements belonging to other resources (e.g., Member, Office, etc.) omitted.

<br />

![image](https://user-images.githubusercontent.com/88680702/163904594-8453d153-a39f-4591-8742-e62d322aed88.png)

<br />

## Performance View
The **Performance** view shows the data provider’s server metrics.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/a6e86b1a-78c4-4a61-bf8d-c3e4a68b860c)

<br />

Performance Reports for organizations with more than one provider contain a dropdown at the top of the report for switching between them.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/3ca5aad5-a6a7-43aa-92e4-474e823d7962)

<br />

## Performance Metrics
Performance is measured on:
* **Average Payload Size** - how much data was retrieved when sampling the resource selected in the Resources dropdown, with "All" representing the average across all resources found. Measured in megabytes (MB).
* **Average Response Time** - how long, on average, a request to the given server took to complete, measured in seconds (s).
* **Average Throughput** - the payload size divided by response time. Similar to an Internet speed test, this metric shows how quickly consumers might expect to retrieve data from the given server. Measured in megabytes per second (MB/s).
* **Estimated Seconds per 1,000 Records** - the estimated time it takes to retrieve 1,000 records from the server. Shows for the specific provider and the industry average.

**N/A** - means that the given recipient has not completed Data Dictionary availability testing yet.

Please contact RESO at certification@reso.org if you have any questions about interpretting reports.

<br />

# Data Dictionary Report
[BACK TO TOP](#table-of-contents)

The Data Dictionary Report allows you to explore an organization's individual resources, fields and lookups, along with their usage metrics.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/8cea4bc1-7359-444e-b2cc-208018eee93f)

<br />

Data Dictionary Reports for organizations with more than one data provider contain a dropdown at the top left of the report for switching between them.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/51d63847-d294-4efc-bd82-f019f69ae5ec)

<br />

## Exploring the Data

Your guide to RESO certification terms:

**Resources** are at the top level of the data structure. Think of a resource as the category of the items contained within it. Examples of resources are **Property**, **Member** and **Office**.

**Fields** are contained within resources and are the descriptions of the listing components themselves. Examples of fields are **ListPrice**, **Appliances** and **YearBuilt**.

**Lookups** are the options within certain fields (e.g., **Appliances**). Within **Appliances**, there are lookups such as **Dishwasher**, **Gas Oven** and **Dryer**.

The top right section of the report displays the overall counts of data elements.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/79f191cd-e9bd-4ee9-b36a-852fa2a8a2cc)

<br />

The Data Elements buttons allow filtering by the following data sets:

**All** - The combination of RESO + Local<br />
**RESO** - All resources, fields and lookups matching the RESO Data Dictionary standard<br />
**Local** - Market-specific custom resources, fields and lookups<br />
**IDX** - Resources, fields and lookups for public display by an MLS broker participant

<br />

![image](https://user-images.githubusercontent.com/88680702/163905578-1b161c85-b916-43f6-9c22-6bed4a76036e.png)

<br />

Selecting a resource displays all of the fields within it. Data availability percentages and payload statistics are shown to the right resources and fields.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/f2d3bd3b-7843-4ebc-94aa-4528e3803aee)

<br />

The text filter box allows you to search for fields across all resources.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/ef4f9f50-cab5-4981-ba8f-40ef5ba5b268)

<br />

Selecting a field displays the field's availability and several categories for additional information:

* **Lookup Values (for lookup fields)** - displays the individual options within the field, which can be filtered by All, RESO and Local. RESO standard lookups are linked to their **[Data Dictionary Wiki](https://ddwiki.reso.org/display/DDW17)** entry.
<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/6e680526-f2c7-4e6b-bb13-e495479f2d07)

<br />

* **Data Dictionary** - displays the Data Type, Payloads (if applicable) and Description.
<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/dc158957-0791-4a82-b1de-7e7b29897fb3)

<br />

* **OData Info** - displays the OData Type, Precision (for number fields) and whether it is nullable or a collection.
  
<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/e6d8de90-561c-4256-887b-ed497188d912)

<br />

* **Annotations** - displays the annotations for the field.
  
<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/a3cf1e92-a04e-4341-a347-1dad34de7e7b)

<br />

# Web API Report
[BACK TO TOP](#table-of-contents)

The Web API Core report displays the name of the organization that was tested as well as that of the data provider.

The report also shows which version of OData the RESO Web API Server was using, the authentication type (OAuth 2 Bearer Token or Client Credentials) and the fields that were used for testing.

![image](https://user-images.githubusercontent.com/88680702/205768015-8cb372b1-9548-48d6-9c4f-ea4e2392874c.png)

<br />

# Other Guides
[BACK TO TOP](#table-of-contents)

**[Providers](/docs/providers.md)**<br />
Contains information for data providers. For example, MLS vendors who are going through the RESO Certification process with their customers.

**[Recipients](/docs/recipients.md)**<br />
Guide for customers of data providers. This would typically be an MLS receiving certification from an MLS vendor.

**[Normal Users](/docs/normal-users.md)**<br />
Normal users have special accounts assigned to them so they can access RESO Certification System information from an API rather than the website.

**[Admins](/docs/admins.md)**<br />
Administrator's guide to the RESO Certification System.
