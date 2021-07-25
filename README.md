# Belly Button Biodiversity - Plotly Challenge

## Project Overview
In this project, an interactive dashboard was built to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels in JSON format.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Demographics information is dynamically populated based upon a user-selected test subject ID. A bar chart, bubble chart and a bonus gauge chart also update once the ID is changed. Code has been written using Plotly, JavaScript, HTML, CSS, and D3.js.

All CSS, JS and images required are under the static folder. The main HTML file index.html is in the root folder of the Github repo.

**The dashboard can be viewed here:** [Belly Button Diversity Dashboard](https://dhivyapadmanaban.github.io/plotly_deployment/)

## Summary

The ask was to retrieve test subject demographics, and draw a bar chart, bubble chart and gauge chart displaying each individual's samples. This was done as follows:

- Read in samples.json using the D3 library
- Retrieve metadata info for each test subject and display this in the form of an unordered list item as a key-value pair on the dashboard.
- Get required data for plotting, including sample_values, otu_ids and otu_labels which were used to create a trace and plot the bar chart.
- Since the task was to only plot the top 10 values, the three arrays were sliced and reversed to display the chart as below.

**BAR CHART**
![image](https://user-images.githubusercontent.com/83181834/126884337-697dffc5-8b1a-4dce-8f90-ba09e2dfb26e.png)

**BUBBLE CHART**
![image](https://user-images.githubusercontent.com/83181834/126884339-a4223dfc-73cb-4b84-acec-16b0dbe724f3.png)

**GAUGE CHART**
![image](https://user-images.githubusercontent.com/83181834/126884345-9aa808d2-09d1-410d-ae07-52703c1b320a.png)


**BELLY BUTTON BIODIVERSITY DASHBOARD**
![image](https://user-images.githubusercontent.com/83181834/126884332-680a0fc0-918b-43ae-876e-7c445d4bd116.png)
