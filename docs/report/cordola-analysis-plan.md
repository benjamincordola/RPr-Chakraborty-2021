# Planned revisions to reproduction of Chakraborty (2021)

Author: Cordola, Benjamin

## Analysis
<!--Enumerate and justify changes to analytical plan here-->
1. Change color ramp for final chloropleth map.
    I recalibrated the color ramp for the chloropleth map showing each country's weight in the GEE model. Previously, only half of the color ramp was being displayed, but by commenting out ___midpoint = 0___ was able to use the whole color ramp.
    (line 1860)
2. Move the "rationale for the updated report" section to the very end.
    This improves readability and flow. 
3. Improve formatting of missing data table with Kable.
    On line 363, we display a table that shows Rio Arriba county and its missing data. For the sake of presentation, I transposed the rows and columns, so that it does not run off the page. I also separated the code block, so that I could display my table as I modified it, before deleting data that prevents the table from being generated. 
4. Integrate discussion sections and any new results.
    
5. Separate conclusions section.
6. 


## Results

<!--Describe how changes will be visualized / compared here-->

## Discussion

<!--Describe how you will interpret the results of your changes here.
For example, in hypothetical terms, if my new/revised map shows ---, it will mean that ---. 
-->