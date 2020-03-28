# UFOs
  
## Objective
  
Create additional filters for the webpage. The advanced filtering capability will allow users to filter the data by multiple factors.
  
## Resources
  
Existing data.js to populate the data.
  
app.js file from the module
  
index.html file  from the module
  
style.css
  
## Steps
Used the existing app.js code from the module and replaced handleClick finction with updateFilters where we are capturing all the 5 filters of Date, City, State, Country and Shape. Also setting filtereddata with the original tabledata.
  
we run if-else for each filter where in if the filter was answered then the filteredData is filtered based on the user value. Else it resets it to the last filteredData snapshot. Thsi way if Date was not answered whereas City was selected, then the data will only be filtered on City and of there was any existing date filter that would be removed from the final data
  
The index.html file was updated to include 4 new filters on City, State, Country and Shape.
  
## New Bootstrap Functions Added:
  
Underlined UFO Sightings: Fact of Fancy? and Filter Search (Enter Below)
  
Bolded Filter Search (Enter Below) and Filter Data button
  
Center Aligned Filter data button
  
Aligned all the filter text boxes.
