![Title-Slide](https://github.com/a-woodbury/Water_World/blob/master/Resources/ghfsplash.jpg)

**Improving water availability in Tanzania by predicting waterpoint function**

### Overview

Tanzanian waterpoints require maintenance to ensure proper water supplyto the local population. We have a dataset with features of each waterpoint and their current function status. After exploring the features of the dataset, we will develop a series of models and identify the most accurate for implementation. 

### Repository Navigation
<pre>
Code               : <a href=https://github.com/a-woodbury/Water_World/tree/master/Jupyter_Notebooks/Modeling>Models </a>
Presentation       : <a href=https://github.com/a-woodbury/Water_World/blob/master/Final_Presentation/Functionality_Prediction.pdf>Slide Deck</a>
</pre>

### ReadME Navigation

[Problem](https://github.com/a-woodbury/Glass_Half-full/blob/master/README.md#problem) - 
[Data](https://github.com/a-woodbury/Glass_Half-full#data) -
[Model](https://github.com/a-woodbury/Glass_Half-full#model) -
[Results](https://github.com/a-woodbury/Glass_Half-full#results) - 
[Recommendations](https://github.com/a-woodbury/Glass_Half-full#recommendations) - 
[Future](https://github.com/a-woodbury/Glass_Half-full#future) - 
[Project Info](https://github.com/a-woodbury/Glass_Half-full#project-info) -
[Works Cited](https://github.com/a-woodbury/Glass_Half-full#works-cited)



## Problem

In Tanzania, only approximately 50% of the Tanzanian population have access to safe water. According to 2015 Tanzania Water Point Mapping data, about 29 percent of all water points are non-functional, out of which 20 percent failed within the first year. Using data from Taarifa and the Tanzanian Minisitry of Water, we were interested in predicting which pumps in Tanzania are functional and which pumps need repair. An understanding of which waterpoints will fail can improve maintence operations and ensure that potable, clean water is available to communities across Tanzania.

## Data


**Data Collection**

Key to understanding the data more fully is identifying how it was collected for the waterpoints. We found the XX organization provides a form for volunteers to complete when inspectiving waterpoints. From our EDA and observations, we have a theory that many of the beguiling observation data is result of the volunteer not knowing the best or most consisten answer and leaving it blank or selecting a close but vague record. This is best seen by observing the water quality data:

![qual.jpg](https://github.com/a-woodbury/Glass_Half-full/blob/master/Resources/form.png)

**Classes**

The original dataset is a ternary classification problem with three target classes. They are unfortunately very unbalanced and we decided to reclassify the targets into a binary problem. 

![classes.jpg](https://github.com/a-woodbury/Glass_Half-full/blob/master/Images/genrecounts.png)

## Model

## Results

The most effective model was the RandomForest which classified the waterpoints 83% accurately.


### Improving the current model

## Future

We have some ideas for expanding this project:

- The majority of observations had 0 total static head; we would like to know if this is expected or missing data

- We would also like data on waterpoint installation and maintenance cost

- Can we use remote-linked meters to collect data on quality, amount, etc., or is this a ‘pipe’ dream?



## Project Info
<pre>
Contributors : <a href=https://github.com/a-woodbury>Alphonso Woodbury</a>
               <a href=https://github.com/rashidbaset>Rashid Baset</a>
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda, Colab
Libraries    : 
</pre>

<pre>
Duration     : April 2020
Last Update  : 06.08.2020
</pre>

## Works Cited
