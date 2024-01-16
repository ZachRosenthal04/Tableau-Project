# Final-Project-Tableau

## Project/Goals
The goals of this project to create at least 5 visualizations, one dashboard, and a presentation based on my choice of a variety of data available for exploration. My project used the data from the W.H.O’s Tuberculosis Burden by Country dataset which covered a 22-23 year period from 1990 to 2013. 


## Process
### Step 1 – Understanding the Data
For me, this was by the far the most challenging and important step in the whole project. I was excited by the opportunity to explore and visualize data from an industry that I had little-to-no experience in. Unsurprisingly, my first step was to understand the data. 

From the number of fields relating to them, I had to first learn the difference between disease prevalence and disease incidence. Disease prevalence is the number of people from a given population that are living with the disease at a particular time. Prevalence is a difficult field to measure and also is much more useful as snapshots rather than trends over time but it is still useful to see.

Disease incidence is the number of new cases of the disease that are present in a given population, generally on a year by year basis. This is a field that is better expressed over time. These fields and the mortality data (the number of people who died that had the disease) were critical in making my calculated fields and trend analysis

Early in my exploration, I didn’t understand why so many fields were repeating themselves and why they said ‘per 100 000 population’. Thankfully, I soon learned that calculating those important metrics ‘per 100 000 populaiton’ is what enables users to compare the data from different regions and countries regardless of the varying sizes of population, incidence, prevalence and mortality.

Other important research into the available data helped to clarify some of the data collection methods and the methods used to derive some of the aforementioned important fields. As an example, the most important method and record type I found was the ‘VR’ and ‘VR imputed’ records in the ‘methods to derive mortality estimates’. VR stands for ‘vital registration’. Vital statistics is accumulated data gathered on live births, deaths, migration, fetal deaths, marriages and divorces. The most common way of collecting information on these events is through civil registration, an administrative system used by governments to record vital events which occur in their populations. It is a sign of a stronger central government and medical infrastructure. An important point in my visualizations and results.

Armed with this new understanding of the data, I continued to the second step. 


### Step 2 – Calculated Fields and basic visualizations
Through some background research for the project on medical data and more specifically on disease burden analysis, I made an important calculated field called case fatality risk (CFR) which I used as a percentage. CFR is a metric to convey the risk that someone with the disease is likely to die from that disease. It is calculated using estimated mortality and estimated incidence.

I used CFR and case detection rate (CDR) as the primary focus of my because I quickly uncovered that they had a strong, negative, correlation. When trying to find trends in the data across countries, I quickly found the data difficult to parse since there were about 219 countries and many of which had records for each of the 22-23 year covered in the set. For clarity, I therefore focused my analysis on regional trends which offer useful insights for future analysis into a more country-specific approach.

## Results
As one may have guessed from the previous sections, I chose option 2 and more specifically the Tuberculosis burden of disease dataset. I created many visualizations to try and understand some of the trends seen in the data. Unfortunately not all made it onto my dashboard.

Since my aim was to get a better understanding of the regional data, I began there. I made visualizations for each region in the: prevalence, incidence, and mortality per 100 000 population to find out the progress of each region as well as which were the most and least burdened with TB. Even in this early exploration, some interesting points emerged. As one might expect, as a region, Africa was by far the most burdened region with TB across all categories and Europe was the least. What is surprising, is that Europe didn’t start that way. In fact, I was very surprised to learn that Europe’s trend looked very similar to Africa’s in incidence and prevalence but very different in mortality. This finding is what inspired the rest of my visualizations.

In support of the trend analysis, I made many maps to look for disease hotspots and the spread of the data collection methods seen in the data. This was important to see since the regions were not neatly divided by continent. The regions were: the Americas, Europe, Eastern Mediterranean Region, Africa, South East Asia, and Western Pacific Region. From the several maps I made, the most important was the one showing the distribution of the ‘methods to derive mortality’. It’s importance conveyed very concretely one of the main differences between the rest of the world (which was all trending well into the same direction) and the most burdened areas. Africa’s data for mortality was mostly gathered indirectly while the rest of the world’s was using vital registration.
Using that knowledge, I made a visualization that I used to attempt to examine which data collection methods accounted for the best average CDR%. I wanted to compare the one in each region so that ideally I could find what strategy might help improve the problem areas in Africa and elsewhere. This visualization offers useful insight into where might be the best use of charitable funding, as well as local or international government resources. 

To further illustrate the importance of improving a country’s CDR, I two visualizations to show the relationship between CDR and CFR. Unsurprisingly, Europe had the lowest CFR% and highest CDR%. What was useful to see in the visualization is the forecasting of these two metrics as well as a powerful demonstration and concrete target to aim for Africa as a region and in turn any heavily-burdened, individual country.  The targets that were the global trend and where Africa should aim is to reach an average case detection rate of about 75-85% and a case fatality risk of between 8-12%. Unfortunately, as of 2013, Africa was around 60% CDR and 20% CFR.



## Challenges 
The biggest was definitely understanding the data and being able to learn how to use it since I had no medical data background. That being said I am very happy to have taken on the challenge and look forward to exploring this kind of data in the future.
Another challenge was dealing with the sheer number of countries and even the inconsistency of the data within one country over the time covered. It made it very hard to analyze any trends that might have existed between countries with similar records that are in different regional groups. To this end, it was also difficult since to understand why some countries that were on the continent of Africa were not considered to be a part of that region.  



## Future Goals
If I had more time, with the regional trends I found, I would like to do a deeper dive into some of the problem areas I found either by country or sub-regionally. Especially as there were some very interesting outliers. An example would be an exploration of sub-Saharan Africa or especially central and southern Africa and why and how it differs from North Africa. Furthermore, an outlier I would like to explore is the entire EMR region. The EMR region generally trended along the same lines as the rest of the world but it also behaved completely different with regards to the relationship between CDR and CFR. While my inclination is to see it as an issue with the way the data was collected, only a deeper dive will actually be able to examine it. Other honourable mentions for outliers to explore is the Caribbean which showed extremely high CFR%’s (some well over 100%) despite having appropriate numbers in most of the other categories. This may offer an important look into the medical institutions and infrastructure that exists in this sub-region.

