# LBseries

The LB chip is a small chip concept that will flash the LED based on the voltage applied to it. Uses only a few components and can be made easily. This repo consists all of the changes, basic components, updates and other details related to the project.

More details about the maker and this project can be found at https://www.esccrasci.in and at www.youtube.com/c/esccrasci

This chip has 5 versions:<br>
- V1.0.0-The very first version
- V1.0.1-2nd edition with minimal changes
- V1.0.2-3rd edition with better structuring but with major flaws
- v1.0.3-4th edition with physical changes but with fatal circuit flaws.

**V1.0.0**

Basic version with single LED flashing capabilities. 

Pros:

- Can flash the LED at different frequencies based on input voltage

- Small size factor only taking 10-12cms in area.

Cons:

- Bad timing and frquency control

- Structural issues-size-alignment

- Voltage vulnerabilities ( cannot handle 1 volt higher than 20 volts)

Image:
![alt text](https://github.com/ESCcrascirepository/LBseries/blob/main/V1.0.1/4.jpg?raw=true)

**V1.0.1**

This is the second version with many major improvemnets but with the addition of different flaws

Pros:

- Can flash the LED at better frequencies which are accurate

- Mild reduction in voltage consumption

- Size made smaller in X and Y axis

- Can work with voltages between 11-20 volts

Cons:

- Cannot handle high volatge and high current LED's

- Voltage change can be fatal if increased above the limit

- Cannot work with SMD LED's due to sudden changes in the voltage

Image:
![alt text](https://github.com/ESCcrascirepository/LBseries/blob/main/V1.0.1a/1.png?raw=true)





