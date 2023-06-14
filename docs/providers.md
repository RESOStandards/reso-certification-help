# Table of Contents

**[Endorsements](#endorsements)**
**[Summary Report](#summary-report)** | [Data Elements View](#data-elements-view) | [Performance View](#performance-view)<br />
**[Data Dictionary Report](#data-dictionary-report)**<br />
**[Web API Report](#web-api-report)**<br />
**[Notifications](#notifications)** | [Sending Notifications](#sending-notifications) | [Notification Tracking](#notification-tracking)<br />
**[Canceling Certification](#canceling-certification)**<br />
**[Archiving Endorsements](#archiving-endorsements)** | [Auto-Archiving](#auto-archiving)<br />
**[My Account](#my-account)** | [Creating a Token](#creating-a-token)<br />
**[Provider FAQ](#provider-faq)**

<br />

# Endorsements
The RESO Certification process requires a provider (MLS vendor) to review customer (MLS) test results and then notify the customer through the RESO Certification System. The customer will then review the results and approve them to receive certification for the given endorsement.

At this time, there are two possible endorsements that can be issued to data providers, **Data Dictionary 1.7** and **Web API Core 2.0.0**, each of which have different reports.

See more information about viewing **[Endorsements](https://certification-help.reso.org/#endorsements)**.

<br />

# Summary Report
Summary reports show information about the resources, fields and lookups that were found on your server for the organization being viewed.

Each report contains two views, **Data Elements** and **Performance**, accessed from a dropdown at the top of the page.

![image](https://user-images.githubusercontent.com/88680702/164076696-5727c0f5-5abb-486e-a3e6-63a161d7dae6.png)

<br />

## Data Elements View
The **Data Elements** view shows the field and lookup counts and how they compare to industry averages. The counts are broken down by **Advertised** and **Available** data.

**Advertised**: the data elements that were found in the server metadata<br />
**Available**: the data elements that were found in the payload during sampling

Use the **Availability Threshold** slider to set a minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

![image](https://user-images.githubusercontent.com/88680702/164076762-2f6df7e0-d1a5-45b3-b33f-d7c9ca1561a0.png)

<br />

**Note:** If the **Available** counts show as zero, the certification was likely issued before the data validation component of testing was required, which began in August 2022. In this case, a new test may be submitted and the original certification archived. See **[Archiving Endorsements](#archiving-endorsement)** for more information.

<br />

Located below the charts, the **Resources** dropdown menu provides a data filter to the specific resource selected. For example, if Property is selected, chart data will only include Property fields and lookups. Elements relating to other resources (e.g., Member, Office, etc.) will be omitted.

![image](https://user-images.githubusercontent.com/88680702/164076802-bfd61448-8164-4813-879e-a83ed88412e8.png)

<br />

## Performance View
The **Performance** view shows your server performance metrics.

**Note:** You may opt out of displaying your server metrics publicly when sending the notification to the customer. If opted out, the performance metrics will be visible only to the customer and RESO admin staff.

![image](https://user-images.githubusercontent.com/88680702/205765348-034da0c1-e056-4cbf-a9c9-0ccb9bbc1b37.png)

<br />

## Performance Metrics
Performance is measured on:

* **Payload Size** - how much data was retrieved when sampling the selected resource. "All" represents the average across all resources found, measured in megabytes (MB).
* **Response Time** - how long, on average, a request to the given server took to complete, measured in seconds (s).
* **Throughput** - the payload size divided by response time. Similar to an Internet speed test, this metric shows how quickly consumers might expect to retrieve data from the given server. Measured in megabytes per second (MB/s).

**N/A** - means that the given recipient has not completed Data Dictionary availability testing yet. Please contact RESO at certification@reso.org if you have any questions.

**Estimated Seconds per 1,000 Records** - the estimated time it takes to retrieve 1,000 records from the server. Shows for the specific provider and industry average.

Providers may reach out to certification@reso.org if they have further questions.

<br />

# Data Dictionary Report
[BACK TO TOP](#table-of-contents)

The Data Dictionary Report allows you to explore the data elements of the server submitted for RESO certification. See more information about **[Exploring the Data Dictionary Report](https://certification-help.reso.org/#exploring-the-data)**.

<br />

# Web API Report
[BACK TO TOP](#table-of-contents)

**IMPORTANT: All MLS providers are required to obtain the Web API Core endorsement prior to that of the Data Dictionary.**

Once the endorsement has been obtained, select **View Details** at the right of the Web API Core 2.0.0 endorsement to view the report.

![image](https://user-images.githubusercontent.com/88680702/205773188-96dd821d-f123-46ed-82a5-f019dddcef6c.png)

<br />

The Web API Core report displays the name of the organization that was tested as well as that of the data provider. If any of this information is incorrect, please contact RESO at certification@reso.org.

The report shows which version of OData the RESO Web API server was using and the authentication type, with the current options being OAuth 2 Bearer Token or Client Credentials. The fields that were used for testing and the status button are also shown.

Data providers (e.g., MLSs) can be notified of the availability of their Web API Report for certification approval by selecting the **Passed** button at the top right of this page. See more information about sending **[Notifications]((#notifications))**.

![image](https://user-images.githubusercontent.com/88680702/205771954-9dd934ba-a002-4928-bc66-e79f79ae296a.png)

<br />

# Notifications
[BACK TO TOP](#table-of-contents)

Certification testing results must be reviewed and approved by customers before the endorsements are certified. The review requests are sent via email.

Selecting **Passed** and then **Notify Recipient** for either the Data Dictionary or the Web API Core results will send a bundled review notification for both. The recipient will then be able to review and approve both results from a single link that directs them to the Certification Summary page.

**Note:** The bundled notification is only available when both Data Dictionary and Web API are in **Passed** status. Otherwise, the email will only include the single result that was selected for notification.

**IMPORTANT: The email that includes a link to the results(s) should only be sent to the organization you are certifying. Any recipient of the email would have the ability to approve the results.**

<br />

## Sending Notifications
Select the **Passed** button from the endorsements page or any report page, then select **Notify Recipient**.

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

<br />

See **[Provider FAQ](#provider-faq)** for troubleshooting notification issues.

<br />

# **Canceling Certification**
[BACK TO TOP](#table-of-contents)

Providers may cancel the certification process when the endorsements are in the **Passed** or **Notified** status. 

Select the **Passed** or **Notified** button and select **Cancel Certification**.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/1fda4789-0b15-45a1-b391-8b4d05c80cf0)

<br />

A confirmation of the cancelation is sent to the provider. The recipient is not notified of a cancel action.

The endorsement will now show as **Canceled** and may be archived (see below).

<br />

See **[Provider FAQ](#provider-faq)** for scenarios around canceling certification.

<br />

# **Archiving Endorsements**
[BACK TO TOP](#table-of-contents)

Providers may now archive endorsements and should do so for any organizations that they are no longer serving or contain results that are otherwise unwanted.

Archiving is available for endorsements in **Passed**, **Notified**, **Certified**, **Canceled** or **Withdrawn** status.

Select the status button on the endorsement you would like to archive and select **Archive**. 

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/e989b730-366a-4d0a-80ac-cc1419519ccf)

<br />

A notification of the archive action will be sent to the provider. The customer is not notified.

<br />

See **[Provider FAQ](#provider-faq)** for scenarios around archiving endorsements.

<br />

## Auto-Archiving
Certification endorsements are automatically archived and replaced if a new endorsement of the same type is initiated by the provider.

Auto-archiving will occur for endorsements in **Passed**, **Notified**, **Canceled** or **Withdrawn** status.

Endorsements in a permanent status (**Certified**, **Revoked**) will remain alongside the new endorsements. The old endorsements may be manually archived by the provider at any time.

<br />

# My Account
[BACK TO TOP](#table-of-contents)

Selecting **My Account** at the top of the page displays your user information and the ability to copy or create a new token hash. If any of this information is incorrect, please contact RESO at certification@reso.org.

<br />

## Creating a Token
A token is needed in order to access the certification data via Web API.

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

You may contact certification@reso.org for assistance.

# Provider FAQ

<br />

## Notifications

**How many review notifications can a provider send to their customer?**<br />
Providers may send a total of two notifications. After the limit has been reached, the **Notify Recipient** option no longer appears and the notification count displays 2, along with the email address to which they were sent.

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/2f73d2f2-2791-43e3-99c8-0ea5c5f4139e)

<br />

**What if a provider has used their maximum number of two (2) notifications?**<br />
Providers are encouraged to reach out to their customers directly through other methods. It may be useful to inform them of the source email address, certification@reso.org, and time/date sent, as shown below. 

![image](https://github.com/RESOStandards/reso-certification-help/assets/88680702/9815724d-69b1-4f90-8681-b0c58ce06611)

<br />

**What if a customer cannot locate the notification emails?**<br />
RESO staff may provide the original notification email directly to the customer if needed. Requests can be made to certification@reso.org.

<br />

## Canceling Certification

**Why would a provider cancel a certification in-process?**<br />
- The organization being certified is no longer a customer or no longer exists. For example, as a result of a merger with other organization(s).
- A new certification process is being initiated and the existing results are out-of-date or otherwise not needed.

**What statuses may be canceled by an provider?**<br />
Endorsements in **Passed** and **Notified** status may be canceled.

<br />

## Archiving Endorsements

**Why would a provider archive an endorsement?**<br />
- The endorsement is for an organization that is no longer a customer or no longer exists. For example, as a result of a merger with other organization(s).
- A more up-to-date endorsement is in-progress.
- A more up-to-date endorsement has been issued.

**What statuses may be archived by an provider?**<br />
Endorsements in **Passed**, **Notified**, **Certified**, **Canceled**, **Revoked** or **Withdrawn** status may be archived.

<br />

## Revoked Certification

**Why would an endorsement show as revoked?**<br />
Questions about revoked certifications should be directed to certification@reso.org.
