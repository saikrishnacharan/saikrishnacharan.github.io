# <span style="color:Blue;">Research Projects</span>
---


#### 1. IoT-for-air-pollution-monitoring
- Funded by Pernod Ricard India Foundation(PRIF)
- Used Python Machine Learning Libraries are Seaborn and Pandas 
- To implement and deploy an IoT network of air pollution monitoring nodes, constituting of various sensors to measure the air quality parameters such as Particulate matter (PM2.5,PM10), Carbon Monoxide(CO), NOX, temperature, humidity, SO2, NH3, which are required for calculating the AQI index according to the Indian AQI guidelines. 
- This IoT network will be deployed in IIIT campus and adjoining regions. The sensor node network is connected to internet using different communication technologies such as WiFi, LoRaWAN, 2G/3G/4G technologies. Data analysis is done on the collected data and data is displayed on the dashboard. 
- [<span style="color:Violet;">Dashboard</span>](https://spcrc.iiit.ac.in/air/)
- I analyzed data collected by pollution monitoring nodes deployed in IIIT campus, using machine learning techniques such as Parallel coordinates, Pair-wise correlation matrix, Correlation heatmap, Joint plots and other Spatial interpolation techniques

___
#### Some Results generated
<img src="images/RawPlot.png?raw=true"/>
<img src="images/Corr_Map.png?raw=true"/>
<img src="images/Pair_WisePlot.png?raw=true"/>

___
### 2. Fast Direction of Arrival Estimation of Multiple Targets using Deep Learning and Sparse Arrays
- This work focuses on improving the Direction-of-Arrival (DoA) estimation of multiple targets/sources from a small number of snapshots. 
- Estimation via the sample covariance matrix is known to perform poorly, since the true manifold structure is not revealed for a small number of samples. 
- First, we explicitly model the sample covariance matrix that is used for the DoA estimation as a noisy version of the true one. Next, we employ a stacked denoising autoencoder (DAE) that predicts a statistically “richer” version of the sampled matrix that is subsequently used for the DoA estimation. Moreover, we consider a limited number of sensors (comparable to the number of sources) in a non-uniform linear configuration and introduce an end-to-end hybrid DoA prediction-estimation scheme.
- The maximum interelement distance constraint (MISC) array, which exhibits several desirable characteristics.
-  The MISC Array Structure is as below:
    <img src="images/MISC1.png?raw=true"/>
- Proposed fast covariance matrix prediction scheme for DoA estimation.
    <img src="images/MISC2.png?raw=true"/>
- The ANN comprises of fully connected layers, followed by a non-linear activation function except for the (last) output layer, which has no activation. The proposed neural network layout is given as:
    <img src="images/MISC3.png?raw=true"/>

___
#### Results Generated
- Hat(Rx) is the conventional approach (MUSIC) and Cap(Rx) is the proposed method
    <img src="images/MISC4.png?raw=true"/><img src="images/MISC5.png?raw=true"/>

