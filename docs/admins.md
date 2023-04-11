# Endorsements 
Data Providers must submit their certification tests through the self-testing UI and then notify their customer to review and approve the certification reports. The customer will then review the results and approve them to receive their certification for the given endorsement.

At this time, there are two possible endorsements that can be issued to data providers, Data Dictionary 1.7 and Web API Core 2.0.0, each of which have different reports.

For data providers certifying MLS recipients, Web API Core 2.0.0 or Web API Core 2.1.0 must be passed for at least one MLS prior to testing for Data Dictionary.

See more information about viewing [Endorsements]([url](https://certification-help.reso.org/#endorsements)).



# Summary Report

Each Summary Report shows information about the resources, fields and lookups that were found on the server for the organization.

Each report contains two views, Data Elements and Performance, accessed from a dropdown at the top of the page.

![image](https://user-images.githubusercontent.com/88680702/164076696-5727c0f5-5abb-486e-a3e6-63a161d7dae6.png) 



## Data Elements View

The Data Elements view shows the field and lookup counts and how they compare to industry averages. The counts are broken down by Advertised and Available data.

**Advertised**: the data elements that were found in the server metadata
**Available**: the data element was found in the payload during sampling

The Availability Threshold slider sets minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

![image](https://user-images.githubusercontent.com/88680702/164076762-2f6df7e0-d1a5-45b3-b33f-d7c9ca1561a0.png)

The Resources dropdown beneath the chart filters the data to the specific resource selected.

![image](https://user-images.githubusercontent.com/88680702/164076802-bfd61448-8164-4813-879e-a83ed88412e8.png)



## Performance View

The **Performance** view shows the server performance metrics for the provider.

**Note:** Providers may opt out of displaying server metrics publicly when sending the notification to the recipient. If opted out, the performance metrics will be visible only to the provider, recipient and RESO admin staff.

![image](https://user-images.githubusercontent.com/88680702/205765348-034da0c1-e056-4cbf-a9c9-0ccb9bbc1b37.png)



## Performance Metrics

Performance is measured on:

**Payload Size** - measures how much data was retrieved when sampling the selected resource. “All” represents the average across all resources found, measured in megabytes (MB).

**Response Time** - shows how long, on average, a request to the given server took to complete, measured in seconds (s).

**Throughput** - is payload size divided by response time. Similar to an Internet speed test, this metric shows how quickly consumers might expect to retrieve data from the given server. Measured in megabytes per second (MB/s).

**N/A** - means that the given recipient has not completed Data Dictionary availability testing yet. 

**Estimated Seconds per 1,000 Records** - the estimated time it takes to retrieve 1,000 records from the server. Shows for the specific provider and industry average.

Providers may reach out to  certification@reso.org if they have further questions.



# Data Dictionary Report
The Data Dictionary Report provides a way to explore the data elements of the server submitted for RESO certification. See more information about [Exploring the Data Dictionary Report](https://certification-help.reso.org/#exploring-the-data).



# Web API Report
All MLS providers are required to obtain the Web API Core Endorsement prior to that of the Data Dictionary.

For example, select **View Details** at the right of the Web API Core 2.0.0 Endorsement to view the report.

![image](https://user-images.githubusercontent.com/88680702/205773188-96dd821d-f123-46ed-82a5-f019dddcef6c.png)

The Web API Core report displays the name of the organization that was tested and the name of the data provider. 

The report shows which version of OData the RESO Web API Server was using and the authentication type, with the current options being OAuth 2 Bearer Token or Client Credentials. The fields that were used for testing and the status button are also shown.

Providers may send the notification of the Web API Report from this page by selecting the **Passed** button at the top right.

![image](https://user-images.githubusercontent.com/88680702/205771954-9dd934ba-a002-4928-bc66-e79f79ae296a.png)



# Notifications

Endorsements must be reviewed and approved by recipients before they are certified. The review requests are sent via email.

When providers select **Passed** and then **Notify Recipient** for either the Data Dictionary or the Web API Core report, a bundled review notification for both endorsements is sent to the recipient. The recipient will be able to review and approve both reports from a single link that directs them to the Certification Summary page.

**Note:** The bundled notification is available ONLY when BOTH Data Dictionary and Web API are in **Passed** status. Otherwise, the email will only include the single endorsement that was selected for notification.

**IMPORTANT: Providers should not send a notification to any other party except the organization they are certifying. Any recipient of the email would have the ability to approve the results.**



## Sending Notifications

Providers should select the **Passed** button from the endorsements page or any report page, then select **Notify Recipient**.

![image](https://user-images.githubusercontent.com/88680702/164080561-d1c6233b-f401-46d3-8020-e3dccfb7cf21.png) 

They then select whether to **Accept** or **Opt-Out** having the performance metrics displayed publicly and select **Next**.

![image](https://user-images.githubusercontent.com/88680702/164259356-26f1c86e-b75b-461b-9c5e-9f20536efb4d.png) 

The email entry screen confirms which endorsements will be included in the email. Providers enter the recipient's email address and select **Send Now**.

![image](https://user-images.githubusercontent.com/88680702/205774052-6488827a-52cb-4cd2-a89b-82860f1baae3.png)

An email with a link to the report will be sent to the recipient for review and approval. The button will then change to indicate **Notified**.

![image](https://user-images.githubusercontent.com/88680702/164080862-f7bbd6bb-935f-4b35-bdb0-d01a4a8bb580.png) 

Once the customer has approved the results, the button will change to indicate **Certified**.

![image](https://user-images.githubusercontent.com/88680702/164080916-825ff706-8037-40ce-b4c4-ceb351044630.png) 

 

# **Archiving Reports**

Providers may archive their reports should they have results they no longer want, have customers listed that they are no longer serving or no longer exist.

A notification will be sent to the provider when a report is archived. The recipient is not notified.

Select the **Certified** button on the endorsement you would like to archive and select **Archive**.

![image](https://user-images.githubusercontent.com/88680702/205774621-bbd83fb3-857d-4000-9f62-4258f05e6c81.png) 



# My Account

Selecting **My Account** at the top of the page displays user information and the ability to copy or create a new token hash. 

## Creating a Token

Providers may create a token in order to access the certification data via Web API with the steps below.

Log in to [certification.reso.org](https://certification.reso.org/) with your Username and Password.

Select **My Account** from the top toolbar.

![image](https://user-images.githubusercontent.com/88680702/164083135-6c835013-5ca4-4e23-a884-118c9739eb2a.png) 

![image](https://user-images.githubusercontent.com/88680702/164082840-d13c0210-d33a-41b8-b49c-3a91801babfd.png) 

Select the **Create Token** button.

![image](https://user-images.githubusercontent.com/88680702/164082516-7fcbef75-49d3-49c8-8bd3-1158535a4122.png) 

The token will then be displayed along with options to copy it to the clipboard or to delete (in the case of multiple tokens).

![image](https://user-images.githubusercontent.com/88680702/164089795-39ccf57c-b6d6-405f-be4c-0b19cb7a22c0.png) 



# Admin Actions

### Creating an Admin User

Admins may create new admin users by selecting the **Admin Actions** button from the top toolbar. 

Select the **Create User** button under the Admins section.

![image-20230410174145392](C:\Users\jdarr\AppData\Roaming\Typora\typora-user-images\image-20230410174145392.png)

Create a username and password.

Enter a full name and email address, select **Save**.

![image-20230410175010250](C:\Users\jdarr\AppData\Roaming\Typora\typora-user-images\image-20230410175010250.png)  



### Creating a Provider User

Select **Create User** under the Users section.

![image-20230410174553231](C:\Users\jdarr\AppData\Roaming\Typora\typora-user-images\image-20230410174553231.png) 

Select **Provider User** radio button.

Create a username and password.

Select the organization for the provider.

Enter a full name and email address, select **Save**.

![image-20230410174819308](C:\Users\jdarr\AppData\Roaming\Typora\typora-user-images\image-20230410174819308.png) 



### Creating a Normal User

Select **Create User** under the Users section.

![image-20230410174553231](C:\Users\jdarr\AppData\Roaming\Typora\typora-user-images\image-20230410174553231.png)  

Select **Normal User** radio button.

Create a username and password.

Enter a full name and email address, select **Save**.

![image-20230410175243655](C:\Users\jdarr\AppData\Roaming\Typora\typora-user-images\image-20230410175243655.png) 



### Syncing UOI Organizations

 See the [UOI Sync Process](https://github.com/RESOStandards/reso-certification/wiki/UOI-Sync-Process)



