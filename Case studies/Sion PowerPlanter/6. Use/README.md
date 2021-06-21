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
 
 If the "Wemos D1" is not avilable, go to "Board administation" in the same menu, and install the ESP32 set. Make sure the "Port" selection is pointing to the device (there is one selection in the list that looks weird, this is the one).

Now comes a very important step: click on "Tools" / "Serial Monitor" and open the serial monitor. It will open a second window. Leave it like it is.

Click on "upload" in the IDE, and the sketch will be uploaded. Your device should reset and the LEDs should shine in magenta. Congrats! You have a working Powerplanter device!

Now head to the serial monitor window. You should see a line like this:

Device ID: SINSLRCR

The 10 digit code it your unique device ID. Write it down. Copy it and send it to you via E-Mail. This is an important key to your device.
    
   * Setup instruction: 
    
 When the device is shining in magenta, it means that everything is fine, but it cannot connect to the internet. To get it online, use your smartphone or your tablet (Android, iOS, all fine) and look for a new wifi network you have not seen before. The new network is from your powerplanter device.

If you connect to it, it will present you a configuration interface:

[Selection of the correct device in the "Tools" section](https://wikifactory-prod-uploads.oss-accelerate.aliyuncs.com/128858/bildschirmfoto-2021-04-02-um-230947.png?response-content-type=image%2Fpng&response-content-disposition=attachment%3B%20filename%3D%22Bildschirmfoto%202021-04-02%20um%2023.09.47.png%22&AWSAccessKeyId=LTAI4GK1mTcvu7wXYTXXtiy6&Signature=cjnjcDyWlOM6MZFxxxssfEdskqI%3D&Expires=1624014055)
#### 3. Update of firmware
#### 4. Troubleshooting
#### 5. Repair information
#### 6. Reporting problems
