# Belly Button Biodiversity Dashboard

## [*An Interactive Dashboard in JavaScript (D3 & Plotly), HTML and JSON*](https://guileless-trifle-f53692.netlify.app/)

*https://guileless-trifle-f53692.netlify.app/* ![belly-button-biodiversity-dashboard](https://github.com/onemanlutta/belly-button-challenge/assets/118937365/75b98d2a-26e7-497e-961b-33b9228b8535)



## Background

The project uses D3.js to fetch and parse the dataset, and Plotly.js to build interactive charts. The main features of the dashboard include:
- A dropdown menu to select test subject ID numbers.
- A panel to display demographic information of the selected test subject.
- A horizontal bar chart to show the top 10 OTUs found in the selected individual.
- A bubble chart to display the sample values for each OTU.

## Getting Started (Prerequisites and Tools)

These instructions will help you set up and run the project on your local machine.

### Prerequisites

- A web browser (e.g., Chrome, Firefox)

### Tools

- D3.js: A JavaScript library for producing dynamic, interactive data visualizations in web browsers.
- Plotly.js: A graphing library that makes interactive, publication-quality graphs online.
- HTML: The standard markup language for creating web pages.
- JSON: A lightweight data-interchange format.

## The Tasks and Solution

### Reading data with the D3 library
D3.js is used to fetch and parse the dataset from a JSON file.

### Horizontal bar chart with dropdown menu
A horizontal bar chart is created to display the top 10 OTUs found in the selected individual, with a dropdown menu to select different test subjects.

![Top 10 Bacteria Cultures](https://github.com/onemanlutta/belly-button-challenge/assets/118937365/f03b0828-e63e-4025-8879-b251c9068cc1)


### Bubble charts
A bubble chart is created to display the sample values for each OTU in the selected individual.

![Bacteria Cultures Per Sample](https://github.com/onemanlutta/belly-button-challenge/assets/118937365/019f1e58-502a-4c15-a3d7-2b8e99492c38)



### Metadata and Deployment
The [dashboard](https://guileless-trifle-f53692.netlify.app/) includes a panel to display demographic information of the selected test subject.

![Demographics](https://github.com/onemanlutta/belly-button-challenge/assets/118937365/dde422ab-f66f-48ab-8688-7477281a6a4a)



## Project Files
- `index.html`: Main HTML file for the dashboard interface
- `app.js`: JavaScript file containing the logic to fetch data and build charts
- `samples.json`: Dataset containing microbial data for each test subject

### Project Structure

- belly-button-challenge   
  - `index.html`
  - `samples.json`
  - Static/js
    - js
      - `app.js`
  - images
    - Bacteria Cultures Per Sample.png
    - belly-button-biodiversity-dashboard.png
    - Demographics.png
    - Top 10 Bacteria Cultures.png
  - `README.md`: Contains the overview, instructions, or other relevant information.


## Usage (this Dashboard)

To use the dashboard:
1. Clone the repository.
2. Navigate to the project directory.
3. Open `index.html` in your web browser.

## Reference

- [D3.js Documentation](https://d3js.org/)
- [Plotly.js Documentation](https://plotly.com/javascript/)
- Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: [http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

## Disclaimer

The sample dataset used in this project is for educational purposes. The microbial data presented here should not be interpreted as medically accurate or reflective of actual scientific research findings.
