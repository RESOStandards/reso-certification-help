# Endorsements
At this time, there are two possible endorsements that can be issued to data providers, **Data Dictionary 1.7** and **Web API Core 2.0.0**, each of which have different reports available.

The results of the endorsement certification tests are available for review in the RESO Certification System at [certification.reso.org](certification.reso.org).

There are several sorting and filtering options at the top of the endorsements page.

_[Endorsement Toolbar]_

Filter by organization name or Unique Organization Identifier (UOI).

_[UOI Search Box]_

Filter by endorsement type and certification status.

_[Filter Options]_

Sort alphabetically ascending or descending.

_[Sort Options]_

The endorsements view includes the current version, a count of data elements (Data Dictionary endorsement), status date and status indicator.

Select **View Details** to the right of the endorsement to view the report.

_[Endorsement List Box]_

You may also access the endorsements page by selecting the **Endorsements** option at the top of the page. This option is hidden if you are currently on the endorsements page.

_[Endorsement on Toolbar]_

# Summary Report

Summary reports show information about the resources, fields and lookups that were found during certification testing.

Each report contains two views, Data Element and Performance, accessed from a dropdown at the top of the page.

_[Views Dropdown]_

The Data Elements View shows the field and lookup counts and how they compare to industry averages. The counts are broken down by Advertised and Available data.

**Advertised** refers to the data elements that were found in the server metadata.

**Available** indicates that the data element was also found in the payload during sampling.

Use the Availability Threshold slider to set a minimum data availability that each field and lookup in the data set must be greater than or equal to. The default availability threshold level shows the count of data elements with availability greater than zero.

_[Data Elements Chart]_

The Resources dropdown beneath the chart filters the data to the specific resource selected.

_[Resources Dropdown]_

The Performance View shows the data provider’s server metrics.

_[Performance View Chart]_

Performance is measured on:

**Payload Size** - measures how much data was retrieved when sampling the selected resource. "All" represents the average across all resources found, measured in megabytes (MB).

**Response Time** - shows how long, on average, a request to the given server took to complete, measured in seconds (s).

**Seconds per 1K Records** - is an estimate of how many seconds it might take to pull 1,000 records using pages of 100 records. It's based on the average response time found during data sampling and validation. Measured in seconds (s).

**N/A** - means that the given recipient has not completed Data Dictionary 1.7 availability testing yet. Please contact RESO at certification@reso.org if you have any questions.

# Data Dictionary Report
The Data Dictionary Report allows you to explore the data elements of the organization being viewed.

_[DD Report]_

Your guide to RESO certification terms:

**Resources** are at the top level of the data structure. Think of a resource as the category of the items contained within it. Examples of resources are **Property**, **Member** and **Office**.

**Fields** are contained within resources and are the descriptions of the listing components themselves. Examples of fields are **ListPrice**, **Appliances** and **YearBuilt**.

**Lookups** are the options within certain fields (e.g., **Appliances**). Within **Appliances**, there are lookups such as **Dishwasher**, **Gas Oven** and **Dryer**.

## Exploring the Data
The top right section of the report displays the overall counts of data elements.

_[Data Element Counts]_

Selecting a resource displays all of the fields within it. Data availability percentages and payload statistics are also shown.

_[Data Elements Boxes]_

The Data Elements buttons allow you to filter by the following data sets:

**RESO** - All resources, fields and lookups matching the RESO Data Dictionary

**Local** - Market-specific custom resources, fields and lookups

**All** - The combination of RESO + Local

**IDX** - Resources, fields and lookups for public display by an MLS broker participant

_[Data Elements Buttons]_

The text filter box allows you to search for fields across all resources.

_[Filter Search Box]_

_[Results of Search]_

Selecting a field displays the lookups (if applicable), OData information and a link to its [Data Dictionary Wiki](https://ddwiki.reso.org/display/DDW17) entry.

_[Standard Status Selected]_

The lookup filter buttons above the lookup values give you the option to filter by All, RESO and Local. RESO Data Dictionary lookup values are also linked to the Data Dictionary Wiki.

_[Lookup Values (Appliances as example)]_

# Web API Report
The Web API Core report displays the name of the organization that was tested as well as that of the data provider.

The report also shows which version of OData the RESO Web API Server was using, the authentication type (OAuth 2 Bearer Token or Client Credentials) and the fields that were used for testing.

_[Web API Report]_



