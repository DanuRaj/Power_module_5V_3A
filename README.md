# Power_module_5V_3A
<p align="left">
<img width="631" height="493" alt="image" src="https://github.com/user-attachments/assets/e9a81f2a-7013-4535-9873-c63284b6c257" />
</p> 

This power module takes power from the flight battery (usually 6 cell) and steps it down to a stable 5.25V output to power the flight controller. It measures the battery voltage and 
current draw and send this analog data to the flight controller.

## Board Function Description
- Voltage Regulator: A switching power supply (Buck Converter) convert the input voltage (input max 28V) to a steady 5.25V (3A max).
- Current Sensor: A high-side, unipolar current shunt monitor (INA139) from Texas Instruments, used to measure current upto 60A.
- Voltage Divider: A simple circuit scales the battery's high voltage down to a range that the flight controller's analog-to-digital converter (ADC) can safely read.

## Links
- Component Comparision, selection and budget calculation: https://docs.google.com/spreadsheets/d/1E6E3Z39MS1AMKON_rcoMTrBAKxuoQgl9/edit?usp=sharing&ouid=118396743550110532630&rtpof=true&sd=true
- Board version details: https://docs.google.com/spreadsheets/d/1RwYq9DlDa9_kEa9Yjs7iCPJi0Gea4oT7bDzQ82SCQtg/edit?usp=sharing
- Board fabrication batch details: https://docs.google.com/spreadsheets/d/1Ot-wO0kC-6jDttAs3GkX9LXFDDRmeL8QQExoFt7C394/edit?usp=sharing
- Block diagram: https://drive.google.com/file/d/1YQ6c-Lb43SASnWm7NJ7m4_MqnetjV_JF/view?usp=sharing

## Top and bottom images
<p align="left">
<img width="400" height="421" alt="image" src="https://github.com/user-attachments/assets/e2bd98ed-9d02-4584-b27f-9fb1a429661d" />
<img width="400" height="421" alt="image" src="https://github.com/user-attachments/assets/49a97b19-3f2b-4ac1-b342-590123e3fe43" />
</p>
