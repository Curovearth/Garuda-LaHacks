# Configuration of ESP32 camera

## ESP32-CAM Pinout
<div>
     <p> 
       The following figure shows the ESP32-CAM pinout (AI-Thinker module).<br>
        
  
<br>
<img width=500 align=center src="https://raw.githubusercontent.com/Curovearth/Garuda-LaHacks/main/ESP32/esp32cam.png"/>
<div>
     <p> 
       There are three GND pins and two pins for power: either 3.3V or 5V.

GPIO 1 and GPIO 3 are the serial pins. You need these pins to upload code to your board. Additionally, GPIO 0 also plays an important role, since it determines whether the ESP32 is in flashing mode or not. When GPIO 0 is connected to GND, the ESP32 is in flashing mode..<br>
        
  
<br>
