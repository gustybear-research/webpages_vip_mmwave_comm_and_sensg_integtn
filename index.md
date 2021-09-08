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
url: ./project/research/x96_multi_moda_pair_sienna/#logistics
- name: PUB
url: ./publication/zheng-insider-resistant-context-based-pairing-2021/
- name: Slides
url: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/presentation/EE496%20Poster_%20SIENNA.pdf
- name: Dataset
url: https://github.com/gustybear-research/x96_wirles_physllgcl_sensing



# Markdown Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

gallery_item:
- album: highlights
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/_DSC2122_00006.jpg
caption: highlights a
- album: highlights
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/_DSC2165_00009.jpg
caption: highlights b
- album: highlights
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/_DSC2167_00010.jpg
caption: highlights c
- album: highlights
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/_DSC2178_00014.jpg
caption: highlights d
- album: highlights
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/_DSC2193_00016.jpg
caption: highlights e
- album: highlights
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/IMG_3548.jpg
caption: highlights f

- album: modality
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/resp_belt.png
caption: The respiratory belt detects chest displacement (breathing) through changes in thoracic or abdominal circumference.
- album: modality
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/prms.png
caption: The PRMS detects displacement (breathing) in patient's chest through phase offset between the TX and RX signal.

- album: sienna
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/clinic_visit.png
caption: A medical technician places a respiratory belt on a user and pairs it with the user's phone.
- album: sienna
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/pairing.png
caption: A user pairs the PRMS with the user's phone.
- album: sienna
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/mod_change.png
caption: User switches to PRMS for OSA screening.
- album: sienna
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/verification.png
caption: Doctor verifies OSA data for any abnormalities.

- album: implementation
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/sienna_prototype.png
caption: Implementation of SIENNA with, an Android application, a contact sensor, and PRMS.
- album: implementation
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/evaluation_01.jpeg
caption: Evaluation 01
- album: implementation
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/evaluation_02.jpeg
caption: Evaluation 02
- album: implementation
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/evaluation_03.jpeg
caption: Evaluation 03
- album: implementation
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/evaluation_04.jpeg
caption: Evaluation 04

- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/iq.png
caption: Raw IQ data received by different RF channels of the PRMS
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/time_domain.png
caption: Breathing mixture obtained by (linear) demodulating the raw IQ (top), individual breathing patterns after source separation in comparison with the ones collected by the respiratory belt (bottom)
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/time_feature.png
caption: Time domain analysis show the inhale and exhale characters are distinct between the two subjects, which allows patient tracking during modality changes.
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/frequency_feature.png
caption: Frequency domain analysis show the inhale and exhale characters are distinct between the two subjects, which allows patient tracking during modality changes.
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/feature_preservation.png
caption: Signal reconstructed after 64-level-crossing quantization with vital related dynamic features preserved.
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/friend_similarity.png
caption: Similarity between belt-based and PRMS-based breathing patterns, measured with the same subject.
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/attack_similarity.png
caption: Similarity between belt-based and PRMS-based breathing patterns, measured with different subjects.
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/slant-ranges.png
caption: The effect on the fingerprint similarity due to the change of slant range between the PRMS and the subject.
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/entropy.png
caption: Average entropy per bit of the fuzzy commitments, e.g., RS encoded key salt XORed with (multiple) fingerprint segments, measured via NIST tests
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/rs_encode.png
caption: Commitment time with RS codes of different message/parity symbol lengths
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/rs_decode.png
caption: Reconstruction time with RS codes of different message/parity symbol lengths and symbols errors
- album: results
image: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/friendly_jamming.png
caption: Performance of SIENNA against eavesdropping and spoofing in terms of aggregated BER

---

***
# Project Summary
 As autonomous vehicles revolutionize our transportation ecosystem, Millimeter-wave (mmWave) communication is a promising technology to meet the data rate demand of V2X (vehicle to everything) networks. This project aims to design an integrated sensing and communication (ISAC) system for V2X network using mmWave MIMO (multiple-input and multiple-output) to deliver accurate radar sensing and reliable communication in a high-mobility environment. 

***
# Logistics
- **CRN**
| EE196 | EE296 | EE396 | EE496 |
| ---   | ---   | ---   | ---   |
| 90737 | 90738 | 90739 | 90740 |
 ***

# Keywords
- Autonomous Vehicle
- CSI (channel state information)
- ISAC (integrated sensing and communication)
- LOS (line of sight)
- mmWave Communication
- mmWave Sensing
- MIMO (multiple-input and multiple-output)
- V2X (vehicle to everything)


***

# Research Issues 
 Design an integrated sensing and communication (ISAC) system for V2X network using mmWave MIMO and deliver accurate radar sensing and reliable communication in a high-mobility environment. Includes three complimentary thrusts: Improve mmWave MIMO Channel Condition with IRS (intelligent reflecting surface), Multi-Target Radar Sensing with CSI (channel state information) and DPS (doppler power spectrum), and reliable Multi-Beam mmWave V2X Network with Predictive IA. 
 ### Equipment
 - TMYTEK BBox Lite mmWave phase array + Ettus N210 USRPs

 
***

# Meeting Time 
### TBA
***

# Advisor
Dr. Yao Zheng

***
# Partners and Sponsors
This project is partially supported NSF grants CNS-1948568, W911NF-19-1-0050, IIP-1831303, IIS-1915738 and TMYTEK mmWave research initiative.



[image]: https://github.com/gustybear-research/conf_globecom_multi_moda_dev_pair/raw/main/figures/website/IMG_3548.jpg
