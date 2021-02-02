<img src="https://www.kokopeliadventure.com/wp-content/uploads/2016/02/IMG_6853-570x570.jpg" alt="Barcelona" width="300"/>

# Population Analysis of Barcelona AC/BC (After Colau/Before Colau)
Raul Castrillo & Pol Serramalera

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description
Our project seeks to analyze the impact of the latest government change (Ada Colau's) by comparing the data of the 2 years prior to the goverment change and the 2 years after.

## Questions & Hypotheses
Our hypoteses is that the inmigration and aging index increased after colau's government, the average birth rate dropped and also we think that the family income distribution has balanced between the poorest and the wealthiest districts.
·Did the inmigration increase After Colau's government compared to the period Before?
·Has the aging index increased After Colau's government compared to the period Before ?
·Did the average birth drop After Colau's government compared to the period Before?
·Have the districts become more balanced in terms of family income After colau compared to the period Before?


## Dataset

From https://www.bcn.cat/estadistica/ :

·births (2013-2017)
·deaths (2013-2017)
·immigrants-by-nationality (2013-2017)
·immigrants-emigrants-by-age (2013-2017)
·immigrants-emigrants-by-destination (2013-2017)
·immigrants-emigrants-by-sex (2013-2017)
·Population of Barcelona (2013-2017)
·Disposable family income (2013-2017)


## Database
We created new tables from the gathered datasets to calculate rates for each district and each year, then we created a final table with 1 row for each district with all the gathered rates Before Colau and After Colau .


## Workflow

1. First we have cleaned the official datasets with the information that mattered to us and took years 2013-2017 as a sample.
2. Creating  sub data frames to study the data  by year and district  out of the main database.
3. Adding new columns with statistics and operations  to the new data frames.
4. Merging immigration and population demography dataframes to a final database.


## Organization

To organize our work we created a kanbas board in trello.com, and we divided the tasks between us 2.

Our repository has 2 initial folders, one for the datasets and another for the python3 coding files.

## Links

[Repository](https://github.com/raulcastr/Population-Analysis-Barcelona-AC-BC)  
[Slides](https://drive.google.com/file/d/15wsNCGVDvU_JuHEGrE5kXIGvx2cGbOyG/view?usp=sharing)  
[Trello](https://trello.com/b/cugCk511/project2-2-year-balance-on-a-new-government)  
