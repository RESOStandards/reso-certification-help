# Table of Contents

**[Certification Endorsements](#certification-endorsements)**<br />
**[Endorsements Page](#endorsements-page)** | [Filtering and Sorting](#filtering-and-sorting)<br />
**[Summary Report](#summary-report)** | [Data Elements View](#data-elements-view) | [Performance View](#performance-view)<br />
**[Data Dictionary Report](#data-dictionary-report)** | [Exploring the Data](#exploring-the-data)<br />
**[Web API Report](#web-api-report)**<br />
**[Other Guides](#other-guides)**

# Certification Endorsements
At this time, there are two main endorsements that can be issued to data providers, product vendors and other organizations, **Data Dictionary 2.0** and **Web API Core 2.0.0**, each of which have different reports.
<br />

Additional endorsements include, **RESO Common Format (RCF)**, **RESO Web API Add/Edit**, **UPI**, **Webhooks** and **Validation Expressions**.

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

## Filter by Endorsement Type
Select specific endorsements to show.

<img width="652" height="668" alt="image" src="https://github.com/user-attachments/assets/af517206-115d-4b4d-8c13-9892020aa880" />

## Filter by a Date Range
Sort by dates that endorsements were issued. The date range may be combined with specific endorsements.

<img width="717" height="979" alt="image" src="https://github.com/user-attachments/assets/094ae91f-5afb-47b6-a739-69e9db1e311d" />

<br />

## Sorting
Sort by organization name alphabetically, ascending or descending.

<img width="520" height="323" alt="image" src="https://github.com/user-attachments/assets/95fd87dd-c161-4a59-8f6c-3bbf4c51c121" />

<br />


Sort by the date/time endorsements were issued, ascending or descending. This will show each endorsement individually rather than grouped by organization.

<img width="485" height="306" alt="image" src="https://github.com/user-attachments/assets/ae3d82be-ce01-433d-bef9-e0d6619e874e" />

<br />


The endorsements page (homepage) may also be accessed by selecting **Endorsements** or the **RESO logo** at the top of the page.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/3e4058c6-84a1-44c2-b889-5554799ed71e)

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/290846fc-8c1e-4fd0-b793-4ef8439eb66e)

<br />

# Summary Report
[BACK TO TOP](#table-of-contents)

Summary Reports show information about the resources, fields and lookups that were found during certification testing for the organization being viewed.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/842f32bf-8c84-4be4-b20c-20853e86f26f)

<br />

Summary Reports for organizations with more than one data provider contain a dropdown at the top of the report for switching between them.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/a3efea18-d880-4dc7-afb1-100918c936a5)


<br />

Each Summary Report contains two views, **Data Elements** and **Performance**, accessed from a dropdown at the top left of the report.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/c18a50b2-a2fd-4402-8521-400971cea513)


<br />


## Data Elements View
The **Data Elements** view shows the field and lookup counts found during certification testing and how they compare with the industry averages. The counts are broken down by **Advertised** and **Available** data.

<br />

* **Advertised**: the fields and lookups that were found on the server metadata during testing. <br />
* **Available**: the fields and lookups that were found in the data payload during sampling.

<br />

The **Availability Threshold** slider filters the field and lookup counts based on how often they were populated with data during sampling. 

The default availability threshold level shows the field and lookup counts that have an availability greater than zero.

Increasing the availability threshold percentage filters the field and lookup counts to those that are populated with data more often (25% setting shown below).

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/9346810b-d5e6-46dc-9f8b-6650429e86ef)

<br />

Located below the charts, the **Resources** dropdown menu filters the fields and lookups to the specific resource selected. For example, if Property is selected, chart data will only include Property fields and lookups, with data elements belonging to other resources (e.g., Member, Office, etc.) omitted.

<br />

![image](https://user-images.githubusercontent.com/88680702/163904594-8453d153-a39f-4591-8742-e62d322aed88.png)

<br />

The **Data Elements** buttons filter by the following data sets (RESO selection shown below):

* **All** - The combination of RESO + Local<br />
* **RESO** - All resources, fields and lookups matching the RESO Data Dictionary standard<br />
* **Local** - Market-specific custom resources, fields and lookups<br />
* **IDX** - Resources, fields and lookups for public display by an MLS broker participant

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/a03669f3-7c34-49ca-996e-7ecce2dabd56)

<br />

## Performance View
The **Performance** view shows the data provider’s server metrics.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/0b33d3b1-a12f-452b-a3e1-296d7e48b6ea)

<br />

Performance Reports for organizations with more than one provider contain a dropdown at the top of the report for switching between them.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/fe36fcc2-502a-4edb-a782-d3385ae5362a)

<br />

## Performance Metrics
Performance is measured on:
* **Average Payload Size** - how much data was retrieved when sampling the resource selected in the Resources dropdown, with "All" representing the average across all resources found. Measured in megabytes (MB).
* **Average Response Time** - how long, on average, a request to the given server took to complete, measured in seconds (s).
* **Average Throughput** - the payload size divided by response time. Similar to an Internet speed test, this metric shows how quickly consumers might expect to retrieve data from the given server. Measured in megabytes per second (MB/s).
* **Estimated Seconds per 1,000 Records** - the estimated time it takes to retrieve 1,000 records from the server. Shows for the specific provider and the industry average.

**N/A** - means that the given recipient has not completed Data Dictionary availability testing yet.

You may contact RESO at certification@reso.org if you have any questions about interpretting reports.

<br />

# Data Dictionary Report
[BACK TO TOP](#table-of-contents)

The Data Dictionary Report allows you to explore and search an organization's individual resources, fields and lookups, along with their usage metrics.

<br />

<img width="1940" height="1011" alt="image" src="https://github.com/user-attachments/assets/59c6225d-fc0b-440d-b1cf-eadf2a02c68c" />

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

The **Data Elements** buttons filter by the following data sets:

* **All** - The combination of RESO + Local<br />
* **RESO** - All resources, fields and lookups matching the RESO Data Dictionary standard<br />
* **Local** - Market-specific custom resources, fields and lookups<br />
* **IDX** - Resources, fields and lookups for public display by an MLS broker participant

<br />

![image](https://user-images.githubusercontent.com/88680702/163905578-1b161c85-b916-43f6-9c22-6bed4a76036e.png)

<br />

Selecting a resource displays all of the fields within it. Data availability percentages and payload statistics are shown to the right of the resources and fields.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/f2d3bd3b-7843-4ebc-94aa-4528e3803aee)

<br />

Resources with expansions show a selectable plus icon to show the expaned items.

<img width="1863" height="603" alt="image" src="https://github.com/user-attachments/assets/8fe33840-53ae-4a73-b665-0f12513745c9" />
<img width="1940" height="639" alt="image" src="https://github.com/user-attachments/assets/c3041deb-d102-484b-b86d-49df17cfabcf" />

The text filter box allows you to search for fields across all resources.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/ef4f9f50-cab5-4981-ba8f-40ef5ba5b268)

<br />

Selecting a field displays the field's availability and several categories for additional information:

* **Lookup Values (for lookup fields)** - displays the individual options within the field, which can be filtered by All, RESO and Local. RESO standard lookups are linked to their **[Data Dictionary Wiki](https://ddwiki.reso.org/display/DDW20/Data+Dictionary+2.0+Wiki)** entry.
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

## Exporting the Metadata

An Export CSV button at the top of the report allows for the metadata report to be exported in csv format, which may be opened in a spreadsheet.

<img width="1372" height="176" alt="image" src="https://github.com/user-attachments/assets/f2cac380-4826-42b2-b02d-5f502384da4a" />

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
