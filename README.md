# Plotly-Belly-Button-Biodiversity

## Overview

Roza, who is a micro-biological researcher want to build a dashboard to explore the Belly Button Biodiversity dataset, which categorized by bacterial species that exists in human belly buttons. Her goal is to identify the top 10 bacterial species in human belly buttons, so that Improbable Beef identifies a species as a candidate to manufacture synthetic beef and Roza's volunteers will be able to identify whether that species is found in their navel.

## Resource

Data Source: samples.json

Software: VS Code, Javascript, Plotly, Bootstrap, d3, HTML

## Results

### Bar Chart

The first step in creating the dashboard was to use the d3 library to read the samples.json dataset. Then,create a horizontal bar chart which will display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu. The horizontal bar chart will display the sample_values as the values, the otu_ids as the labels, and the otu_labels as the hover text for the bars on the chart. The image is as follows:

![](https://github.com/akthersr/Plotly-Belly-Button-Biodiversity/blob/main/bar%20chart.png)

### Bubble Chart

The second step of creating the dashboard is to create a bubble chart using plotly and similar script fromat we used for bar chart. The markers for the bubbles were set to be sized based on the sample_values and marker colors as otu_ids.The bubble chart is as follows:

![](https://github.com/akthersr/Plotly-Belly-Button-Biodiversity/blob/main/Resources/bubble%20chart.png)

### Gauge Chart

The final chart of the dashboard was created to show how often each of the test subjects washed their belly buttons per week. This gauge chart will displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar, when an individual ID is selected from the dropdown menu. From the data, the wFreq data was converted to a floating deciaml and saved as wFreq var. The gauge chart is as follows:

![](https://github.com/akthersr/Plotly-Belly-Button-Biodiversity/blob/main/Resources/gauge%20.png)


## DashBoard

The final step is to create the Belly Button Bio-diversity dashboard, was to cutomize the webpage and make more visually attractive to the user. The final dashboard is shown below:

![](https://github.com/akthersr/Plotly-Belly-Button-Biodiversity/blob/main/final.png)
