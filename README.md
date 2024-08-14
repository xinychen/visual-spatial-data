# Visualizing Spatial Data with Python

> Nowadays, Python has many popular and excellent packages such as `geopandas` for exploring various spatial data and visualizing them for basic analysis. As we know the importance of data visualization for researchers and practioners, it would be right time to pose some interesting cases for beginners to study.

In a hurry? Please check out the contents as follows.

## Tutorials

[Spatiotemporal data modeling project](https://spatiotemporal-data.github.io/) provides a series of tutorials on visualizing spatiotemporal data in Python, including

- [x] [Analyzing millions of taxi trips in the City of Chicago](https://spatiotemporal-data.github.io/Chicago-mobility/taxi-data/)
  - [Taxi trip data (from 2013 to 2023)](https://data.cityofchicago.org/Transportation/Taxi-Trips-2013-2023-/wrvz-psew/about_data)
  - [Taxi trip data (starting January 2024)](https://data.cityofchicago.org/Transportation/Taxi-Trips-2024-/ajtu-isnz/about_data)
  - [TNP rideshare trip data (from November 2018 to December 2022)](https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips-2018-2022-/m6dm-c72p/about_data)
  - [TNP rideshare trip data (starting January 2023)](https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips-2023-/n26f-ihde/about_data)
  - [Divvy bikeshare trip data (from 2013 to the latest date)](https://divvybikes.com/system-data)
  - [Electric scooter trip data (2019 & 2020)](https://catalog.data.gov/dataset/e-scooter-trips)

<p align="center">
<img align="middle" src="https://spatiotemporal-data.github.io/images/tnp_pickup_dropoff_trips_chicago_2022.png" width="600" />
</p>

<p align = "center">
<b>Figure 1.</b> Rideshare pickup and dropoff trips (2022) in the City of Chicago, USA. There are 57,290,954 remaining trips after the data processing.
</p>

<br>

- [x] [Constructing human mobility tensor on NYC rideshare trip data](https://spatiotemporal-data.github.io/NYC-mobility/rideshare/)
  - [TLC trip record data (from 2009 to the latest date)](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
  - High Volume For-Hire Vehicle (HVFHV) includes rideshare companies Juno, Uber, Via, and Lyft.

<p align="center">
<img align="middle" src="https://spatiotemporal-data.github.io/images/pickup_dropoff_trips_nyc_2024_april_may.png" width="700" />
</p>

<p align = "center">
<b>Figure 2.</b> Daily rideshare pickup and dropoff trips during the first 8 weeks since April 1, 2024 in New York City, USA. There are 37,404,265 trips in total, while the average daily trips are 667,933.
</p>

<br>

- [x] [High-resolution sea surface temperature data visualization](https://spatiotemporal-data.github.io/climate/sst/)

<p align="center">
<img align="middle" src="https://spatiotemporal-data.github.io/images/sst_2407_1.png" width="500" />
</p>

<p align = "center">
<b>Figure 3.</b> Daily sea surface temperature data with optimum interpolation on July 1, 2024. The unit of temperature data is centigrade (<img style="display: inline;" src="https://latex.codecogs.com/svg.latex?&space;^\circ\text{C}"/>).
</p>

<br>

- [x] [Visualizing Germany energy consumption data in Python](https://spatiotemporal-data.github.io/energy/E-usage-data/)
  - [JERICHO-E-usage dataset](https://www.nature.com/articles/s41597-021-00907-w)
  - [Processed data on GitHub](https://github.com/xinychen/vars/tree/main/datasets/energy)

<p align="center">
<img align="middle" src="https://spatiotemporal-data.github.io/images/Germany_energy_dist.png" width="750" />
</p>

<p align = "center">
<b>Figure 4.</b> Geographical distribution of seasonal energy consumption of 2019 in Germany.
</p>


<br>

- 可视化案例
  - [x] [全球水蒸气数据](https://medium.com/@xinyu.chen/visualizing-global-water-vapor-patterns-in-python-776bf08b3179) [[数据集](https://github.com/xinychen/climate-tensor)]
  - [x] [美国气象观测站气候数据](https://medium.com/@xinyu.chen/visualizing-station-level-usa-temperature-data-in-python-4f813fb9116a)
  - [x] [德国能源数据](https://medium.com/@xinyu.chen/visualizing-germany-energy-consumption-data-in-python-200e7cc3e506)
  - [x] [蒙特利尔共享自行车出行数据](https://medium.com/@xinyu.chen/montreal-bikeshare-data-analysis-ii-visualizing-bike-trips-on-road-networks-3d9ab7e5787c) [[站点分布数据](https://medium.com/@xinyu.chen/montreal-bikeshare-data-analysis-i-bikeshare-station-visualization-and-analysis-f5bec23e72f0)]
  - [x] [海洋表层气温数据](https://medium.com/@xinyu.chen/visualize-global-sea-surface-temperature-data-in-python-21a6324df563)
  - [x] [纽约出租车数据](https://github.com/xinychen/vars) [[数据预处理代码](https://transdim.github.io/dataset/NYC-taxi/)]
  - [x] [纽约出租车数据-toddwschneider](https://github.com/toddwschneider/nyc-taxi-data)
  - [x] [When Are Citi Bikes Faster Than Taxis in New York City?](https://toddwschneider.com/posts/taxi-vs-citi-bike-nyc/)
  - [x] [Analyzing 1.1 Billion NYC Taxi and Uber Trips, with a Vengeance](https://toddwschneider.com/posts/analyzing-1-1-billion-nyc-taxi-and-uber-trips-with-a-vengeance/)
 
<br>

## 公开数据集

### 城市数据集

- [x] [纽约城市公开数据网站](https://www.nyc.gov/site/designcommission/design-references/open-data.page)
   - [纽约出租车数据](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) (时间跨度为2009年至今，含OD信息，不含轨迹)
   - [纽约公交公司General Transit Feed Specification (GTFS)数据](https://transitfeeds.com/p/mta/85)
   - [公交车故障与延误数据](https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips-2018-2022-/m6dm-c72p)
   - [citibike共享自行车数据](https://citibikenyc.com/system-data) (时间跨度为2013年6月至今)
- [x] [芝加哥城市公开数据网站](https://www.chicago.gov/city/en/narr/foia/CityData.html)
   - [出租车出行数据](https://data.cityofchicago.org/Transportation/Taxi-Trips/wrvz-psew) (时间跨度为2013年至今)
   - [TNP网约车出行数据](https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips-2018-2022-/m6dm-c72p) (时间跨度为2018年11月至2022年12月)
   - [Divvy共享自行车出行数据](https://divvybikes.com/system-data) (时间跨度为2013年至今)
   - [E-scooter出行数据](https://catalog.data.gov/dataset/e-scooter-trips)
- [x] 华盛顿特区公开数据
   - [出租车出行数据](https://opendata.dc.gov/explore?query=taxi) (时间跨度为2015年至2022年)
   - [Capital Bikeshare共享自行车数据](https://capitalbikeshare.com/system-data) (时间跨度为2010年至今)
- [x] [波士顿Bluebikes共享自行车数据](https://bluebikes.com/system-data)
- [x] [佛罗里达州公共自行车](https://www.citibikemiami.com/#stationmap)
- [x] [纽约交通安全论坛](https://trafficsafetyforum.nypdonline.org/2e5c3f4b-85c1-4635-83c6-22b27fe7c75c/view/89)
- [x] [洛杉矶城市公开数据网站](https://data.lacity.org/)
- [x] [美国政府公开各州交通相关数据](https://catalog.data.gov/dataset/?tags_limit=0&res_format=XML&groups=local&tags=transportation)	
- [x] [Climate dataset](https://climexp.knmi.nl/start.cgi?id=51e9b9c2ffa5bf2a83a469eba86afa0f)
- [x] [American Government Open data/Traffic data of America](https://catalog.data.gov/dataset)

## Metrics (指数)

- [x] [Shared Mobility Data Availability and Usage Trends](https://publications.anl.gov/anlpubs/2022/05/175312.pdf)
- [x] [Global Micromobility Index (61 Cities and 7 Regions)](https://public.ridereport.com/) [[Austin ride report](https://public.ridereport.com/austin) & [Shared Micromobility Vehicle Trips in Austin](https://data.austintexas.gov/Transportation-and-Mobility/Shared-Micromobility-Vehicle-Trips/7d8e-dm7r)]
- [x] [APTA Ridership Trends](https://transitapp.com/APTA)

## Publications

Most of these examples are from our papers:

- Xinyu Chen, Chengyuan Zhang, Xiaoxu Chen, Nicolas Saunier, Lijun Sun (2024). [**Discovering dynamic patterns from spatiotemporal data with time-varying low-rank autoregression**](https://doi.org/10.1109/TKDE.2023.3294440). IEEE Transactions on Knowledge and Data Engineering. 36 (2): 504-517. [[PDF](https://xinychen.github.io/papers/time_varying_model.pdf)] [[Blog post](https://spatiotemporal-data.github.io/posts/time_varying_model/)] [[Data & Python code](https://github.com/xinychen/vars)]

