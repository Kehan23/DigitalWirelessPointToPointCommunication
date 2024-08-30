# Communication System Design

## Contents

1. [Overview](#1-overview)
2. [Project Approach](#2-project-approach)
3. [Challenges & Future Work](#3-challenges--future-work)
4. [Contributors](#4-contributors)

## 1. Overview

This project involves the design and implementation of a digital wireless communication system using GNU Radio and bladeRF 2.0 micro xA9 hardware. The system is designed to transmit and receive different types of data, including:

- Text files
- Image files
- Audio files

The primary objective was to transmit data between two laptops using bladeRF hardware, with varying distances to analyze the effects of noise, attenuation, distortion, and other environmental factors on the transmission quality.

## 2. Project Approach

### **Modulation Scheme: QPSK**

- **Simulation:** The transmitter and receiver were successfully simulated on a single laptop, allowing for the transmission and reception of text, image, and audio files.
  
- **Physical Transmission:** The physical tests involved using bladeRF for transmission and an RTL-SDR for reception. 

  - **Text and Image Files:** These files were successfully transmitted and received, although noise and environmental impacts introduced noticeable errors in the data.
  - **Audio Files:** The transmission of audio files was heavily impacted by noise and other factors, resulting in unsuccessful transmission and a high Bit Error Rate (BER).

## 3. Challenges & Future Work

The experiments revealed that the noise and environmental parameters significantly affected the quality of the transmission, especially for audio files. The BER was too high for reliable communication, indicating the need for further refinement. Future improvements will focus on:

- Implementing better error correction and noise reduction techniques
- Exploring encryption methods to enhance the robustness of the communication system

## 4. Contributors

- [Manamperige Kehan Anjula](https://github.com/Kehan23)
- [Javin Manatunge](https://github.com/javin-5)
- Shenal Ranasinghe
- Selaka Deemantha

The design encompasses the entire system, from the foundational blocks that define key parameters to the intricate components of the transmitter and receiver. Each part is carefully crafted to ensure seamless communication and reliable data transmission.

![Entire Design](https://github.com/Kehan23/DigitalWirelessPointToPointCommunication/blob/main/Images/overall%20com.png)
