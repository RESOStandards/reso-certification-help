# Provider Alignment Report

The Provider Alignment Report is a tool to help an organization, such as an MLS, see how consistent its data is presented across multiple API services.

Many MLSs offer more than one API, which may contain differences in their data elements (fields and lookups), which are then encountered by consumers of the data.

This report provides both a high-level visual summary for presentations and a detailed view for internal analysis, allowing organizations to identify where better alignment of data elements may be needed.

## Venn Diagram

The Venn Diagram can display up to three providers at a time, with each provider represented by a circle.

The overlapping sections indicate that the data elements in that section are used by each provider included in it.

<img width="1735" height="1022" alt="image" src="https://github.com/user-attachments/assets/6d27ef22-cf99-4aad-bd83-92da9ea5c0b1" />

The Extended tooltips provide details about each provider, including the provider's name, Data Dictionary version and counts of RESO and Local data elements.

<img width="268" height="134" alt="image" src="https://github.com/user-attachments/assets/7e62405e-082c-4af1-a5ce-916b73e99101" />

Hover over a non-overlapping region to see a count of the RESO and Local data elements it includes. This represents data elements that are included for only that provider.

<img width="1134" height="603" alt="image" src="https://github.com/user-attachments/assets/d6e0acfe-4f5f-4d7b-b4c3-c45be7093a85" />

Hover over an intersection to see the percentage of alignment and count of data elements between the overlapping providers. This represents the data elements that are included for every provider in that section.

<img width="1097" height="615" alt="image" src="https://github.com/user-attachments/assets/0b5bc23d-9d11-46c8-a3c3-03fe197430cb" />

Select a region or intersection to see the specific data elements with their availability (how often they are populated with data) as compared to the industry average and the other providers represented on the diagram.

<img width="1746" height="1035" alt="image" src="https://github.com/user-attachments/assets/fe85f6e9-1f94-490e-8251-419620d81c21" />

## Counts and Alignment Summary
This section summarizes the counts and overall alignment of fields and lookups between the selected providers.

<img width="836" height="173" alt="image" src="https://github.com/user-attachments/assets/f89dbb3e-7bfa-49e6-b22c-66adb62dcd1c" />

Select All or Common to narrow the summary data. All includes every field and lookup, while Common displays only those shared across the selected providers.

## Filters
The Provider Alignment Report can be narrowed to represent specific criteria with the options below.

For example, an organization may want to focus on aligning the RESO standard data elements for the Property Resource between its providers. The report can also help them pinpoint fields that are populated with data (availability) significantly more often in one provider or another (**[Anomalies](###Anomalies**)).

### Provider Selection

Select which providers are included in the diagram (maximum of three).

<img width="1746" height="732" alt="image" src="https://github.com/user-attachments/assets/a592fb05-a95a-4fa4-af99-6333b79a8004" />

### Data Elements Filter
Filter the data in the diagram by classification of the data elements. RESO are standard Data Dictionary data elements, Local are unique to the system being viewed and IDX are those tagged with the IDX Payload.

For example, an organization might want to identify where its IDX data elements differ between providers to make them more consistent. The RESO standard data elements can also be a point of focus for aligning data across different providers.

<img width="838" height="103" alt="image" src="https://github.com/user-attachments/assets/5c2d0ee3-1481-4813-93b6-4fc2362e1ddd" />

### Report View Selection

Navigate between the Diagram and Details Report Views.

<img width="189" height="103" alt="image" src="https://github.com/user-attachments/assets/8f631953-63e3-476c-bb9e-4f944874f73f" />

### Resource Selection
Select a resource to narrow the diagram, summary counts and other metrics to data elements from only that resource.

<img width="349" height="489" alt="image" src="https://github.com/user-attachments/assets/751c5682-c1f9-48b7-a1cc-975a1adfc023" />

### Fields and Lookups Filter
Select whether fields or lookups are represented on the diagram. The report can be used to identify differences for either type of data element.

<img width="327" height="80" alt="image" src="https://github.com/user-attachments/assets/cff1a623-7e5c-4d0c-a960-4d234cfee807" />

### Availability Threshold
Increase the Availability Threshold percentage to narrow the diagram to data elements that are populated with data more frequently. For example, an organization may want to see how consistently their highly used (e.g. 75% or greater) data elements are represented across the providers.

<img width="821" height="85" alt="image" src="https://github.com/user-attachments/assets/da5c8830-c487-4e6f-9a66-b55f7d7285f4" />

### Anomalies
Check the Anomalies box to filter the diagram to show only data elements whose availability varies by 25% or more between at least two of the selected providers. Anolalies provides a quick way to narrow the diagram to data elements that may need attention. For example, a field populated 76% of the time from one provider but only 18% from another.

<img width="1661" height="83" alt="image" src="https://github.com/user-attachments/assets/66fd70eb-eedc-4591-9f02-e5f76e4c5fb4" />

## Details

The Details View of the report shows the individual data elements, their availability under each provider system, the industry average availability and the number of unique recipients (usually MLSs) in a sortable table format.

This view can be used in conjunction with the diagram for organizations to see where their data elements differ between provider systems. These differences may include whether specific fields or lookups are not present for all systems. Additionally, the details view makes it easy to spot differences in availablity between systems. For example, an organization may want to investigate cases where a field is populated much more frequently in one system over another.

The Details View contains the same [filter options](##Filters) as the Diagram View, with the addition of the [Heat Grid](###Heat-Grid).

### Heat Grid
Check the Heat Grid box to to apply a color-coded layer to the data elements in the table, showing a range of availability differences between providers. The legend appears below the table.

<img width="1746" height="1039" alt="image" src="https://github.com/user-attachments/assets/122825bb-bf82-4520-af36-6047937e0fc6" />











