# Kickstarting with Excel
## Overview of Project:
This project is comprised of 3 "Deliverables"
The first deliverable is to create a chart that displays Outcomes Based on Launch Date. This task allows the user to visualize the successful, failed and canceled campaign outcomes.
This exercise also allows the user to manipulate and filter the data using pivot tables and a wide range of  built in excel functions. In doing this each user creates a Kickstarter_Challenge.xlsx
file. This was accomplished easily enough by opening the StarterBook.xlsx file and using the "save as" command to capture all the data and edits that has been done up to this point
in the learning modules. Once the Kickstarter_Challenge.xlsx is created the first task is to create a new column entitled "Years". The user will then use the excel YEAR() function
to capture the year data from the "Date Created Conversion" column. The next task is to create a pivot table in a new sheet entitled "Theater Outcomes by Launch Date". This
task allows the user to demonstrate their ability to organize anf filter Outcome data and then display the data using a line chart. This allows the user to better visualize any 
trends a pattens in the data.

The second deliverable is to create a chart that displays Outcomes Based on Goals. This task rquires the user to create an Outcomes Based on Goals Sheet and then create columns for
"Goal","Number Successful", "Number Failed", "Number Canceled", "Total Projects", "Percentage Successful", "Percentage Failed", and "Percentage Canceled. This task requires the user to
use the Excel COUNTIFS function to filter the data for specific criteria. This task also calls out for sumations and percentages for different "Goal" dollar amounts, this prompts
the user to use the SUM() function and the a percentage calculation. After the data is organized into a more structured layout, the user creates a line graph to help visualize the trends for 
the sets of data. For each of the first two deliverables the user saves the charts as a PNG to accompany the data.

The third deliverable is a basic summary of the kickstarter challenge. The task is to summerize the challenge in the REAME.md file on GITHUB. The written analysis is comprised of three sections, Project Overview, Analysis and
Challenges, and a Results Section.

### Purpose

The purpose of the analysis was to examine the relationship between to sets of data. The first analysis looks at outcomes compared to the launch dates. The second analysis looks at outcomes based on goals. By graphing both sets of data we are able to visualize and interpret the data to fully understand the relationships between the two if any.

##  Analysis and Challenges:

### Analysis of Outcomes Based on Launch Date

Here the graph shows the Outcome data over a 12 month range. It breaks the data sets into failures, successes, and cancellations. The graph also shows how each rate changes from month to month. You can see how the success data trends in a similar way with the failures. This seems logical because the summation of the two sets equals the total of of the data.

<img width="240" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/104540261/171261171-a850ab48-5319-4909-a642-cd4666a06519.png">

### Analysis of Outcomes Based on Goals

Here the graph shows the Outcome data compared to a range of goals. It breaks the data sets into failures, successes, and cancellations. The graph also shows how each rate changes from a range of goals. You can see how the success data trends in an inverse manner compared to failures. This seems logical because as the goal's dollar amount becomes higher you sucess rate drops and you failure rate increase.

<img width="636" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/104540261/171261566-2cb90bd0-20ed-4bd8-bc22-12f7e27bc86d.png">


### Challenges and Difficulties Encountered







## Results:

What are two conclusions you can draw about the Theater Outcomes by Launch Date? Although the successful data shows more pronounced peaks and troughs, the successful outcomes data
and the failed outcomes data seems to exhibit a similar trend. This would lead me to believe that there is another influential factor that effects both the rates of success and failures on a month by month bases.
If there is a seasonal effect there are more total Outcomes in warmer months than colder months. People show more interest in going to the theater when it is warm.

What can you conclude about the Outcomes based on Goals? The general trend of the data seems to indicate the higher you goal amount the less likely you are to succeed in reaching 
your goal.

What are some limitations of this dataset? One limitation of the data sets is that they don't provide any insight on the type of theater. It isn't broken down into theater subsets. It looks at
theater as a whole but provides no insight on how drama, comedies, or action trend on an individual basis.

What are some other possible tables and/or graphs that we could create? I would like to know if the number of backers effects the rate of success and I would like to overlay the data
with the exsisting charts to see if any correlation exsist.
