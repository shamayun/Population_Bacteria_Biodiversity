# Bacteria Biodiversity in Human Population

## Overview of the project
A dashboard to dynamically visualize and share bacteria samples data. The drop down within the dashboard allows volunteers to select a their id number. The interactive tables and charts will then display with the corresponding data, allowing for further analysis and exploration.
## Resources
* Javascript, 
* HTML, 
* D3.js ,
* CSS &
* Plotly
## Results
I've created 4 functions to display volunteer's information:
1. init() that gets data from .json file and builds a selector with options to choose,
2. buildMetadata() which builds table "Demographic Info" with metadata of the volunteer based on id, gender, age, location 
3. buildCharts() that builds charts:
  * horizontal bar chart for top 10 bacteria found
  * bubble chart to show types and values of bacterias found
  * gauge chart for belly button washing frequency
4. optionChanged() which tracks the option change and call buildMetadata() and buildCharts() functions
Website can be accessed by going to
