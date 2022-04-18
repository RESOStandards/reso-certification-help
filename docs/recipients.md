# Notifications
You will receive an email from certification@reso.org with a link to review and approve your results. The body of the email will contain a review link for the endorsement(s) that were submitted by your provider. If both **Data Dictionary 1.7** and **Web API Core 2.0.0** were submitted, they may be reviewed from the same link.

Select the **REVIEW AND APPROVE RESULTS** link located below the endorsement(s) to be taken to the Certification Summary Report.

_[Body of Bundled Email]_

# Endorsements
The RESO Certification process requires providers (MLS vendors) to review their customers’ (MLSs’) testing reports and then use the RESO Certification System to notify them. The customers will then review the results and approve them to receive certification for the given endorsement.

At this time, there are two possible endorsements that can be issued to data providers, **Data Dictionary 1.7** and **Web API Core 2.0.0**, which have different reports available.

The Web API Core 2.0.0 endorsement must be approved prior to Data Dictionary 1.7.

# Summary Report
Select your organization name with the blue button at the top to view your Certification Summary Report.

_[Organization Name Blue Box]_

Each report contains two views, Data Elements and Performance, accessed through a dropdown at the top of the page.

_[Views Dropdown]_

The Data Elements view shows your field and lookup counts and how they compare to the industry averages. The counts are broken down by Advertised and Available data.

**Advertised** refers to the data elements that were found in the server metadata.

**Available** indicates that the data element was also found in the payload during sampling.

Use the Availability Threshold slider to set a minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

_[Data Elements Chart]_

The Resources dropdown beneath the chart filters the data to the specific resource selected.

_[Resources Dropdown]_

The Performance View shows the data provider’s server metrics.

_[Performance View Chart]_

Performance is measured on:

**Payload Size** - a measure of how much data was retrieved when sampling the selected resource. When All is selected, it's the average across all resources found, measured in megabytes (MB).

**Response Time** - shows how long, on average, a request to the given server took to complete, measured in seconds (s).

**Seconds per 1K Records** - an estimate of how many seconds it might take to pull 1,000 records using pages of 100 records. It's based on the average response time found during data sampling and validation. Measured in seconds (s).

**N/A** means that the given recipient has not completed Data Dictionary 1.7 availability testing yet. Please contact RESO at certification@reso.org if you have any questions.

Your endorsements along with the count of Data Dictionary elements are shown below the charts.

_[Endorsement List]_

Once you have reviewed and are satisfied with the report, select the Approve button next to the endorsement to be taken to the Terms and Conditions page.

_[Approve Button]_

Once you have read and agreed terms and conditions, check the box to confirm and select **Proceed**.

The **Contact RESO** button allows you to send an email to RESO at certification@reso.org.

# Data Dictionary Report
The Data Dictionary Report allows you to explore the data elements of the server submitted for RESO certification.

[DD Report]

Your guide to RESO certification terms:

**Resources** are at the top level of the data structure. Think of a resource as the category of the items contained within it. Examples of resources are **Property**, **Member** and **Office**.

**Fields** are contained within Resources and are the descriptions of the listing components themselves. Examples of fields are ListPrice, Appliances and YearBuilt.

**Lookups** are the options within certain fields (e.g. **Appliances**). Within **Appliances**, there are lookups such as **Dishwasher**, **Gas Oven** and **Dryer**.

## Exploring the Data
The top right section of the report displays the overall counts of your data elements as submitted by your data provider.

_[Data Elements Counts]_

Selecting a resource displays all of the fields within it.

_[Data Elements Boxes]_

Selecting a field displays the data attributes, a link to its [Data Dictionary Wiki](https://ddwiki.reso.org/display/DDW17/RESO+Data+Dictionary+Wiki+1.7) entry and any lookups it may contain.

_[Standard Status Selected]_

The Data Elements buttons allow you to filter by the following data sets:

**RESO** - All Resources, Fields and Lookups matching the RESO Data Dictionary

**Local** - Market specific custom Resources, Fields and Lookups

**All** - The combination of RESO + Local

**IDX** - Resources, Fields and Lookups for public display by an MLS broker participant

_[Data Elements Buttons]_

The search filter allows you to search for fields across all resources.

_[Filter Search Box]
[Results of Search]_

# Web API Report
All MLS providers are required to obtain the Web API Core Endorsement prior to that of the Data Dictionary.

Selecting **Review and Approve** for Web **API Core 2.0.0** allows you to view your high level certification information including your Organization Name and Vendor Name. If any of this information is incorrect, please contact RESO at certification@reso.org.

_[Web API Report]_

Once you have reviewed your Web API Core 2.0.0 report, select the **Approve** button to be taken to the Terms and Conditions page.

A **Contact RESO** button on this page allows you to send an email to certification@reso.org.

Once you have read and agreed terms and conditions, check the box to confirm and select **Proceed**.

Your Web API Core Endorsement will then be issued and your report will be published.
