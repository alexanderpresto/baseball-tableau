<h1>
<div style="text-align: center"> Baseball: Who makes the most home runs? </div>
</h1>

## Summary
The [dataset](../master/baseball_data.csv) consists of 1,157 records of professional baseball players. The variables include name,  handedness (left or right handed), weight in pounds, the batting average and number of home runs.

The batting average refers to the rate at which the player hits the ball pitched at him which is a number between 0 and 1.

We will try to determine if the variable in the dataset is a reliable predictor of home runs.

Click [here](https://public.tableau.com/profile/alex.presto#!/vizhome/Baseball_final_0/BaseballvFinal?publish=yes) to go to the Tableau Story.

## Design
The choice of colors are based on what is the most visible for the color blind. You will notice that the main color of choice is blue and where contrast is need, the other colors used are orange and red.

Previously, the text used to make comments or interpret the data was typed in the caption box. As requested, I reduced the amount of text and place more in the visualization. I generally put an introduction in the caption box along with summary of what can be concluded in anything. Then, bulk of the details are entered in the body of the visualization.

Initially, a few visualizations where separated into different slides for different filtering for each data. This gave me more real estate on the screen to type interpretation of the data. However, feedback included desire to have it all in a single slide so the reader can compare the results of the turning on, off or modifying the filter.

This in turn necessitated creating calculated fields to allow filtering like BMI Levels (Normal, Overweight, Obese), Percentiles of number of home runs and batting average like Tops 95%, 75%, 50% and bottom 50%. This allowed me to filter everything on a single slide.
