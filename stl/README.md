# 3D Printing Files

This folder contains all the files to print a HullPixelbot and accessories. You don't need to print them all to make a robot. Here are the ones that you need. 

## chassis - Basic HullPixelbot chassis

The basic HullPixelbot chassis just holds the motors, batteries and processor. You can start with this and then add the pixel and other items later. 

- base: this is the base of the HullPixelbot. You attach the motor supports, the stepper driver boards and the skid to the base. You need to print one of these.  The base can be fitted either way up. One way it has mounting pillars for an Arduino Uno or compatible, the other way up you can stick a breadboard on the top of the robot. 

- top: this is the top of the HullPixelbot. It holds the processor. You'll need to print one of these. 

- motorTowerLeft and motorTowerRight: these provide the sides of the robot. You attach the motor to a tower, which is then bolted to the base. 

- wheelLeft and wheelRight: these are the wheels for the robot. The wheels fit onto the shafts of the stepper motors and can be further secured with a bolt. 

- skidFront and skidBack: this is the skid that goes underneath the robot base. You can fit a 10mm ball bearing (or catapult ammunition) into the skid to provide a bearing surface for when the robot moves. You'll need to print two of these.

## ringLed - Pixel ring Display

The pixel display is a holder for a pixel ring that is mounted on top of the robot. There are two supports for the pixel, a cross piece that holds the pixel ring and a shade which fits over the top.

- ledSupportLeft and ledSupportRight: these are mounted on the base plate (using the bolts that secure the base plate to the motor towers. Each  contains a small square hole into which the cross-support piece fits. They also serve as a handles you can use to pick the robot up.

- ringCrossSupport: this is mounted between the handle support elements and holds a ring of Neopixel devices. The square pegs at each end of the cross support enage with the holes in the handle support.

- ringShade: this is the shade for the pixel ring. It can be printed using clear or white filament and will serve as a diffuser for the lights. It is a push fit onto the ringCrossSupport. Use your printer settings to print a single layer for best results.

- ledPipeShade: this is an alternative shade for the pixel ring. It contains a "light pipe" for each of the 12 leds in the ring. This can be used to get a different visual effect for the robot pixel, and also to make it easier for optical tracking of individual led elements in the single large pixel. 

## singleLed - single pixel display

This provides mountings for a single pixel that is mounted above the robot. It contains the same 
- ledCrossSupport: this is an alternative to the ring version which only holds a single pixel. 

- shade: this is a shade for a single pixel. It is a push fit onto the single pixel shade base.

- shadeBase: this holds the design for base that can hold a single Neopixel and be bolted to the rear of the robot base.

## Distance Sensor

You can fit a distance sensor on the front of your robot. The sensor also has fittings for three lignt sensors. It bolts into holds on the base of the robot. It is in the file distanceSensorHolder

## Power Switch Holder

If you wish to add a rocker switch to turh the robot on and off you can use this holder to hold the switch, which can then be bolted to the back of the robot. It is in the file powerSwitchHolder.

## Breadboard shelf

If you have constructed your robot using an Arduino and want to add a second processor the breadboard shelf can be printed and mounted above the Arduino using the same bolt holes. You can then stick a small breadboard to the shelf and connect it to the Arduino underneath.

## Cheese Plate

If you want your robot to be able to carry cheese around you can print a cheese plate that fits around the large pixel ring and lets you move small pieces of cheese around. 







