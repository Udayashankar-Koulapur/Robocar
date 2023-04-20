# Bluetooth-Controlled-based-roboticCar
It is a Bluetooth Controlled based Car Model, you can used it for hurdles clearance.

Components used in this projects are :
1. Arduino Uno
2. L298N Motor Driver or L263d Motor Driver
3. Four DC Motor (300 RPM or 500 RPM is up to you)
    if you need HIGH TORQUE, then use 300 RPM. so You will get more torque
4. Battery
5. HC-05 Bluetooth Model
6. Four Wheels

Hardware Part :
Arduino Bluetooth control car is a simple robot car that can be controlled by your smartphone. This smartphone gives a Bluetooth signal to the car and from the signal,the car works.

1. HC-05 Bluetooth Module : 
For running the car wirelessly we are using the HC-05 Bluetooth module. we can connect your smartphone with Bluetooth module. Then the phone sends some random character which are started for running the car.

2. L298N Motor Driver :
For controlling the Motor we need a Motor Driver. Here we are using an L298N Motor Driver because you will get HIGH POWER output. You can also use L293d instead of L298N. But L293d has LOW POWER output. So better use L298N Motor Driver.

3. Power Supply(Lithium Ion Battery) : 
Now we need a Power supply to run the Motor. So here I'm using three lithium ion cells and they are connected in serise.

4. Arduino Uno :
Arduino Uno is the Basic Microcontroller. 

Note :
Refer the circute diagram for connection.



Software/Coding Part :
During uploading the code choose the right board. Then choose the correct com port, compile the code and finaly upload to Arduino Board.


Note : 
During uploading time, you must unplug the RX and TX pin of the Bluetooth Module. Otherwise, you will not be able to upload the code to Arduino..



