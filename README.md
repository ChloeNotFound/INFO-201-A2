# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through quantitative means. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps. 

This assignment is your opportunity to work directly with the same data used by the New York Times. While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

You'll load the data directly from the [New York Times GitHub page](https://github.com/nytimes/covid-19-data/), and you should make sure to read through their documentation to understand the meaning of the datasets. 

Note, this is a long assignment, meant to be completed over the two weeks when we'll be learning data wrangling skills. I strongly suggest that you **start early**, and approach it with patience. We're asking real questions of real data, and there is inherent trickiness involved. 

## Analysis
You should start this assignment by opening up your `analysis.R` script. The script will guide you through an initial analysis of the data. Throughout the script, there are prompts labeled **Reflection**. Please write 1 - 2 sentences for each of these reflections below:

- What does each row in the data represent (hint: read the [documentation](https://github.com/nytimes/covid-19-data/)!)?

In the dataset of national, the rows represent the number of cases and deaths every day. 
In the dataset of states, the rows represent the number of cases and deaths every day in each state.
In the dataset of counties, the rows represent the number of cases and deaths every day in each state and different counties.

- What did you learn about the dataset when you calculated the state with the lowest cases (and what does that tell you about testing your assumptions in a dataset)?

It will be helpful to separate the dataset apart, and calcuate the needed information from it.

- Is the location with the highest number of cases the location with the most deaths? If not, why do you believe that may be the case? 

No. I think it depends on the regional medical development and policy. 
Despite there are probably more cases in a region, it does not represent the 
lower medical level in this region, which means that this region probably will have lower 
death cases due to advanced medical development. Therefore, the location with the highest 
number of cases is not the location with the most deaths.

- Why are there so many observations (counties) in the variable `lowest_in_each_state` (i.e., wouldn't you expect the number to be ~50)?

Because each state may have the counties with the same lowest number of deaths.

- What surprised you the most throughout your analysis?

It is interesting to find out the least number of cases and deaths in different counties and in different states. The comparison of the number of death and the number of cases is good evidence to reflect the medical level and policies in different regions. 