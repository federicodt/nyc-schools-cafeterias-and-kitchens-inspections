# **NYC school cafeterias & kitchens continue to fail inspections.**
  
## **Project objectives.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The initial objective of the project was to find out why most of the inspections of school cafeterias and kitchens in New York City were being done at Jewish educational institutions. Also, to see what other stories I could find by analyzing the data.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For this purpose, the following databases were analyzed: 
1. [DOHMH School Cafeteria inspections](https://data.cityofnewyork.us/Health/DOHMH-School-Cafeteria-inspections/9hxz-c2kj), Department of Health and Mental Hygiene of NYC.

2. [DOHMH School Cafeteria inspections (2020 - Present)](https://data.cityofnewyork.us/widgets/5ery-qagt?mobile_redirect=true), Department of Health and Mental Hygiene of NYC.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The dataset contains current inspection data for cafeterias permitted in public, private, and parochial schools in NYC. All school cafeterias are required to be in compliance with NYS and NYC Food Safety Regulations, found in New York City Health Code Article 81. School cafeteria inspections are conducted at least annually to ensure compliance with food safety regulations. This dataset includes information obtained as part of the permitting process and data collected during inspections. This data includes inspection results for active school cafeterias for the last three years. Data for cafeterias that have ceased operations and any violations cited during the inspection that were dismissed during adjudication are excluded from this dataset.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As a complement, I carried out traditional journalistic work of news archive, to know what was published on the subject.

## **Project findings.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With respect to the initial objective I found that more inspections were conducted at Jewish schools because they did not comply with New York State and New York City food safety standards as set forth in Article 81 of the New York City Sanitary Code. It was for this precise reason that they had more inspections than others that did comply. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;However, I decided to analyze the data to see if I could find any more interesting stories to tell. In the process, I realized that most of the public schools failed inspections and the reasons repeated.

## **Project data collection.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As I mentioned earlier, the project was based on public databases.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[DOHMH School Cafeteria inspections](https://data.cityofnewyork.us/Health/DOHMH-School-Cafeteria-inspections/9hxz-c2kj) and [DOHMH School Cafeteria inspections (2020 - Present)](https://data.cityofnewyork.us/widgets/5ery-qagt?mobile_redirect=true), both by the Department of Health and Mental Hygiene of NYC and available at NYC Open Data website.

## **Project data analysis process & notebooks.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I used notebooks to organize, clean, select, analyze and graph information in order to extract what I needed for my project.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I then used the notebooks to browse and analyze the available data. Also, to cross-reference and/or generate new DataFrames.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Then I graph some of the findings in Matplotlib, Altair or Seaborn. I also made some in DataWrapper. 

## **Learnings and obstacles during the project.**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The first challenge was all the work I had to do to clean up, complete and fix errors in the database. As I explained in the article, in the section “About the data”, the information about inspections of NYC school cafeterias and kitchens has several problems. First, there is more than one database. One has records from December 18, 2016 through December 12, 2019, although the website states that the data was last updated on August 23, 2021. This dataset has 24.6K rows and 22 columns. The other, contains inspections from October 27, 2020, to March 23, 2023. The records have almost 11.1K rows and 25 columns. I do not understand why it was not all kept in the same database. In both cases, the data are available on the NYC Open Data website. The website does not provide more information. For this article I decided to work, mainly, with the most recent information: from 2020 onwards.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;These problems, and others explained in the article, made the cleanup work very extensive. The vast majority of the time of this project was spent fixing errors and cleaning data. For example, I had to manually correct some school names. Moreover, more than 150 schools were missing latitude and longitude data. Therefore, I had to find out if there was any way other than manually. I ended up using Nominatim and was able to complete two-thirds of the missing data. The others had problems in the address, zip code or other data that did not allow me to get the correct data.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Another problem that arose was when I wanted to put all the schools together in a map. The database was so large and heavy that none of the tools I tried allowed me to do it. In addition, I tried to build a map only with the schools that had violations, critical violations, another one with the public schools, by neighborhood; among others. In all cases I had the same result, too much information and a very heavy file that caused the tool to close. Even I found a solution, I did not do it in time.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this project I decided that I was going to use other ways of graphing and/or displaying the information. In one I made a table in D3 inside a Scrollama, which turns into a bar chart as you scroll down. The classification, assembly and modifications was a long and difficult process, because I don't know Javascript and/or D3. Practically everything I wanted to do I had to look up. Clearly, this involved a lot of time. For another part of the article I decided to modify a Scrollama to change the images and text, as I had done in the previous project, but I was not satisfied with the result. This time I think it was better and I used photographs that I supported with data that I obtained from the analysis of the information.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I think the most difficult thing was the number of errors, obstacles and problems that arose throughout the project, such as the lack of coordinates in some schools, to mentioned an example. Until this project I hadn't had to do and invest so much time and effort in data cleaning. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If I had more time, more skills and more confidence in them, I would have used Mapbox and Ilustrator for the maps. Also, I would have made a better and Deep data análisis, article, graphics and web page.

## **Proyect link.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NYC school cafeterias & kitchens continue to fail inspections.](https://federicodt.github.io/nyc-schools-cafeterias-and-kitchens-inspections/)
