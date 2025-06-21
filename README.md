# Excel-Basic-youtube-analytics
## Youtube Trends report :

My first data analytics project I came up with to test my Excel and Analytical skills
- **Main objective:**
  
    **1.** To know what type(or catagory) of videos are mostly found trending on Youtube.
  
- **Project objective:** 

    **1.** Extract [data](https://github.com/Deborshi-analyst/Excel-Basic-youtube-analytics/blob/main/raw%20data.pdf) regarding trending videos on Youtube.
  
    **2.** Load the data in to excel [sheet](https://github.com/Deborshi-analyst/Excel-Basic-youtube-analytics/blob/main/trending%20Youtube%20Videos.xlsx) with proper table format.
  
    **3.** Create a [report](https://github.com/Deborshi-analyst/Excel-Basic-youtube-analytics/blob/main/Trending%20videos%20report.pdf) to understand what kind of videos are trending now days on Youtube of different catagories and how each catagories are doing in compaired to each other.

- **Steps:**
  
    **1.** To perform analysis and generate reports, the first thing that is required is data on the specific subject of analysis. To get data I did web scrapping by going to Youtube and searching for trending videos, then generated a PDF file of the search result from browser.
  
    **2.** Opened Google Gemini and provided [prompt](https://github.com/Deborshi-analyst/Excel-Basic-youtube-analytics/blob/main/AI%20in%20youtube%20analytics%20project.png) along with the screenshots from the trending video list PDF, to generate the data in a specific structure and format.

    **3.** After providing the prompt to Gemini, I got a Google spreadsheet generated that contained the necessary data in tabular format and I downloaded the spreadsheet in '.xlsx' format to clean and transform the data in Excel.

    **4.** Opened the excel file and started cleaning the data from built in Power query tool as it is much quicker and efficient than excel. As it is my first project initially I found it a bit hectic to clean the data. Majorly I had to clean the 'Catagory' and the 'Views' column. I used split the coulmn option to remove unnecessary data from the column.

    **5.** Transformed the data by adding custom column as new column that contained all the view values in common unit (thousands unit).

    **6.** Created a reference of that query and loaded that query as just connection and added it to data model.

    **7.** At last Created report using pivot table from the data model.

  
## Technical Skills:
- [x]	Proficiency in ETL methodology (Extract, Transform, Load).
- [x]	Using AI to fetch required data to work on from webpage to excel sheet.
- [x]	Skills to clean data using Power Query.
- [x]	Establishing data model to generate report using Pivot table.
- [x]	Proficiency in incorporating supplementary data into an existing data model.

## Soft Skills:
- [x]	Designing user-centric reports with empathy in mind.
- [x]	Optimization of report generation through meticulous fine-tuning.
- [x]	Developing a systematic approach to devising a report building plan.
