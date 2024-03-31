# Belly Button Biodiversity

A dashboard that explores the biodiversity of the human belly button also catalogs the microbes that inhabit the naval of humans.

This dataset consisted of 661 participants, on average they scrubbed their belly buttons twice a week. The study looks at microbial species
(also called operational taxonomic units, or OTUs). In this dataset, a small handful of OTUs were present in more than 70% of people, 
while the rest were relatively rare.

# Technologies and Tools Used:
D3.js: For reading the samples.json dataset and manipulating the DOM.
Plotly.js: To create interactive visualizations, including a bar chart, bubble chart, and an optional gauge chart.
HTML/CSS: For structuring and styling the dashboard's webpage.
JavaScript: The primary programming language used for the web application's functionality.

# Dashboard Features:
A drop-down menu, demographic info panel, horizontal bar graph, gauge chart, and bubble chart.
Repository Navigation:
index.html: The main HTML document for the dashboard.
samples.json: The dataset containing microbial species (OTUs) data.
static/js/app.js: Contains the JavaScript code for fetching the data, and generating and updating the visualizations.
static/css/style.css: Custom CSS styles for the dashboard.

You can use the drop-down to see a particular participant in the study. 
The demographic panel shows information about the participants in the study.
The horizontal bar graph is generated when someone is selected from the drop-down. The top 10 OTUs in that test subject will be displayed in bars. 
When a user hovers over a bar, the otu_labels are presented as the hovertext for the chart. 
The gauge chart is generated when someone is selected from the drop-down. The value of scrubs per week is displayed on a chart with a blue colored bar. 
The bubble chart is generated when a test subject is selected on the drop menu. Each sample will be displayed as a bubble, where the larger the sample value is the larger the bubble size.
On the chart, the x values are the otu_ids, and the y values are the sample_values. The colors of the bubbles are based on otu_ids, and the hover text is the otu_labels.

# Conclusions:
A significant portion of the microbial species found in human navels are common across a majority of the population.
The diversity of rare microbes varies significantly between individuals, suggesting personalized microbial ecosystems.
The dashboard effectively demonstrates the potential of interactive web visualizations in engaging users with complex datasets.
