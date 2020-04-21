# Impact_of_COVID19_on_Counties
Using Python coding, I analyzed how COVID 19 can affect different counties and further analyzed how certain ages and other categories such as sex ratio is affected by COVID 19

## Background
This year, the pandemic, COVID 19, recently spread across the United States causing severe injuries and deaths. Thus, we can ask which US counties are most vulnerable based on population demographics and hospital bed availability?

## Data 

With [Johns Hopkins University Center for Systems Science and Engineering](https://github.com/CSSEGISandData/COVID-19),[US Census](https://www.census.gov/geographies/reference-files/2018/demo/popest/2018-fips.html), [New York Times](https://github.com/nytimes/covid-19-data), [American Community Service](https://data.census.gov/cedsci/table?q=United%20States&g=0100000US&tid=ACSDP1Y2018.DP05),and [Homeland Infrastructure Foundation-Level](https://hifld-geoplatform.opendata.arcgis.com/datasets/hospitals)data, I could see how different counties are affected by the COVID 19 and possibly come up with some implications that these counties can follow to minimize the injuries, cases, and deaths.

## Heat Map
![alt](https://github.com/ywonjun1021/Impact_of_COVID19_-on_-Counties/blob/master/COVID%2019%20Heat%20Map.png)
Looking at the heat map, the correlation of the number of hospital beds per 1,000 people and number of COVID 19 cases per 1,000 is 0.04. Also, the correlation of the number of hospital beds per 1,000 and the number of deaths is 0.05. In fact, with these low correlation, I can conclude that county's danger of COVID 19 is not related to the number of hospital beds.

Now,for demographics, we can see from the heat map that there are more cases of COVID 19 and death with older people than younger people. In fact, the heat map informs us that the correlation between the number of deaths per 1,000 and the total number of people who are 60 years and over is 0.17, higher than the number of people who are younger. 




