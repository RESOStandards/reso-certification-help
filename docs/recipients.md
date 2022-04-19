# Notifications
You will receive an email from certification@reso.org with a link to review and approve the results of your certification tests as submitted by your provider. The body of the email will contain a review link for any endorsements that were submitted. 

If both **Data Dictionary 1.7** and **Web API Core 2.0.0** were submitted, they will be reviewed from the same link.

To be taken to the Certification Summary Report, select the **REVIEW AND APPROVE RESULTS** link located below the endorsement(s), which looks like this:

![image](https://user-images.githubusercontent.com/88680702/164032768-c33b6768-fa5a-4e95-992a-f8c19d21e27f.png)

# Endorsements
The RESO Certification process requires a provider (MLS vendor) to review customer (MLS) testing reports and then notify the customer through the RESO Certification System. The customer will then review the results and approve them to receive certification for any given endorsement.

See more information about veiwing [Endorsements](https://github.com/RESOStandards/reso-certification-help/blob/4-create-consumer-public-content/README.md#endorsements).

# Summary Report
The Certification Summary Report provides a high level overview of the data found during certification testing, displayed in charts. Server performance metrics for the data provider are also included.

Each report contains two views, Data Elements and Performance, accessed from a dropdown menu in the top left corner.

![image](https://user-images.githubusercontent.com/88680702/164037823-fa0661db-010b-4255-a540-eacf27e387f3.png)

Data Elements refers to fields and lookups as defined below:

**Fields** are are the descriptions of the listing components. Examples of fields are **ListPrice**, **Appliances** and **YearBuilt**.

**Lookups** are the options within certain fields (e.g., **Appliances**). Within **Appliances**, there are lookups such as **Dishwasher**, **Gas Oven** and **Dryer**.

The counts of these data elements are categorized by Advertised and Available data and are shown against industry averages.

**Advertised** refers to the data elements that were found in the server metadata.

**Available** indicates that the data element was also found in the data during sampling.

The Availability Threshold slider on the right allows you to set a minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

![image](https://user-images.githubusercontent.com/88680702/164042643-a5979d9e-59fd-43b1-898c-20c7e632519b.png)

Located below the charts, the Resources dropdown menu provides a data filter to the specific resource selected. For example, if Property is selected, chart data will only include Property fields and lookups. Elements relating to other resources (e.g., Member, Office, etc.) will be omitted.

![image](https://user-images.githubusercontent.com/88680702/164042681-63dbff92-321f-4321-ab7d-002e4924f1e7.png)

The Performance option displays the data provider’s server metrics.

![image](https://user-images.githubusercontent.com/88680702/164044656-0c87b91e-2383-4328-9cfc-f26e589da57f.png)

Performance is measured on:

**Payload Size** – measures how much data was retrieved when sampling the selected resource. "All" represents the average across all resources found, measured in megabytes (MB).

**Response Time** – shows how long, on average, a request to the given server took to complete, measured in seconds (s).

**Seconds per 1K Records** – is an estimate of how many seconds it might take to pull 1,000 records using pages of 100 records. It's based on the average response time found during data sampling and validation. Measured in seconds (s).

**N/A** – means that the given recipient has not completed Data Dictionary 1.7 availability testing yet. Please contact RESO at certification@reso.org if you have any questions.

Your endorsements are shown below the charts and may be approved from this page.  

Select **View Details** next to the [Data Dictionary](https://github.com/RESOStandards/reso-certification-help/edit/3-create-provider-and-recipient-content/docs/recipients.md#data-dictionary-report) and [Web API Core](https://github.com/RESOStandards/reso-certification-help/blob/4-create-consumer-public-content/README.md#web-api-report) endorsements to review the reports.

![image](https://user-images.githubusercontent.com/88680702/164047765-9e0f2110-d1b4-4e48-8119-a77b74690df2.png)

You may return to the Certification Summary Report by selecting the blue button that contains the name of your organization.

![image](https://user-images.githubusercontent.com/88680702/164037790-44199bbf-e97a-4ea1-9950-e37416b5c339.png)

If you have reviewed and are satisfied with the report, select the **Approve** button next to the endorsement to be taken to the Terms and Conditions page.

![image](https://user-images.githubusercontent.com/88680702/164045326-602eff64-3c72-48a4-a255-a9c9890ff5e7.png)

Once you have read and agreed to RESO's Terms and Conditions, check the box to confirm and select **Proceed**.

The **Contact RESO** button allows you to send an email to RESO at certification@reso.org.

# Data Dictionary Report
The Data Dictionary Report allows you to explore the data elements as submitted by your provider for RESO certification. See more information about [Exploring the Data Dictionary Report](https://github.com/RESOStandards/reso-certification-help/edit/4-create-consumer-public-content/README.md#exploring-the-data).

The Data Dictionary Endorsement may be approved with the **Approve** button at the top of the report.

![image](https://user-images.githubusercontent.com/88680702/164051539-9ecdd667-6d26-4ee9-8df9-0a139b97400b.png)


# Web API Report
All MLS providers are required to obtain the Web API Core Endorsement prior to that of the Data Dictionary.

The Web API Report allows you to view your high-level certification information, including your Organization Name and Vendor Name. If you believe that any of this information is incorrect, please contact RESO at certification@reso.org.

![image](https://user-images.githubusercontent.com/88680702/164054365-51cba5ae-c59e-44f9-be8c-c1143e3c103a.png)

Once you have reviewed your Web API Core 2.0.0 report, select the **Approve** button to be taken to the Terms and Conditions page.

![image](https://user-images.githubusercontent.com/88680702/164054482-5f121053-f0ad-4a01-a8d8-1b9053d70f12.png)

A **Contact RESO** button on this page allows you to send an email to certification@reso.org.

Once you have read and agreed to RESO's Terms and Conditions, check the box to confirm and select **Proceed**.
