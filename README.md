# Highcharts Pie
This modifies the [Highcharts Column Chart](https://github.com/teochewthunder/hsbar) to form a pie chart based on the same data.

## Changes
- The dataset is massaged into an array of objects, each with the property `name` and `y`, where `name` is the name of the player and `y` is the statistic value. 

## Requirements
- Function renaming and text changes.
- The `plotOptions` property here will do the following
  - `allowPointSelect`: allow individual pie slices to be selected via a click
  - `dataLabels`
    - `distance`: move the labels closer to the center
    - `filter`: remove certain labels based on a comparison operator and value
