# scs-m14-belly-button-challenge

In this challenge, we will be using data provided to plot charts

Deployed GitHub Pages: https://msncn.github.io/scs-m14-belly-button-challenge/

## Instructions

1. Use the D3 library to read in samples.json from the URL `https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.`

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use `sample_values` as the values for the bar chart.
* Use `otu_ids` as the labels for the bar chart.
* Use `otu_labels` as the hovertext for the chart.

![image](https://github.com/msncn/scs-m14-belly-button-challenge/assets/130943141/949450a5-0d2a-4ff3-b567-20b2daaccbbe)

3. Create a bubble chart that displays each sample.

* Use `otu_ids` for the x values.
* Use `sample_values` for the y values.
* Use `sample_values` for the marker size.
* Use `otu_ids` for the marker colors.
* Use `otu_labels` for the text values.

![image](https://github.com/msncn/scs-m14-belly-button-challenge/assets/130943141/9397ee5a-a03f-42ea-bd7b-ffa3dfefdfd1)

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.
![image](https://github.com/msncn/scs-m14-belly-button-challenge/assets/130943141/53851b77-6a00-4e4b-aabf-9b2adc6f1d07)

6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:
![image](https://github.com/msncn/scs-m14-belly-button-challenge/assets/130943141/416b4b33-9a09-4c5d-b09a-d619dc2b417d)

7. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file


## Optional

The following task is advanced and therefore optional.

* Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.
* You will need to modify the example gauge code to account for values ranging from 0 through 9.
* Update the chart whenever a new sample is selected.

![image](https://github.com/msncn/scs-m14-belly-button-challenge/assets/130943141/a9b80bae-3d01-4987-b281-41927d0ae2c8)

Hints
* Use `console.log` inside of your JavaScript code to see what your data looks like at each step.
* Refer to the Plotly.js documentation (https://plotly.com/javascript/) to an external site. when building the plots.
