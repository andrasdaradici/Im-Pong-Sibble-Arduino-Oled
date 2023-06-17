# Im-Pong-Sibble-Arduino-Oled

Im-Pong-Sibble ported to Arduino on a 1.3-inch SSD1306 OLED display using two Analog Joysticks for control.

# Components required
- Arduino Nano
  - Link: https://www.aliexpress.com/item/4000579100527.html
- Dual-axis joystick (2 or 1 piece, depending on which file/mode you're using)
  - Link: https://www.aliexpress.com/item/32672164557.html
- Passive Buzzer Module
  - Link: https://www.aliexpress.com/item/32720786204.html
- 1.3-inch SSD1306 OLED
  - Link: https://www.aliexpress.com/item/32879702750.html  

# Features
- 1-player endless mode against an unbeatable opponent
- 2-player mode

# Showcase
- You can check a video to see what the game looks like on my father's channel
  - Only 1-player mode:
    - Test: [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/JdPYtcu4LfI/0.jpg)](https://www.youtube.com/watch?v=JdPYtcu4LfI)
    - Link: https://youtu.be/JdPYtcu4LfI
  - 1-player and 2-player modes:
    - Link: https://youtu.be/-K7Vt8vrE0U

# Wiring
## On the left side you can see the ports of the component, on the right side you can see the ports of the Arduino.

- OLED screen
  ```VDD --- 3.3V
  GND --- GND
  SCK --- A5
  SDA --- A4

- Joystick 1
  ```+5V --- 5V
  GND --- GND
  VRX --- A0
  VRY --- A1
  SW --- D2

- Joystick 2
  ```+5V --- 5V
  GND --- GND
  VRX --- A2
  VRY --- A3
  SW --- D4

- Piezo
  ```VCC --- 5V
  GND --- GND
  I/O --- D3
