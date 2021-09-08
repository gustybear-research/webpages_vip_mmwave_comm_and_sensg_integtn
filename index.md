---
draft: true
title: "V2SX: Integrate mmWave Vehicular Communication with Radar Sensing"

subtitle: "Vertically Integrated Project (VIP), Spring 2022 - present"

summary: "This project aims to develop mmWave communication systems with integrated radar sensing functionality to address the coexistence challenge between vehicular communication and automative radar sensors operating within the mmWave spectrum."

tags:
- autonomous vehicle
- v2x
- mmwave communication
- mmwave sensing
- los mimo
#- active project
#- active VIP project

date: 2021-09-02T00:00:00-10:00

authors:
- Yao Zheng
- Yingfei Dong
- Aaron Ohta
- Wayne Shiroma
- June Zhang

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
placement: 3
caption: ""
focal_point: "Center"
preview_only: true
alt_text: " "

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
- name: CRN
  url: ./project/research/vip_mmwave_comm_and_sensg_integtn/#logistics
#- name: PUB
#  url: ./publication/zheng-insider-resistant-context-based-pairing-2021/
#- name: Slides
#  url: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/presentation/EE496%20Poster_%20SIENNA.pdf
#- name: Dataset
#  url: https://github.com/gustybear-research/x96_wirles_physllgcl_sensing



# Markdown Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

gallery_item:

---
***
# Executive Summary
 As autonomous vehicles revolutionize our transportation ecosystem, Millimeter-wave (mmWave) communication is a promising technology to meet the data rate demand of V2X (vehicle to everything) networks. This project aims to design an integrated sensing and communication (ISAC) system for V2X network using mmWave MIMO (multiple-input and multiple-output) to deliver accurate radar sensing and reliable communication in a high-mobility environment. 

***
# Introduction
 Autonomous vehicles are revolutionizing the transportation ecosystem. With the assistance of Artificial Intelligence algorithms, these vehicles can interpret volumes of real time information shared through a Vehicular-to-Everything (V2X) network to anticipate and respond to driving condition changes, achieving safety and reliability beyond human drivers. However, the required data rate for V2X to transmit large messages, containing processed sensor data, raw sensor data, vehicles’ intention data, coordination, confirmation of future maneuvers, etc., is over the capacity of sub-6GHz wireless link [1] [2].
 
Millimeter-wave (mmWave) communication is a promising technology to meet the data rate demand of a V2X network due to its large fractional bandwidth. Unfortunately, mmWave bands, particularly between 24 to 32 GHz, are ideal for short-range radar sensing that are also essential for autonomous vehicles. A standalone V2X network in these bands would increase the spectrum congestion, leading to suboptimal performance for both communication and radar sensing operations. To address this conflict, this proposal aims to design an integrated sensing and communication (ISAC) system for V2X network using mmWave MIMO (multiple-input and multiple-output) and deliver accurate radar sensing and reliable communication in a high-mobility environment. Three complimentary thrusts are detailed below to realize the proposed system.
 
Improve mmWave MIMO Channel Condition with IRS. This thrust investigates the design and use of (vehicle-mounted) intelligent reflecting surface (IRS) to increase mmWave scattering between V2X nodes and support effective MIMO spatial multiplexing [3] [4]. A low-cost mmWave IRS based on reconfigurable phase conjugation arrays will be designed, fabricated, and deployed into a V2X system to create additional reflection paths between mmWave transmitters and receivers, allowing multi-beam mmWave connections that are robust against signal blockage.
 
Multi-Target Radar Sensing with CSI and DPS. This thrust aims to explore the multiple mmWave beams to realize a multi-target automotive radar. The design leverages the channel sounding step that is common during the communication link establishment process to detect the range and velocity of objects in the vicinity of the car. The proposed algorithm utilizes the differences of channel state information (CSI) and Doppler power spectrum (DSP) among subcarriers of a wideband OFDM mmWave transmission to compute the distance and relative speed from the transmitter (or IRS) to the receiver [5].
 
Reliable Multi-Beam mmWave V2X Network with Predictive IA. This thrust aims to exploit the trajectory information acquired through radar sensing to achieve interference alignment (IA) for mmWave MIMO communication in a high-mobility environment [6]–[8]. The design predicts the channel changes based on the relative speed and range between the transmitter and receiver and lets the transmitter precode the transmission along each beam to minimize the interferences at the receiver side, which maximizes the MIMO spatial multiplexing gain.

***

# Logistics
- **CRN**
| EE196 | EE296 | EE396 | EE496 |
| ---   | ---   | ---   | ---   |
| 90737 | 90738 | 90739 | 90740 |
 ***

# Research Issues 
 Design an integrated sensing and communication (ISAC) system for V2X network using mmWave MIMO and deliver accurate radar sensing and reliable communication in a high-mobility environment. Includes three complimentary thrusts: Improve mmWave MIMO Channel Condition with IRS (intelligent reflecting surface), Multi-Target Radar Sensing with CSI (channel state information) and DPS (doppler power spectrum), and reliable Multi-Beam mmWave V2X Network with Predictive IA. 
 ### Equipment
 - TMYTEK BBox Lite mmWave phase array + Ettus N210 USRPs

 
***

# Meeting Time 
### TBD
***

# Partners and Sponsors

***

# Majors
-EE

***

# Contact Info


***

