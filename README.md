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
  
We run forEach loop with if for each filter where in if the filter was answered then the filteredData is filtered based on the user value. This way if Date was not answered whereas City was selected, then the data will only be filtered on City and of there was any existing date filter that would be removed from the final data
  
The index.html file was updated to include 4 new filters on City, State, Country and Shape.
  
## Screenshot
  
Screenshot for a sample working filter on City = fresno
![alt text](https://github.com/29bharat/UFOs/blob/master/static/images/Filtered%20Data%20Sample.PNG)
  
## New Bootstrap Functions Added:
  
Underlined UFO Sightings: Fact of Fancy? and Filter Search (Enter Below)
  
Bolded Filter Search (Enter Below) and Filter Data button
  
Center Aligned Filter data button
  
Aligned all the filter text boxes.
