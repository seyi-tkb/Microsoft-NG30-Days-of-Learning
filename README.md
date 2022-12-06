# Microsoft-NG30-Days-of-Learning
Projects on the data analysis track.
----
# 1 - Financial Sample
* Problem Statement:
To recreate the first days work by replication. The dataset was a sales record of products(across various segments) sold by a manufacturing company. 

* Data Sourcing:
The sample data used for the project was downloaded from a link provided by the programme coordinators and accessed with Microsoft Excel.

* Data Transformation:
The dataset had already been cleaned and transformed as it was a sample dataset for practice from Microsoft. It contained fields such as product segment, country, units sold, sales, profit among others.

* Analysis:
The analyze data option was used to automatically generate a series of pivot tables and charts for analysis and some important set were chosen to create the dashboard. Slicers were also added to enable easy access and maneuverability around the dataset.

* Insights:
Even though government and small business segements had high sale prices, government noticeable still had higher units sold.
The products VTT and Amarilla were the most expensive to produce.
Discounts for high and medium type products were very high and majority of all discounts were given in 2014.

----
# 2-3 - Covid-19 Global Cases
Introduction:
Covid-19 is an infectious disease caused by the SARS-CoV-2 virus. The virus can be spread through exposure to small particles(respiratory droplets or smaller aerosols) from infected people or sources. Most people who fall sick experience mild to moderate symptoms and recover without special treatment. Although, some become seriously ill and recover without special treatment.
The first known infection was in Wuhan, China on 31, Dec 2019.

* Problem Statement:
To generate insight into Covid-19 numbers all around the world.

* Data Sourcing and Preparation:
The dataset which is updated daily was scrapped from the Github data repository by the Center for Systems Science and Engineering at John Hopkins University. Itc came in 3 different files of the .csv format. The raw format for the confirmed global cases was viewed with its link copied and pasted into Excel using the insert from web function. The same steps were also followed for the files containing the death records and recovered cases with all then loaded unto the power query.

* Data Cleaning and Transformation:
On loading the confirmed cases to the power query, the source code was was first corrected as there were 879 columns(mostly dates) due to daily updates.
The first row was promoted to headers. Necessary columns were chosen with others unpivoted and combined  to make up the date and confirmed fields. Same steps were repeated for death and recovered cases files after which all files were merged. The necessary fileds were formatted to the types they were meant to be, numbers, dates and texts, with the consolidated data then loaded unto an Excel worksheet. New fields of year, month and day were then added.

* Exploration and Analysis:
The newly loaded dataset which reported cases of Covid-19 and had 11 columns of 251655 rows contained information about the province, country/region, latitude and longitude, number of confirmed cases, confirmed deaths where recorded and recovered cases based on estimates of local and state media reports. Active cases and fatality rate was also calculated.
Pivot tables and charts were created to draw out insights from the various fields with slicers also added to easily access specific information.

* Insights:
North korea reported the lowest recorded cases(just 40) with no deaths from Covid(good numbers especially when comparing them to rest of the countries in the world).
This was actualized by stringent methods put in place by its government such as declaring national emergency, boder closure and stay-at-home orders. It was also one of the first countries to implement all these. Although, this later affected their economy leading to food shortages and blocked channels to basic amenities.
India had the highest reported confimed recoveries in the world.
The U.S. had the most deaths and confirmed cases from Covid-19 in the world.
Brazil was also really affected being the country with the 2nd most deaths and 3rd most confirmed cases. Also, the data showed most confirmed cases were reported in May across all 3 years of recording.

* Note that these numbers and visualization only accounts for reported cases as some were unreported and numbers could be substantially larger than this. 

----
