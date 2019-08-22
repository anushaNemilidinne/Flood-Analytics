# Flood-Analytics
Floods are a hazardous disaster which threaten the United States and its territories
as they affect millions of people every year. In this context, having suitable
approaches for forecasting flooding will benefit people by reducing property
damage and saving lives, by warning citizens of dangerous flooding events in
advance. Consequently, many cities have developed sensor-based early warning
systems which report water levels in real-time. The goal of this thesis is to take advantage
of the data collected by such systems to develop data-driven water level
prediction techniques.
In past research, physics-based hydrology models have been developed, such
as the National Water Model, which predict water levels by simulating the rise
and fall of water. The purpose of this research is to generate alternative, complementary,
data-driven water-level forecasting models using existing statistical
models and recurrent neural networks which extrapolate the past into the future.
We investigate various time series forecasting approaches, in particular: Vector
Autoregressive (VAR) and Long Short-Term Memory (LSTM) Networks. The investigated
forecasting techniques are applied and evaluated using USGS datasets.
Moreover, we analyze the role of soil moisture — a less explored parameter —
in flood incidence and conduct some experiments that explore the relationship
between rainfall and soil moisture. Finally, we develop a web application called
FloodNet, a real time water level prediction system, with a forecast horizon of 2
hours for a location along Buffalo Bayou in Houston, Texas.
<img width="950" alt="floodnet_frstpart" src="https://user-images.githubusercontent.com/35274794/63553124-1cc6b580-c4ff-11e9-9a2c-f4781b965c5d.PNG">



<img width="944" alt="floodnet_secpart" src="https://user-images.githubusercontent.com/35274794/63553917-89db4a80-c501-11e9-855d-fb82c2c85a2e.PNG">


<img width="946" alt="floodnet_thrdpart" src="https://user-images.githubusercontent.com/35274794/63554289-af1c8880-c502-11e9-867b-819d4df02509.PNG">
