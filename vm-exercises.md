# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- revenue_data.csv

#### Files

https://public.tableau.com/views/YearOverYearCalculation/FinalVisualization?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link

#### Learning Objective

Students will learn how to createa a year over year calculation in Tableau from scratch.

#### Context

Learning how to use year over year calculations in Tableau is important because it allows users to quickly identify trends and changes in data across different time periods. This can be used in real-life situations to analyze sales or other types of data over a period of time, allowing businesses to make informed decisions based on their data. Year over year calculations are an effective way of understanding how data changes over time, which can be essential for businesses to accurately measure their performance.

#### Steps to be executed by the student (max 6)

- Open the exercise dataset in Tableau.
- Drag the Date dimension onto the columns field and the Revenue measure onto the rows field.
- Create a filter on the Date dimension to only include data from 2021 and 2022. 
- Drag this filter onto the Color mark to display different lines from each year on the worksheet.
- Add the Revenue measure to the rows field again, and apply the year-over-year table calculation to this second Revenue measure.
- Change the visualization type for the new Revenue table calculation view to 'Area'.

#### Exercise question:

In which week do we observe the greatest yoy (year on year) difference in revenue?

#### End goal:

[![Alt text](https://drive.google.com/file/d/1qGC3ft8DgjE2XCQ3n6l6u7sT9SawhD4a/view?usp=sharing)](https://drive.google.com/file/d/1qGC3ft8DgjE2XCQ3n6l6u7sT9SawhD4a/view?usp=sharing)


## 2nd VM Exercise

#### Dataset

- revenue_data.csv

#### Files

https://public.tableau.com/views/YearOverYearCalculationTwo/FinalVisualization?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link

#### Learning Objective

Students will learn how to change the calculation type of a year over year calculation.

#### Context
Tableau enables us to display year over year calculations in different ways. Knowing how to change the calculation type gives us greater flexibility in how we present data to stakeholders.

#### Steps to be executed by the student (max 6)

- Change the year filter to only include data for 2020 and 2021.
- Add the Revenue measure to the rows field for a third time.
- Apply the year-over-year table calculation to this third Revenue measure.
- Edit the table calculation and change the calculation type from Percentage Difference From to Difference From.
- Change the visualization type of this new view to 'Bar'.

#### Exercise question:
What metric does the y-axis on the bar graph show? 
1. The running sum of revenue in 2022 compared with 2021
2. The total difference in revenue between the same period in 2022 compared with 2021
3. The percentage difference in revenue between the same period in 2022 compared with 2021.

#### End goal:
[![Alt text](https://drive.google.com/file/d/1xXErPMgauyWwGghifZKe-OMDmpErjdTH/view?usp=sharing)](https://drive.google.com/file/d/1xXErPMgauyWwGghifZKe-OMDmpErjdTH/view?usp=sharing)
