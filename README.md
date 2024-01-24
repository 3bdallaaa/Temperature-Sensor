# Temperature-Based Fan Control
![image](https://github.com/3bdallaaa/Temperature-Sensor/assets/118936824/8d7bfd24-13a3-42e1-9b45-21833b9fc903)

The input is ADC (Temperature) and output is PWM (Duty)

**Ranges of Duty:**   
- Below 52°C: Fan is turned off.  
- Between 52°C and 55°C: Fan operates at 50% duty cycle.   
- Above 55°C: Fan operates at 100% duty cycle.   

The temperature sensor used is NTC 10K   
The arm is STM32F103C8   
