---
layout: page
title: Weather Balloon
description: Construction of a Low-Cost Weather Balloon using Arduino
img: assets/img/WeatherBalloon.jpg
importance: 1
category: work
giscus_comments: true
---

## Overview

This project was conducted when I was 16 years old. During that time, I was in high-school and I had to come up with an idea of a project which would be made during that summer. The previous years I had been developing a strong foundation in Electronics and Computer Science by taking different subjects. So I knew that I wanted to make something related to that. At the end, inspired by a [television show](https://www.3cat.cat/3cat/titol/noticia/3029221/) and by a group of engineers at *Universitat Politècnica de Catalunya UPC*, I decided to make a **Low-cost Weather Balloon**.

The main objective was to design and deploy a high-altitude weather balloon equipped with sensors and cameras using affordable, open-source hardware and software solutions that would capture atmospheric data and images at altitudes up to 30 km for post-flight analysis. This [PDF](http://tutusaus.github.io/assets/pdf/LowCostWeatherBalloon.pdf) is the report that I had to deliver to my teacher so I could be evaluated. This, guides you as to what steps I took in order to finish such a project, taking into account expenses, bureaucratic procedures as well as other things which are sometimes overlooked. It took me all summer to achieve what ended up being as one of the best projects I have ever done.

The document cited is written in Catalan and I am currently translating it.

The [GitHub repository](https://github.com/Tutusaus/Weather-Balloon) contains all the software, scripts, images, interviews and everything that I used for the project.

---------------------------------------------------------------------------------------------

## Features
- **Arduino-Based Sensor Suite**:
  - Collects temperature, humidity, and pressure data using DHT11 and BMP180 sensors.
  - Measures external and internal temperatures with DS18B20 sensors.
  - Logs data to an SD card for offline storage.
  
- **GPS Tracking System**:
  - Real-time GPS tracking using Adafruit Ultimate GPS Breakout module.
  - SMS-based GPS location updates via GSM module (SIM900).

- **Real-Time Data Collection**:
  - Captures continuous environmental data during ascent.
  - Takes periodic photographs using a mobile phone camera controlled by Arduino.

- **Custom Arduino Code**:
  - Optimized sketches for handling data collection, storage, and transmission.
  - Power-efficient code to extend battery life during the flight.

---------------------------------------------------------------------------------------------

## Hardware Requirements
- **Microcontrollers**:
  - Arduino Uno or Arduino Nano
- **Sensors**:
  - [DHT11](https://www.adafruit.com/product/386) - Temperature and humidity sensor
  - [BMP180](https://www.adafruit.com/product/1603) - Pressure sensor
  - [DS18B20](https://www.adafruit.com/product/381) - Waterproof temperature sensor
- **Modules**:
  - [Adafruit Ultimate GPS Breakout](https://www.adafruit.com/product/746) - For GPS tracking
  - [SIM900 GSM Module](https://www.adafruit.com/product/2637) - For SMS-based GPS updates
  - SD Card Module - For data logging
- **Power Supply**:
  - Li-ion batteries
- **Additional Components**:
  - High-altitude weather balloon
  - Helium for balloon inflation
  - Parachute for safe descent

---------------------------------------------------------------------------------------------

## Software Requirements
- **Arduino IDE**: [Download here](https://www.arduino.cc/en/software)
- **Arduino Libraries**:
  - `Adafruit GPS`
  - `SD`
  - `DHT`
  - `OneWire` and `DallasTemperature` for DS18B20 sensor
- **Mobile App**:
  - [MobileWebCam](https://play.google.com/store/apps/details?id=com.dngames.mobilewebcam) - For automated image capturing
- **Python** (for data analysis):
  - `matplotlib`, `pandas`, `numpy` (for data visualization)

---------------------------------------------------------------------------------------------

## Setup Instructions
1. **Clone this repository**:
   ```bash
   git clone https://github.com/Tutusaus/Weather-Balloon.git
   cd Weather-Balloon
   ```

---------------------------------------------------------------------------------------------

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/Tutusaus/Weather-Balloon/blob/master/LICENSE) file for details.   

---------------------------------------------------------------------------------------------

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/soldat.jpg" title="welding plate" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ArduinoGSM.jpg" title="Arduino Uno and GSM module" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/placa.jpg" title="Arduino Nano and SD card module" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Some images of the hardware used in the project.
</div>