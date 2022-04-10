# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of the analysis is to provide Louise information about how different campaigns fared in relation to their launch dates and their funding goals

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To understand the outcomes based on launch dates, the analysis focused in the relation between the 'Date Created Conversion' grouped by months and the count of different outcomes excluding the outcome 'live'. The analysis was perfomed for the parent category "tether. A pivot table was created containing the following relevant fields:
	* Filters:
		- 'Parent category' field filtered in 'theater'
		- 'Year' field
	* Columns: 'Outcomes' filed
	* Rows: 'Date Created Conversion' field 
	* Values: Count of 'Outcomes'
	
PIVOT image

To help visualize the outcomes of the analysis, a Line chart of the different outcomes was created containing the count of 'outcomes' on the Y axis and the 'date created conversion' grouped by months on the X axis.

CHART image
	

### Analysis of Outcomes Based on Goals

To understand the outcomes based on goals, the analysis focused in the relation between twelve different goal ranges and the count of different outcomes excluding the outcome 'live'. The analysis was performed for the subcategory 'plays'. A table was created using the formula 'countifs' and then the percentage of each outcome was calculated for the different goal ranges.

TABLE image

To better understand and visualize the analysis, a Line chart was created with the information described above. In the chart, we can oberve the relation between the plays outcome and the goal.

CHART image 

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	* The months of May and June have a greater success rate
	* The month of December seems not to be a good month to launch a theater campaign as the quantity of successful and failed campaigns is very similar. According to the data base, 35 out of 75 campaigns or 47% of the campaigns failed in the month of December
	* The number of failed therater campaigns is more stable throughout the year with an average number of 41 failed campaings per month

- What can you conclude about the Outcomes based on Goals?

	* Theater is a popular and successful type of campaign overall
	* There is a negative correlation between the percentage of successful theater campaigns and the campaigns goals. This means that the greater the goal, the more chances the campaign will fail
	* There is a positive correlation between the percentage of successful theater campaigns and the campaigns goals. This means that the lower the goal, the more chances the campaign will succeed

- What are some limitations of this dataset?

	* We could keep filtering the pivots and charts to be more precise. We could filter countries, years, weeks, etc. However, we need to be careful not to miss gereral trends or lose the aim of the analysis	
	* There could be outliers we need to understand and manage. There could also be mistakes in the dataset
	
- What are some other possible tables and/or graphs that we could create?

	* We could create an Analysis of Outcomes Based on Launch Date grouped by year
	* We could create a stacked column chart of the outcomes based on goals
	
	
