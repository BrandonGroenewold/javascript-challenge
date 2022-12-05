# Belly Button Biodiversity

Here is an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Overview of project

1. I used the D3 library to read in `samples.json` from the URL `https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json`.

2. Then I created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

  * `sample_values` as the values for the bar chart.

  * `otu_ids` as the labels for the bar chart.

  * `otu_labels` as the hovertext for the chart.

  ![bar Chart](Images/hw01.png)

3. Next I created a bubble chart that displays each sample.

  * `otu_ids` for the x values.

  * `sample_values` for the y values.

  * `sample_values` for the marker size.

  * `otu_ids` for the marker colors.

  * `otu_labels` for the text values.

![Bubble Chart](Images/bubble_chart.png)

4. After that I displayed the sample metadata, for example an individual's demographic information.

5. Then I displayed each key-value pair from the metadata JSON object somewhere on the page.

![hw](Images/hw03.png)

6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:

![hw](Images/hw02.png)

7. Finally I deployed my app to a free static page hosting service
