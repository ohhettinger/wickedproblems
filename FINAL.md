# Final Project

## Political Subdivisions

The Central African Republic has four different administrative divisions: country, prefecture, sub prefecture, and ADMs. The country is first divided up into 17 prefectures, which includes the capital city of Bangui (ADM1). Throughout this class, I have investigated areas in four different prefectures: Bangui (capital city), Lobaye, Ombella M'Poko, and Mambéré-Kadéi. All of these prefectures are clustered in the southwestern section of the state and represent some of the most populated areas. The next level of subdivision is sub prefecture, of which is has 72. As I was completing this project, I found an interesting discrepancy in my data. The GADM data that I had used for the first project only has 51 ADM2s. So, I went back and redid the graph of the Central African Republic with the HDX data that I used for projects 2-4. 

![pic](New_Central_African_Republic.png)

Anyway, as far as adm3s, the Central African Republic has 175. I did not investigate any ADM3s outside of Bangui. 

## Population 

The total population of the Central African Republic is 5,990,855 according to the CIA's July 2020 estimate. The most populated area is the capital city of Bangui, which the CIA estimates will have 889,000 residents in July 2020. I used exclusively 2015 and 2019 population data, so this estimate is larger than the data I worked with (835103.9 in 2019 for the city of Bangui and 5,238,313 for the country at large). This is the raster data for the entire population of the Central African Republic. For more detailed descriptions of the population of Bangui, visit the Project 1 write up. 

![pic](CAR_raster.png)

You can see that most of the country is very sparsely populated. The country itself is quite large from a land prespective, and so this exacerbates its already lacking population density. Here is a dataframe displaying the population of each adm1 in the Central African Republic (pop19 column) as well as the population density. You can see that the capital city of Bangui is by far the most densly populated. 

![pic](adm1_df.png)

For more information about populaiton density in and around Bangui, visit the Project 2 write up. In project 2, I attempted to predict population and density values using land cover data for the three prefectures of Bangui, Lobaye, and Ombella M'Poko. The results from the project tend to indicate that the predictive models were not very accurate, likely due to the develoing nature of the Central African Republic. Here is a quick graph of the difference between the unconstrained random forest model and the actual population of each gridcell in Bangui. 

![pic](Bangui_mapview.png)

Bangui is not very densely populated, but its lack of greenery indicates a much denser city. Anyway, once the model was contrained with built area data, it was much more successful. Here is a quick graph of the difference between the actual population of the area in and around Bangui and the predicted population.

![pic](Log_pop_diff.png)

As the first population raster indicates, the Central African Republic is largely rural. Once the model accounted for this, it was much more successful. The rural nature of CAR presents some very interesting challenges for the country's development. It's large size but rural population allows many rebel groups to rise and occupy large territory. CAR is plagued with many uprisings and rebel groups, and population location/density is certainly a contributing factor. Furthermore, a sparsely populated country will complicate access to services and spread of technology and ideas. Tune in next time to learn more about human settlements. 

## Human Settlements, Roadways, and Healthcare


## Sources

https://www.cia.gov/library/publications/the-world-factbook/geos/ct.html
