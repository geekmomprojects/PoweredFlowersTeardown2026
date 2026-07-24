# WLED links and configuration files

Find the access point for your board - default name is **WEAR-WLEDXX** where **XX** is the one or two digit number on the sticker on the board. The default password is **wled1234**. Connecting to it should bring up a captive portal with the control web page, but if not, open a browser and go to IP address **4.3.2.1** in the address bar.

- The ESP32s we used are pre-flashed, using the installer at [WLED Installation Website](https://wled-install.github.io/), with the **Nightly Build 16.x branch** version, and the **ESP32 C3 4MB Flash with Audio Reactive Usermod**
   option under that version
-  Files for installing the presets and configurations are included, and set up WLED with 10 WS2812 LEDs on **pin 8**, and a push button on **pin 9**
- An I2S microphone is configured as well.
   
