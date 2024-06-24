# Using Kalman Filter to Analyze and Predict Seismic Activity

### Project Title
Using Kalman filter to analyze and predict seismic activity

### Problem Statement
Develop and implement a Kalman filter-based model for analyzing real-time seismic activity data to accurately predict future seismic events and improve understanding of earthquake patterns and behaviors.

### Uniqueness
- **Kalman Filter Utilization**: Interpolating irregular earthquake data into a time sequential series.
- **Multiple Data Streams**: Integrating multiple streams of time series data from multiple neighboring sensor stations.
- **State Estimation and Prediction**: Leveraging Kalman filter’s effectiveness in dynamic systems for better predictions compared to models like Bi-LSTM or ANN.

### Dataset
- [IRIS Data Services](https://service.iris.edu/fdsnws/dataselect/docs/1/builder/)
- [USGS Earthquake Data](https://earthquake.usgs.gov/fdsnws/event/1/)

### Approach
![mml](https://github.com/viridi-5/Kalman-filter-to-predict-seimic-activity-/assets/113525455/58b4f8bf-0e89-464d-881d-29a4515181d3)


### Progress
| Task                                                       | Status                |
|------------------------------------------------------------|-----------------------|
| Analysis using Virtual data stream                         | Done                  |
| Analysis using a single channel live data                  | Done                  |
| Analysis using multiple channels of live data              | To be done            |
| Analysis using multiple channels of live data from multiple sources | To be done   |
| Utilizing Extended Kalman Filter / Ensemble Kalman Filter or better models | To be done   |

### Code and Results
- [Project Notebook](https://colab.research.google.com/drive/1ZazSblayJ8ZajuvOaV7RY6GlDWxezysN?usp=drive_link)

### Completed Work
| Component                                    | Completion | Runs without problem | Issues         |
|----------------------------------------------|------------|----------------------|----------------|
| Data Preprocessing                           | 100%       | Yes                  | -              |
| Kalman Smoothing                             | 100%       | Yes                  | -              |
| Plotting graphs to infer trends and residuals| 100%       | Yes                  | -              |
| ARIMA filter to predict future instances     | 100%       | Yes                  | -              |
| Importing data stream into Kalman filter     | 100%       | Yes                  | -              |
| Creating a numpy array of live data          | 100%       | Yes                  | -              |
| Analysis of live data                        | 25%        | Yes                  | Incomplete implementation |

### Reference Papers
1. **A new algorithm for landslide dynamic monitoring with high temporal resolution by Kalman filter integration of multiplatform time-series InSAR processing**
   - Jialun Cai, Guoxiang Liu, Hongguo Jia, Bo Zhang, Renzhe Wu, Yin Fu, Wei Xiang, Wenfei Mao, Xiaowen Wang, Rui Zhang
   - Faculty of Geosciences and Environmental Engineering, Southwest Jiaotong University, Chengdu, China
   - 2022

2. **Earthquake prediction based on Bi-LSTM+CRF model and Spatio-Temporal Data**
   - Zhittong Su, Qian Zhang
   - College of Information Science and Technology, North China University of Technology, Beijing, China
   - 2020

3. **Trajectory prediction based on long short-term memory network and Kalman filter using hurricanes as an example**
   - Wanting Qin, Jun Tang, Cong Lu, Songyang Lao
   - 2019, Computational Geosciences

### Key Learnings
1. Using Kalman filter to generate a time sequential series from irregular earthquake data.
2. Working with live data streams.
3. Combining multiple data sources and analyzing outcomes.
4. Utilizing ARIMA models alongside Kalman filters for future predictions.

---

Feel free to reach out to us for any queries or contributions!

