# PyBer_Analysis :taxi:

## Purpose

Using Python knowledge of Pandas,  I created a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, I created a multiple-line graph that shows the total weekly fares for each city type.

## Technologies

  * Python
  * Pandas
  * Matplotlib

## Ride share summary data by city type.

### Deliverable 1 

 * The total number of rides for each city type is retrieved. 
 * The total number of drivers for each city type is retrieved.
 * The sum of the fares for each city type is retrieved.
 * The average fare per ride for each city type is calculated.
 * The average fare per driver for each city type is calculated.
 * A PyBer summary DataFrame is created.
 * The PyBer summary DataFrame is formatted as shown in the example.


## Results
  * More fares by urban cities.

<br>
<img src="https://github.com/Acromic/PyBer_Analysis/blob/main/Resources/Screen%20Shot%202022-03-26%20at%2011.57.41%20PM.png" width="25%" height="25%">
<br>

  * Rural areas carry the biggest average fare per driver

<br>

<img src="https://github.com/Acromic/PyBer_Analysis/blob/main/Resources/Screen%20Shot%202022-03-27%20at%2012.01.48%20AM.png" width="25%" height="25%">

<br>

### Deliverable 2

 * A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
 * A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare." 
 * A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28.
 * A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
 * An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.
 
## Results

 * Urban total fares more than double Rural and Suburban put together
  

<img src="https://github.com/Acromic/PyBer_Analysis/blob/main/Resources/PyBer_fare_summary.png" width="50%" height="50%">

<br>

## Summary
More drivers needed in urban cities have generated more money than both rural and suburban areas combined.
With shorter average fares, more fares are taken daily. The longer the distance travelled the total rides go down.
With shorter distances travelled and higher rides rates, Urban areas are the biggest opportunity for revenue.
