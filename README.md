# Belly Button Challenge

## Activity: Build an Interactive Dashboard

Build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogues the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Instructions

- The "Starter_Code" folder contains files: `index.html`, `samples.json`, and a "static" folder containing the "js" folder that contains `app.js`.

- It is not required to access the `samples.json` file locally, but it is provided for reference.

- Use `console.log` inside the JavaScript code to see what the data looks like at each step.

- Use the D3 library to read in `samples.json` from the URL. 

- Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual. Use `sample_values` as the values for the bar chart. Use `otu_ids` as the labels for the bar chart. Use `otu_labels` as the hover text for the chart.

- Ensure the Bar Chart initializes without error, updates when a new sample is selected, uses Top 10 sample values as values, uses `otu_ids` as the labels, uses `otu_labels` as the tooltip.

- Create a bubble chart that displays each sample. Use `otu_ids` for the x values. Use `sample_values` for the y values. Use `sample_values` for the marker size. Use `otu_ids` for the marker colors. Use `otu_labels` for the text values.

- Ensure the Bubble Chart initializes without error, updates when a new sample is selected, uses `otu_ids` for the x values, uses `otu_ids` for marker colors, uses `sample_values` for the y values, uses `sample_values` for the marker size, uses `otu_labels` for text values.

- Display the sample metadata, i.e., an individual's demographic information.

- Display each key-value pair from the metadata JSON object somewhere on the page.

- Update all the plots when a new sample is selected.

- Ensure Metadata initializes without error.

## Dashboard

Explore the Belly Button Biodiversity dashboard at [https://leedavidarmstrong.github.io/]
