# Temperature-Sensor-Failure-Detection-and-Diagnosis-Based-on-the-ARIMA-Model.
Second Year-EDAI-Project _ Data Prediction and Early Detection of Errors in Temperature Sensors (DPEDETS)

Abstract
In industry, the use of temperature sensors is paramount, with real-time sensors being crucial for temperature fluctuations. 
However, such sensing systems may fail due to environmental or technical factors such as corrosion, sensor body fault, or wire 
fault in the assembly line. Therefore, a reliable sensor on that infrastructure is required to complete the process efficiently. In this 
context, this paper introduces Data Prediction and Early Detection of Errors in Temperature Sensors (DPEDETS), a method 
which helps the digital monitoring of sensor health conditions of a temperature system for stool monitoring DPEDETS. The 
methodology involves the autoregressive integrated moving average model (ARIMA) the mathematical concept test method to 
initiate a tentative assessment of sensory variation. Then, it detects and distinguishes confusion in the continuous transmission of 
sensory data, detecting premature sensory failure. The proposed DPEDETS method provides a reliable measurement of the time 
sensing data for the duration of sensing failure or temperature monitoring systems. The DPEDETS method has been tested on the
temperature data collected from different types of temperature sensors. The results illustrate effectiveness of the DPEDETS 
process and sensory function of temperature monitoring on suites.


Block Representation of the Suggested DPEDETS System

![Block Diagram](https://user-images.githubusercontent.com/84955646/223953169-b78c5b90-11b0-4fa7-a061-638f4937d197.jpg)


Autocorrelation
Only stationary time series statistics are appropriate for the ARMA (p,q) model. However, the sensor statistics that 
the system is generating exhibits non-stationary behaviour. Let’s see that with the help of the graphs of 
autocorrelation of non-stationary behaviour of our four temperature sensors. In the below figure graphs of 
autocorrelation of non-stationary behaviour of four temperature sensors are plotted. According to these graphs data 
which we have gathered from sensors show trend as it is increasing data.

![Autocorrelation](https://user-images.githubusercontent.com/84955646/223953735-016f319d-fd34-4ce1-b163-a25a97ae1bea.jpg)


Differencing
we need stationary data only so first we need to make it stationary and for this we 
have a method known as Difference. Below graph shows the difference in the data values which we obtained by 
shifting the values by one. Now it has become stationary

![Differencing](https://user-images.githubusercontent.com/84955646/223954044-649a00b0-77dd-4c81-b1be-b18dd3dcdb37.jpg)



