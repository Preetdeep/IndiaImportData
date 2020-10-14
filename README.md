# IndiaImportData
To generate a country wise report from import data

## Background
* We use Data from Export Import Data Bank from Government of India. 
* Data contains 8 digit product codes for 2019-20 and 2018-19.
* We also use Country-wise data.

## Code
The code is to be run as R Markdown. The first bit of the code processes the data to get summaries at 2 digit, to clean names and to convert the amount from Rupees to Dollars.
Once the data is clean, we use a loop to generate details of each country and chapter. 
We look at dependence of a country on a product and dependent on a country for a product. 
If India imports 70% of its total apples from Vietnam, then India is dependent on Vietnam for that product. 
Similarly if apples make up 50% of Vietnam's total exports to India then Vietnam is depedent on apples.

## Report
Output is a word file with graphs and details of each country, each chapter and dependence.
I could generate a better looking PDF using knit to LaTeX but i would need to add things here and there later, therefore knit to Word.

## Issues
Yet to figure out how to add headings in the loop. 
