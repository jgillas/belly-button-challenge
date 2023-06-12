# belly-button-challenge

In this challenge we were asked to analyze samples.json from the url: https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json

First I created a dropdown menu for all the different test subject ID numbers. This allows for you to select different test subject ID numbers and see all the different data for each test subject. 

I then created a horizontal bar chart showing the top 10 OTUs. The sample_values are the values for the bar chart. The otu_ids are the labels for the bar chart. Lastly, the otu_labels are the hovertext for the chart. This bar chart will change when you change the test subject ID number.

A picture of the horizontal bar chart I created is below: 

  ![bargraph](https://github.com/jgillas/belly-button-challenge/assets/125215083/3256835f-fa28-406c-a236-a72663a36723)

The next thing I did was create a bubble chart to display each sample. The otu_ids are the x-values. The sample_values are the y-values. The sample_values are also used for the marker size. The otu_ids are used for the marker colors and the otu_labels are used as the text values. 

A picture of the bubble chart I created is below: 

  ![bubblechart](https://github.com/jgillas/belly-button-challenge/assets/125215083/15660236-dff6-446c-b4c4-db1a0c5326f8)

The next thing I did was I displayed the sample metadata information (the test subject's demographic information). In the demographic information each key-value pair from the metadata JSON object is displayed. This includes the id number, their ethnicity, their gender, their age, their location, their bbtype and their wfreq. A picture of the demographic information chart is below: 

  <img width="176" alt="Screenshot 2023-06-12 at 2 13 55 PM" src="https://github.com/jgillas/belly-button-challenge/assets/125215083/226acf18-0ed6-40a7-bba9-65043c956743">

The last thing that I did was update all the plots when a new sample is selected. This concludes this assignment. 
