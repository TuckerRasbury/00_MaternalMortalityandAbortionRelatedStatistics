# Culture Wars Over Abortion Access Lead to Death and other Spinechilling Statistics - An Ongoing Project

## Abstract
In light of Roe v. Wade  being overturned in June of 2022 by the Supreme Court [[citation]](https://www.npr.org/2022/06/24/1102305878/supreme-court-abortion-roe-v-wade-decision-overturn), I decided to channel my frustrations and technical skills towards exploring the data landscape of abortion access.

Herein, I conduct research and compile datasets with information on the state of abortion access, maternal mortality, and related information to better inform myself. Subsequently, I analyze that information with Python in a google collab data analytics environment, and take it a step further by networking with subject matter experts and journalists via LinkedIn. 

While a passion project, this speaks to my professional interests and personal values. Abortion is healthcare and by doing this project I hope to better inform myself on the data landscape on the subject while also practicing my coding skills thus bridging the gap between armchair academic and useful applicable knowledge.

## Executive Summary - In Progress
As of 11/9/22, my research has yielded a handful of leads on useful data and has led to networking with real journalists.

## Tools Used
- Python via Google Collab
- Research obtained via publicly available resources
- Github
- Datasets in .csv and .xlsx format

## Research Questions
01. What does available research say about the effect of changes in abortion access? Why does any of this matter
02. What public data can be collected datasets and what feedback can be obtained via networking.
03. Mining available data to surface insights.


### 01. What does the research say about abortion access and if it does or does not matter?
The University of Colorado Boulder in no uncertain terms states that "banning abortion nationwide would lead to a 21% increase in the number of pregnancy-related deaths overall and a 33% increase among Black women" [[citation]](https://www.colorado.edu/today/2021/09/08/study-banning-abortion-would-boost-maternal-mortality-double-digits). Furthermore, they state that these deaths would be due to complications of being pregnant and delivering a baby. Deaths due to unsafe abortions or attempted abortions would be in **addition** to those estimates.

Moreover, the US Republican party is advocating for a nationwide and federal abortion ban [[citation]](https://www.politico.com/newsletters/politico-pulse/2022/09/14/the-federal-abortion-ban-bill-is-here-and-it-has-some-republicans-stunned-00056510). This is not a hypothetical. It is a part of the party's platform. 

Given the above, the GOP is advocating for a ban that will drive a spike in deaths throughout the country and that burden will be heaviest on black women.

Excluding poltical realities, here are the medical and individual level factors that increase a person's risk for maternal morbidity and mortality [according to the Eunice Kennedy Shriver National Institute for Child Health and Human Development:](https://www.nichd.nih.gov/health/topics/maternal-morbidity-mortality/conditioninfo/factors).

> - Existing or pre-pregnancy health conditions, such as cardiovascular disease, obesity, asthma, or a compromised immune system
> - Older maternal age
> - Lifestyle factors, such as being a current or former cigarette smoker
> - Having twins, triplets, or other multiples
> - Certain pregnancy complications:
>    - Preeclampsia, a spike in blood pressure after the 20th week of pregnancy, increases a woman’s risk for high blood pressure, blot clots, and stroke later in life.2
>    - Women who have gestational diabetes, high blood sugar during pregnancy, are at higher lifetime risk for diabetes (usually type 2) and for fatty liver disease.3,4
> - Certain features of giving birth:
>    - An NICHD-funded study found that first-time moms who delivered vaginally were at higher risk for pelvic floor disorders.
>    - Although vaginal birth after cesarean (VBAC) is safe for some women, women who had certain types of incisions are at higher risk for rupture of the uterus, a rare but serious problem, during VBAC. A rupture can lead to infection, bleeding, and other problems.5
> - Racial, ethnic, and socioeconomic backgrounds. Research shows disparities in the rates of maternal deaths in the United States, with black women and American Indian/Alaska Native women at highest risk for pregnancy-related death.

### 02. Collected Data and Feedback

#### Data
- Data: [National Vital Statistics System. CDC - Maternal deaths and mortality rates 2018-2020 [rates per 100k live births]](https://github.com/TuckerRasbury/00_MaternalMortalityandAbortionRelatedStatistics/blob/e83ebfd619306c5c9981265e4f624780afb0bb35/data/VitalStatistics_raw_data.xlsx) || [source](https://www.cdc.gov/nchs/maternal-mortality/MMR-2018-2020-State-Data.pdf)
- Data: [Guttmacher Data](https://github.com/TuckerRasbury/00_MaternalMortalityandAbortionRelatedStatistics/blob/06c11624c04bb8cf571ba2132403441b89db3476/data/GuttmacherDataCenter-2.xlsx) || [source](https://data.guttmacher.org/regions)
- Data: [NationalandStatePregnancy_PublicUse](https://github.com/TuckerRasbury/00_MaternalMortalityandAbortionRelatedStatistics/blob/99ef86899667d7ea2d63c0d56ba556fa039ce1be/data/NationalAndStatePregnancy_PublicUse.csv) || [source]()

#### DataViz
- [After Roe Fell: Abortion Laws by State || Center for Reproductive Rights](https://reproductiverights.org/maps/abortion-laws-by-state/)
- [Interactive Map: US Abortion Policies and Access After Roe || Guttmacher Institute](https://states.guttmacher.org/policies/)

#### Networking Contacts
- [Alvin Chang, US Head of Visuals and Data @ The Guardian](https://www.theguardian.com/profile/alvin-chang)

### 03. Insights Gained from Investigating Data
- **What is the state of abortion access by state?**

_Planning to leverage Dataviz from Research Questions | Prt 2 | DataViz_

- **Which states have the highest rates of maternal mortality? (Bottom 10)**

_Planning to use Maternal Deaths and Mortality Rates from NCHS dataset_

- **Which states have the lowest number of abortion providers? (Bottom 10)**

_Planning to use Guttmacher dataset._

## Appendix

***Institutions***
* [Centers for Disease Control and Prevention's National Center for Health Statistics (NCHS)](https://www.cdc.gov/nchs/maternal-mortality/data.htm)

***Data Sources***
* [National Center for Health Statistics. Compressed Mortality File, 1999-2016 (machine readable data file and documentation, CD‑ROM Series 20, No. 2V) as compiled from data provided by the 57 vital statistics jurisdictions through the Vital Statistics Cooperative Program.  Hyattsville, Maryland. 2017.](https://www.cdc.gov/nchs/data_access/cmf.htm)

* [Maternal deaths and mortality rates: Each state, the District of Columbia, United States, 2018‐2020](https://www.cdc.gov/nchs/maternal-mortality/MMR-2018-2020-State-Data.pdf)

* [Centers for Disease Control and Prevention's Reproductive Health Data and Statistics](https://www.cdc.gov/reproductivehealth/data_stats/index.htm)


***Articles/Academic Papers***
* [University of Colorado Boulder - Study: Banning abortion would boost maternal mortality by double digits](https://www.colorado.edu/today/2021/09/08/study-banning-abortion-would-boost-maternal-mortality-double-digits)

* [National Institute of Health's Office of Research on Women's Health - What Are Maternal Morbidity and Mortality?](https://orwh.od.nih.gov/mmm-portal/what-mmm)

* [Nelson, D.B., Moniz, M.H. & Davis, M.M. Population-level factors associated with maternal mortality in the United States, 1997–2012. BMC Public Health 18, 1007 (2018)](https://bmcpublichealth.biomedcentral.com/articles/10.1186/s12889-018-5935-2)

* [The Pew Charitable Trusts | Critics Fear Abortion Bans Could Jeopardize Health of Pregnant Women by Michael Ollove](https://www.pewtrusts.org/en/research-and-analysis/blogs/stateline/2022/06/22/critics-fear-abortion-bans-could-jeopardize-health-of-pregnant-women)

* [National Institutes of Health | Eunice Kennedy Shriver National Institute of Child Health and Human Development | What factors increase the risk of maternal morbidity and mortality?](https://www.nichd.nih.gov/health/topics/maternal-morbidity-mortality/conditioninfo/factors#)

* [The Guardian | Tracking Where Abortion Laws Stand in Every US State](https://www.theguardian.com/us-news/ng-interactive/2022/jun/28/tracking-where-abortion-laws-stand-in-every-state)
