# Table of Contents

**[Endorsements](#endorsements)**<br />
**[Summary Report](#summary-report)** | **[Data Elements View](#data-elements-view)** | **[Performance View](#performance-view)**<br />
**[Data Dictionary Report](#data-dictionary-report)**<br />
**[Web API Report](#web-api-report)**<br />
**[Notifications](#notifications)** | **[Sending Notifications](#sending-notifications)** | **[Notification Tracking](#notification-tracking)**<br />
**[Canceling Certification](#canceling-certification)**<br />
**[Archiving Endorsements](#archiving-endorsements)** | **[Auto-Archiving](#auto-archiving)**<br />
**[My Account](#my-account)** | **[Creating a Token](#creating-a-token)**<br />

<br />

# Endorsements
The two main endorsements issued to data providers, product vendors and other organizations are **Data Dictionary 2.0** and **Web API Core 2.0.0**, each of which have their own reports.
<br />

Additional endorsements include **RESO Common Format (RCF)**, **RESO Web API Add/Edit**, **UPI**, **Webhooks** and **Validation Expressions**.

<br />

Certification Statuses:

- **Certified:** The organization is certified on the most current version of the endorsement.
- **Legacy:** The organization is certified on an older but still recognized version of the endorsement.
- **In Review:** The provider is in the process of reviewing their Data Dictionary variations report prior to submitting for live server testing.
- **Passed:** The provider has passed certification testing but has not yet notified the customer to review and approve the results.
- **Notified:** The provider has passed certification testing and has notified the customer to review and approve the results.
- **Canceled:** A passed-status endorsement was canceled prior to the provider notifying the customer.

See more information about viewing **[Endorsements](https://certification-help.reso.org/#endorsements)**.

<br />

# Summary Report
[BACK TO TOP](#table-of-contents)

**Summary Reports** provide information about the resources, fields and lookups for the selected organization.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/842f32bf-8c84-4be4-b20c-20853e86f26f)

<br />

For organizations with multiple providers, Summary Reports include a dropdown at the top to switch between them.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/a3efea18-d880-4dc7-afb1-100918c936a5)


<br />

The Summary Report offers two views, **Data Elements** and **Performance**, available via a dropdown in the top left corner.

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/c18a50b2-a2fd-4402-8521-400971cea513)


<br />

## Data Elements View
The **Data Elements** view displays the number of fields and lookups identified during certification testing, along with comparisons to industry averages. Counts are categorized as **Advertised** and **Available** data.

<br />

-   **Advertised:** Fields and lookups detected in the server metadata during testing<br />
-   **Available:** Fields and lookups found in actual data payloads during sampling

<br />

The  **Availability Threshold** slider allows you to filter field and lookup counts based on how frequently data is populated during sampling.

By default, the slider includes all fields and lookups with availability greater than zero.

Increasing the availability threshold percentage narrows the view to only those data elements that appear more frequently (e.g., a 25% setting will display only elements populated in at least 25% of samples).

<br />

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/9346810b-d5e6-46dc-9f8b-6650429e86ef)

<br />

The **Resources** dropdown, located below the charts, filters the displayed data to a selected resource. For example, selecting **Property** will show only fields and lookups in the **Property Resource**, excluding those from other resources such as the **Member Resource** or **Office Resource**.

<br />

![image](https://user-images.githubusercontent.com/88680702/163904594-8453d153-a39f-4591-8742-e62d322aed88.png)

<br />

The **Data Elements** buttons filter by the following data sets (RESO selection shown below):

-   **All:**  The combination of RESO + Local
-   **RESO:**  All resources, fields and lookups matching the RESO Data Dictionary standard
-   **Local:**  Market-specific custom resources, fields and lookups
-   **IDX:**  Resources, fields and lookups for public display by an MLS broker participant

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

- **Average Payload Size:**  Measured in megabytes (MB), this indicates how much data was retrieved when sampling the resource selected in the **Resources** dropdown, with **All** representing the average across all resources found.
- **Average Response Time:**  Measured in seconds (s), this indicates how long, on average, a request to the given server took to complete.
- **Average Throughput:**  Measured in megabytes per second (MB/s), this indicates the payload size divided by response time. Similar to an Internet speed test, this metric shows how quickly consumers might expect to retrieve data from the given server.
- **Estimated Seconds per 1,000 Records:** Displayed for the specific provider and by industry average, this indicates the estimated time it takes to retrieve 1,000 records from the server.

**N/A:** This indicates that the given recipient has not completed Data Dictionary availability testing yet.

Contact analytics@reso.org with further questions about interpreting reports.

<br />

# Data Dictionary Report
[BACK TO TOP](#table-of-contents)

The Data Dictionary Report allows for the exploration of data elements from the server submitted for RESO certification. See more information about **[Exploring the Data Dictionary Report](https://certification-help.reso.org/#exploring-the-data)**.

<br />

# Web API Report
[BACK TO TOP](#table-of-contents)

**IMPORTANT: All MLS providers are required to obtain the Web API Core endorsement prior to that of the Data Dictionary.**

Once the endorsement has been obtained, select **View Details** to the right of the Web API Core 2.0.0 endorsement to view the report.

![image](https://user-images.githubusercontent.com/88680702/205773188-96dd821d-f123-46ed-82a5-f019dddcef6c.png)

<br />

The Web API Core report displays the name of the organization that was tested, as well as that of the data provider. If any of this information is incorrect, please contact certification@reso.org.

The report shows which version of OData the RESO Web API server was using and the authentication type, with the current options being **OAuth 2 Bearer Token** or **Client Credentials**. The fields that were used for testing and the status button are also shown.

Data providers (e.g., MLSs) can be notified of the availability of their Web API Report for certification approval by selecting the **Passed** button at the top right of this page. See more information about sending **[Notifications]((#notifications))**.

![image](https://user-images.githubusercontent.com/88680702/205771954-9dd934ba-a002-4928-bc66-e79f79ae296a.png)

<br />

# Notifications
[BACK TO TOP](#table-of-contents)

Customers must review and approve the certification testing results before certifications are issued. Review requests are sent to customers via email.

**IMPORTANT: The email that includes a link to the results(s) should only be sent to the organization you are certifying. Any recipient of the email would have the ability to approve the results.**

<br />

## Sending Notifications
**Data Dictionary** and **Web API** review requests are bundled in the same notification, as long as both endorsements are in **Passed** status. If only a single endorsement is Passed, the email will include only that endorsement.

To send a bundled review notification, select **Passed** and then **Notify Recipient** on either endorsement. The recipient will receive a single link to the Certification Summary page, where they can review and approve both results.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/328de65f-5682-4681-9765-c7978b548e0b)

<br />

Select whether to **Accept** or **Opt-Out** of having the performance metrics displayed publicly and select **Next**.

![image](https://user-images.githubusercontent.com/88680702/164259356-26f1c86e-b75b-461b-9c5e-9f20536efb4d.png)

<br />

The email entry screen displays which results will be included in the email. Enter the email address for your customer and select **Send Now**.

![image](https://user-images.githubusercontent.com/88680702/205774052-6488827a-52cb-4cd2-a89b-82860f1baae3.png)

<br />

An email with a link to the results will be sent to your customer for review and approval. The button will then change from **Passed** to **Notified**.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/3ac6e616-aa59-434e-bd0a-35e454dfc50b)

<br />

Once the customer has approved the results, the button will change to **Certified**.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/7556d16a-74eb-4ffd-a190-af51012a89be)

<br />

## Notification Tracking
Providers are allowed to send a maximum of two notifications for each recipient.

If a notification has previously been sent, the notification count and recipient email address will appear when the **Notified** button is selected.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/aa02720f-db1b-4607-87fb-f528880c5c3f)

If the two-notification maximum was reached and the recipient was not able to retrieve the emails, you may email certification@reso.org for assistance.

<br />

# **Canceling Certification**
[BACK TO TOP](#table-of-contents)

Providers may cancel the certification process when endorsements are in **Passed** status.

Select the **Passed** button and select **Cancel Certification**.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/1fda4789-0b15-45a1-b391-8b4d05c80cf0)

<br />

A confirmation of the cancelation is sent to the provider. The recipient is not notified of a cancel action.

The endorsement will now show as **Canceled** and may be archived (see below).

<br />

# **Archiving Endorsements**
[BACK TO TOP](#table-of-contents)

Providers may archive endorsements and are encouraged to do so for any organizations they no longer serve or for results that are no longer needed or valid.

Archiving is available for endorsements in **Passed**, **Notified**, **Legacy**, **Certified**, **Canceled** or **Withdrawn** status.

Select the status button on the endorsement you would like to archive and select **Archive**.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/e989b730-366a-4d0a-80ac-cc1419519ccf)

<br />

A notification of the archive action will be sent to the provider. The customer is not notified.

<br />

## Auto-Archiving
When a provider initiates a new endorsement of the same type and version, the existing certification endorsement is automatically archived and replaced.

Auto-archiving will occur for endorsements in **Passed**, **Notified**, **Canceled** or **Withdrawn** status.

Endorsements in a permanent status (**Certified**, **Legacy**, **Revoked**) will remain alongside the new endorsements. The old endorsements may be manually archived by the provider at any time.

<br />

# My Account
[BACK TO TOP](#table-of-contents)

Select **My Account** at the top of the page to view your user details and access options to copy your provider token or create a new API token. If any account information is incorrect, please contact RESO at certification@reso.org.

<br />

## Creating a Token
A token is required to access certification data through the Web API.

Log in to **[certification.reso.org](https://certification.reso.org)** with your username and password.

Select **My Account** from the top toolbar.

![image](https://user-images.githubusercontent.com/88680702/164083135-6c835013-5ca4-4e23-a884-118c9739eb2a.png)

![image](https://user-images.githubusercontent.com/88680702/164082840-d13c0210-d33a-41b8-b49c-3a91801babfd.png)

<br />

Select the **Create Token** button.

![image](https://user-images.githubusercontent.com/88680702/164082516-7fcbef75-49d3-49c8-8bd3-1158535a4122.png)

<br />

The token will then be displayed along with options to copy it to the clipboard or to delete it (in the case of multiple tokens).

![image](https://user-images.githubusercontent.com/88680702/164089795-39ccf57c-b6d6-405f-be4c-0b19cb7a22c0.png)

<br />

Should you require further assistance or have any questions, contact certification@reso.org.

# Alignment Reports

In addition to the complimentary **Industry Alignment Report**, two premium reports – **Provider Alignment Report** and **Market Alignment Report** – are available under the Reports option in the toolbar. **See:** [Alignment Reports Pricing]([url](https://www.reso.org/reso-alignment-reports-pricing/))

<img width="1088" height="255" alt="image" src="https://github.com/user-attachments/assets/d03eebf0-7eba-4d06-8027-56a858e8391f" />

<br />

## Industry Alignment Report
- Provides a visual representation of how an organization's data compares to industry averages, such as RESO-standard and IDX payload data elements
- Offers insights on what data elements might be added to improve alignment with the Data Dictionary
- Allows data providers to fine-tune their systems before notifying customers to review and approve reports.

<br />

Access the Industry Alignment Report by selecting the status box of the Data Dictionary Endorsement.

<br />

<img width="667" height="301" alt="image" src="https://github.com/user-attachments/assets/501bf320-33ce-4f7d-bd7a-50a18b776f9a" />

<br />
<br />

For help with reviewing the report, see the **Industry Alignment Report Help Guide** (_link to guide_).

<br />

## Provider Alignment Report
- Shows differences in data outputs for MLSs that use more than one API (about 30% do)
- Enables organizations, such as MLSs, to evaluate data consistency across multiple API services
- Offers a visual summary for high-level presentations and detailed views of each system’s full data set for comparison and in-depth analysis
- See the **Provider Alignment Report Help Guide** (_link to guide_)

<br />

## Market Alignment Report
- Illustrates alignment across multiple organizations (e.g., comparing data from five different MLSs using different API vendors)
- Provides a detailed view of all data elements across organizations, helping regional or statewide data share participants evaluate which API service is best suited for collaboration
- Reveals alignment opportunities even across disparate systems
- See the **Market Alignment Report Help Guide** (_link to guide_)

<br />

**TODO:** Preflight Check<br />
**TODO:** Certification Dropdown Items
