# Table of Contents

**[Certification Endorsements](#certification-endorsements)**<br />
**[Endorsements Page](#endorsements-page)** | **[Filtering and Sorting](#filtering-and-sorting)**<br />
**[Summary Report](#summary-report)** | **[Data Elements View](#data-elements-view)** | **[Performance View](#performance-view)**<br />
**[Data Dictionary Report](#data-dictionary-report)** | **[Exploring the Data](#exploring-the-data)**<br />
**[Web API Report](#web-api-report)**<br />
**[Other Guides](#other-guides)**

# Certification Endorsements
The two main endorsements issued to data providers, product vendors and other organizations are **Data Dictionary 2.0** and **Web API Core 2.0.0**, each of which have their own reports.
<br />

Additional endorsements include **RESO Common Format (RCF)**, **RESO Web API Add/Edit**, **UPI**, **Webhooks** and **Validation Expressions**.

<br />

# Endorsements Page
The Endorsements page (or homepage) displays each organization along with its endorsements (e.g., Data Dictionary, Web API), their version, certification status and status date.

Certification Statuses:

- **Certified:** The organization is certified on the most current version of the endorsement.
- **Legacy:** The organization is certified on an older but still recognized version.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/108787f7-69a2-41c7-a454-384a347c9ec0)

<br />

## Filtering and Sorting
There are several filtering and sorting options at the top of the Endorsements page.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/580cc375-7282-4280-8437-5bb803889c7c)

<br />

## Organization Name or Identifier Search
Filter by typing in an organization name or Unique Organization Identifier (UOI).

![image](https://user-images.githubusercontent.com/88680702/163901524-6390ecc4-8c79-4485-b783-84d717d86d21.png)

<br />

## Filter by Endorsement Type
Filter to show only specific endorsements.

<img width="652" height="668" alt="image" src="https://github.com/user-attachments/assets/af517206-115d-4b4d-8c13-9892020aa880" />

## Filter by a Date Range
Use the calendar to filter endorsements issued within a specific date range.

<img width="799" height="784" alt="image" src="https://github.com/user-attachments/assets/bb8b589a-36b7-4d33-8433-430d43b70d20" />

<br />
<br />


A date range may be combined with specific endorsements.

<img width="717" height="979" alt="image" src="https://github.com/user-attachments/assets/094ae91f-5afb-47b6-a739-69e9db1e311d" />

<br />

## Sorting
Sort organization names alphabetically in ascending or descending order.

<img width="520" height="323" alt="image" src="https://github.com/user-attachments/assets/95fd87dd-c161-4a59-8f6c-3bbf4c51c121" />

<br />
<br />

Sort endorsements by issue date in ascending or descending order. This displays each endorsement individually instead of grouping them by organization.

<img width="485" height="306" alt="image" src="https://github.com/user-attachments/assets/ae3d82be-ce01-433d-bef9-e0d6619e874e" />

<br />
<br />

The Endorsements page is also accessible via the **Endorsements** link or the **RESO logo** located at the top of the page.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/3e4058c6-84a1-44c2-b889-5554799ed71e)

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/290846fc-8c1e-4fd0-b793-4ef8439eb66e)


<br />

# Summary Report
[BACK TO TOP](#table-of-contents)

Summary Reports provide information about the resources, fields and lookups for the selected organization.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/842f32bf-8c84-4be4-b20c-20853e86f26f)

<br />

For organizations with multiple providers, Summary Reports include a dropdown at the top to switch between them.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/a3efea18-d880-4dc7-afb1-100918c936a5)


<br />

The Summary Report offers two views, **Data Elements** and **Performance**, available via a dropdown in the top-left corner.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/c18a50b2-a2fd-4402-8521-400971cea513)


<br />


## Data Elements View
The **Data Elements** view displays the number of fields and lookups identified during certification testing, along with comparisons to industry averages. Counts are categorized as **Advertised** and **Available** data.
<br />

* **Advertised:** Fields and lookups detected in the server metadata during testing <br />
* **Available:** Fields and lookups found in actual data payloads during sampling

<br />

The **Availability Threshold** slider allows you to filter field and lookup counts based on how frequently data is populated during sampling.

By default, the slider includes all fields and lookups with availability greater than zero.

Increasing the availability threshold percentage narrows the view to only those data elements that appear more frequently (e.g., a 25% setting will display only elements populated in at least 25% of samples).

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/9346810b-d5e6-46dc-9f8b-6650429e86ef)

<br />

The **Resources** dropdown, located below the charts, filters the displayed data to a selected resource. For example, selecting **Property** will show only fields and lookups in the Property resource, excluding those from resources like **Member** or **Office**.

<br />

![image](https://user-images.githubusercontent.com/88680702/163904594-8453d153-a39f-4591-8742-e62d322aed88.png)

<br />

The **Data Elements** buttons allow filtering by specific data sets (e.g., RESO, vendor-specific).

* **All:** The combination of RESO + Local<br />
* **RESO:** All resources, fields and lookups matching the RESO Data Dictionary standard<br />
* **Local:** Market-specific custom resources, fields and lookups<br />
* **IDX:** Resources, fields and lookups for public display by an MLS broker participant

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/a03669f3-7c34-49ca-996e-7ecce2dabd56)

<br />

## Performance View
The **Performance** view shows the data provider’s server metrics.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/0b33d3b1-a12f-452b-a3e1-296d7e48b6ea)

<br />

For organizations with more than one data provider, Performance Reports include a dropdown at the top for switching between providers.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/fe36fcc2-502a-4edb-a782-d3385ae5362a)

<br />

## Performance Metrics
Performance is measured on:
* **Average Payload Size:** Indicates how much data was retrieved when sampling the resource selected in the Resources dropdown, with "All" representing the average across all resources found. Measured in megabytes (MB)
* **Average Response Time:** Indicates how long, on average, a request to the given server took to complete, measured in seconds (s)
* **Average Throughput:** Indicates the payload size divided by response time; similar to an Internet speed test, it shows how quickly consumers might expect to retrieve data from the given server, measured in megabytes per second (MB/s)
* **Estimated Seconds per 1,000 Records:** Indicates the estimated time it takes to retrieve 1,000 records from the server; shows for the specific provider and the industry average

**N/A:** Indicates that the given recipient has not completed Data Dictionary availability testing yet.

Contact certification@reso.org for any questions about reports.

<br />

# Data Dictionary Report
[BACK TO TOP](#table-of-contents)

The **Data Dictionary Report** allows you to explore and search an organization’s resources, fields and lookups, as well as related usage metrics.

<br />

<img width="1940" height="1011" alt="image" src="https://github.com/user-attachments/assets/59c6225d-fc0b-440d-b1cf-eadf2a02c68c" />

<br />
<br />

If an organization has multiple data providers, a dropdown is available for switching between them.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/51d63847-d294-4efc-bd82-f019f69ae5ec)

<br />

## Exploring the Data

**Resources:** The top level of the data structure; the category of the items contained within it, such as **Property**, **Member** and **Office**

**Fields:** Contained within resources; descriptions of the listing components themselves, such as **ListPrice**, **Appliances** and **YearBuilt**

**Lookups:** Options within certain fields, such as **Dishwasher**, **Gas Oven** and **Dryer** contained within the **Appliances** field

The top right section of the report displays the overall counts of data elements.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/79f191cd-e9bd-4ee9-b36a-852fa2a8a2cc)

<br />

The **Data Elements** buttons filter by the following data sets (RESO selection shown below):

* **All:** The combination of RESO + Local<br />
* **RESO:** All resources, fields and lookups matching the RESO Data Dictionary standard<br />
* **Local:** Market-specific custom resources, fields and lookups<br />
* **IDX:** Resources, fields and lookups for public display by an MLS broker participant

<br />

![image](https://user-images.githubusercontent.com/88680702/163905578-1b161c85-b916-43f6-9c22-6bed4a76036e.png)

<br />

Selecting a resource shows all of its associated fields. Data availability percentages and payload statistics are displayed for each resource and field.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/f2d3bd3b-7843-4ebc-94aa-4528e3803aee)

<br />

A selectable plus icon appears next to resources with expansions.

<br />

<img width="1863" height="603" alt="image" src="https://github.com/user-attachments/assets/8fe33840-53ae-4a73-b665-0f12513745c9" />
<img width="1940" height="639" alt="image" src="https://github.com/user-attachments/assets/c3041deb-d102-484b-b86d-49df17cfabcf" />

<br />
<br />

The text filter box allows you to search for fields across all resources.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/ef4f9f50-cab5-4981-ba8f-40ef5ba5b268)

<br />

Selecting a field opens a detailed view of its availability and various informational categories.

* **Lookup Values (for lookup fields):** This displays the individual options within the field, which can be filtered by All, RESO and Local. RESO standard lookups are linked to their **[Data Dictionary Wiki](https://ddwiki.reso.org/display/DDW20/Data+Dictionary+2.0+Wiki)** entry.
<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/6e680526-f2c7-4e6b-bb13-e495479f2d07)

<br />

**Data Dictionary:** This displays the Data Type, Payloads (if applicable) and Description.
<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/dc158957-0791-4a82-b1de-7e7b29897fb3)

<br />

**OData Info:** This displays the OData Type, Precision (for number fields) and whether it is nullable or a collection.
  
<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/e6d8de90-561c-4256-887b-ed497188d912)

<br />

**Annotations:** This displays the annotations for the field.
  
<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/a3cf1e92-a04e-4341-a347-1dad34de7e7b)

<br />

Selecting a lookup-type field shows its individual lookups, their availability and other metrics.

<img width="1405" height="527" alt="image" src="https://github.com/user-attachments/assets/3d1f145b-5cd5-463e-a92b-2786316eb18b" />

<br />

## Exporting the Metadata

An **Export CSV** button at the top of the report allows you to export the metadata report in CSV format for use in a spreadsheet application.

<img width="1372" height="176" alt="image" src="https://github.com/user-attachments/assets/f2cac380-4826-42b2-b02d-5f502384da4a" />

<br />


# Web API Report
[BACK TO TOP](#table-of-contents)

The Web API Core report displays the name of the organization that was tested and the data provider.

The report also shows which version of OData the RESO Web API Server was using, the authentication type (OAuth 2 Bearer Token or Client Credentials) and the fields that were used for testing.

![image](https://user-images.githubusercontent.com/88680702/205768015-8cb372b1-9548-48d6-9c4f-ea4e2392874c.png)

<br />

# Other Guides
[BACK TO TOP](#table-of-contents)

**[Providers](/docs/providers.md):** For data providers like MLS vendors going through the RESO Certification process with their customers

**[Recipients](/docs/recipients.md):** For customers of data providers like an MLS receiving certification from an MLS vendor

**[Normal Users](/docs/normal-users.md):** For those that access RESO Certification System information from an API rather than the website

**[Admins](/docs/admins.md):** An administrator's guide to the RESO Certification System
