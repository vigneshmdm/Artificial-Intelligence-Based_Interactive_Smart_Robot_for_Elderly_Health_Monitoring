# Artificial Intelligence (AI) Based Interactive Smart Robot for Elderly Health Monitoring

## Overview

With the rise in aging populations, there is a growing need for intelligent and accessible health monitoring solutions for elderly individuals. This project presents the development of an AI-based interactive smart robot that leverages IoT, embedded sensors, and Recurrent Neural Networks (RNNs) to monitor and interpret vital health parameters in real time.

The system collects health data through temperature, humidity, and heartbeat sensors connected to a NodeMCU (ESP8266) microcontroller. The data is displayed on an LCD screen and transmitted to a cloud server for remote monitoring. To enhance accuracy, a machine learning algorithm based on RNN is used to analyze the sensor inputs and predict the user's health status. The predictive system improves reliability and helps identify critical conditions early.

This smart health monitoring robot also features interactive components such as a speaker for audio feedback and supports two-way communication via Bluetooth. Alerts are sent to healthcare providers using a GSM module when vital signs cross critical thresholds, enabling timely medical response and remote consultation.

The solution integrates Embedded C (Arduino) for sensor and communication control, and Python for AI-driven predictive analytics, demonstrating a comprehensive and practical approach to elderly care using artificial intelligence and IoT.

## Files Included

- `esp8266_rnn_monitor.ino`  
  Arduino sketch that handles sensor data acquisition, LCD display, HTTP communication, and trigger mechanism for AI prediction.

- `rnn_timeseries.py`  
  Python script that preprocesses sensor data and trains a Recurrent Neural Network (RNN) for time series health prediction.

## Core Technologies

- NodeMCU ESP8266 with Wi-Fi
- Temperature & Humidity Sensor (DHT11)
- Heartbeat Sensor
- 16x2 LCD Display
- GSM Module for SMS Alerts
- HC-05 Bluetooth Module for voice interaction
- Recurrent Neural Network (RNN) using Python and TensorFlow
- IoT cloud integration for remote health tracking

## Acknowledgement

This project is based on the following peer-reviewed paper:

**“Artificial Intelligence (AI) Based Interactive Smart Robot for Elderly People Health Monitoring System”**  
Presented at: *IEEE International Conference on Advances in Computing, Communication and Applied Informatics (ACCAI), 2023*  
[Read the full paper on IEEE Xplore](https://ieeexplore.ieee.org/document/10201135)

Authors: Vasudevan. B, Vignesh Karuppasamy. D. M, Uppuliappan. M

---

## System Architecture

![Block Diagram](images/block_diagram.png)

---

## IoT Web Dashboard

**Health Data Log Interface**  
![IoT Web Logs](images/ui_data_log.png)

**Device Control Panel**  
![IoT Web Switches](images/ui_switches.png)

---

## Robot Prototype

**Top View**  
![Prototype Top](images/prototype_top.jpg)

**Side View**  
![Prototype Side](images/prototype_side.jpg)

---

## Recurrent Neural Network Diagram

![RNN Diagram](images/rnn_diagram.png)

---

## SMS Alert Notifications

![GSM Alert](images/gsm_alert.png)

---

## Bluetooth Voice Command Interface

![Voice App](images/voice_app.jpg)
