pressure-sensitive-smartcoaster
===============================

a drink coaster that is sensitive to pressure, hardware created with arduino, interface with Actionscript 3. Video available here: 

https://www.youtube.com/watch?v=mVF8kK9JGSc&feature=youtu.be

The first step of the project was to create the Arduino code to trigger the different colours of the RGB LED based on different amounts of pressure detected by the FSR. 

Once that was worked out it was a simple matter of modifying the Standard Firmata Code so that the LED would be triggered at the same time as the apparatus is communicating with the Flash interface. 

To create the interface I modified Kasper Kampermann's code from  http://www.kasperkamperman.com/blog/arduino/arduino-flash-communication-as3/.

The interface is a visualization using custom graphics that displays a virtual glass on screen with different levels of virtual beer inside depending on the amount of pressure applied to the FSR. 

