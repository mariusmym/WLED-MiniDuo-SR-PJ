# WLED-MiniDuo-SR-PJ
ESP32-powered WLED board with sound reactive capabilities and a 6.5mm power jack 

![IMG_7980](https://github.com/user-attachments/assets/fba4d508-bf65-4818-abaf-03b0f6912378)
 
## MAIN FEATURES :

- 2 Channels - Control two separate LED strips however you want.
- Supports 5V - 24V -  No more power worries - use the LEDs that fit your project!
- DC Power Jack – 2.5mm×6.5mm jack makes connecting power adapters easier and more reliable
- Wi-Fi & OTA Updates – Set it up once, tweak it anytime - no hassle.
- Perfect for WS2812/B, SK6812 & more – Smooth animations, stunning effects!
- Use an INMP441 module to enable sound-reactive capabilities. https://www.aliexpress.com/w/wholesale-INMP441-module.html

<img width="1280" height="400" alt="Screenshot 2025-11-16 160859" src="https://github.com/user-attachments/assets/ea30f9b8-9447-48f9-a4c9-d8400790152c" />

  
## IMPORTANT INFORMATIONS ! ⚠️

  1.**Make sure your power supply voltage matches your LED strip voltage** (for example: 5V LEDs → 5V power supply, 12V LEDs → 12V power supply, 24V LEDs → 24V power supply).
**The onboard voltage regulators only provide power for the ESP32 and the level shifter - they do not convert or regulate power for the LEDs. As you can see in the image below, the voltage from power jack goes through the resettable fuse and then goes directly to the LED VCC pin in the back of the board.**
![cd48d32c68e24dc4ab7b51e82c295eb8](https://github.com/user-attachments/assets/cbc363d5-15ae-460f-8229-07210f06c6d6)

2. Please make sure your power adapter matches the jack size (2.5mm×6.5mm).
Also please keep in mind that the DC-DC power jack I used can handle **up to 5A**, so ensure your setup does not exceed this limit.

3. You will need a **USB-to-TTL/UART converter** for the initial flashing of the software. Alternatively, you can build / order this handy CH340C adapter with an auto-reset function: https://oshwlab.com/mariusmym/ch340c_auto-reset
4. If you are using a standard USB-to-TTL/UART converter (such as the common CH340 modules found on AliExpress), **make sure you supply +3.3V to the ESP via 3V3 pin**, cross RX and TX connections, press and hold BOOT button, **then power up the board** and only after release the button, and proceed to upload your firmware.
 

## Installer website ⚙️: 
https://install.wled.me/

For more information about the WLED project, check out the official page: https://kno.wled.ge/
Also don`t forget to show your appreciation to Aircoookie and the whole team for his awesome work!

## WLED App 📱:

- Google Play:  https://play.google.com/store/apps/details?id=ca.cgagnier.wlednativeandroid
- Apple App Store: https://apps.apple.com/us/app/wled-native/id6446207239
 
## WS2812B LED strip 🎆: 
used in the photos can be found here (black wire – 20 m length):
https://www.aliexpress.com/item/1005005598428130.html

 ## 3D printable case🧩:
https://www.printables.com/model/1232890-wled-sound-reactive-controller-mini-esp32-32de-cas

Project can also be found here: https://oshwlab.com/mariusmym/wled-miniduo-sr-pwr_jack-pro-v1-3


☕ If you'd like to say thanks or buy me a coffee, a PayPal donation is always appreciated!

Have fun and enjoy it ! 😊


