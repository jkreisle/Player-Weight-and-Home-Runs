Click link for visualization: http://bl.ocks.org/jkreisle/73323bc6ba757f64c012dbdccb4c1922

## Objective

Determine the relationship between a baseball player's weight and home runs

###Skills applied

    - Javascript, in particular d3.js and dimple.js
    - CSS
    - Github collaboration
    - Usability: Made interactive graph and legend so user can more easily explore data

## Summary

I wanted to explore a baseball dataset containing:

    - player's name
    - handedness (right, left, both)
    - height
    - weight
    - batting average
    - home runs. 

I chose to create a visualization using d3.js and dimple.js because it allowed me to easily chart csv data and communicate my findings .

## Findings

Players with weights around average weight scored the most amount of home runs.

## Design

The chart's x axis tracks weight in pounds, and the y axis tracks home run count. The size of each dot is relative to the players batting average, where a player with a higher batting average will have a larger dot. A scatterplot was chosen as it was found to show the spread of data most effectively. The data is color coded based on handedness and can be filtered using the interactive legend. 

## Feedback

The feedback I received on my original chart focused on three main suggestions:

    - The need for more interactivity

        Solution: I chose to create a visualization using d3.js and dimple.js.
    - A reference line or some other visual showing trend

        Solution: I added a reference line to the chart where the average players weight occurs. This is at 187 pounds.
    - Improvements to stylistic elements in the code and css

        Solution: Uniform spacing throughout the code

## Resources

    1) https://github.com/PMSI-AlignAlytics/dimple/wiki
    2) http://dimplejs.org/examples_index.html
    3) http://dimplejs.org/advanced_examples_index.html
    4) https://bl.ocks.org/mbostock/3887118
    5) http://christopheviau.com/d3list/gallery.html
