# My_Data_Science_Portfolio
My DS projects


# Project 1: Charts-and-interactive-annotations

Comparing bars to a range using tricolor palette and interactive annotations
Comparing bars to a range using tricolor palette and interactive annotations


Using matplotlib to apply interactive annotations to the base visualization in order to understand uncertain data better


This project is a part of my work done for the Coursera Data Science specialization by University of Michigan. We were asked to recreate the visual presented in the paper Ferreira et al, 2014. 
 
![Screen Shot 2021-11-16 at 09 56 07](https://user-images.githubusercontent.com/57463075/142032118-359f8000-3b62-4da0-818d-e9dacec788a2.png)


I implemented the bar coloring where the color of the bar is actually based on the amount of data covered. I added the interactivity button that allows user to interactively set a range of y values they are interested in, and recolor based on this

      
Note: The data given for this assignment is not the same as the data used in the article and as a result the visualizations may look a little different.


# Project 2: Cairo-s-principles-of-visualization
Number of hailstorms in Denver, Collin and Laramie over the past 30 years

This project is a part of my work done for the Coursera Data Science specialization by University of Michigan. 

We were given the overall assignemnet instructions  but the research question and the data source are my ideas.

Denver, Collin or Laramie? Which county has had the most hailstorms over the past 30 years ?

This visual is supposed to attract readers attention by displaying two apparently 'contradictory' graphs. The final purpose of the visual is to help reader to answer the research question: 'Which county had the most hailstorms over the past 30 years?' and to illustrate how graphics can lie. 

I am using the Cairo's method of "Hiding the relevant data" in this example. In order two answer the research question data was collected through NOOA website (data download is limited to 500 entries so Laramie county had to be separated in 2 files). CSV files were used to construct the data frames , but only column BEGIN_DATE was used. Dataframes had no NaN values. 
For the purpose of this task 2 sets of data frames were created. One set represents the cumulative sum over years, ignoring the county area and the second set incorporates the county area . The visual comprises of 2 subplots. The first one shows the cumulative number of hailstorms by county (Jan,1990-Dec,2020) ignoring the county area . We can see that the rate of change is increasing much faster in Laramie and Collin county than in the Denver county. Actually, the rate of change in Denver county is relatively steady. We can also notice that there is an increasing number of hailstorms from 2010 onward in Laramie and Collin county because the curve is getting steeper. According to this graph the Denver county had the smallest number of hailstorms and that the Laramie county had the most hailstorms over the last 30 years. The totals are presented at the very end of each line. The second subplot represents cumulative number of hailstorms per sq mi. The visual is totally opposite from the first one! The Laramie county which has had the most hailstorms over the last 30 years according to the first graph , is actually now the one with the least number of hailstorms when we include the county area into consideration. Vice versa, the Denver county is now the county with the most hailstorms over the last 30 years including the area into consideration.
I found this investigation very interesting as it shows how hiding the relevant data and changing the axes unit (from number to number/sq mi) can produce contradictory conclusions. This is a simple example of how the designer of the visual (data scientist ?) can create a misleading visual by omitting the relevant data or by simply not having the adequate skills or knowledge. 

I adressed following Cairo's principles in this project:
- thruthfulness: I chose 2 plots. One of them obscures (hides) data and the second one displays the relevant data
- beauty: colors that were used increase bauty and clarity of the graph
- functionality: I payed the attention to the data-ink ratio and removed all unnecessary elements of the graph. I highlighted only elements that are purposeful for the current graph 
-insightfulness: the format of the graph clearly displays the existing relationships and trends

The data for this project can be found below:

[storm_data_search_results Collin TX.csv](https://github.com/Joki79/Cairo-s-principles-of-visualization/files/7546932/storm_data_search_results.Collin.TX.csv)

[storm_data_search_results Denver.csv](https://github.com/Joki79/Cairo-s-principles-of-visualization/files/7546933/storm_data_search_results.Denver.csv)

[storm_data_search_results laramie_till2012.csv](https://github.com/Joki79/Cairo-s-principles-of-visualization/files/7546934/storm_data_search_results.laramie_till2012.csv)

[storm_data_search_resultsLaramie.csv](https://github.com/Joki79/Cairo-s-principles-of-visualization/files/7546935/storm_data_search_resultsLaramie.csv)


# Project 3

This project is a part of my work done for the Coursera Data Science specialization by University of Michigan. 


