# Provider Alignment Report

The Provider Alignment Report is a tool to help an organization, such as an MLS, see how consistent its data is presented across multiple API services.

Many MLSs offer more than one API, which may contain differences in their data elements (fields and lookups), which are then encountered by comsumers of the data.

This report provides both a high-level visual summary for presentations and a detailed view for internal analysis, allowing organizations to identify where better alignment of data elements may be needed.

## Diagram

The Venn Diagram can display up to three providers at a time, with each provider represented by a circle.

The overlapping sections indicate that the data elements in that section are used by each provider included in it.

<img width="1735" height="1022" alt="image" src="https://github.com/user-attachments/assets/6d27ef22-cf99-4aad-bd83-92da9ea5c0b1" />

The Extended tooltips provide details about each provider, including the provider name, Data Dictionary version and counts of RESO and Local data elements.

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

## Filters and Other Options
The Provider Alignment Report can be narrowed to represent specific criteria with the options below. For example, an organization may want to view the alignment between two of their providers for only the RESO data elements of the Property Resource.

### Provider Selection

Select which providers are included in the diagram (maximum of three).

<img width="1746" height="732" alt="image" src="https://github.com/user-attachments/assets/a592fb05-a95a-4fa4-af99-6333b79a8004" />

### Data Elements Filter
Filter the data in the diagram by classification of the data elements. RESO are standard Data Dictionary data elements, Local are unique to the system being viewed and IDX are those tagged with the IDX Payload.

<img width="838" height="103" alt="image" src="https://github.com/user-attachments/assets/5c2d0ee3-1481-4813-93b6-4fc2362e1ddd" />

### Report View Selection

Navigate between the Diagram and Details Report Views.

<img width="189" height="103" alt="image" src="https://github.com/user-attachments/assets/8f631953-63e3-476c-bb9e-4f944874f73f" />

### Resource Selection
Select a resource to narrow the diagram, summary counts and other metrics to data elements from only that resource.

<img width="349" height="489" alt="image" src="https://github.com/user-attachments/assets/751c5682-c1f9-48b7-a1cc-975a1adfc023" />

### Fields and Lookups Filter
Select whether fields or lookups are represented on the diagram.













