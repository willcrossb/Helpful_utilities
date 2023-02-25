# Helpful_utilities
A collection of small projects and pieces of code that will hopefully be built into a macro data analysis libary at some point
 
## Auto_Report
This contains the Auto_report notebook which outputs a pdf of selected fred variables

**Instructions:**
* User provides a list of codes for fred
  * they must be provided in multiples of six, as the pdf function is set up to format properly with this number only. 
* User must also provide a logo.png in the assets subfolder
  * Alternately they could comment out that line in the pdf function

**Dependencies:**
* fredapi
* pandas
* datetime
* plotly
* fpdf

## fredget
Automatically collects fred data and stores dataframe as well as metadate

**Dependencies:**
* fredapi
* pandas

