

# COVID-19 World Vaccine Adverse Reactions-visualization project

## by Maha Koutb


## Dataset


Dataset by The Vaccine Adverse Event Reporting System (VAERS) . Downloaded from kaggle.com ,

https://www.kaggle.com/ayushggarg/covid19-vaccine-adverse-reactions?select=2021VAERSSYMPTOMS.csv

VAERS was created by the Food and Drug Administration (FDA) and Centers for Disease Control and Prevention (CDC) to receive reports about adverse events that may be associated with vaccines 

Data is mixed between categorical & numeric variables with original size after merge 34630 rows & 42 columns , after discovering and cleaning size become 22971 rows & 12 cloumns only

the data set is about statistcs regarding vaccine receipts , in my investigation i focused  on DIED statiscs and tried to find correlatios between variables to answer the following questions :

1-does age has affect on DIED records ? 
2-does sex has affect on DIED records ? 
3-does type of vaccine has affect on DIED records ?

i focused on the following variables :

STATE

CAGE_YR

SEX

DIED

L_THREAT

ER_VISIT

HOSPDAYS

VAX_MANUE

I have worked with two CSV'S file that needed to be merged first , then i have started to check missing and duplicated data and cleaned them to avoid any unwanted affect of them on my results ,,


## Summary of Findings


## Univariate :


STATES : 26.6% of vaccine receipt @#CA & TX & NY & FL
CAGE_YR : The largest amount of vaccine receipt are between 36 to 40 & 50years old
SEX : 75.1% female & 24.4 % male
DIED : 6.4% of vaccinated people are DIED
ER_VISIT : 0.04 % need emergency room after Vaccinatd
L_THREAT : 4.6% Faced a threat after vaccinated
HOSPDAYS : 10.6% of vaccinated people need to spend somedays at hospital-- most of patients spent 0 to 5 Days
VAX MANU : Moderna has the most frequent values

## Bivariate :

###   visuals & statistcs said that the following variables seems  to have a significant impact on the died records.

* CAGE_YR // 
As shown there is a strong relation between Age & Die ,, most Died people exceed 70 years old
* SEX // 
Despite the aproximately similarity of no who  died in each gender , the % of male who died are bigger than female 3% DIED in female & 14 % in male
* VAX MANU // 
The highist % of died recorded in PFIZER

### following variables seems to have no a significant impact on the died records.

* HOSPDAYS
* LH_THREAR
* ER_VISIT

## Multivariate :

*  moderna & pfizer seems to have the same manner regarding age and DIED records

* Janssen shown some unsual points due to having higher recoreds for young people who died in 30's




## Key Insights for Presentation

* Over all the total visuals & statiscs shown that low % of DIED people after vaccinated approximately 6.4 %
* Most of died people exceed 70 years old 
* Females has the 75 % of total data records 
* %Males who died after vaccinated is higher than females 14% males vs 3% females
* Moderna and Pfizer seems to have the same manners 

## Recommendations 
* to find more insights regarding people who died we need to work with greater samples for males who exceed 60 yrs old 
* we need to work on greater samples for people who janssen vaccinated in age between 18 to 40

