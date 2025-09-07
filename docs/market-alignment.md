# Market Alignment Report

The Market Alignment Report combines organizations, such as MLSs, and their provider systems (organization may have multiple providers) as one entity and shows how well the data aligns across those systems. For example, it can compare the data from five different MLSs that may each have multiple providers systems.

The report provides a detailed view of all data elements from the organizations, including their specific resources, fields and lookups, the frequency that they are filled with data and how they overlap with each other. This is especially useful for MLSs that are involved in or are considering becoming part of a data share.

## Select the Organizations and Provider Systems
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

<img width="1661" height="83" alt="image" src="https://github.com/user-attachments/assets/66fd70eb-eedc-4591-9f02-e5f76e4c5fb4" /><br/>

## Diagram

The Venn Diagram can display up to three organizations and their providers systems at a time, with each organization/provider combo represented by a circle.

The overlapping sections indicate that the data elements in that section are used by every organization/provider included in it.

<img width="1735" height="1024" alt="image" src="https://github.com/user-attachments/assets/0854f0f1-7598-49ef-b643-8c7e1cda3910" /><br/>

The Extended tooltips provide details about each organization/provider, including their names, Data Dictionary version and counts of RESO and Local data elements.

<img width="276" height="138" alt="image" src="https://github.com/user-attachments/assets/14dac13e-6cac-467f-ac71-42c3e3732860" /><br/>

Hover over a non-overlapping region to see a count of the RESO and Local data elements it includes. This represents data elements that are included for only that organization/provider.

<img width="1087" height="599" alt="image" src="https://github.com/user-attachments/assets/3d45b096-dd6c-4925-a992-7ba31d180f01" /><br/>

Hover over an intersection to see the percentage of alignment and count of data elements between the overlapping organizations/providers. This represents the data elements that are included for every organization/provider in that section.

<img width="1038" height="582" alt="image" src="https://github.com/user-attachments/assets/7b1049ec-d0e5-4ef2-9b5a-d5a81b4beeea" /><br/>

Select a region or intersection to see the specific data elements with their availability (how often they are populated with data) as compared to the industry average and the other organizations/providers represented on the diagram.

<img width="1736" height="1021" alt="image" src="https://github.com/user-attachments/assets/dfeaa237-ce72-4dfb-a4f8-1726ca7cfa20" /><br/>

### Counts and Alignment Summary

This section summarizes the counts and overall alignment of fields and lookups between the selected organizations/providers. These counts change based on any [Filters](##Filters) selections.

<img width="830" height="158" alt="image" src="https://github.com/user-attachments/assets/f1bb6346-21de-4de3-9a34-a624ed2227a1" /><br/>

Select **All** or **Common** to narrow the summary data. All includes every field and lookup, while Common displays only those shared across the selected organizations/providers.

## Filters

The Market Alignment Report can be narrowed to represent specific criteria with the Filter options below.

For example, a user might want to analyze how well fields from different systems in a specific market align with each other and with the RESO standard. More specifically, they may want to focus on just the Property Resource and the IDX data fields that are filled with data (availability) 50% of the time or more.

### Organization and Provider System Selection

Select which organizations/providers are included in the diagram (maximum of three).

<img width="701" height="492" alt="image" src="https://github.com/user-attachments/assets/466f378a-7e41-4d10-b066-fc5e50cd41f1" /><br/>

### Data Elements Filter
Filter the data in the diagram by classification of the data elements. **RESO** are standard Data Dictionary data elements, **Local** are unique to the system being viewed and **IDX** are those tagged with the IDX Payload.

<img width="838" height="103" alt="image" src="https://github.com/user-attachments/assets/5c2d0ee3-1481-4813-93b6-4fc2362e1ddd" /><br/>

### Report View Selection

Navigate between the Graph, Diagram and Details Report Views.

<img width="244" height="87" alt="image" src="https://github.com/user-attachments/assets/3466964b-612b-4136-b240-d70c0cd78579" /><br/>

### Resource Selection
Select a resource to narrow the diagram, summary counts and other metrics to data elements from only that resource.

<img width="349" height="489" alt="image" src="https://github.com/user-attachments/assets/751c5682-c1f9-48b7-a1cc-975a1adfc023" /><br/>

### Fields and Lookups Filter
Select whether fields or lookups are represented on the diagram.

<img width="327" height="80" alt="image" src="https://github.com/user-attachments/assets/cff1a623-7e5c-4d0c-a960-4d234cfee807" /><br/>

### Availability Threshold
Increase the Availability Threshold percentage to narrow the diagram to data elements that are populated with data more frequently.

<img width="821" height="85" alt="image" src="https://github.com/user-attachments/assets/da5c8830-c487-4e6f-9a66-b55f7d7285f4" /><br/>

For example, a user may want to see how consistently the highly used (e.g. 75% or greater) IDX data elements are represented across multiple systems in a market.

<img width="1740" height="1028" alt="image" src="https://github.com/user-attachments/assets/c7218f14-7616-40f2-b8e7-717b7498c551" /><br/>

### Anomalies
Check the Anomalies box to filter the diagram to show only data elements whose availability varies by 25% or more between at least two of the selected systems.

<img width="1661" height="83" alt="image" src="https://github.com/user-attachments/assets/66fd70eb-eedc-4591-9f02-e5f76e4c5fb4" /><br/>

## Details

The Details View shows the individual data elements, their availability under each provider system, the industry average availability and the number of unique recipients (usually MLSs) in a sortable table format.

This view, when used with the diagram and graph, allows comparison of data elements and their availability across various organizations and provider systems within a market. For example, a user interested in a data share may use the report to assure that their critical fields are present in all of the systems that they may collaborate with.

The Details View contains the same [Filter](##Filters) options as the Graph [Diagram View](##-Venn-Diagram), with the addition of the [Heat Grid](###Heat-Grid)

### Heat Grid
Check the Heat Grid box to to apply a color-coded layer to the data elements in the table, showing a range of availability differences between provider systems. The legend appears below the table.

## Print and Export
Print or export the data from both report views by selecting the Print and Export buttons at the top right.

<img width="140" height="93" alt="image" src="https://github.com/user-attachments/assets/3052add5-a08c-4949-8006-6cec464da682" /><br/>








