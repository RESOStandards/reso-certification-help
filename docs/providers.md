# Endorsements
The RESO Certification process requires a provider (MLS vendor) to review customer (MLS) testing reports and then notify the customer through the RESO Certification System. The customer will then review the results and approve them to receive certification for any given endorsement.

At this time, there are two possible endorsements that can be issued to data providers, **Data Dictionary 1.7** and **Web API Core 2.0.0**, each of which have different reports.

information about viewing [Endorsements](https://certification-help.reso.org/#endorsements).

# Summary Report
Summary reports show information about the resources, fields and lookups that were found on your server for that organization.

Each report contains two views, Data Elements and Performance, accessed from a dropdown at the top of the page.

![image](https://user-images.githubusercontent.com/88680702/164076696-5727c0f5-5abb-486e-a3e6-63a161d7dae6.png)

## Data Elements View
The Data Elements view shows the field and lookup counts and how they compare to industry averages. The counts are broken down by Advertised and Available data.

**Advertised**: the data elements that were found in the server metadata<br />
**Available**: the data element was found in the payload during sampling

Use the Availability Threshold slider to set a minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

![image](https://user-images.githubusercontent.com/88680702/164076762-2f6df7e0-d1a5-45b3-b33f-d7c9ca1561a0.png)

The Resources dropdown beneath the chart filters the data to the specific resource selected.

![image](https://user-images.githubusercontent.com/88680702/164076802-bfd61448-8164-4813-879e-a83ed88412e8.png)

## Performance View
The **Performance** view shows your server performance metrics.

**Note:** You may opt out of displaying your server metrics publicly when sending the notification to the customer. If opted out, the performance metrics will be visible only to the customer and RESO admin staff.

![image](https://user-images.githubusercontent.com/88680702/205765348-034da0c1-e056-4cbf-a9c9-0ccb9bbc1b37.png)

## Performance Metrics
Performance is measured on:

**Payload Size** - measures how much data was retrieved when sampling the selected resource. "All" represents the average across all resources found, measured in megabytes (MB).

**Response Time** - shows how long, on average, a request to the given server took to complete, measured in seconds (s).

**Throughput** - payload size divided by response time. Similar to an Internet speed test, this metric shows how quickly consumers might expect to retrieve data from the given server. Measured in megabytes per second (MB/s).

**N/A** - means that the given recipient has not completed Data Dictionary availability testing yet. Please contact RESO at certification@reso.org if you have any questions.

# Data Dictionary Report
The Data Dictionary Report allows you to explore the data elements of the server submitted for RESO certification. See more information about [Exploring the Data Dictionary Report](https://certification-help.reso.org/#exploring-the-data).

# Web API Report
All MLS providers are required to obtain the Web API Core Endorsement prior to that of the Data Dictionary.

For example, select **View Details** at the right of the Web API Core 2.0.0 Endorsement to view the report.

![image](https://user-images.githubusercontent.com/88680702/205773188-96dd821d-f123-46ed-82a5-f019dddcef6c.png)

The Web API Core report displays the name of the organization that was tested as well as that of the data provider. If any of this information is incorrect, please contact RESO at certification@reso.org.

The report shows which version of OData the RESO Web API Server was using and the authentication type, with the current options being OAuth 2 Bearer Token or Client Credentials. The fields that were used for testing and the status button are also shown.

Notification of the Web API Report may be sent from this page by selecting the **Passed** button at the top right.

![image](https://user-images.githubusercontent.com/88680702/205771954-9dd934ba-a002-4928-bc66-e79f79ae296a.png)

# Notifications
Endorsements must be reviewed and approved by customers before they are certified. The review requests are sent via email.

Selecting **Passed** and then **Notify Recipient** for either the Data Dictionary or the Web API Core report will send a bundled review notification for both endorsements. The recipient will be able to review and approve both reports from a single link that directs them to the Certification Summary page.

**Note:** The bundled notification is available ONLY when BOTH Data Dictionary and Web API are in **Passed** status. Otherwise, the email will only include the single endorsement that was selected for notification.

**IMPORTANT: The email that includes a link to the report(s) should only be sent to the organization you are certifying. Any recipient of the email would have the ability to approve the results.**

## Sending Notifications
Select the **Passed** button from the endorsements page or any report page, then select **Notify Recipient**.



**Screenshot of Passed button dropdown with "Notify Recipient" highlighted" and with all options visible (Cancel, Archive)**



Select whether to **Accept** or **Opt-Out** having the performance metrics displayed publicly and select **Next**.

![image](https://user-images.githubusercontent.com/88680702/164259356-26f1c86e-b75b-461b-9c5e-9f20536efb4d.png)

The email entry screen displays which endorsements will be included in the email. Enter the email address for your customer and select **Send Now**.

![image](https://user-images.githubusercontent.com/88680702/205774052-6488827a-52cb-4cd2-a89b-82860f1baae3.png)

An email with a link to the report will be sent to your customer for review and approval. The button will then change to indicate **Notified**.

![image](https://user-images.githubusercontent.com/88680702/164080862-f7bbd6bb-935f-4b35-bdb0-d01a4a8bb580.png)

Once the customer has approved the results, the button will change to indicate **Certified**.

![image](https://user-images.githubusercontent.com/88680702/164080916-825ff706-8037-40ce-b4c4-ceb351044630.png)

## Notification Tracking

Providers are allowed to send a maximum of two notifications for each recipient. 

If a notification has previously been sent, the notification count and recipient email address will appear when the **Notified** button is selected.

**Screenshot of Notify button dropdown when selected for a recipient with one notification**



# **Canceling Certification**

Providers may cancel the certification process for reports in **Passed** or **Notified** status. 

Select the **Passed** or **Notified** button and select **Cancel Certification**.

**Screenshot of Passed button select with "Cancel Certification" highlighted and all other options visible (notify recipient, Cancel, Archive)**

A confirmation of the cancelation is sent to the provider. The recipient is not notified of a cancel action.

The report will now show as Canceled and may be archived (see below).



# **Archiving Reports**

Providers may archive their reports should they have results they no longer want to keep or for or customers they are no longer serving. 

Archiving is available for reports in **Passed**, **Notified**, **Certified** or **Canceled** status.

Select the **Certified** button on the endorsement you would like to archive and select **Archive**. 

**Screenshot of Passed button dropdown with "Archive" highlighted" and with all options visible (Cancel, Archive)**

A notification of the archive action will be sent to the provider. The recipient is not notified.

## Auto-Archiving

Certification reports are automatically archived and replaced if a new report of the same type is initiated by the provider.

Auto-archiving will occur for reports in **Passed**, **Notified** or **Canceled** status.



# My Account

Selecting **My Account** at the top of the page displays your user information and the ability to copy or create a new token hash. If any of this information is incorrect, please contact RESO at certification@reso.org.

## Creating a Token
A token is needed in order to access the certification data via Web API.

Log in to [certification.reso.org](https://certification.reso.org) with your Username and Password.

Select **My Account** from the top toolbar.

![image](https://user-images.githubusercontent.com/88680702/164083135-6c835013-5ca4-4e23-a884-118c9739eb2a.png)

![image](https://user-images.githubusercontent.com/88680702/164082840-d13c0210-d33a-41b8-b49c-3a91801babfd.png)

Select the **Create Token** button.

![image](https://user-images.githubusercontent.com/88680702/164082516-7fcbef75-49d3-49c8-8bd3-1158535a4122.png)

The token will then be displayed along with options to copy it to the clipboard or to delete (in the case of multiple tokens).

![image](https://user-images.githubusercontent.com/88680702/164089795-39ccf57c-b6d6-405f-be4c-0b19cb7a22c0.png)

You may contact certification@reso.org for assistance.
