# Reference Towns in Turkish Elections

After each election, we face with different maps and numbers on TVs. Agencies and institutions deliberately share the results of some cities or towns to shape public opinion and social tension.

Despite the high frequency of elections and increasing data analysis & visualization technologies, no TV channel share projections depending on the previous elections' results and regional populations.

In this study, I would like to identify, if exist, reference towns that point out the overall results.

This project use Python 3 and libraries of numpy, pandas, chardet, sklearn.cluster, scipy.cluster.hierarchy, matplotlib.pyplot, sklearn.decomposition.PCA, sklearn.linear_model.LinearRegression, sklearn.linear_model.Lars, sklearn.preprocessing.StandardScaler, sklearn.metrics, and itertools.

The data includes the results of 2014, June 2015, November 2015, 2017 (referendum), 2018, and 2019 elections. I've reformatted 3 files (yerel2014.csv, genel25_26_referandum2017_27meclis_cb2018.csv, 31mart2019yerelsecimilcesonuclari11.csv) to get data frames with columns
- "Town" as the CITY_TOWN tuple
- "Party-1", "Party-2", "Party-3"… as the ratio of overall

A detailed summary of the study is given on medium.com: https://medium.com/@utkucivelek/reference-towns-in-turkish-elections-91063c526444
