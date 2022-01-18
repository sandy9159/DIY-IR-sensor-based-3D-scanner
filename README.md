# DIY-IR-sensor-based-3D-scanner

![image](https://user-images.githubusercontent.com/19898602/149886156-3b7f4e16-ebcf-42cf-9cf9-9ec615e64d51.png)


Hello friends in this project I have made a 3D scanner machine, basically this machine have a sharp IR sensor which measure the distance between sensor and surface of object 

at every 1.8 degree angle in this way it takes 200 readings in 1 full turn of object then sensor itself lift up by 1 mm 

and again take 200 readings in this way a point cloud data is stored in memory card and the point cloud file then imported in MeshLab software and here we can convert into mesh and we can export it STL format also.

# Component reuired

> Arduino Nano
> Custom PCB
> 2 Stepper motor
> 2 A4988 stepper driver
> sharp IR sensor
> Laser diode
> 8mm Smooth rod
> T8 Lead screw
> 3D printed parts
> 8mm linear bearing

# Circuit diagram

I have used my multipurpose PCB for Arduino based resistor reel cutting machine project. If you want to have this PCB
Please find the Gerber file from the link below so that you can order your own PCB
I suggest you JLCPCB.COM to choose your PCB manufacturer they really have very good service and low price
Multipurpose PCB link https://oshwlab.com/sharmaz747/multipurpose-pcb

![image](https://user-images.githubusercontent.com/19898602/147902257-944dde5c-a1d4-4965-8f19-e7afe7c55594.png)


![image](https://user-images.githubusercontent.com/19898602/147902264-771d306d-764e-43c0-839d-90a81e485e16.png)


![FTQFHXZKLBNXU2X](https://user-images.githubusercontent.com/19898602/122632825-db9b8e80-d0f2-11eb-8281-3239f1275adc.jpg)
![147494540_1146948692400891_5797782675789162173_o](https://user-images.githubusercontent.com/19898602/122632834-ee15c800-d0f2-11eb-9385-0bcb4b05119a.jpg)

Making such projects without PCB is night mare yes trust me
you cannot get wanted result and professional touch in your project if you ignore PCB
So some days back I have developed my Multipurpose PCB.
This PCB is used to build wide range of arduino projects 

followings are the some features of PCB

1. Wide range of power input 9V to 24V DC
2. Cross polarity protection
3. DC motor voltage selection 9V or 12 V DC
4. Servo motor voltage selection 5V or 9V DC
5. Manual microstepping setting for stepper motor
6. Power indication LED
7. L298N IC for heavier DC motor
8. ON board 5V and 9V regulator no need to arrange different power sources
9. Header pins and screw terminals for easy connections

List of the Components you can connect to the PCB

1. 2 DC motor ( 9V to 24V DC)
2. 2 Potentiometer
3. 2 Servo motors ( 5V to 9V DC)
4. 1 Serial device (BT module, HMI, Communication module, RX, TX)
5. 1 Encoder (2 interrupt pin & 1 PB pin)
6. 1 I2C device (SCL/SDA Device, display, MPU6050 etc)
7. 2 Stepper motors

![147560983_1146948889067538_4990854912671411429_o](https://user-images.githubusercontent.com/19898602/122632848-fff76b00-d0f2-11eb-955e-207472be636d.jpg)
![component](https://user-images.githubusercontent.com/19898602/122632849-01289800-d0f3-11eb-970a-53fc1b6e0b58.jpg)


I have design circuit and PCB in [easyEDA](https://easyeda.com/) and ordered PCB from [JLCPCB](https://jlcpcb.com/IAT )

This is the link of [PCB editabl file](https://oshwlab.com/sharmaz747/multipurpose-pcb)

If you seriously need quality PCB quickly in your hand then you must have to try [JLCPCB](https://jlcpcb.com/IAT ) PCB manufacturing service.
They have Special offer of $2 for 1-4 Layer PCBs, free SMT assembly monthly.
If you get yourself registered today at [JLCPCB](https://jlcpcb.com/IAT ) you get 27$ welcome coupon from [JLCPCB](https://jlcpcb.com/IAT ).


![image](https://user-images.githubusercontent.com/19898602/147902413-8c479fb7-86f1-4295-b4b9-e4c6cfd24a4a.png)
![image](https://user-images.githubusercontent.com/19898602/147902429-2381ce25-9def-4ef0-b7bf-b4dddc201822.png)
