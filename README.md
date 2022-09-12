# UFO Sightings
JavaScript, Bootstrap, and UFOs

## Overview
The purpose of this analysis is to build a responsive website that contains a table of all of the UFO sitings for users to filter and analyze.

## Results
Step by Step Instructions to Filter UFO Sightings Data
1. Load the Site
2. Scroll down to the filter section
3. Choose an option from any or all of the drop-down lists
4. The table will update automatically
5. (Optionally) Click "Download results as CSV" to download the filtered data into CSV format.

## Analysis
### Drawbacks of this design
* Using text fields requires the users to already be familiar with the data, as they have to type in an exact match (spelling mistakes will return no data)
    * FIXED - Changed the input type from a text filed to a drop down list for each field
* Without a Clear Filter button, the users may be unsure how to reset the filter eaisly (reload page)
* Cannot return a wildcard search, as the search has to be an exact match

### Recommendations for Improvement
1. (Implemented) Switch to drop down lists instead of text input
2. (Implemented) Improve readability in the table data by formatting the text to the proper case
3. Add a form control to search the comments with partial text
4. Clean and standardize the Duration column