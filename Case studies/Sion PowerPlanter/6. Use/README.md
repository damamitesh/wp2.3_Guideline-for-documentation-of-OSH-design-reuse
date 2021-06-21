 #### 1. Description of product
 
N/A
     
 #### 2. Use of product
 
  * Materials required
      * Software
   
  * Procedure
  
     * Install the software:
      
  To install the software on the EPS32 you can use the free "Arduino IDE". If you don't have it, you can get it here for free: https://www.arduino.cc  /en/software

  Load the code (powerplant.ino, version number may vary, higher is better) from GitHub:
https://github.com/munichseb/powerplant and open it in the Arduino IDE.

  Connect the ESP32 to your computer, and select the correct device in the "Tools" section. It should look like this:
  
 [Selection of the correct device in the "Tools" section](https://wikifactory.com/files/RmlsZTo1NzE4NDc=)
 
 ![image](https://user-images.githubusercontent.com/59058909/122737358-3fec5880-d281-11eb-81fd-1ac220b75c09.png)

 
 If the "Wemos D1" is not avilable, go to "Board administation" in the same menu, and install the ESP32 set. Make sure the "Port" selection is pointing to the device (there is one selection in the list that looks weird, this is the one).

Now comes a very important step: click on "Tools" / "Serial Monitor" and open the serial monitor. It will open a second window. Leave it like it is.

Click on "upload" in the IDE, and the sketch will be uploaded. Your device should reset and the LEDs should shine in magenta. Congrats! You have a working Powerplanter device!

Now head to the serial monitor window. You should see a line like this:

Device ID: SINSLRCR

The 10 digit code it your unique device ID. Write it down. Copy it and send it to you via E-Mail. This is an important key to your device.
    
   * Setup instruction: 
    
 When the device is shining in magenta, it means that everything is fine, but it cannot connect to the internet. To get it online, use your smartphone or your tablet (Android, iOS, all fine) and look for a new wifi network you have not seen before. The new network is from your powerplanter device.

If you connect to it, it will present you a configuration interface:

![image](https://user-images.githubusercontent.com/59058909/122736953-d8cea400-d280-11eb-9bfe-d77c418d32dd.png)

Select "Configure Wifi (Auto Scan)" to get a list of all available WiFi-Networks the device can see.

![image](https://user-images.githubusercontent.com/59058909/122737180-129faa80-d281-11eb-92ee-429594199952.png)

Pick your WiFi, enter your credentials. The device should now get online immediately. As soon as it online, the color will change from magenta to white. You are all set!

![image](https://user-images.githubusercontent.com/59058909/122737991-dfa9e680-d281-11eb-9938-0c07a54a3a42.png)


#### 3. Update of firmware

N/A

#### 4. Troubleshooting

N/A

#### 5. Repair information

N/A

#### 6. Reporting problems

N/A
