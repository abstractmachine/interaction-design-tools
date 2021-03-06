### Arduino
Arduino allows you to create interactions with the physical world. It is *the* starting point for most interaction desginers learning to make reactive physical objects or experiences.

<https://www.arduino.cc>

You should always have an Arduino Uno or an Arduino Leonardo at your disposal, along with a basic set of core electronics such as a breadboard, wires for prototyping, buttons, LEDs and a servomotor or two.

- [Arduino Leonardo](https://store.arduino.cc/arduino-leonardo-with-headers)
- [Arduino Uno](https://store.arduino.cc/arduino-uno-rev3)

There are many starter kits containing everything you need to get started (circuit + electronic components):

- [Elegoo Starter Kit](https://www.amazon.fr/Elegoo-Démarrage-dUtilisation-Débutants-Professionnels/dp/B01JD2Z5XW?ref_=ast_sto_dp)

Download the Arduino software here:

<https://www.arduino.cc/en/software>

Arduino is simple software, so it's great for beginners. But you can also use VS Code (cf. [code](03_code)) to program your Arduino projects using the [Arduino extension for VS Code](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino).

If you already feel comfortable with the Arduino platform, and wish to have access to more advanced features such as wifi or bluetooth, you can opt instead for an ESP32-based microcontroller:

[ESP-32 Microcontrollers](https://en.wikipedia.org/wiki/ESP32)

There is a really cool and really cheap all-in-one ESP32-based microcontroller called the TTGO T-Display that integrates an Arduino-programmable circuit with a tiny LCD screen, bluetooth and wifi connection, as well as an integrated connector for rechargeable lipo batteries that can be recharged via an integrated USB-C connector. In other words, you can build an entire portable Game & Watch style console via this solution that costs somewhere around 10 CHF:

[Lilygo TTGO T-Display](http://www.lilygo.cn/prod_view.aspx?TypeId=50044&Id=1126&FId=t3:50044:3)

### Raspberry PI
An alternative to Arduino-based electronics is the Raspberry PI, which is more or less a fully functional Linux computer inside a small form factor, along with a similar system of "pins" for connecting sensors and actuators as Arduino. If you need more processing power, or need to run software like a web browser, or some other PC-style application like video or audio processing, you can use a Raspberry PI.

The [Raspberry PI](https://www.raspberrypi.org) foundation is organized around the principle of open-source, with a strong education and DIY-oriented mindset. So it's great for hacking bespoke, particular applications. And they are cheap.

I have written a how-to guide for starting with the Rapberry PI from scratch and ending up with a fully-functional video-player, or a more sophisticated solution using OpenCV to capture a video input and control some form of electronics with the Raspberry PI :

- [Raspberry Video Player](https://github.com/abstractmachine/Raspberry-Video-Player)
- [RPI 4 Computer Vision Setup](https://github.com/abstractmachine/RPI4-OF11-OpenCV4.5-Instructions)

### Fritzing
Yes, you can design your own circuitboards. You can even integrate them into your own custom housings (cf. (tutorial:CAD link:tools/3d-cad) Tools) that you print out using various prototyping methods.

[Fritzing](https://fritzing.org) is a simple, easy to learn software tool for creating your own custom Printed Circuit Board (PCB) designs.

### KiCAD
This is an open-source project slowly emerging as the de-facto hobbyist+professional tool for designing Printed Circuit Boards (PCB). It requires a strong understanding of electronics, and is very much the professional upgrade from Fritzing (cf. above). Another solution is (tutorial:Fusion 360 link:tools/3d-cad) that integrates a PCB design environment inside of a larger 3D CAD tool.

[KiCAD](https://www.kicad.org)
