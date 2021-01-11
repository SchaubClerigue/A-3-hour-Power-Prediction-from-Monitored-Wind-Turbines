# A-3-hour-Power-Prediction-from-Monitored-Wind-Turbines
# Abstract
In scenarios of low power production in windfarms, due to abrupt wind variations, reserve power is immediately activated. However, energy distribution from secondary sources can experience delays. Short-term power predictions derived from monitored wind turbines become useful to address such circumstances: while meteorological models are computationally intense, data-science models obtain faster and more accurate results for short-term periods (e.g., 3-6 hours). In this study, raw data from 4 monitored wind turbines has been combined with meteorological information from a weather station located 35 Km away from the windfarm. Feature engineering led to creation of: (1) 30 new time variables and (2) our target; the mean power of the next 3 hours. Four models are proposed in this study to successfully predict the power output, being the runtime of each model a key matter for near-term predictions. Modelling with a single turbine offers the most efficient results: accurate predictions, low MAE (~ 8%) and fast runtime (less than 10 minutes).
# Data
This study is supported by data from three csv files: two csv files with data from monitored wind turbines and one csv file containing data from an independent meteorological station. On the one hand, data derived from monitored wind turbines was gathered at the website from the French multinational electric utility company “Engie”. On the other hand, the data from the meteorological station belongs to the French national meteorological service: “Météo France”. Both datasets are open sources and can be downloaded from the links below:

 1) Windfarm's data: https://opendata-renewables.engie.com/explore/index
 2) Meteorological station's data: https://public.opendatasoft.com/explore/dataset/donnees-synop-essentielles-omm/export/?refine.nom_reg=Grand+Est&refine.libgeo=Thuilley-aux-Groseilles&q.timerange.date=date:%5B2012-12-31T23:00:00Z+TO+2018-01-13T22:59:59Z%5D
