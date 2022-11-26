# mobile_price_range_prediction
A classification model to predict whether price range of mobile based on certain specifications.
## Problem :
 Create a classification model to predict whether price range of mobile based on certain specifications
## Details of Feature :
The columns are described as follows:
Dataset as 21 features and 2000 entries. The meanings of the features are given
below.
- battery_power: Total energy a battery can store in one time measured in mAh
- blue: Has bluetooth or not
- clock_speed: speed at which microprocessor executes instructions
- dual_sim: Has dual sim support or not
- fc: Front Camera mega pixels
- four_g: Has 4G or not
- int_memory: Internal Memory in Gigabytes
- m_dep: Mobile Depth in cm
- mobile_wt: Weight of mobile phone
- n_cores: Number of cores of processor
- pc: Primary Camera mega pixels
- px_height: Pixel Resolution Height
- px_width: Pixel Resolution Width
- ram: Random Access Memory in Mega Bytes
- sc_h: Screen Height of mobile in cm
- sc_w: Screen Width of mobile in cm
- talk_time: longest time that a single battery charge will last when you are
- three_g: Has 3G or not
- touch_screen: Has touch screen or not
- wifi: Has wifi or not
- price_range: This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).
## Methedology : 
We will proceed with reading the data, and then perform data analysis. The practice of examining data using analytical or statistical methods in order to identify meaningful information is known as data analysis. After data analysis, we will find out the data distribution and data types. We will train 4 classification algorithms to predict the output. We will also compare the outputs
## ML Models : 
#### KNN Classifier: 
  ![image](https://user-images.githubusercontent.com/108235775/204091882-2f5745a4-4aa3-496d-b52c-96c8bfda30a5.png)
#### Logistic Regession: 
  ![image](https://user-images.githubusercontent.com/108235775/204092117-b65e8f2c-175f-46e5-a23c-77868cffd79d.png)
#### SVM Classifier:
   ![image](https://user-images.githubusercontent.com/108235775/204091903-aaf61cba-e8ca-473e-8c0c-52d41e94a02b.png)
