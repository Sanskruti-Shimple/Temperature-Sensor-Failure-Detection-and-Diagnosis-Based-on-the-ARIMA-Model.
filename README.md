# Temperature-Sensor-Failure-Detection-and-Diagnosis-Based-on-the-ARIMA-Model.

 -----------------------------------------------------------------------------------------------------------
| Second Year-EDAI-Project _ Data Prediction and Early Detection of Errors in Temperature Sensors (DPEDETS) |
 -----------------------------------------------------------------------------------------------------------
 
 
*Dataset Prepared in Excel using the tool Data Stramer

![image](https://user-images.githubusercontent.com/84955646/223958627-12588166-4b7a-4908-b5dc-437c008d384e.png)

*Algorithm of the Project 

![image](https://user-images.githubusercontent.com/84955646/223958766-18dfcbbd-d366-4d80-b152-6590d6b22ab3.png)

*Pseudocode

![image](https://user-images.githubusercontent.com/84955646/223958850-b27149b3-32ec-483b-93c0-34b028e3b6d3.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------------


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


1) Block Representation of the Suggested DPEDETS System

![Block Diagram](https://user-images.githubusercontent.com/84955646/223953169-b78c5b90-11b0-4fa7-a061-638f4937d197.jpg)


2) Autocorrelation
Only stationary time series statistics are appropriate for the ARMA (p,q) model. However, the sensor statistics that 
the system is generating exhibits non-stationary behaviour. Let’s see that with the help of the graphs of 
autocorrelation of non-stationary behaviour of our four temperature sensors. In the below figure graphs of 
autocorrelation of non-stationary behaviour of four temperature sensors are plotted. According to these graphs data 
which we have gathered from sensors show trend as it is increasing data.

![Autocorrelation](https://user-images.githubusercontent.com/84955646/223953735-016f319d-fd34-4ce1-b163-a25a97ae1bea.jpg)


3) Differencing
we need stationary data only so first we need to make it stationary and for this we 
have a method known as Difference. Below graph shows the difference in the data values which we obtained by 
shifting the values by one. Now it has become stationary

![Differencing](https://user-images.githubusercontent.com/84955646/223954044-649a00b0-77dd-4c81-b1be-b18dd3dcdb37.jpg)


4) Checking Autocorrelation
Again check the autocorrelation of these graphs to see whether we are getting correct stationary or not. Below 
graphs shows the autocorrelation after applying the method of differencing and it is observed that graph is now 
symmetric along the both axes. Now we are ready to apply ARIMA model on our data.

![Check Autocorrelation](https://user-images.githubusercontent.com/84955646/223954678-8b196833-69ac-456a-aa48-2bb123223b8a.jpg)


5) Prediction
The graph between our 
actual data and the data that we have predicted for our four sensors Thermistor, Thermocouple, RTD and LM 35 
respectively.

![Prediction Plots](https://user-images.githubusercontent.com/84955646/223955186-1187a1c1-0c75-4876-a362-8411f1639d69.jpg)


6) Flow Chart 

![Flow Chart](https://user-images.githubusercontent.com/84955646/223955603-b1ad26be-896b-46c7-85c5-7759306d0399.jpg)


7) Experimental Set-up

a) Simulation

1) Thermocouple

![image](https://user-images.githubusercontent.com/84955646/223956227-ff2c35de-d1c1-455f-9216-bc169256d366.png)


b) Hardware

1) Thermocouple

![image](https://user-images.githubusercontent.com/84955646/223956106-2d7f0fb0-06a5-4e7b-bcf4-ceeb21fc580b.png)


a) Simulation

2) RTD

![image](https://user-images.githubusercontent.com/84955646/223956529-65ba66af-ad3b-4a8d-8ef2-a05ef0aae9b3.png)


b) Hardware

2) RTD

![image](https://user-images.githubusercontent.com/84955646/223956615-7644aa59-39fe-4528-be6d-a346b35344c2.png)


a) Simulation

3) Thermistor

![image](https://user-images.githubusercontent.com/84955646/223956742-b386f202-28cb-4ca8-9847-16c6242472ec.png)


b) Hardware

3) Thermistor

![image](https://user-images.githubusercontent.com/84955646/223956837-c119d5de-b23a-455d-9412-36b84a21263a.png)


a) Simulation

4) LM35

![image](https://user-images.githubusercontent.com/84955646/223956976-8aa11490-c18e-4049-a382-50ac97c83768.png)


b) Hardware

4) LM35

![image](https://user-images.githubusercontent.com/84955646/223957031-14e937e6-6af8-46b7-b012-d8e2f25ca06b.png)




8) Experimental Result Analysis
A predictive data frame that has been created can be transformed into a CSV file. With the aid of projected figures, 
we can determine what kind of inaccuracy took place. The red line in the following picture represents expected data, 
whereas the blue line represents sensory data. In Fig. 6.1 the first graph is a thermistor sensor data graph. We 
compare two data sets; suddenly there is a big difference between the two readings, which is why we conclude that 
there is a sensory error.

![Faulty Sensor Responses](https://user-images.githubusercontent.com/84955646/223957709-6b31e04c-163e-420b-8800-6424e934082f.jpg)


We compared two sets of data, there was a lot of difference between the two readings and the difference was 
even bigger, so we concluded that there was a sensor error. The third graph shown is the graphical database of the 
RTD PT100 sensor. We compared two data sets, and there is a lot of variation between the two curves, and the 
difference is also huge, which is why we conclude that there is a sensory error. The fourth graph is the graphical data 
graph of the LM35 shown. We compared two data sets, and there is a lot of variation between the two curves, and 
the difference is also huge, which is why we conclude that there is a sensory error.



9)  Conclusion
Introduces a method called DPEDETS, which detects premature neurological failure based on realtime exposure. Data were taken from industrial temperature sensors. The DPEDETS method uses the ARIMA model 
to evaluate sensory data to understand temporal adaptive capabilities. This assessment method is employed as a 
framework to offer an additional indicator of body sensitivity. Used as a reference to the DPEDETS method for 
misinterpreting expected data from the ARIMA model, early detection of sensory failure, and data retention. The 
DPEDETS method involves both predictive and diagnostic methods. In case of confusion, the algorithm separates 
the false data and finds the data number and related estimates. In addition, in the case of persistent error data, 
detection can be a very quick sensory failure and requested data retention process to provide predictable measures. 
Experimental tests indicate that the DPEDETS method can be used in industrial temperature monitoring systems 
with high accuracy and efficiency.
