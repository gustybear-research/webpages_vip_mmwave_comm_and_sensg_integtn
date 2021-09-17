---
draft: false
title: "V2SX: Integrate mmWave Vehicular Communication with Radar Sensing"

subtitle: "Vertically Integrated Project (VIP), Spring 2022 - present"

summary: "This project aims to develop mmWave communication systems with integrated radar sensing functionality to address the coexistence challenge between vehicular communication and automative radar sensors operating within the mmWave spectrum."

tags:
- autonomous vehicle
- v2x
- multipath
- phased array
- reconfigurable MIMO
- rayleigh's criterion
- intelligent reflecting surface
- fresnel zone analysis
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
  caption: ""
  focal_point: ""
  preview_only: true

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

# gallery_item:

---
***
# Executive Summary
This project aims to design a millimeter-wave (mmWave) V2X (vehicle to everything) communication system with integrated radar sensing capability for autonomous vehicles. As a promising technology, radio communication at mmWave frequencies, particularly between 24 to 32 GHz, can meet the data rate demand of V2X. Unfortunately, these bands are occupied by short-range radar sensors equally essential for autonomous vehicles. Introducing a separate V2X system in these bands would strain the spectrum congestion, leading to suboptimal performance for both communication and sensing. To address this issue, V2SX aims to unify mmWave radar and communication functions via the multiple-input and multiple-output (MIMO) technique augmented by vehicle-mounted reflective arrays to achieve reliability V2X communication and accurate radar ranging.

***

# Logistics {#logistics}
- **CRN**
| EE196 | EE296 | EE396 | EE496 |
| ---   | ---   | ---   | ---   |
| 90737 | 90738 | 90739 | 90740 |

- **Personnel**:
|                                                    |                                             |
| ----                                               | ---                                         |
| Lecturer: [Yao Zheng](mailto:yao.zheng@hawaii.edu) | Office Hours: see [here](../../../#contact) |

 ***
# Research Issues 
 Increase mmWave Channel Multipath: The mmWave channel lacks multipath, which precludes effective MIMO spatial multiplexing and causes interference between communication and sensing functions. V2SX designs several low-cost vehicle-mounted reconfigurable reflective arrays to create artificial multipath. In addition, V2SX designs algorithms to adapt and configure the angle and spread of the reflecting multipath, hence maximizing the MIMO spatial multiplexing gain.

Decouple mmWave Channel Correlation: The exterior of a vehicle limits the spaces between MIMO antenna arrays, which correlates channel states among MIMO receptions and causes interference between communication and sensing functions. V2SX designs several reconfigurable antenna arrays with diverse beam patterns/directions to decouple channel correlations. Furthermore, V2SX designs algorithms to optimize the arrays' beam configurations based on the observed multipath profile, hence maximizing the MIMO channel condition.
 
***




