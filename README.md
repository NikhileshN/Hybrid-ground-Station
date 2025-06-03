# Hybrid Ground Station Communication System

This project implements a hybrid ground station communication system using Raspberry Pi and NRF24L01+ modules to simulate communication with two CubeSat transmitters. Each CubeSat is equipped with a DHT22 sensor that collects environmental data (temperature and humidity) and transmits it wirelessly to a central ground station. The ground station receives the data and displays it on an I2C-connected LCD screen in real time.

## Features

- Wireless communication between CubeSats and ground station using NRF24L01+ modules
- Real-time environmental data collection using DHT22 sensors
- Data display on a 16x2 I2C LCD at the ground station
- Support for multiple transmitters

## Hardware Requirements

- 3 x Raspberry Pi boards (2 transmitters, 1 receiver)
- 3 x NRF24L01+ transceiver modules
- 2 x DHT22 temperature and humidity sensors
- 1 x 16x2 I2C LCD display
- Jumper wires and breadboards

## Software Requirements

- Python 3.x
- Libraries:
  - Adafruit_DHT
  - RPi.GPIO
  - RF24
  - RPLCD

Install Python libraries using pip:

```bash
pip install Adafruit_DHT RPi.GPIO RPLCD
