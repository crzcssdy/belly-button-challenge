# belly-button-challenge

# Module 14: Belly Button Biodiversity Challenge

In this assignment, I've built an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

### Notice to Graders: 
Please note that I worked with a couple of other classmates to troubleshoot and debug certain issues I encountered when completing this challenge. Additionally, I used ChatGPT to explain and provide examples on how to effectively navigate and establish the metadata field and the loop functions.


## Instructions
I've completed the following steps:

1. Used the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.

2. Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual, including the following: 

- Used sample_values as the values for the bar chart.

- Used otu_ids as the labels for the bar chart.

- Used otu_labels as the hovertext for the chart.

3. I created a bubble chart that displays each sample, with the following details:

- Used otu_ids for the x values.

- Used sample_values for the y values.

- Used sample_values for the marker size.

- Used otu_ids for the marker colors.

- Used otu_labels for the text values.

4. Next, I displayed the sample's metadata, i.e., an individual's demographic information.

- Then, I looped through each key-value pair from the metadata JSON object and create a text string and appended an html tag with that text to the #sample-metadata panel.

5. Updated all the plots when a new sample is selected.
   
6. Finally, I deployed the app to a free static page hosting service, GitHub Pages.
