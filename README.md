# Alcohol-Detector

The system utilizes the NXP LPC 1768 microcontroller, a 32-bit ARM Cortex-M3 microcontroller known for its performance and power efficiency. 
The MQ3 alcohol sensor, which operates by changing its resistance in response to alcohol levels, detects alcohol vapour in the air and sends an analog signal to the microcontroller.
The microcontroller then uses its built in ADC (Analog to Digital Converter) to convert this signal into a digital value. The processed data triggers an alert if the detected alcohol level exceeds a predefined threshold. 
The system provides real-time feedback through visual indicators: a 16x2 LCD display shows the percentage of alcohol present. 
