# Dashboards 📊
## Table of Contents
1. [Unemployment in Madrid](#Unemployment-in-Madrid)
2. [Data in unemployment in Madrid](#Data-in-unemployment-in-Madrid)


### Unemployment in Madrid
*For this dashboard I have used data from the [**Public Database of the Madrid City Council**](https://servpub.madrid.es/CSEBD_WBINTER/seleccionSerie.html?numSerie=0904010000014) 

**District and neighborhood view**

In these tables, you can view the data presented in both a map and a clustered bar chart, along with a card displaying the total percentage. I have included slicers to filter by age group, month, gender, and district/neighborhood. Additionally, a toggle button allows you to switch between district and neighborhood views seamlessly. 

![District View](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/DistrictsView.png)

![Neighborhood View](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Barrios.png)

**Evolution by district and neighborhood**

In the following sheet you can see in line graphs the evolution by district with the evolution by sex, by age and in the upper part a fixed graph of the city for comparison.
When you click on the button to change to neighborhoods, you will see the line graphs with the total of the respective district, neighborhood total, by gender and by age. 

![Evolution by district](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Evolucion.png)

![Evolution by neighborhood](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Evolucion2.png)


**Unemployment rate** 

Finally, a stacked column bar for the distribution of the unemployment rate by districts and neighborhoods and a treemap for the grouped rate.

![Unemployment rate](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Tasa.png)


### Data in unemployment in Madrid
The data was uploaded through the web option. 
When we look at the data we see this: 

**Cleaning Data** ![Clean Data 1](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Datos1.png)

In Queries we duplicate it to separate the districts from the neighborhoods when cleaning it. 

![Duplicate](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Dupli.png)

**Cleaned Data**

We delete, replace, rename, split, univot to finally have it the way we want it.

![Clean Data 2](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Datos2.png)


**Model View** 

Not forgetting the connections with the codes in the model view.

![Model view](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/conexiones.png)

***For privacy reasons, it is not possible to upload other sheets of this dashboard. But here is other way to upload data*** 

Some data are obtained on a monthly or quarterly basis, for which a union folder can be created. In this folder the files will be incorporated as they come out, and in Power BI will appear merged as if they were a single document.
![Union](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Union.png)
