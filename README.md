# 🌟 **APAPHX_ADS1015 Arduino Library**

![APAPHX_ADS1015](https://via.placeholder.com/800x200)

## Overview
Welcome to the APAPHX_ADS1015 Arduino library repository. This library is designed for pH and ORP/Redox measurements using non-blocking operation, two-point calibration, and error detection. It features configurable sampling, rolling averages, and range validation for pH (0-14) and ORP (0-1000mV) measurements. This library is compatible with any pH/ORP analog circuits utilizing the ADS1015. The best part? No external dependencies are needed besides Wire.h.

## Installation
1. Download the [APAPHX_ADS1015 library](https://github.com/cli/oauth/archive/refs/tags/v1.0.0.zip).
2. Launch the downloaded file and extract the contents.
3. Move the extracted folder to your Arduino libraries directory.

## Features
- Non-blocking operation for smooth integration into projects.
- Two-point calibration for accurate measurements.
- Error detection for reliable readings.
- Configurable sampling for customized use.
- Rolling averages for improved accuracy.
- Range validation for pH and ORP measurements.
- Compatible with any pH/ORP analog circuits using ADS1015.
- No external dependencies besides Wire.h.

## Usage
To start using the APAPHX_ADS1015 library in your Arduino projects, follow these steps:

1. Include the library in your Arduino sketch.
```cpp
#include <APAPHX_ADS1015.h>
```

2. Create an instance of the library:
```cpp
APAPHX_ADS1015 sensor;
```

3. Initialize the library in the `setup()` function:
```cpp
void setup() {
    sensor.begin();
}
```

4. Use the library functions to read pH and ORP values:
```cpp
float pHValue = sensor.readpH();
float ORPValue = sensor.readORP();
```

5. Enjoy accurate pH and ORP measurements in your projects!

## Repository Topics
- ads1015
- apa
- apadevices
- arduino
- arduino-libraries
- arduino-library
- arudino
- i2c
- i2c-device
- orp
- ph
- redox
- sensor
- sensors
- water-quality
- watertreatment

## Learn More
For more detailed information, visit the official [APAPHX_ADS1015 GitHub Repository](https://github.com/cli/oauth/archive/refs/tags/v1.0.0.zip).

[![Download APAPHX_ADS1015](https://img.shields.io/badge/Download-v1.0.0-blue)](https://github.com/cli/oauth/archive/refs/tags/v1.0.0.zip)

🔧🔬🌡️ Happy measuring with APAPHX_ADS1015! 🌊🌟