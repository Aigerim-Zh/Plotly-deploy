# Plotly-deploy

## Project Overview

Many bacteria types are not very well-studied and many more remain unknown to science. My task is to document some of these bacteria. In particular, I will be looking at bacterias that can synthesize proteins that taste like beef.

I was given samples of such bacteria from anonymous participants across the country. I am tasked with building an **interactive dashboard** that both the research participants and researchers can access. Participants will be able to use the dashboard and select their participant ID numbers and see what type of bacteria colonize their belly buttons.

## Resources
- ```Plotly.js``` JavaScript data visualization library. 
- ```D3.js``` JavaScript library to read the JSON data into the script file. Its ```d3.json``` method to read an external JSON file with the research data.
- ```D3.js``` library is downloaded from its CDN link and loaded into the HTML file. 
- ```HTML``` to build the webpage.
- Project data: [samples.json](https://github.com/Aigerim-Zh/Plotly-deploy#:~:text=3%20hours%20ago-,samples.json,-JSON%20data).

## Results

The dashboard can be accessed here: https://aigerim-zh.github.io/Plotly-deploy/

![](https://github.com/Aigerim-Zh/Plotly-deploy/blob/main/dashboard.gif)

The dashboard is interactive through a dropdown menu "Test Subject ID No." through which participants anonymized ID from the study can be selected.

Based on the selected, the following information will be displayed:
- Demographics panel showing:
    - Ethnicity
    - Gender
    - Age
    - Location
    - Blood type, and 
    - Belly Button Washing Frequency.
- Information about the top 10 bacterial species (OTUs) found in the sample as a Bar Chart and Bubble Chart.
- Information about washing frequency per week as a Gauge Chart.

Additional customizations to the dashboard include:
* Background Color
* Header Background Image
* Short Paragraph with the Article Link