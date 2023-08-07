# **NYC school cafeterias & kitchens continue to fail inspections.**
  
## **Project objectives.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The initial objective of the project was to find out why most of the inspections of school cafeterias and kitchens in New York City were being done at Jewish educational institutions. Also, to see what other stories I could find by analyzing the data.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For this purpose, the following databases were analyzed: 
1. [DOHMH School Cafeteria inspections](https://data.cityofnewyork.us/Health/DOHMH-School-Cafeteria-inspections/9hxz-c2kj), Department of Health and Mental Hygiene of NYC.

2. [DOHMH School Cafeteria inspections (2020 - Present)](https://data.cityofnewyork.us/widgets/5ery-qagt?mobile_redirect=true), Department of Health and Mental Hygiene of NYC.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The dataset contains current inspection data for cafeterias permitted in public, private, and parochial schools in NYC. All school cafeterias are required to be in compliance with NYS and NYC Food Safety Regulations, found in New York City Health Code Article 81. School cafeteria inspections are conducted at least annually to ensure compliance with food safety regulations. This dataset includes information obtained as part of the permitting process and data collected during inspections. This data includes inspection results for active school cafeterias for the last three years. Data for cafeterias that have ceased operations and any violations cited during the inspection that were dismissed during adjudication are excluded from this dataset.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As a complement, I carried out traditional journalistic work of news archive, to know what was published on the subject.

## **Project findings.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We find that mass shootings are increasing year after year since 2015, with the exception of 2020, due to the measures of closure by the Pandemic of the Coronavirus. Also, there is a correlation between the increase in incidents involving firearms and the increase in mass shootings.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Also, 2022 was a record year of deaths of children under 17 years of age by firearms. This year saw the highest number of deaths and injuries from firearms since the organization began recording them in 2014. Besides, it was also a record for deaths of children under the age of 17.

## **Project data collection.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As I mentioned earlier, the project was based on The Violence Project database.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Their records are not public, but anyone can request them. In my case, I sent an email asking for access. As I was not answered soon, I thought of scrapping the information. While I was coding they answered and granted me access to their records.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;All data and records of The Gun Violence Archive [GVA] are publicly available on their [website](https://www.gunviolencearchive.org/charts-and-maps).

## **Project data analysis process & notebooks.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I used notebooks to organize, clean, select, analyze and graph information (mass shootings by state, by years, etc.) in order to extract what I needed for my project.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I then used the notebooks to browse and analyze the available data. Also, to cross-reference and/or generate new DataFrames.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Then I drew the findings in Matplotlib, Altair or Seaborn. For the maps, I had to prepare DataFrames and made them with Datawrapper. 

## **Learnings and obstacles during the project.**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The first challenge was all the work I had to do to find new information in a database as used as mass shootings. I did a lot of cross-referencing and analysis until I found a story to tell. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For this project I chose a basic html template and modified it for use with Scrollama. It was a challenge to create the classes, in the style.css, encode in html and, above all, implement the Scrollama. The latter was not sensible and I had many difficulties because I wanted the images to change as well.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On the other hand, I had never made maps, not even in Datawrapper. This was a challenge I wanted to overcome in this project. In addition, I learned how to use "tooltips" and added additional information to the map and graphics. Another difficulty was that to graph the information on the map, it had to be very clean and accurate. That took me a while, because I’ve never done it before. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The graphics of the Scrollama didn’t look good as well as I wanted. I would have liked to know Ilustrator and have it so that they looked better. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I wanted to do a pretty deep analysis of the information, but time did not allow it. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I think the most difficult thing was the number of errors, obstacles and problems that arose throughout the project. But they also helped me to learn.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If I had more time, more skills and more confidence in them, I would have used API or scrapping techniques. Also, I would have made better graphics and a better web page.

## **Proyect link.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[US Mass shootings](https://federicodt.github.io/us-mass-shootings/)
