# :alien: UFO Sightings :alien:
JavaScript, Bootstrap, and UFOs

## Overview
The purpose of this analysis is to build a responsive website that contains a table of all of the UFO sitings for users to filter and analyze.

## Results
When users land on this page, they can use the instructions below to filter the UFO Sightings Table to filter for the specific information that they need and even download the results as a CSV.

| Step by Step Instructions to Filter UFO Sightings Data |
| ----------------------|
| 1. Scroll down to the filter section|
| <img src="https://user-images.githubusercontent.com/107961905/189763720-2315687d-6683-4529-842d-2974654f7150.png" width="400"> |
|   |
| 2. Choose an option from any or all of the drop-down lists |
| <img src="https://user-images.githubusercontent.com/107961905/189762116-ff1b5b28-77d5-492f-aa76-c2fb4cc03e16.png" width="400"> |
|   |
| 3. The table will update automatically
| <img src="https://user-images.githubusercontent.com/107961905/189764394-59ef81ec-59c6-4b50-a176-b7122e8c8fd1.png" width="400"> |
|   |
| 4. (Optionally) Click "Download results as CSV" to download the filtered data.
| <img src="https://user-images.githubusercontent.com/107961905/189761959-7b5202ce-711a-4b03-afc2-c8a594449896.png" width="200"> |

## Analysis
### Drawbacks of this design
* Using text fields requires the users to already be familiar with the data, as they have to type in an exact match (spelling mistakes will return no data)
    * FIXED - Changed the input type from a text filed to a drop down list for each field
* Without a Clear Filter button, the users may be unsure how to reset the filter eaisly (reload page)
* Cannot return a wildcard search, as the search has to be an exact match

### Recommendations for Improvement
1. (Implemented) Switch to drop down lists instead of text input
    1.1 Load the Drop-Down list contents dynamically
    1.2 Adjust Drop-Down list contents based on choices in other lists.
2. (Implemented) Improve readability in the table data by formatting the text to the proper case
3. (Implemented) Add a count of filtered results
4. Add a form control to search the comments with partial text
5. Clean and standardize the Duration column

## Website Preview
<img src="https://user-images.githubusercontent.com/107961905/189765177-c7e44b3c-1832-4234-8cca-c4fa2c2e97bf.png" width="600">