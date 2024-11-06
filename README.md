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

In the following sheet, you can see line graphs displaying trends by district, with additional breakdowns by gender and age. At the top, a fixed graph shows citywide trends for comparison. When you click the button to switch to neighborhood view, the line graphs will display the total for the selected district, neighborhood totals, and breakdowns by gender and age.

![Evolution by district](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Evolucion.png)

![Evolution by neighborhood](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Evolucion2.png)


**Unemployment rate** 

Finally, a stacked column chart displays the distribution of the unemployment rate across districts and neighborhoods, alongside a treemap illustrating the grouped rate.

![Unemployment rate](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Tasa.png)


### Data in unemployment in Madrid
The data was uploaded via the web option. When reviewing the data, we observe the following:

**Cleaning Data** ![Clean Data 1](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Datos1.png)

In Queries we duplicate it to separate the districts and the neighborhoods when cleaning it. 

![Duplicate](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Dupli.png)

**Cleaned Data**

We deleted, replaced, renamed, split, and unpivoted data to achieve the desired format.

![Clean Data 2](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Datos2.png)


**Model View** 

Not forgetting the connections to the codes in the model view.

![Model view](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/conexiones.png)

***For privacy reasons, it is not possible to upload other sheets of this dashboard. However, here is an alternative method to upload data*** 

Some data is obtained on a monthly or quarterly basis, for which a union folder can be created. In this folder, files will be added as they are released, and in Power BI, they will appear merged as if they were a single document.
![Union](https://github.com/laurasalvadorglez/Dashboards/blob/main/Assets/Union.png)
