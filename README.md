# A driving behaviour analyser

## Motivation
There’s no objective metric to measure driving behavior right now
Examples
- Driving tests are executed in a subjective manner (instructors, examiners)
- Insurance companies have trouble determining a new customer’s     driving skills and thus their insurance fee quote

## How it is built
Micro Bit
- used as an accelerometer
- Matplotlib to plot the real time acceleration change
- Numpy to calculate standard deviation
   
Vision
- Camera and OpenCV
   
Lego Car (developed previously)
- a toy model simulating a real life scenario
- color sensor
    
Raspberry Pi
- process data collected by Micro Bit. For this prototype, we are using a MacBook Pro due to computational requirements and connection problems

## Future Applications
1. Auto-driving algorithms
2. AI driving instructors
3. Insurance quotes
