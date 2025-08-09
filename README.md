# Netflix_data_analysis

 Overview
                                                                       
This project focuses on data cleaning, exploration, and visualization of a movie dataset containing information such as release date, genres, popularity, votes, and more.
The goal is to extract meaningful insights and answer specific analytical questions using Python, Pandas, Matplotlib, and Seaborn.





📂 Dataset
Rows: 9,827 (expanded to 25,552 after exploding multiple genres)

Columns: 9 (reduced to 6 after cleaning)

Key Features:

Release_Date (converted to year)

Title

Popularity

Vote_Count

Vote_Average (categorized)

Genre (split into individual rows)






🛠️ Steps Performed
1️⃣ Data Loading & Exploration
Checked dataset shape, data types, null values, and duplicates (none found).

Examined basic statistics.

2️⃣ Data Cleaning
Converted Release_Date to year.

Dropped unnecessary columns: Overview, Original_Language, Poster_Url.

Categorized Vote_Average into:

not_popular

below_avg

average

popular

Split Genre column into multiple rows using .explode().

3️⃣ Data Visualization
Created count plots for genres and vote categories.

Visualized distribution of movie release years.






❓ Key Questions & Insights
Question	Answer
Most frequent genre?	Drama (~14% of all entries)
Genre with highest votes?	Drama again leads (>18.5% of popular movies)
Highest popularity movie & genres?	Spider-Man: No Way Home (Action, Adventure, Sci-Fi)
Lowest popularity movie & genres?	The United States vs. Billie Holiday (Music, Drama, History) & Threads (War, Drama, Sci-Fi)
Year with most movies?	2020







📊 Tools & Libraries Used
Python

Pandas

NumPy

Matplotlib

Seaborn

