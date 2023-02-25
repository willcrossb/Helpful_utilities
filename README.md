# Helpful_utilities
First main project here was the automated financial markets pdf using FRED database and fpdf
 
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

