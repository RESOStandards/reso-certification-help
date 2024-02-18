# Table of Contents

**[Endorsements](#endorsements)**<br />
**[Notifications](#notifications)**<br />
**[Summary Report](#summary-report)** | [Data Elements View](#data-elements-view) | [Performance View](#performance-view)<br />
**[Reviewing and Approving Results](#reviewing-and-approving-results)** | [Data Dictionary Report](#data-dictionary-report) | [Web API Report](#web-api-report)

<br />

# Endorsements
The RESO Certification process requires a provider (MLS vendor) to review customer (MLS) testing results and then notify the customer through the RESO Certification System. The customer will then review the results and approve them to receive certification for the given endorsement.

At this time, there are two possible endorsements that can be issued to data providers for each customer they serve, **Data Dictionary 1.7** and **Web API Core 2.0.0**, each of which have different reports.

See more information about viewing **[Endorsements](https://certification-help.reso.org/#endorsements)**.

<br />

# Notifications
You will receive an email from certification@reso.org with a link to review and approve the results of your certification tests as submitted by your provider. The body of the email will contain a review link for any endorsements that were submitted for certification. 

For example, if both **Data Dictionary 1.7** and **Web API Core 2.0.0** were submitted, they will be reviewed from the same link.

Select the **REVIEW AND APPROVE RESULTS** link located below the endorsement(s) to be taken to the Certification Summary Report.

![image](https://user-images.githubusercontent.com/88680702/205775765-d25de46f-bb2b-4326-bf33-7224e817ded5.png)

<br />

# Summary Report
[BACK TO TOP](#table-of-contents)

The Certification Summary Report provides a high level overview of the data found during certification testing, displayed in charts. Server performance metrics for the data provider are also included.

Each report contains two views, **Data Elements** and **Performance**, accessed from a dropdown menu in the top left corner.

![image](https://user-images.githubusercontent.com/88680702/163904475-7c13c048-65c4-4c60-8e72-891418bb44b8.png)

<br />

## Data Elements View
The **Data Elements** view shows the field and lookup counts and how they compare to industry averages. The counts are broken down by **Advertised** and **Available** data.

**Advertised**: the data elements that were found in the server metadata<br />
**Available**: the data elements that were found in the payload during sampling

The **Availability Threshold** slider on the right allows you to set a minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

![image](https://user-images.githubusercontent.com/88680702/164042643-a5979d9e-59fd-43b1-898c-20c7e632519b.png)

<br />

Located below the charts, the **Resources** dropdown menu provides a data filter to the specific resource selected. For example, if Property is selected, chart data will only include Property fields and lookups. Elements relating to other resources (e.g., Member, Office, etc.) will be omitted.

![image](https://user-images.githubusercontent.com/88680702/164042681-63dbff92-321f-4321-ab7d-002e4924f1e7.png)

<br />

## Performance View
The **Performance** view shows the data provider’s server metrics.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/0b33d3b1-a12f-452b-a3e1-296d7e48b6ea)

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

# Reviewing and Approving Results
[BACK TO TOP](#table-of-contents)

Your endorsements, including the count of Data Dictionary elements found during testing, are shown below the charts.

Select **View Details** next to the Data Dictionary and Web API Core endorsements to review the reports.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/66621855-062e-47f4-b0e4-aeb9678725bc)

<br />

You may return to the Certification Summary Report by selecting the blue button that contains the name of your organization.

![image](https://user-images.githubusercontent.com/88680702/205776355-e5f13a31-e99d-464c-86a6-76b2ca50b7f7.png)

<br />

## Data Dictionary Report
The Data Dictionary Report allows you to explore the data elements as submitted by your provider for RESO certification. See more information about [**Exploring the Data Dictionary Report**](https://certification-help.reso.org/#exploring-the-data).

![image](https://user-images.githubusercontent.com/88680702/205767370-b996480b-47e4-4c17-9b19-4cadc022e77b.png)

<br />

Once you have reviewed your Data Dictionary Report, select the **Approve** button to be taken to the Terms and Conditions page.

![image](https://user-images.githubusercontent.com/88680702/164054482-5f121053-f0ad-4a01-a8d8-1b9053d70f12.png)

<br />

A **Contact RESO** button on this page allows you to send an email to certification@reso.org.

Once you have read and agreed to RESO's Terms and Conditions, check the box to confirm and select **Proceed**.

<br />

## Web API Report
The Web API Report allows you to view your high-level certification information, including your **Organization Name** and **Vendor Name**. If you believe that any of this information is incorrect, please contact RESO at certification@reso.org.

![image](https://user-images.githubusercontent.com/88680702/205768015-8cb372b1-9548-48d6-9c4f-ea4e2392874c.png)

<br />

Once you have reviewed your Web API Core 2.0.0 report, select the **Approve** button to be taken to the Terms and Conditions page.

![image](https://user-images.githubusercontent.com/88680702/164054482-5f121053-f0ad-4a01-a8d8-1b9053d70f12.png)

<br />

A **Contact RESO** button on this page allows you to send an email to certification@reso.org.

Once you have read and agreed to RESO's Terms and Conditions, check the box to confirm and select **Proceed**.

<br />
