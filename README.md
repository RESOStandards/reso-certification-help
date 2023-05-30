# Endorsements
At this time, there are two possible endorsements that can be issued to data providers, **Data Dictionary 1.7** and **Web API Core 2.0.0**, each of which have different reports.

Endorsements are shown under their respective organizations at **[certification.reso.org](http://certification.reso.org)**.

# Filtering and Sorting

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

# Sorting
Sort by organization name alphabetically, ascending or descending.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/9b207c00-c936-4029-8b23-b41a2c0ff1b9)

<br />

Sort by the date/time certifications were issued, ascending or descending. This will show each endorsement individually rather than grouped by organization.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/3fbe9fc9-d350-4540-a219-720a0229acfb)

<br />

# Endorsements Report

The **Endorsements** view includes the data elements (e.g., Data Dictionary, Web API), endorsement version, status and status date.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/108787f7-69a2-41c7-a454-384a347c9ec0)

<br />

The endorsements page may also be accessed by selecting the **Endorsements** option at the top of the page. This option is hidden if you are currently on the endorsements page itself.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/3e4058c6-84a1-44c2-b889-5554799ed71e)

<br />

Selecting the RESO logo at the top left also directs back the Endorsement view.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/290846fc-8c1e-4fd0-b793-4ef8439eb66e)

<br />

# Summary Report
Summary reports show information about the resources, fields and lookups that were found during certification testing.

Each report contains two views, **Data Elements** and **Performance**, accessed from a dropdown at the top of the page.

![image](https://user-images.githubusercontent.com/88680702/163904475-7c13c048-65c4-4c60-8e72-891418bb44b8.png)

<br />

The **Data Elements** view shows the field and lookup counts and how they compare to industry averages. The counts are broken down by **Advertised** and **Available** data.

**Advertised**: the data elements that were found in the server metadata<br />
**Available**: the data elements that were found in the payload during sampling

Use the **Availability Threshold** slider to set a minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

<br />

![image](https://user-images.githubusercontent.com/88680702/163904566-ed0fdc2b-85a4-49e1-b609-66ab3b5cae02.png)

<br />

Located below the charts, the **Resources** dropdown menu provides a data filter to the specific resource selected. For example, if Property is selected, chart data will only include Property fields and lookups. Elements relating to other resources (e.g., Member, Office, etc.) will be omitted.

![image](https://user-images.githubusercontent.com/88680702/163904594-8453d153-a39f-4591-8742-e62d322aed88.png)

<br />

The **Performance** view shows the data provider’s server metrics.

![image](https://user-images.githubusercontent.com/88680702/205765348-034da0c1-e056-4cbf-a9c9-0ccb9bbc1b37.png)

<br />

## Performance Metrics
Performance is measured on:
* **Payload Size** - how much data was retrieved when sampling the selected resource. "All" represents the average across all resources found, measured in megabytes (MB).
* **Response Time** - how long, on average, a request to the given server took to complete, measured in seconds (s).
* **Throughput** - the payload size divided by response time. Similar to an Internet speed test, this metric shows how quickly consumers might expect to retrieve data from the given server. Measured in megabytes per second (MB/s).

**N/A** - means that the given recipient has not completed Data Dictionary availability testing yet.

**Estimated Seconds per 1,000 Records** - the estimated time it takes to retrieve 1,000 records from the server. Shows for the specific provider and industry average.

Please contact RESO at certification@reso.org if you have any questions.

# Data Dictionary Report
The Data Dictionary Report allows you to explore the data elements of the organization being viewed.

![image](https://user-images.githubusercontent.com/88680702/205767370-b996480b-47e4-4c17-9b19-4cadc022e77b.png)

<br />

## Exploring the Data
Your guide to RESO certification terms:

**Resources** are at the top level of the data structure. Think of a resource as the category of the items contained within it. Examples of resources are **Property**, **Member** and **Office**.

**Fields** are contained within resources and are the descriptions of the listing components themselves. Examples of fields are **ListPrice**, **Appliances** and **YearBuilt**.

**Lookups** are the options within certain fields (e.g., **Appliances**). Within **Appliances**, there are lookups such as **Dishwasher**, **Gas Oven** and **Dryer**.

The top right section of the report displays the overall counts of data elements.

![image](https://user-images.githubusercontent.com/88680702/205769231-afe2a970-9b95-42ea-8289-2a7ce47fcb50.png)

<br />

The Data Elements buttons allow filtering by the following data sets:

**All** - The combination of RESO + Local<br />
**RESO** - All resources, fields and lookups matching the RESO Data Dictionary<br />
**Local** - Market-specific custom resources, fields and lookups<br />
**IDX** - Resources, fields and lookups for public display by an MLS broker participant

![image](https://user-images.githubusercontent.com/88680702/163905578-1b161c85-b916-43f6-9c22-6bed4a76036e.png)

<br />

Selecting a resource displays all of the fields within it. Data availability percentages and payload statistics are also shown.

![image](https://user-images.githubusercontent.com/88680702/205777048-95fe40ec-277a-4bd8-b508-8c3efcbb803b.png)

<br />

The text filter box allows you to search for fields across all resources.

![image](https://user-images.githubusercontent.com/88680702/163905625-f9e073a2-12ce-4f2f-ab5d-a47ee3237d1c.png)

<br />

![image](https://user-images.githubusercontent.com/88680702/163905695-2f044f47-deaf-4d57-bb10-b9fe886c8b2f.png)

<br />

Selecting a field displays the lookups (if applicable), OData information and a link to its **[Data Dictionary Wiki](https://ddwiki.reso.org/display/DDW17)** entry.

![image](https://user-images.githubusercontent.com/88680702/163905793-b28b4f5e-7014-4b37-a3f0-f81a1db0b71f.png)

<br />

The lookup filter buttons above the lookup values allow filtering by All, RESO and Local. RESO Data Dictionary lookup values are also linked to the Data Dictionary Wiki.

![image](https://user-images.githubusercontent.com/88680702/163908793-ed3f900f-eb2e-4324-bf30-6f7155eedac9.png)

<br />

# Web API Report
The Web API Core report displays the name of the organization that was tested as well as that of the data provider.

The report also shows which version of OData the RESO Web API Server was using, the authentication type (OAuth 2 Bearer Token or Client Credentials) and the fields that were used for testing.

![image](https://user-images.githubusercontent.com/88680702/205768015-8cb372b1-9548-48d6-9c4f-ea4e2392874c.png)

<br />

---

# Other Guides

**[Providers](/docs/providers.md)**<br />
Contains information for data providers. For example, MLS vendors who are going through the RESO Certification process with their customers.

**[Recipients](/docs/recipients.md)**<br />
Guide for customers of data providers. This would typically be an MLS receiving certification from an MLS vendor.

**[Normal Users](/docs/normal-users.md)**<br />
Normal users have special accounts assigned to them so they can access RESO Certification System information from an API rather than the website.

**[Admins](/docs/admins.md)**<br />
Administrator's guide to the RESO Certification System.
