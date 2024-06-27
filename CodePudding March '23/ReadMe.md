# File Title: HNA TT CP '24.twbx

This was a Code Jam Competition project that took place in March '24 after completing the TripleTen Business Intelligence Analytics Program. The purpose was to create a visually compelling story from a provided dataset in 4 days with Tableau and collaboration with assigned team members. Our team name was Horizon Nexus Alliance. 

Team Horizon Nexus Alliance's recorded presentation can be found <a href='https://www.youtube.com/watch?v=rWTYgq_3ER4' target=_blank><u>here</u>.</a>
Tableau Public link <a href='https://public.tableau.com/views/HNATTCP24/Home?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link' target=_blank><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Animated_Movies.twbx](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Animation%20Movies/Animated_Movies.twbx) | The Tableau Workbook file with all interactive Visualizations, Dashboards, and Story. |
| 2 | [Animation_Movies.csv](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Animation%20Movies/Animation_Movies.csv) | Original spreadsheet file in csv format provided at the start of the competition. |
| 3 | [March_Code_Pudding_Data_Cleaning_..ipynb](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Animation%20Movies/March_Code_Pudding_Data_Cleaning_.ipynb) | Jupiter Notebook file using Python for Data cleaning and EDA performed at the start of the analysis. |
| 4 | README.md | This current page, with all relevant information about the project, just past the Table of contents. |
| 5 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Animation%20Movies/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen and The Pudding. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |
| Results | List of accomplishments and skills practiced in this project. |

### Data
The data was one .csv file provided by TripleTen
- `'Animation_Movies.csv'`: Original data. 1 Table with 23 Fields. Fields kept after data cleaning:
    - `'id'`: Unique Identifier
    - `'title'`: Movie Title
    - `'vote_average'`: Average voter score
    - `'vote_count'`: Total number of votes
    - `'status'`: Boolean stat- released for viewing or still in production
    - `'release_date'`: The date the movie was released to the public
    - `'revenue'`: Money earned after release
    - `'runtime'`: Length of movie in time
    - `'adult'`: Boolean stat to tag if it was made for adults
    - `'budget'`: Money reserved for the creation of the movie
    - `'original_language'`: Primary language spoken upon first release
    - `'popularity'`: Numerical value comparing demand for a movie compared to other movies
    - `'genres'`: List of all genre tags for each movie
    - `'production_companies'`: List of all production companies involved in each movie
    - `'production_countries'`: Country of origin

### Description:
- 1 Tableau Story made from 6 Dashboards and 14 visuals
- Includes parameters, calculations, sets, and a final presentation of the Tableau Story.

### Assumptions:
- The main genre was the 1st one listed, analysis was based on the main genre.
- Missing values or inconsistencies in the data are minimal and can be ignored.
- The provided data was clean when provided to us.

### Process:
First, We held a Google Meet to organize our team details and technical details on how to best seemlessly share the work between time zones and workstations.
Then, team member Michelle explored, filtered, and cleaned the data through Jupyter Notebook via Python.
Next, we took turns passing the Tableau Workbook between members via Discord Chat based on availability. Keeping in constant connection and collaboration about our live edits through the same chat.
Simultaneously, preparing the presentation requirements, outline, and details in the same collaborative method via Discord and .txt file.
Lastly, We recorded our assigned portions of the presentation and used video manipulation to make it one seamless video presentation.

### Findings:
- The United States produces the most animated movies, but production is happening far and wide across the globe.
- The most produced genre was Comedy until the 1970s when Family films took over. Except for a brief period at the beginning of the pandemic when Documentaries were Top.
- English the primary language of animated movies.
- Original Language had a positive correlation with film runtime.
- Animated movies have been steadily getting longer over time until the 2008 recession, and have steadily declined since.
- Pixar, when in conjunction with Disney had the highest revenue at 7.9 Billion.
- Frozen 2 made the highest revenue at 1.45 Billion.
- There is a direct correlation between budget size and revenue.
- Sequels bring more money in than their original titles.
- ONF | NFB has the most produced films yet does not reach near the top in revenue.
- Sleeping Beauty had the highest average vote scores.
- Elemental had the highest Popularity scores

### Results:
Collaborative Brainstorming: I effectively worked with a team to identify interesting stories within the provided datasets.
Data-Driven Storytelling: I focused on insights supported by data, ensuring clear and ethical use of information.
Visual Storytelling: I created unique data visualizations that complemented the narrative and communicated key points effectively.
Presentation Skills: I participated in crafting a clear and concise presentation that showcased our project's findings within a limited timeframe.

This project highlights my strengths in:
Data Analysis & Exploration (understanding and manipulating data)
Data Visualization (creating clear and informative visuals)
Communication & Teamwork (conveying insights and collaborating effectively)
