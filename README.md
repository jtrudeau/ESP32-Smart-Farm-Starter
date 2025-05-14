# ESP32 Smart Farm Starter Kit

A sustainable technology solution for STEAM education addressing UN Sustainable Development Goals through innovative microcomputing.

## Project Overview

This Smart Farm project uses an ESP32 microcontroller to create an automated sustainable farming system. Students can learn about electronics, programming, and sustainable agriculture while building a system that monitors environmental conditions and automates farm management tasks.

## Features

- **Environmental Monitoring:**
  - Temperature and humidity sensing
  - Soil moisture detection
  - Water level monitoring
  - Light level sensing
  - Rainwater detection

- **Automated Controls:**
  - LED lighting system
  - Automated irrigation via water pump
  - Cooling fan control
  - Automatic feeding system
  - Alert system with buzzer

- **User Interfaces:**
  - Mobile app control
  - WiFi web interface
  - LCD display for real-time data

## Educational Value

This project helps students:
- Apply STEM concepts to real-world environmental challenges
- Understand IoT (Internet of Things) technology
- Learn programming fundamentals with Arduino
- Develop solutions for sustainable agriculture
- Gain hands-on experience with sensors and actuators

## Sustainable Development Goals Addressed

- **SDG 2:** Zero Hunger - By improving agricultural efficiency
- **SDG 4:** Quality Education - Through hands-on STEAM learning
- **SDG 6:** Clean Water - By optimizing water usage
- **SDG 9:** Industry, Innovation and Infrastructure - Through technology application
- **SDG 13:** Climate Action - By reducing resource consumption

## Getting Started

1. Install the CH340 driver for your system ([Windows](Driver/CH340%20Driver%20File-Windows) / [Mac](Driver/CH340%20Driver%20File-MAC))
2. Set up the Arduino IDE with ESP32 board support
3. Connect the hardware components according to the tutorials
4. Upload the example code for individual components to test functionality
5. Progress to integrated systems (e.g., automatic irrigation, temperature control)
6. Finally build the complete smart farm system

## Repository Structure

- [`CODE_KS0567/`](CODE_KS0567) - Arduino code examples for all modules
  - [`12.1APP-Smart-Farm/`](CODE_KS0567/12.1APP-Smart-Farm) - Complete smart farm system with app control
  - [`11.2WiFi-HTML-Smart-Farm/`](CODE_KS0567/11.2WiFi-HTML-Smart-Farm) - Web interface examples
  - [`7.4Temperature-Control-System/`](CODE_KS0567/7.4Temperature-Control-System) - Temperature monitoring and control
  - [`10.2Auto-irrigation/`](CODE_KS0567/10.2Auto-irrigation) - Automated watering system
- [`Driver/`](Driver) - CH340 USB drivers for Windows and Mac
- [`libraries/`](libraries) - Required Arduino libraries
- [Assembly and Arduino Tutorial.pdf](Assembly%20and%20Arduino%20Tutorial.pdf) - Setup instructions
- [Product List.pdf](Product%20List.pdf) - Components inventory

## Requirements

- ESP32 development board
- Various sensors (DHT11, soil moisture, water level, etc.)
- Actuators (servo, pump, LEDs, etc.)
- Basic electronics tools
- Arduino IDE

## License

This project is intended for educational purposes.

---

*This project was developed for the STEAM Challenge for Sustainability, empowering students to create innovative technology solutions for environmental challenges.* 