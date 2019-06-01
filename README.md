# esp_softAP_home_automation
Controlling 4 relays using a NodeMCU in WiFi soft access point mode.

  STEPS to ensure that you upload your code smoothly into your NodeMCU using arduino IDE in windows 10:
  
  
  Step1:
        Download and install the drivers required to flash your NodeMCU using your PC. It can be the CP2102 drivers
        or CH340 drivers depending on the model that you are aiming to program.
  
  
  
  
  Step2:
        Open the arduino IDE and paste the following link in additional board managers and URLs in File->Preferences->Setting.
        http://arduino.esp8266.com/stable/package_esp8266com_index.json
  
  
  
  
  Step3:
        Go to Sketch->Include library->Manage Libraries and download the Wi-Fi libraries for ESP-12E.
  
  
  
  
  Step4:
        Start programming by connecting the NodeMCU to your PC using a USB cable. Selecting the correct COM port and baud rate(generally           115200 in most cases).
