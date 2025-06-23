# Table of Contents

**[Endorsements](#endorsements)** <br />
**[Summary Report](#summary-report)** <br />
&nbsp;&nbsp;&nbsp;&nbsp;[Data Elements View](#data-elements-view) <br />
&nbsp;&nbsp;&nbsp;&nbsp;[Performance View](#performance-view)<br />
**[Data Dictionary Report](#data-dictionary-report)** <br />
**[Web API Report](#web-api-report)** <br />
**[Notifications](#notifications)** <br />
&nbsp;&nbsp;&nbsp;&nbsp;[Sending Notifications](#sending-notifications) <br />
&nbsp;&nbsp;&nbsp;&nbsp;[Notification Tracking](#notification-tracking) <br />
**[Canceling Certification](#canceling-certification)** <br />
**[Revoking Certification](#revoking-certification)** <br />
**[Archiving Endorsements](#archiving-endorsements)** <br />
&nbsp;&nbsp;&nbsp;&nbsp;[Auto-Archiving](#auto-archiving) <br />
**[My Account](#my-account)** <br />
&nbsp;&nbsp;&nbsp;&nbsp;[Creating a Token](#creating-a-token)<br />
**[Admin Actions](#admin-actions)** <br />
&nbsp;&nbsp;&nbsp;&nbsp;[Creating an Admin User](#creating-an-admin-user) <br />
&nbsp;&nbsp;&nbsp;&nbsp;[Creating a Provider User](#creating-a-provider-user) <br />
&nbsp;&nbsp;&nbsp;&nbsp;[Creating a Normal User](#creating-a-normal-user) <br />
&nbsp;&nbsp;&nbsp;&nbsp;[UOI Syncing](#uoi-syncing) <br />
**[Admin FAQ](#admin-faq)** <br />

# Endorsements
Data providers (e.g., MLS vendors) must submit their certification tests through the self-testing user interface and then notify their customers (e.g., MLSs) to review and approve the results. The customer will then review the results and approve them to receive their certification for the given endorsement.

At this time, there are two possible endorsements that can be issued to data providers, **Data Dictionary 1.7** and **Web API Core 2.0.0**, each of which have different reports.

For data providers certifying MLS recipients, Web API Core 2.0.0 or Web API Core 2.1.0 must be passed for at least one MLS prior to testing for Data Dictionary.

See more information about viewing **[Endorsements](https://certification-help.reso.org/#endorsements)**.

<br />

# Summary Report
Each Summary Report shows information about the resources, fields and lookups that were found on the server for the organization.

Each report contains two views, **Data Elements** and **Performance**, accessed from a dropdown at the top of the page.

![image](https://user-images.githubusercontent.com/88680702/164076696-5727c0f5-5abb-486e-a3e6-63a161d7dae6.png) 

<br />

## Data Elements View
The **Data Elements** view shows the field and lookup counts and how they compare to industry averages. The counts are broken down by **Advertised** and **Available** data.

**Advertised**: the data elements that were found in the server metadata<br />
**Available**: the data elements that were found in the payload during sampling

The **Availability Threshold** slider sets minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

![image](https://user-images.githubusercontent.com/88680702/164076762-2f6df7e0-d1a5-45b3-b33f-d7c9ca1561a0.png)

<br />

The **Resources** dropdown beneath the chart filters the data to the specific resource selected.

![image](https://user-images.githubusercontent.com/88680702/164076802-bfd61448-8164-4813-879e-a83ed88412e8.png)

<br />

## Performance View
The **Performance** view shows the server performance metrics for the provider.

**Note:** Providers may opt out of displaying server metrics publicly when sending the notification to the recipient. If opted out, the performance metrics will be visible only to the provider, recipient and RESO admin staff.

![image](https://user-images.githubusercontent.com/88680702/205765348-034da0c1-e056-4cbf-a9c9-0ccb9bbc1b37.png)

<br />

## Performance Metrics
Performance is measured on:

* **Payload Size** - how much data was retrieved when sampling the selected resource. “All” represents the average across all resources found, measured in megabytes (MB).
* **Response Time** - how long, on average, a request to the given server took to complete, measured in seconds (s).
* **Throughput** - the payload size divided by response time. Similar to an Internet speed test, this metric shows how quickly consumers might expect to retrieve data from the given server. Measured in megabytes per second (MB/s).

**N/A** - means that the given recipient has not completed Data Dictionary availability testing yet.

**Estimated Seconds per 1,000 Records** - the estimated time it takes to retrieve 1,000 records from the server. Shows for the specific provider and industry average.

Providers may reach out to certification@reso.org if they have further questions.

<br />

# Data Dictionary Report
[BACK TO TOP](#table-of-contents)

The Data Dictionary Report provides a way to explore the data elements of the server submitted for RESO certification. See more information about **[Exploring the Data Dictionary Report](https://certification-help.reso.org/#exploring-the-data)**.

<br />

# Web API Report
[BACK TO TOP](#table-of-contents)

**IMPORTANT: All MLS providers are required to obtain the Web API Core Endorsement prior to that of the Data Dictionary.**

For example, select **View Details** at the right of the Web API Core 2.0.0 Endorsement to view the report.

![image](https://user-images.githubusercontent.com/88680702/205773188-96dd821d-f123-46ed-82a5-f019dddcef6c.png)

<br />

The Web API Core report displays the name of the organization that was tested and the name of the data provider.

The report shows which version of OData the RESO Web API Server was using and the authentication type, with the current options being OAuth 2 Bearer Token or Client Credentials. The fields that were used for testing and the status button are also shown.

Data providers (e.g., MLSs) can be notified of the availability of their Web API Report for certification approval by selecting the **Passed** button at the top right of this page. See more information about sending **[Notifications]((#notifications))**.

![image](https://user-images.githubusercontent.com/88680702/205771954-9dd934ba-a002-4928-bc66-e79f79ae296a.png)

<br />

# Notifications
[BACK TO TOP](#table-of-contents)

Certification testing results must be reviewed and approved by recipients before they are certified. The review requests are sent via email.

When providers select **Passed** and then **Notify Recipient** for either the Data Dictionary or the Web API Core report, a bundled review notification for both endorsements is sent to the recipient. The recipient will be able to review and approve both results from a single link that directs them to the Certification Summary page.

**Note:** The bundled notification is only available when both Data Dictionary and Web API are in **Passed** status. Otherwise, the email will only include the single endorsement that was selected for notification.

**IMPORTANT: Providers should not send a notification to any other party except the organization they are certifying. Any recipient of the email would have the ability to approve the results.**

<br />

## Sending Notifications
Providers may select the **Passed** button from the endorsements page or any report page, then select **Notify Recipient**.

![image](https://user-images.githubusercontent.com/88680702/237737630-328de65f-5682-4681-9765-c7978b548e0b.png) 

<br />

They then select whether to **Accept** or **Opt-Out** of having the performance metrics displayed publicly and select **Next**.

![image](https://user-images.githubusercontent.com/88680702/164259356-26f1c86e-b75b-461b-9c5e-9f20536efb4d.png)

<br />

The email entry screen confirms which endorsements will be included in the email. Providers enter the recipient's email address and select **Send Now**.

![image](https://user-images.githubusercontent.com/88680702/205774052-6488827a-52cb-4cd2-a89b-82860f1baae3.png)

<br />

An email with a link to the results will be sent to the recipient for review and approval. The button will then change from **Passed** to **Notified**.

![image](https://user-images.githubusercontent.com/88680702/237753878-3ac6e616-aa59-434e-bd0a-35e454dfc50b.png) 

<br />

Once the customer has approved the results, the button will change to **Certified**.

![image](https://user-images.githubusercontent.com/88680702/237754344-7556d16a-74eb-4ffd-a190-af51012a89be.png) 

<br />

## Notification Tracking
Providers are allowed to send a maximum of two notifications for each recipient.

If a notification has previously been sent, the notification count and recipient email address will appear when the **Notified** button is selected.

![image](https://user-images.githubusercontent.com/88680702/237749774-aa02720f-db1b-4607-87fb-f528880c5c3f.png) 

<br />

See **[Admin FAQ](#admin-faq)** for troubleshooting notification issues.

<br />

# **Canceling Certification**
[BACK TO TOP](#table-of-contents)

Providers may cancel the certification process for endorsements in **Passed** or **Notified** status.

Select the **Passed** or **Notified** button, then select **Cancel Certification**.

![image](https://user-images.githubusercontent.com/88680702/237750117-1fda4789-0b15-45a1-b391-8b4d05c80cf0.png)

<br />

A confirmation of the cancelation is sent to the provider. The recipient is not notified of a cancel action.

The endorsement will now show as **Canceled** and may be archived (see below).

See **[Admin FAQ](#admin-faq)** for scenarios around canceling certification.

<br />

# **Revoking Certification**
[BACK TO TOP](#table-of-contents)

RESO staff may revoke certifications under certain conditions and should consult with Josh Darnell prior to doing so.

See **[Admin FAQ](#admin-faq)** for scenarios around revoking certification.

<br />

# **Archiving Endorsements**
[BACK TO TOP](#table-of-contents)

Providers may now archive endorsements and should do so for any organizations that they are no longer serving or contain results that are otherwise unwanted.

Archiving is available for endorsements in **Passed**, **Notified**, **Certified**, **Canceled** or **Withdrawn** status.

Select the status button on the endorsement to be archived and select **Archive**.

![image](https://user-images.githubusercontent.com/88680702/237750397-e989b730-366a-4d0a-80ac-cc1419519ccf.png)

A notification of the archive action will be sent to the provider. The recipient is not notified.

See **[Admin FAQ](#admin-faq)** for scenarios around archiving endorsements.

<br />

## Auto-Archiving
Certification endorsements are automatically archived and replaced if a new endorsement of the same type is initiated by the provider.

Auto-archiving will occur for endorsements in **Passed**, **Notified**, **Canceled** or **Withdrawn** status.

Endorsements in a permanent status (**Certified**, **Revoked**) will remain alongside the new endorsements. The old endorsements may be manually archived by the provider at any time.

<br />

# My Account
[BACK TO TOP](#table-of-contents)

Selecting **My Account** at the top of the page displays user information and the ability to copy or create a new token hash.

<br />

## Creating a Token
Providers may create a token in order to access the certification data via Web API with the steps below.

Log in to **[certification.reso.org](https://certification.reso.org/)** with your username and password.

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

# Admin Actions
[BACK TO TOP](#table-of-contents)

<br />

## Creating an Admin User
Admins may create new admin users by selecting the **Admin Actions** button from the top toolbar.

Select the **Create User** button under the Admins section.

![img](https://lh4.googleusercontent.com/Z2uI46adcjJmOZZfs0yFr26dHsysRihOxkjXt7aFbTJ1tT3Ozo18ulpEMVzPI1oMmE4IOamob29WTwpn6sJJKQMOwZml-f3963dZYjl_dWXLBidv9pmapUO6yw_3V-1jpouFjmol0o2x0gF_OzUvQFA)

<br />

Create a username and password.

Enter a full name and email address, then select **Save**.

![img](https://lh3.googleusercontent.com/6hwmbf09CsIoL7iU7irmZrRI-lOpSJsIOUVXyVajd3Z8lCyA1wT9DPbzJIWKi-kJaD2c1vrniSaN2nhlPO6T8HwnRMASLCipNo-fCpwt5N9Y-KgZEKrylVPix_tpFPr88m835ypelbDg-nqdu7cCStE)

<br />

## Creating a Provider User
Select **Create User** under the Users section.

![img](https://lh6.googleusercontent.com/_t4LCDefXBF3PFj0uLnQPTWEIg8fyLYe7RFlrQbefNLqsMSlqi2YjH3sP4HOwvNEt1uUGmFYfJBpGzdJ_y0TXe_AaLi_gKUth4EoV8IbB2hZGdclCpXLodZFRJdSrzQAMdtTzJqfgOkmHoqTnsmcsEk)

<br />

Select the **Provider User** radio button.

Create a username and password.

Select the organization for the provider.

Enter a full name and email address, then select **Save**.

![img](https://lh4.googleusercontent.com/sSI8WTGLep82QSG7v3JfQ0_C1to6woNSBrzwicWNrsL3D3l1CzDkmuQq1UhoNlcEAtoe46jT3C9_bJ3lYVc3TLT-Sh-KPlSieW_PYWOEovNYqry0Hjztx77kjKGCiWjPeta_VFyJlwvKSEXOnSETjRU)

<br />

## Creating a Normal User
Select **Create User** under the Users section.

![img](https://lh4.googleusercontent.com/aI_MNeZ6MK-c4d9q-RV0t1MdTMhqcPS5zKLToM6VqYlfrQkaKmkyLQdEeaYmXrO3h8_TS6csZAvIKEzMGcn5vJOACe6ta4BDzTkRhHhFSVkdi555jhJmZZv7JhrzMpqDgH3ON_H4OAEYeJaUF-xNqrw)

<br />

Select the **Normal User** radio button.

Create a username and password.

Enter a full name and email address, then select **Save**.

![img](https://lh5.googleusercontent.com/l1aRbyk4yRlaE63Iqp8lcFrZbfqhcYVizs-IncfiJ-bvUX64CIvenzXCbVBbLV_oZT6CPmtii3UOKEn_naSZi8QQzjDXZoKyRrV5sKQpGtPcqoXHnnGpjl1RxOkrUJNaSUeOngy9NjntegjpNdHdvok)

<br />

## UOI Syncing
Currently, organization records are populated on the certification site by syncing from an internal spreadsheet containing Unique Organization Identifier (UOI) details.

See the **[UOI Sync Process](https://github.com/RESOStandards/reso-certification/wiki/UOI-Sync-Process)**.

<br />

# Admin FAQ
[BACK TO TOP](#table-of-contents)

<br />

## Notifications
**How many notifications can a provider send to their recipient (customer)?**<br />
Two notifications, partly due to spam concerns.

**What if a provider has used their maximum number of two notifications?**<br />
Providers should be encouraged to reach out to their customers directly through other methods. RESO staff may provide the original notification emails through copies of the email or the certification-alerts Slack channel to providers to relay to their customers, including date sent, destination email address and the original sender (i.e., certification@reso.org).

**What if the provider reports that their customer cannot locate the notification emails?**<br />
Confirm the recipient's email address with the recipient, copy the "magic link" used to review results from the original notification emails and send it directly to the recipient with instructions that the link is sensitive and not to be shared. Here is a sample email:

<br />

Greetings,

The most recent notification email was sent to [recipient email address] on [date] and came from certification@reso.org. The email contains a link to review and approve your certification endorsements. If you are unable to locate the email, the following link may be used to access and approve the results:

[paste magic link here]

**Note:** This is a sensitive link akin to a password and should not be shared outside of the appropriate staff at your organization.

Help with viewing and approving the certification endorsements may be found **[here](https://certification-help.reso.org/docs/recipients.html)**.

<br />

## Archiving Endorsements
**Why would an admin need to archive an endorsement?**<br />
* A recipient organization is disabled in the UOI sheet as the result of a merger
* A recipient organization is disabled as a result of nonpayment
* A nonmember organization purchases a single use report and then goes defunct (inactive)

**What statuses may be archived by an admin?**<br />
All Statuses: Passed, Notified, Certified, Canceled, Revoked or Withdrawn.

<br />

## Canceling Certification
**Can RESO staff cancel a certification at the request of a recipient?**<br />
Recipients should be directed to their provider for requests regarding cancelation.

**What if a recipient asks why their certification was canceled?**<br />
Recipients should be directed to their provider for the reason.

<br />

## Revoking Certification
**Why would an admin revoke a certification?**<br />
A certified provider or recipient may be found to be out of compliance in practice. The provider should be contacted and informed of the compliance issue.

**Can a provider revoke certification?**<br />
No, **Revoke** is a RESO admin-only function.

<br />

## Recipient Organization Mergers
**Do certified organizations that merge to create a new organization need to retest?**<br />
Yes, the new organization will need to retest regardless of the statuses of the organizations that comprise it.
