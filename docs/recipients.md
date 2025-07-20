# Table of Contents

**[Certification Endorsements](#certification-endorsements)**<br />
**[Notifications and Review](#notifications-and-review)**<br />
**[Summary Report](#summary-report)** | [Data Elements View](#data-elements-view) | [Performance View](#performance-view)<br />
**[Reviewing and Approving Results](#reviewing-and-approving-results)** | [Data Dictionary Report](#data-dictionary-report) | [Web API Report](#web-api-report)

<br />

# Certification Endorsements
As part of the RESO Certification process, the data provider (e.g., an MLS vendor) must review the customer's (e.g., an MLS) testing results and notify them through the RESO Certification System. The customer then reviews and approves the results to complete certification for the specified endorsement.

The two main endorsements issued to data providers, product vendors and other organizations are **Data Dictionary 2.0** and **Web API Core 2.0.0**, each of which have their own reports.

Additional endorsements include **RESO Common Format (RCF)**, **RESO Web API Add/Edit**, **UPI**, **Webhooks** and **Validation Expressions**.

See more information about viewing **[Endorsements](https://certification-help.reso.org/#endorsements)**.

<br />

# Notifications and Review

- You will receive an email from certification@reso.org containing a link to review and approve the certification test results submitted by your provider.
- The email includes a link to review any endorsement submitted for certification.
- If multiple endorsements (e.g., **Data Dictionary 2.0** and **Web API Core 2.0.0**) were submitted, they can be reviewed using the same link.
- Select the **REVIEW AND APPROVE RESULTS** link in the email to access the Certification Summary Report.

<img width="771" height="518" alt="image" src="https://github.com/user-attachments/assets/7189201e-bdbf-466f-bd79-9270133bbe63" />

<br />

# Summary Report
[BACK TO TOP](#table-of-contents)

Summary Reports provide information about the resources, fields and lookups for your system. Charts illustrate the number of data elements (fields and lookups) and how they compare to industry averages. Server performance metrics for the data provider are also included.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/842f32bf-8c84-4be4-b20c-20853e86f26f)

Each report contains two views, **Data Elements** and **Performance**, accessed from a dropdown menu in the top left corner.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/c18a50b2-a2fd-4402-8521-400971cea513)

<br />

## Data Elements View
The **Data Elements** view displays the number of fields and lookups identified during certification testing, along with comparisons to industry averages. Counts are categorized as **Advertised** and **Available** data.

**Advertised**: Fields and lookups detected in the server metadata during testing<br />
**Available**: Fields and lookups found in actual data payloads during sampling

The **Availability Threshold** slider allows you to filter field and lookup counts based on how frequently data is populated during sampling.

By default, the slider includes all fields and lookups with availability greater than zero.

Increasing the availability threshold percentage narrows the view to only those data elements that appear more frequently (e.g., a 25% setting will display only elements populated in at least 25% of samples).

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/9346810b-d5e6-46dc-9f8b-6650429e86ef)

<br />

The **Resources** dropdown, located below the charts, filters the displayed data to a selected resource. For example, selecting **Property** will show only fields and lookups in the Property resource, excluding those from resources like **Member** or **Office**.

![image](https://user-images.githubusercontent.com/88680702/164042681-63dbff92-321f-4321-ab7d-002e4924f1e7.png)

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

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/0b33d3b1-a12f-452b-a3e1-296d7e48b6ea)

<br />

## Performance Metrics
Performance is measured on:

* **Average Payload Size** - Indicates how much data was retrieved when sampling the resource selected in the Resources dropdown, with "All" representing the average across all resources found. Measured in megabytes (MB).
* **Average Response Time** - Indicates how long, on average, a request to the given server took to complete, measured in seconds (s).
* **Average Throughput** - Indicates the payload size divided by response time. Similar to an Internet speed test, this metric shows how quickly consumers might expect to retrieve data from the given server. Measured in megabytes per second (MB/s).
* **Estimated Seconds per 1,000 Records** - Indicates the estimated time it takes to retrieve 1,000 records from the server. Shows for the specific provider and the industry average.

**N/A** - Indicates that the given recipient has not completed Data Dictionary availability testing yet.

Please contact RESO at certification@reso.org if you have any questions about interpreting reports.

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

## Industry Alignment Report
The Industry Alignment Report is a complimentary report available to all RESO members and organizations that are certified or in the process of becoming certified.

- Visualize how your data compares to industry averages, such as RESO-standard and IDX payload fields.
- Gain insights on what data elements might be added to improve alignment with the Data Dictionary and industry at large.

<br />
Access the Industry Alignment Report by selecting the status box of the Data Dictionary Endorsement.

<img width="667" height="301" alt="image" src="https://github.com/user-attachments/assets/501bf320-33ce-4f7d-bd7a-50a18b776f9a" />

For help with reviewing the report, see the **Industry Alignment Report Guide** (_link to guide_).
