# LongitudinalResilienceStudy2024
Info on the Master Data
###Longitudinal Dealers Project

##Background:
In order to calculate fisheries engagement and reliance, we depend on several variables. One of the critical variables is the number of dealers a community has in a given year. This is a valuable metric, and even proxy, in determining how important fisheries is to a community – the higher the number of dealers can imply: more opportunities for fishermen to sell their fish (thus drawing in more fishermen into that community), a community which depends on, or promotes, its seafood heritage, and/or a community which is located in an area with good fishing grounds.
Dealer data is currently collected through various data sources: ALS, ACCSP, and GSFMC. Over the past several decades, many states have transitioned, at different times, to the Trip Ticket program. Yet, not all states have digitized nor kept records of “historic” fisheries landings data. Because of the lack in “clean” and “accurate” data, it is difficult to properly calculate long-term fisheries engagement and reliance scores.
In early 2022, SSRG sought to fill the gaps in historic dealer data. Over the course of half a year, researchers have collected and cleaned fisheries landing data from the first year of available data, 1977, to 2013.

##Methodology:
All of the landings data was first downloaded, each year, from 1977-2013.
The data has many limitations and shortcomings. A Dealer’s name can be listed, yet its community is unresolved. A landing could have an associated community, yet no Dealer. There are several combinations of mismatches which needed to be patched. For the purposes of the data, “unresolved” (in the community field) is when the dealer is known and the community is not known. “Unknown” is when both dealer and community are not known.
The data was first cross-referenced to find any dealers that were identified in one year but not the other. Dealer’s names were ascertained by SupplierDealerID and/or License Number. It was common for dealers to be described (their community identified) in later years compared to the first years of the data records.
Multiple online sources were used to locate and identify historic dealers. Some of the sources used, but not limited to, were: annual Interstate Certified Shellfish Shippers Lists (ICSSL), state business directories, online newspaper archives, and extensive google searches.
After all the data that could have been collected through available sources, SSRG researchers contacted each state’s respective agency.  Because not all states began their Trip Ticket program at the same time, states varied in the accuracy of their data. Other states, like Texas and Georgia, did not digitize any landings data predating a certain year. There was only one state which refused to cooperate – Louisiana.
The data shared by the states was integrated into the historic landings data. Dealers were identified through provided license/supplier numbers. 

Outputs:
There are several folders and spreadsheets found in the “Longitudinal Dealers Project” folder.
A folder with each year’s cleaned data can be found in “1977-2013 Cleaned Data”. In each decade’s folder, you can find a spreadsheet with the whole decade’s landings.
In the “Resolved and Unresolved Dealers by State” folder, you can find a spreadsheet of partially identified dealers from each state. This was the information gathered from each state’s agency. Note: this data has to be checked if it has been thoroughly integrated in the “1977 – 2013 Cleaned Data”. The fastest way to check and/or fill in the data is through a “vlookup” formula in Excel. The spreadsheets in this folder contains all the dealers that have not been identified.

Remaining Tasks:
To calculate fisheries engagement and reliance, vessel permit data and population data is needed. 
Find the permit/vessel data by year and associate it with the respective community.
Find the population data for each community. Not all communities were/are incorporated for the duration of this study, so population data might not be readily available.

