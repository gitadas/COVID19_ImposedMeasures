# **Covid-19-Imposed measures**

**Overview**

Since the outbreak of COVID-19 in Wuhan, China, the infection has spread around the world. In 11thMarch, 2020, World Health Organisation has declared it as a Pandemic. This project is to examine the imposed measures in countries around the world, and how do they cluster in terms of measures. Our study is focussed only with the countries having number of confirmed cases more than in Australia.

**Data**

The datasets are downloaded from [https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases].They are time series data tracking the number of people affected by COVID-19 worldwide and include cases of confirmed, recovered and deaths, and the world populationdata. The measures data acaps\_covid19\_government\_measures\_dataset.xlsx(https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases.%20They%20are%20time%20series%20data%20tracking%20the%20number%20of%20people%20affected%20by%20COVID-19%20worldwide%20and%20include%20cases%20of%20confirmed,%20recovered%20and%20deaths,%20and%20the%20world%20population%20data.%20The%20measures%20data%20acaps_covid19_government_measures_dataset.xlsx) is also sourced from the same site.

**Analysis**

Create feature vectors using the measures applicable for respective countries. Use K-means clustering to group them into different clusters. Identify the measures that are significant in terms of discriminating different clusters, and also the ones that help in forming the clusters.

**ongoing**

