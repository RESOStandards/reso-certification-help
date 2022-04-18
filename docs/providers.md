# Endorsements
The RESO Certification process requires providers (MLS vendors) to review their customers’ (MLSs) testing reports and then use the RESO Certification System to notify them. The customers will then review the results and approve them to receive certification for the given endorsement.

At this time, there are two possible endorsements that can be issued to data providers, **Data Dictionary 1.7** and Web **API Core 2.0.0**, which have different reports available.

After logging in to [certification.reso.org](certification.reso.org), the endorsements are shown under their respective organizations.

There are several sorting and filtering options at the top of the endorsements page.

_[Endorsement List]_

Filter by typing in an organization name or Unique Organization Identifier (UOI).

_[UOI Search Box]_

Filter to only show your customer organizations.

_[Results Slider]_

Filter by endorsement type and certification status.

_[Filter Options]_

Sort alphabetically ascending or descending.

_[Sort Options]_

The endorsements view includes the current version, a count of data elements (Data Dictionary endorsement), status date and status button.

Select **View Details** to the right of the endorsement to view the report.

_[Endorsement List Block]_

You may also access your endorsements by selecting the **Endorsements** option at the top of the page. This option is hidden if you are currently on the endorsements page.

_[Endorsement on Toolbar]_

# Summary Report
Selecting your customer organization name in the blue button at the top of the page will display the Certification Summary Report.

_[Organization Name Blue Box]_

Summary reports show information about the resources, fields and lookups that were found on your server for that organization.

Each report contains two views, Data Elements and Performance, accessed through a dropdown at the top of the page.

_[Views Dropdown]_

The Data Elements view shows the field and lookup counts and how they compare to the industry averages. The counts are broken down by Advertised and Available data.

**Advertised** refers to the data elements that were found in the server metadata.

**Available** indicates that the data element was also found in the payload during sampling.

_[Data Elements Chart]_

Use the Availability Threshold slider to set a minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

The Resources dropdown beneath the chart filters the data to the specific resource selected.

The Performance View shows your server performance metrics.

_[Performance View Chart]_

Performance is measured on:

**Payload Size** - a measure of how much data was retrieved when sampling the selected resource. When All is selected, it's the average across all resources found, measured in megabytes (MB).

**Response Time**- shows how long, on average, a request to the given server took to complete, measured in seconds (s).

**Seconds per 1K Records** -  is an estimate of how many seconds it might take to pull 1,000 records using pages of 100 records. It's based on the average response time found during data sampling and validation. Measured in seconds (s).

**N/A** means that the given recipient has not completed Data Dictionary Availability 1.7 testing yet. Please contact RESO at certification@reso.org if you have any questions.

# Data Dictionary Report
The Data Dictionary Report allows you to explore the data elements of the server submitted for RESO certification.

_[DD Report]_

The top right section of the report displays the overall counts of data elements.

_[Data Element Counts]_

The metadata viewer allows you to explore the data elements through a data tree. Selecting a resource displays all of the fields within it. Data availability percentages and payload statistics are also shown.

_[Data Elements Boxes]_

The Data Elements buttons allow you to filter by the following data sets:

**RESO** - All resources, fields and lookups matching the RESO Data Dictionary

**Local** - Market specific custom resources, fields and lookups

**All** - The combination of RESO + local

**IDX** - Resources, fields and lookups for public display by an MLS broker participant

_[Data Elements Buttons]_

The text filter box allows you to search for fields across all resources.

_[Filter Search Box]
[Results of Search]_

Selecting a field displays the lookups (if applicable), OData information and link to it’s [Data Dictionary Wiki](https://ddwiki.reso.org/display/DDW17/RESO+Data+Dictionary+Wiki+1.7) entry.

_[Standard Status Selected]_

The lookup filter buttons above the lookup values give you the ability to filter by All, RESO and Local. Data Dictionary lookup values are also linked to the Data Dictionary Wiki while local lookup values are not.

_[Lookup Values (Appliances as example)]_

# Web API Report
All MLS providers are required to obtain the Web API Core Endorsement prior to that of the Data Dictionary.

Select **View Details** at the right of the Web API Core 2.0.0 Endorsement to view the report.

_[Endorsement List]_

The Web API Core report displays the name of the organization that was tested as well as that of the data provider. If any of this information is incorrect, please contact RESO at certification@reso.org.

The report shows which version of OData the RESO Web API Server was using and the authentication type, with the current options being OAuth 2 Bearer Token or Client Credentials. The fields that were used for testing and the status button are also shown.

_[Web API Report]_

# Notifications
Endorsements must be reviewed and approved by customers before they are certified. The review requests are sent via email.

Selecting **Notify** for either Data Dictionary or the Web API Core report will send a bundled review notification for both endorsements. The recipient will be able to review and approve both reports from a single link that directs them to the Certification Summary page.

**Note:** The bundled notification is available ONLY when BOTH Data Dictionary and Web API are in **Passed** status. Otherwise, the email will only include the single endorsement that was selected for notification.

**Important: The email linking to the report should only be sent to the organization you are certifying. Any recipient of the email would have the ability to approve the results.**

## Sending Notifications
Select the **Passed** button from the endorsements page or any report page and select **Notify Recipient**.

_[Passed Button with Notify Dropdown]_

The email entry screen displays which endorsements will be included in the email. Enter the email address for your customer and select **Send Now**.

_[Email Address Entry Box]_

An email with a link to the report will be sent to your customer for review and approval. The button will then change to indicate **Notified**.

_[Notified Button]_

Once the customer has approved the results, the button will change to indicate Certified.

_[Certified Button]_

# My Account
Selecting **My Account** at the top of the page displays your user information and the ability to copy or create a new token hash. If any of this information is incorrect, please contact RESO at certification@reso.org.
