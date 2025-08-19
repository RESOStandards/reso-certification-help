# Market Alignment Report

The Market Alignment Report shows how well data lines up across multiple organizations. For example, it can compare the data from five different MLSs that all may use different API services.

The report provides a detailed view of all data elements from the organizations, including their specific resources, fields and lookups, the frequency that they are filled with data and how they overlap with each other. This is especially useful for MLSs that are involved in or are considering becoming part of a data share.

## Selecting the Organizations and Systems
Select **Reports**, **Market Alignment Report** from the toolbar.

<img width="541" height="180" alt="image" src="https://github.com/user-attachments/assets/476d3c43-87d1-4b0a-9846-911ab7fb3966" /><br/>

Select the organizations and provider systems to be included in the report.

<img width="1736" height="1032" alt="image" src="https://github.com/user-attachments/assets/2024e072-6047-4cd4-8874-03df0f15275b" /><br/>

Select **Next**.

## Graph
The first part of the report is a graph that uses color-coded lines to visually represent the percentage of alignment between each organization's data.

<img width="1748" height="1027" alt="image" src="https://github.com/user-attachments/assets/f3069f4d-7afe-410a-985a-0ca30c519b5e" /><br/>

Select the alignment ranges on the legend to add or remove them from the graph. By default, all ranges are selected.

<img width="1005" height="52" alt="image" src="https://github.com/user-attachments/assets/b2389b0e-d160-4139-9810-60ad6bca0ec4" /><br/>

You can use the alignment ranges to focus on specific data elements. For example, to view only highly aligned data, you can deselect the red, orange, and yellow ranges.

<img width="1688" height="726" alt="image" src="https://github.com/user-attachments/assets/9c384c79-dddf-42b6-92ff-19e18372e1d6" /><br/>

Hover over the alignment lines to see a count of the types data elements they include.

<img width="1674" height="584" alt="image" src="https://github.com/user-attachments/assets/358c928b-1aee-4a73-ab19-1ad72c62f6cf" /><br/>

### Counts and Alignment Summary
This section summarizes the counts and overall alignment of fields and lookups between the selected organizations and providers. These counts change based on any [Filters](##Filters) selections.

<img width="829" height="170" alt="image" src="https://github.com/user-attachments/assets/5666ac26-d95b-495a-9fdb-d38e81fd912e" /><br/>

Select All or Common to narrow the summary data. All includes every field and lookup, while Common displays only those shared across the selected providers.

## Filters

The Market Alignment Report can be narrowed to represent specific criteria with the options below.

### Organization and Provider System Selection

Select which organizations and provider systems are included in the graph.

<img width="1754" height="744" alt="image" src="https://github.com/user-attachments/assets/fd3e31f9-351e-4061-a14e-58fbc5455dad" /><br/>

### Data Elements Filter
Filter the data in the graph by classification of the data elements. RESO are standard Data Dictionary data elements, Local are unique to the system being viewed and IDX are those tagged with the IDX Payload.

For example, the report can be used to find out how well IDX data elements align between organizations and systems. The RESO standard data elements can also be a key focus for identifying data alignment between systems.

<img width="838" height="82" alt="image" src="https://github.com/user-attachments/assets/1b488ef8-bbdf-4679-b42a-d5f240678875" /><br/>

### Report View Selection

Navigate between the Graph, Diagram and Details Report Views.

<img width="189" height="103" alt="image" src="https://github.com/user-attachments/assets/8f631953-63e3-476c-bb9e-4f944874f73f" /><br/>

### Resource Selection
Select a resource to narrow the graph, summary counts and other metrics to data elements from only that resource.

<img width="378" height="515" alt="image" src="https://github.com/user-attachments/assets/3870baa2-3811-4b8c-9172-e666ff379cc1" /><br/>

### Fields and Lookups Filter
Select whether fields or lookups are represented on the graph. The report can be used to identify differences for either type of data element.

<img width="327" height="80" alt="image" src="https://github.com/user-attachments/assets/cff1a623-7e5c-4d0c-a960-4d234cfee807" /><br/>

### Availability Threshold
Increase the Availability Threshold percentage to narrow the graph to data elements that are populated with data more frequently. For example, a user may want to see how the systems align for fields that are populated with data at least 75% of the time.

<img width="821" height="85" alt="image" src="https://github.com/user-attachments/assets/da5c8830-c487-4e6f-9a66-b55f7d7285f4" /><br/>

### Anomalies
Check the Anomalies box to filter the graph to show only data elements whose availability varies by 25% or more between the systems.

<img width="1661" height="83" alt="image" src="https://github.com/user-attachments/assets/66fd70eb-eedc-4591-9f02-e5f76e4c5fb4" />












