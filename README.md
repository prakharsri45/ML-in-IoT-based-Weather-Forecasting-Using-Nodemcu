# ML-in-IoT-based-Weather-Forecasting-Using-Nodemcu

Nowadays the focus has been shifted towards intelligent technologies like Internet of Things and Machine Learning. This project proposes a method for forecasting weather conditions such as temperature and humidity by means of machine learning. Many IoT hardware platforms are available for IoT implementations and ESP-12E chip is one of them. The system utilizes a temperature and humidity sensor i.e. DHT22. The sensed data from the sensor uploaded to a MySQL and Google Sheet cloud server using NodeMCU (ESP-12E) module. The data is also displayed on a website for monitoring the real time values. Further, the recorded data then transferred to the Google Colab that utilizes a python environment. A Random Forest algorithm
is used for setting up the machine learning environment. This model is trained using the prerecorded values of sensor data. Afterwards, the web-app is used to predict temperature and humidity of the desired date. This real time data is required to test the model and prediction is done for a particular value by blinking the led connected to NodeMCU.

![image](https://user-images.githubusercontent.com/81968507/144976217-85e49250-7704-444c-a3ea-31680a0b4090.png)
