# BHT-ARIMA4TC
This repository is the official implementation of "A Short-Term Tropical Cyclone Intensity Forecasting Method Based on High-order Tensor".


Due to the file volume and file size limitation of gihub, we had to split the files into two zip packages, please download and unzip them before use and place the CMABSTdata folder under the CMA folder.

The main code of the experiment is located in the CMA folder.
It contains the following parts：

   (1)Experimental data (CMABSTdata folder)
   
   (2)data_process1.py and data_process2.py for CMA best path data preprocessing
   
   (3)year_TC_recordnumber.xlsx records the number of records of each typhoon data in the CMA best path data
   
   (4)year_TC_recordnumber_40.xlsx records the names of typhoons with more than 40 records
   
   (5)BHT_ARIMA forecast typhoon intensity(predict_BHT_ARIMA folder)
  
   (6)BHT_ARIMA predicts the typhoon intensity change at the point where the typhoon suddenly intensifies(point_predict_bht_ARIMA folder)
   
   (7)Draw a comparison chart of typhoon intensity prediction based on the typhoon number in the TC_wind or TC_pressure file(TC_plot folder)

In particular, it should be noted that since the code is a rolling forecast and is influenced by the previous moment's forecast, the resulting results will not be constant and will fluctuate a little.  
We acknowledge the authors for the code released at ''[https://github.com/huawei-noah/BHT-ARIMA](https://github.com/huawei-noah/BHT-ARIMA)'', which provides useful operations for our implementation.
