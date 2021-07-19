# bioDiversity

### Purpose of this challenge:
After completing the panel for demographic information, we now need to visualize the bacterial data for each volunteer. In particular, the volunteers should be able to identify the top 10 bacterial species in their belly buttons. If Improbable Beef identifies a species as a candidate to manufacture beef, the volunteers will be able to identify whether that species is found in their naval.

Studies found that more than 70% of people revealed that a small handful of microbal species called operational taxonomic units (OTUs) were present.

### Steps:
By creating the trace object, the layout, and Plotly.newplot() function we created the horizontal bar chart.

The bat chart has the following:

- The top 10 sample_values are sorted in descending order
- The top 10 sample_values as values
- The otu_ids as the labels

<img width="432" alt="HorizontalBarChartModule12" src="https://user-images.githubusercontent.com/83566868/126098988-8ef2fe4f-5596-43ae-a861-40c498ef9e02.png">

Using JavaScript, Plotly, and D3.js, a bubble chart was created that will display the following when an individual’s ID is selected from the dropdown menu webpage:

- The otu_ids as the x-axis values
- The sample_values as the y-axis values
- The sample_values as the marker size
- The otu_ids as the marker colors
- The otu_labels as the hover-text values

<img width="735" alt="BubbleChartModule12" src="https://user-images.githubusercontent.com/83566868/126099340-197bcb70-5a03-4de1-9e8c-8b520417deba.png">

Using JavaScript, Plotly, and D3.js,a gauge chart was created that displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

<img width="418" alt="GaugeChartModule12" src="https://user-images.githubusercontent.com/83566868/126099500-ec60942c-c9b6-4115-b75f-749251ea5534.png">

### The final we browser page looks like:

<img width="1200" alt="FinalModule12" src="https://user-images.githubusercontent.com/83566868/126099649-32ca802f-cdcb-4b83-a634-88014d5b97f6.png">



