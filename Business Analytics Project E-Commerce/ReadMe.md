# File Title: Copy of Copy of Business Analytics Project v1.xlsx

The third project that I worked on in the TripleTen Business Intelligence Analytics Program. The purpose was to analyze the companies' raw transaction logs and turn the event logs into business metrics.

Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/10PqOonkWAtGhEy_ziaRHj7QoUS7eeK3G_PTsVhaDjxg/edit?usp=sharing' target=_blank><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Business Analytics Project.csv](https://docs.google.com/spreadsheets/d/1yuavBZ4OYYUD1opH-dq0d6nejREDy8f0ozumT9-yEuo/edit#gid=0) | The original data file provided by TripleTen that was used in the analysis of this project. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/LeeRIII/Data_projects_TripleTen/blob/main/Business%20Analytics%20Project%20E-Commerce/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 4 | [ReviewerGrade3.png](https://drive.google.com/file/d/1apyEbT7Gtkg_ZBJAB5fg-QOmNYthKh3O/view?usp=sharing) | This is the comments left by my project reviewer. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |

### Data
The data was one Google spreadsheet file provided by TripleTen
- `'Business Analyst Project.csv'`: raw transaction logs
    - `'raw_user_activity'`: Each row represents an activity, or event, by a user on the company’s website
        - `'user_id'`: unique customer IDs
        - `'event_type'`: the type of activity by the user
        - `'category_code'`: category of the product being viewed or purchased
        - `'brand'`: the company that makes the product
        - `'price'`: price of the product, in USD
        - `'event_date'`: date of the user activity, in YYYY-MM-DD format
    - `'Table of Contents'`: Preformated yet empty table of contents sheet
    - `'Executive Summary`: Preformated yet empty executive summary sheet

### Description:
- 10 page spreadsheet
- Includes raw data (Hidden), processed data, data analysis, and pivot tables.

### Assumptions:
- The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe.
- Missing values or inconsistencies in the data are minimal and can be ignored.
- The provided data format (columns, data types) is correct and consistent.

### Process:
Explored, filtered, and cleaned the data.
Created and built a conversion funnel.
Prepared data for cohort analysis.
Calculated retention rates.
Finalized formatting and documentation for the client's readability, including auto change log and manual change log.

### Findings:
| Results | Synopsis |
| :-----------: | ----------- |
| Conversion Funnel | 10.34% of customers make purchases | 
| Retention Rates | Only 3.43% of customers return through the first month on average | 
