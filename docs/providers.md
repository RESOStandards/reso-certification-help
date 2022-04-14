# Endorsements
The RESO Certification process requires providers (MLS vendors) to review their customers’ (MLSs) testing reports and then use the RESO Certification System to notify them. The customers will then review the results and approve them to receive certification for the given endorsement.

At this time, there are two possible endorsements that can be issued to data providers, **Data Dictionary 1.7** and Web **API Core 2.0.0**, which have different reports available.

After logging in to [certification.reso.org](certification.reso.org), the endorsements are shown under their respective organizations.

There are several sorting and filtering options at the top of the endorsements page.

Filter by typing in an organization name or Unique Organization Identifier (UOI).

Filter to only show your customer organizations.

Filter by endorsement type and certification status.

Sort alphabetically ascending or descending.

The endorsements view includes the current version, a count of data elements (Data Dictionary endorsement), status date and status button.

Select View Details to the right of the endorsement to view the report.

You may also access your endorsements by selecting the Endorsements option at the top of the page. This option is hidden if you are currently on the endorsements page.

# Summary Report
Selecting your customer organization name in the blue button at the top of the page will display the Certification Summary Report.

Summary reports show information about the resources, fields and lookups that were found on your server for that organization.

Each report contains two views, Data Elements and Performance, accessed through a dropdown at the top of the page.

The Data Elements view shows the field and lookup counts and how they compare to the industry averages. The counts are broken down by Advertised and Available data.

**Advertised** refers to the data elements that were found in the server metadata.

**Available** indicates that the data element was also found in the payload during sampling.

Use the Availability Threshold slider to set a minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

The Resources dropdown beneath the chart filters the data to the specific resource selected.

The Performance View shows your server performance metrics.

Performance is measured on:

Payload Size - a measure of how much data was retrieved when sampling the selected resource. When All is selected, it's the average across all resources found, measured in megabytes (MB).

**Response Time**- shows how long, on average, a request to the given server took to complete, measured in seconds(s).

**Bandwidth** - is payload size divided by response time. Similar to an internet speed test, this metric shows how quickly consumers might expect to retrieve data from the given server, measured in megabytes per second (MB/s).

**N/A** means that the given recipient has not completed Data Dictionary 1.7 payloads testing yet. Please contact RESO at certification@reso.org if you have any questions.

# Data Dictionary Report
The Data Dictionary Report allows you to explore the data elements of the server submitted for RESO certification.

The top right section of the report displays the overall counts of data elements.

The metadata viewer allows you to explore the data elements through a data tree. Selecting a resource displays all of the fields within it. Data availability percentages and payload statistics are also shown.

The Data Elements buttons allow you to filter by the following data sets:

**RESO** - All Resources, Fields and Lookups matching RESO Data Dictionary

**Local** - Market specific custom Resources, Fields and Lookups

**All** - The combination of RESO + Local

**IDX** - Resources, Fields and Lookups for public display by an MLS broker participant

The text filter box allows you to search for fields across all resources.

Selecting a field displays the lookups (if applicable), OData information and link to it’s [Data Dictionary Wiki](https://ddwiki.reso.org/display/DDW17/RESO+Data+Dictionary+Wiki+1.7) entry.

The lookup filter buttons above the lookup values give you the ability to filter by All, RESO and Local. Data Dictionary lookup values are also linked to the Data Dictionary Wiki while local lookup values are not.

# Web API Report
All MLS providers are required to obtain the Web API Core Endorsement prior to that of the Data Dictionary.

Select View Details at the right of the Web API Core 2.0.0 Endorsement to view the report.

The Web API Core report displays the name of the organization that was tested as well as that of the data provider. If any of this information is incorrect, please contact RESO at certification@reso.org.

The report shows which version of OData the RESO Web API Server was using and the authentication type, with the current options being OAuth 2 Bearer Token or Client Credentials. The fields that were used for testing and the status button are also shown.

# Notifications
Endorsements must be reviewed and approved by customers before they are certified. The review requests are sent via email.

Sending notification of the Data Dictionary report will send the approval requests together in a bundle along with the Web API Core report. The recipient will be able to explore and approve both reports from either link in the case of a bundled notification.

**Note:** the only time the email is a bundle is when BOTH Data Dictionary and Web API are in Passed status. Otherwise, the email will only be for the endorsement selected.

***Important: The email linking to the report should only be sent to the organization you are certifying. Any recipient of the email would have the ability to approve the results.**

## Sending Notifications
Select the Passed button from the endorsements page or any report page.

Enter the email address for your customer and select Send Now.

An email with a link to the report will be sent to your customer for review and approval. The button will then change to indicate **Notified**.

Once the customer has approved the results, the button will change to indicate Certified.

# My Account
Selecting **My Account** at the top of the page displays your user information and the ability to copy or create a new token hash. If any of this information is incorrect, please contact RESO at certification@reso.org.
