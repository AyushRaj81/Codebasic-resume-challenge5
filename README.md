# Codebasic-resume-challenge5
Domain:  Tourism | Function: Revenue / Municipal Administration

Project Overview

Telangana is one of India’s leading states and has published its tourism data under its open data policy.As a data analyst my task is to analyze the given visitor data for 2016-2019 and answering the research question provided and provide data imformtion recommendations to the telangana government which can be used to increase their revenue by improving administrative operation

Resources provided:

a.    Dataset required to answer preliminary research questions.

b.    Metadata

c.    Instructions for using dataset.

d.    Sample Presentation


In my project, I encountered a data set consisting of two folders. One folder contained domestic tourist data, which included separate files for the years 2016 to 2019. The other folder contained foreign tourist data specific to the region of Telangana, also organized into separate files for the same time period.

Tools used for completion of project

To merge these data sets, I leveraged the capabilities of the Python pandas library. I began by reading and loading the domestic tourist data files into a pandas DataFrame, creating a separate DataFrame for each year. Using pandas' concatenation function, I combined these separate DataFrames into a single DataFrame, resulting in a merged domestic tourist dataset.

Similarly, I repeated the process for the foreign tourist data from the Telangana folder. Reading and loading the foreign tourist data files into separate DataFrames for each year, I then concatenated them together to obtain a merged foreign tourist dataset specific to Telangana.

To merge the domestic and foreign tourist datasets, I employed pandas' merge function. By specifying a common key, such as a unique identifier for each record, I combined the two datasets into a final merged dataset. This merged dataset contained information on both domestic and foreign tourist data for the years 2016 to 2019.

link of jupyter notebook of merging multiple file: https://jovian.com/ayushraj21042002/mergingmultiple-file

Once the data merging was complete, I utilized the openxlsx library to export the merged dataset into an Excel file. This allowed for further analysis and manipulation using Excel's extensive functionalities.

 I leveraged Excel's extensive charting and graphing features to visually represent key findings and insights. Creating visually appealing and informative charts helped me communicate the project's outcomes effectively. Furthermore, Excel's built-in calculation functions allowed me to perform complex calculations and derive meaningful metrics from the merged data.

To present the project's accomplishments in a professional and engaging manner, I turned to Microsoft PowerPoint. PowerPoint provided a user-friendly interface to create visually compelling slides. I incorporated the charts and graphs created in Excel into PowerPoint slides, combining data visualization with explanatory text to communicate the project's key takeaways concisely.

# About the data set 
The dataset you described contains several columns: "district" which represents the district in Telangana, "date" for the specific date, "month" for the month of the recorded data, "year" indicating the year of the recorded data, and "no of visitors" representing the number of visitors in that particular district on the given date.

The "district" column provides information about the specific regions within Telangana that were included in the dataset. This column allows for the analysis of tourism patterns and trends across different districts within the state.

The "date" column indicates the specific date on which the data was recorded. This information is useful for tracking daily variations in visitor numbers and analyzing the impact of specific events or holidays on tourism in Telangana.

The "month" column provides the month in which the data was recorded. This allows for the aggregation and analysis of visitor numbers on a monthly basis, enabling the identification of seasonal patterns and trends in tourism activity.

The "year" column represents the year in which the data was recorded. It allows for the analysis of long-term trends and changes in visitor numbers over the years, providing insights into the overall growth or decline of tourism in Telangana.

The "no of visitors" column holds the recorded number of visitors for a given district, date, month, and year combination. This numerical data is crucial for analyzing visitor patterns, identifying popular tourist destinations within Telangana, and evaluating the overall tourism growth or decline in specific districts over time.

# link of project challenge : https://codebasics.io/challenge/codebasics-resume-project-challenge
# link of video prejentation : 





