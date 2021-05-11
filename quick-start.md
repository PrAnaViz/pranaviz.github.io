---
title: "Quick-Start Guide"
layout: page
---

## *PrAnaViz*

### Introduction

The aim of this tool is to visualize and analyze the prescription data to calculate total prescribed quantity of different APIs and to explore spatiotemporal trends of different APIs at Clinical Commissioning Group (CCG) regions with resolution to individual postcode. ***Note:*** The demo version of the tool hosted in the [link](http://51.141.234.162/shiny/pranaviz/ "PrAnaViz Demo") present only **Bath and North East Somerset CCG** dataset.

We have created, **PrAnaViz**, in a familiar browser-based dashboard layout that most users are familiar with from typical websites and online tools. The basis functionality of *PrAnaViz* is filtering datasets and producing graphs according to selection criteria defined by the user.

*PrAnaViz* grouped into two panels (1) Targeted API, (2) Non-targeted API, that each consist of two to three output boxes displaying the results. Users can navigate between different panels through clicking the respective option in the sidebar. And the user-defined selection can be downloaded in a *.pdf* or *.eps* and data as *.csv* format for further analysis.

### Targeted Approach

In this panel, user can input a list of APIs in *.csv* format, and find out the total prescription quantity of each API in the selected year, at the selected CCG region, as in the Figure: 4.1.

Results are shown in bar chart and line chart based on the user selection criteria (Month or Year).

This tab also visualize the total quantity of APIs prescribed by month, GP, Chemical form, and Medicinal form for a CCG region in a selected year.

<img src="/img/targeted_01.png" alt="targeted approach"/> Figure 4.1: PrAna Targeted Approach.

+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Option* | *Remarks*                                                                                                                                                                                              |
+==========+========================================================================================================================================================================================================+
| 1        | Select Targeted or Non-Targeted Approach                                                                                                                                                               |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 2        | Upload targets i.e., APIs in `.csv` format                                                                                                                                                             |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 3        | Select Year                                                                                                                                                                                            |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 4        | Select Region                                                                                                                                                                                          |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 5        | Select Setting Type                                                                                                                                                                                    |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 6        | Select month-wise or year-wise plots                                                                                                                                                                   |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 7        | Action button to generate the plot                                                                                                                                                                     |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 8        | Plot generated based on user selection                                                                                                                                                                 |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 9        | Download buttons to download the generated plot as `.pdf` or `.eps` and data as `.csv` format                                                                                                          |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 10       | Maximize and minimize the tab                                                                                                                                                                          |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 11       | More insights on a selected API, visualize total prescribed quantity of the API per month, GP practice, postcode and medicinal form (click on a particular API on the barplot to generate these plots) |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 12       | Download buttons to download the generated plot as `.pdf` or `.eps` and data as `.csv` format                                                                                                          |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| 13       | Maximize and minimize the tab                                                                                                                                                                          |
+----------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

### Non-targeted Approach

Total prescription quantity of an individual API at different postcode per month at a CCG region, can be rendered in this tab, as in the Figure: 4.2. The calculated total prescription quantity of an individual API at postcode level helps to find the hotspots. User can download data as *.csv* file and publication ready image *.eps* and *.pdf* files.

<img src="/img/non_targeted_01.png" title="non-targeted" alt="non-targeted approach"/> Figure 4.2: PrAna Non-targeted Approach.

+----------+--------------------------------------------------------------------------------------------------+
| *Option* | *Remarks*                                                                                        |
+==========+==================================================================================================+
| 1        | Select Targeted or Non-Targeted Approach                                                         |
+----------+--------------------------------------------------------------------------------------------------+
| 2        | Select *API* in the `drop-down` menu                                                             |
+----------+--------------------------------------------------------------------------------------------------+
| 3        | Select Region                                                                                    |
+----------+--------------------------------------------------------------------------------------------------+
| 4        | Select Year                                                                                      |
+----------+--------------------------------------------------------------------------------------------------+
| 5        | Select a month                                                                                   |
+----------+--------------------------------------------------------------------------------------------------+
| 6        | Button to generate the plot                                                                      |
+----------+--------------------------------------------------------------------------------------------------+
| 7        | Plot generated based on user selection, click on a particular postcode to generate further plots |
+----------+--------------------------------------------------------------------------------------------------+
| 8        | click on a particular postoode on the plot to generate these plots)                              |
+----------+--------------------------------------------------------------------------------------------------+
| 9        | Visualize the total prescribed quantity of the API per month on the selected postcode            |
+----------+--------------------------------------------------------------------------------------------------+
| 10       | Download buttons to download the generated plot as `.pdf` or `.eps` and data as `.csv` format    |
+----------+--------------------------------------------------------------------------------------------------+
