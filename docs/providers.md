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

**Advertised** refers to the data elements that were found in the server metadata.

**Available** indicates that the data element was also found in the payload during sampling.

Use the Availability Threshold slider to set a minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

![image](https://user-images.githubusercontent.com/88680702/164076762-2f6df7e0-d1a5-45b3-b33f-d7c9ca1561a0.png)

The Resources dropdown beneath the chart filters the data to the specific resource selected.

![image](https://user-images.githubusercontent.com/88680702/164076802-bfd61448-8164-4813-879e-a83ed88412e8.png)

## Performance View
The Performance View shows your server performance metrics.

**Note:** You may opt-out of displaying your server metrics publicly when sending the notification to the customer. If opted-out, the performance metrics will be visible only to the customer and RESO admin staff.

![image](https://user-images.githubusercontent.com/88680702/164076852-3baf895f-f22f-4507-811c-22ede6c0916b.png)

## Performance Metrics
Performance is measured on:

**Payload Size** - measures how much data was retrieved when sampling the selected resource. "All" represents the average across all resources found, measured in megabytes (MB).

**Response Time** - shows how long, on average, a request to the given server took to complete, measured in seconds (s).

**Seconds per 1K Records** -  is an estimate of how many seconds it might take to pull 1,000 records using pages of 100 records. It's based on the average response time found during data sampling and validation. Measured in seconds (s).

**N/A** - means that the given recipient has not completed Data Dictionary 1.7 availability testing yet. Please contact RESO at certification@reso.org if you have any questions.

# Data Dictionary Report
The Data Dictionary Report allows you to explore the data elements of the server submitted for RESO certification. See more information about [Exploring the Data Dictionary Report](https://certification-help.reso.org/#exploring-the-data).

# Web API Report
All MLS providers are required to obtain the Web API Core Endorsement prior to that of the Data Dictionary.

Select **View Details** at the right of the Web API Core 2.0.0 Endorsement to view the report.

![image](https://user-images.githubusercontent.com/88680702/164080293-b9651375-56eb-4f1f-99be-44a7316c16c5.png)

The Web API Core report displays the name of the organization that was tested as well as that of the data provider. If any of this information is incorrect, please contact RESO at certification@reso.org.

The report shows which version of OData the RESO Web API Server was using and the authentication type, with the current options being OAuth 2 Bearer Token or Client Credentials. The fields that were used for testing and the status button are also shown.

Notification of the Web API Report may be sent from this page by selecting the **Passed** button at the top right.

![image](https://user-images.githubusercontent.com/88680702/164079962-e05317f9-b29c-4bc5-9273-0292946eda04.png)

# Notifications
Endorsements must be reviewed and approved by customers before they are certified. The review requests are sent via email.

Selecting **Passed** and then **Notify Recipient** for either the Data Dictionary or the Web API Core report will send a bundled review notification for both endorsements. The recipient will be able to review and approve both reports from a single link that directs them to the Certification Summary page.

**Note:** The bundled notification is available ONLY when BOTH Data Dictionary and Web API are in **Passed** status. Otherwise, the email will only include the single endorsement that was selected for notification.

**IMPORTANT: The email that includes a link to the report(s) should only be sent to the organization you are certifying. Any recipient of the email would have the ability to approve the results.**

## Sending Notifications
Select the **Passed** button from the endorsements page or any report page, then select **Notify Recipient**.

![image](https://user-images.githubusercontent.com/88680702/164080561-d1c6233b-f401-46d3-8020-e3dccfb7cf21.png)

Select whether to **Accept** or **Opt-Out** having the performance metrics displayed publicly and select **Next**.

![image](https://user-images.githubusercontent.com/88680702/164259356-26f1c86e-b75b-461b-9c5e-9f20536efb4d.png)

The email entry screen displays which endorsements will be included in the email. Enter the email address for your customer and select **Send Now**.

![image](https://user-images.githubusercontent.com/88680702/164080764-f1e0cd68-a530-4837-94ee-782fcf887697.png)

An email with a link to the report will be sent to your customer for review and approval. The button will then change to indicate **Notified**.

![image](https://user-images.githubusercontent.com/88680702/164080862-f7bbd6bb-935f-4b35-bdb0-d01a4a8bb580.png)

Once the customer has approved the results, the button will change to indicate **Certified**.

![image](https://user-images.githubusercontent.com/88680702/164080916-825ff706-8037-40ce-b4c4-ceb351044630.png)

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
