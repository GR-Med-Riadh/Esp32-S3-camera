# Esp32-S3-camera

JLCPCB is a company that constructs PCBs and prints 3D mechanical designs, they give us great offers with cheap prices for high quality precision PCBs. I would like to thank JLCPCB for their sponsorship and for supporting me in creating and innovating schematics, and improving my PCBs designs.

Artificial intelligence now is a tendency of our cycle. Most electronics companies work on chips or microcontrollers have AI calculators with minimum specification and more performance.

AIOT is the combination of Artificial intelligence (AI) technologies with the Internet of things (IoT) infrastructure to achieve more efficient IoT operations,improve human-machine interactions and enhance data management and analytics.

After the big success that the ESP32-S3 got, it's time for the new revolution ESP32-S3 Camera.

 ESP32-s3 is a dual-core XTensa LX7 MCU, capable of running at 240 MHz. Apart from its 512 KB of internal SRAM, it also comes with integrated 2.4 GHz, 802.11 b/g/n Wi-Fi and Bluetooth 5 (LE) connectivity that provides long-range support. It has 45 programmable GPIOs and supports a rich set of peripherals.it supports larger, high-speed octal SPI flash, and PSRAM with configurable data and instruction cache.

This pcb is designed for AI uses,it could be divided into différents parts.
First, The Microcontroller ESP32-S3 has an Artificial internet of things calculator (AIOT),So it helps us to implement Ai and IOT in this chip, to use AI in this microcontroller we need to use tensorflow lite or micro.
TensorFlow is a free and open-source software library for machine learning and artificial intelligence. It can be used across a range of tasks but has a particular focus on training and inference of deep neural networks but this version is applied in computers, jetson nano, raspberry… because it contains a suffisant ram for it. In our case we used the  optimized version of TF.
TensorFlow Lite (TFLite) is a collection of tools to convert and optimize TensorFlow models to run on mobile and edge devices. It was developed by Google for internal use and later open-sourced.

Then,it contains USB for OTG and FTDI pins for UART communication,it's peer to peer communication, It used for uploading code, and using Serial monitor/ Serial plot to show  or send résults

The camera support makes the big difference with the latest ESP32-S3, it’s the support of ESP32-S3 eye,It's the bridge between external world and Microcontroller.

Finally, we use regulators to adapt our voltage with the power supply of the circuit.

you could see our results plotted in Plot Serial of arduino ide, It represents percentage of a person detection.

JLCPCB link: https://jlcpcb.com/HAR


