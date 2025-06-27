# TUM Faster Than Real-Time Build

This document outlines the build used by the TUM Faster Than Real-Time team for Roboracer, former F1TENTH, competitions.
We provide the BOM on the basis of the Traxxas Fiesta SL VXL + Orin Nano platform, updated from [https://github.com/TUM-AVS/F1TENTH-Auxiliaries](https://github.com/TUM-AVS/F1TENTH-Auxiliaries/tree/main/F1TENTH%20-%20Bill%20of%20Materials%20Deutschland%3A%20Germany%3A%20EU).
The links typically lead to shops where the components can be ordered in Germany.
Additionally, suggested components to upgrade and *tune* the base configuration are given (in compliance with the Roboracer rules).

## Overview

- **Platform:** Traxxas Fiesta1/10 Scale
- **Target Application:** Autonomy Platform with Orin Nano Integration
- **Purchase Method:** Mixed (invoice & direct)

## Bill of Materials

### Main Body
| Component | Qty | Cost per Unit | Comments | Payable by invoice | Link |
|:-|:-|:-|:-|:-|:-|
| Traxxas TRX74276-4 Ford Fiesta ST Rally VXL RTR 1:10 | 1 | 429.95 | | yes | [Link](https://www.rcfox.de/TRX74276-4ORNG-Traxxas-Ford-Fiesta-ST-orange-1/10-Rally-VXL-RTR-Brushless)|
| 2 Lipos and Charger Combo | 1 | 249.95 | | yes | [Link](https://www.monsterhopups.de/Traxxas-TRX2990GX-POWER-PACK-Dual-EZ-Peak-Plus-Ladegeraet-2x-ID-LiPo-111V-5000mah-25C) |

### Fasteners
| Component | Qty | Cost per Unit | Comments | Payable by invoice | Link |
|:-|:-|:-|:-|:-|:-|
| Standoff M3 SW6 45mm | 3 | 36.51 | pack of 100 | yes | [Link](https://abstandsbolzen-shop.de/abstandsbolzen/stahl/innen-innengewinde/16/stahl-abstandsbolzen-i/i-gewinde-m3-sw-6?number=BM345&c=15) |
| Standoff M3 SW6 25mm | 3 | 21.6 | pack of 100, for Powerboard  | yes | [Link](https://abstandsbolzen-shop.de/abstandsbolzen/stahl/innen-innengewinde/16/stahl-abstandsbolzen-i/i-gewinde-m3-sw-6?number=BM325&c=15) |
| Standoff M3 SW6 20mm | 4 | 21.07 | pack of 100, for Jetson | yes | [Link](https://abstandsbolzen-shop.de/abstandsbolzen/stahl/innen-innengewinde/16/stahl-abstandsbolzen-i/i-gewinde-m3-sw-6?number=BM320&c=15) |
| Screws M3x14mm | 10     | 2.142 | pack of 100 | yes | [Link](https://www.conrad.de/de/p/iso4762-din912-m3x14-zylinderschrauben-mit-innensechskant-vollgewinde-material-a2-blank-100-stueck-865439039.html) |
| | | | 3x for Autonomy Platform | | |
| | | | 4x for Jetson bottom | | |
| | | | 3x for Powerboard bottom | | |
| Screws M3x8mm | 9 | 28.9884 | pack of 100 | yes | [Link](https://www.conrad.de/de/p/toolcraft-888123-zylinderschrauben-m3-8-mm-sechsrund-iso-14579-stahl-verzinkt-100-st-888123.html?refresh=true) |
| | | | 4x for Jetson top | | |
| | | | 3x for Powerboard op | | |
| | | | 2x for ZED 2 | | |
| Screws M3x20mm | 2 | 3.6294999999999997 | pack of 100, 2x for LiDAR-Camera mount | yes | [Link](https://www.conrad.de/de/p/iso4017-din933-m3x20-sechskantschraube-gewinde-bis-kopf-vollgewinde-material-a2-blank-100-stueck-865407903.html) |
| Screws M5x | 2 | 6.366499999999999  | pack of 100, 2x for VESC | yes | [Link](https://www.conrad.de/de/p/zylinderschraube-din-912-innen-6kt-m5x20-8-8-galv-verz-100st-806478117.html) |

### Compute Module
| Component | Qty | Cost per Unit | Comments | Payable by invoice | Link |
|:-|:-|:-|:-|:-|:-|
| Nvidia Super Developer Kit Jetson Orin Nano 8 GB | 1 | 689.01 | | yes | [Link](https://www.conrad.de/de/p/nvidia-super-developer-kit-jetson-orin-nano-8-gb-6-x-1-5-ghz-2998506.html?utm_source=idealo&utm_medium=cpc&utm_term=2998506&utm_campaign=idealo) |
| Micro SD Card 128 GB | 1 | 15.993599999999999 | | yes | [Link](https://www.conrad.de/de/p/sandisk-extreme-microsdxc-karte-128-gb-class-10-uhs-i-stosssicher-wasserdicht-2621014.html) |
| NVMe SSD Card 1TB | 1 | 97.80609999999999  | | yes | [Link](https://www.conrad.de/de/p/samsung-970-evo-plus-1-tb-interne-m-2-pcie-nvme-ssd-2280-m-2-nvme-pcie-3-0-x4-retail-mz-v7s1t0bw-1910197.html) |
| Wifi Antenna | 1 | 29.988 | Optional, since Jetson has a not so good internal Bluetooth and Wifi module | yes | [Link](https://www.conrad.de/de/p/edimax-ew-7811uac-wlan-stick-usb-2-0-433-mbit-s-1188098.html) |
| Bluetooth Adapter | 1 | 14.8988 | see above | yes | [Link](https://www.conrad.de/de/p/asus-usb-bt500-bluetooth-stick-5-0-2336738.html ) |

### Sensors
| Component | Qty | Cost per Unit | Comments | Payable by invoice | Link |
|:-|:-|:-|:-|:-|:-|
| ZED 2 camera (optional) | 1 | 449.0 | | no | [Link](https://store.stereolabs.com/en-de/products/zed-2) |
| Hokuyo 10LX | 1 | 1606.5 | | yes | [Link](https://www.roboparts.de/epages/63257595.sf/sec37340fc51c/?ObjectPath=/Shops/63257595/Products/UST-10LX) |

### Electronics
| Component | Qty | Cost per Unit | Comments | Payable by invoice | Link |
|:-|:-|:-|:-|:-|:-|
| VESC 6 MkVI | 1 | 413.62 | incl. Bluetooth module for easier parameter tuning and dust cover | no | [Link](https://trampaboards.com/vesc-6-mkvi-the-amazing-trampa-vesc-6-mkvi--gives-maximum-power-original-p-27536.html) |
| | | | incl. Customs fees | | |
| Dualshock 5 for PS5 | 1 | 76.2076 | | yes | [Link](https://www.conrad.de/de/p/sony-dualsense-wireless-controller-midnight-black-gamepad-playstation-5-schwarz-2386057.html?hk=SEM&WT.mc_id=google_pla&gad_source=1&gclid=Cj0KCQiAmNeqBhD4ARIsADsYfTf7bROVEh_HibS0lI4BMvAXFILRlXcfWSL6Zm6slvzBWg7Lv8U1Fb0aAhBlEALw_wcB) |
| USB A to USB micro cable | 1 | 3.9865 | | yes | [Link](https://www.conrad.de/de/p/renkforce-usb-kabel-usb-2-0-usb-a-stecker-usb-micro-b-stecker-0-30-m-schwarz-vergoldete-steckkontakte-rf-4463076-1487692.html) |
| Cable to connect the battery with the VESC and powerboard | 1 | 24.99 | | yes | [Link](https://www.monsterhopups.de/Traxxas-TRX2938XX-2938X-ID-Ladekabel-LiPo-Akku-auf-Balancer-Board-2S-bis-4S-XH) |
| 4mm male to 3,5mm female bullet adapter for VESC to motor connection | 1 | 7.98 | | no | [Link](https://www.ebay.de/itm/195564348829?hash=item2d888b259d:g:694AAOSwE3ljyaFR&amdata=enc%3AAQAIAAAA8CUtDB%2B13vHLE9fhMNhfwzKAlt%2F0rYczyeexMYnIdTL%2FI3a5l3mOSnrm8WhvG7bOSVYrIw4QYnXwPG4kUTB%2B4qJb03uxgZnADwOO9wSp7zbbRztAe72XaRjjXoLItyPp5bCFKzcHnZ6xHdwDDCwJ6jnrvUTxWAPj9iSIJA%2BoyROS5S1Jv6Si5V0%2Bz%2Fox%2BHcEmYmkU4dkXaVNZIFd%2BOWHghgjFOXC4iI6MNAOXCotNyslUqnc6c4hyyWIrqXb3WD1EH%2Bcw1zCYAWyPdBX%2Br6%2B4B0akaPXlT3Cn2wD8mkNQ0NgiDluCyfrVV9UpyCnSFCNaQ%3D%3D%7Ctkp%3ABk9SR8a49o77Yg) |
| Powercord Jetson | 1 | 1.9872999999999998 | | yes | [Link](https://www.conrad.de/de/p/tru-components-tc-9556652-niedervolt-anschlusskabel-niedervolt-stecker-offene-kabelenden-5-5-mm-2-5-mm-2-00-m-1-st-2389163.html?hk=SEM&WT.mc_id=google_pla&gclid=Cj0KCQjwmICoBhDxARIsABXkXlJaYE0ghEBC1SKgXbTVUaXbEA0PeVULI70-NVMmI5N1bFHGMH25XaIaAsL9EALw_wcB) |
| Shrink tube for Servo cable | 1 | 6.949599999999999  | | yes | [Link](https://www.conrad.de/de/p/toolland-has07-schrumpfschlauchsortiment-schwarz-1-set-2574855.html#productDescription ) |
| PPM cable for VESC 6 | 1 | 4.99 | | yes | [Link](https://shop.elektro-skateboard.de/eigenbau-tuning/esc-motorregler/vesc/747/ppm-kabel-fuer-vesc-6-esc) |

### Miscellaneous
| Component | Qty | Cost per Unit | Comments | Payable by invoice | Link |
|:-|:-|:-|:-|:-|:-|
| LiPo safety bag like the Aketek Silver Large Size Lipo Battery Guard Sleeve/Bag for Charge & Storage. | 1 | 8.984499999999999  | | yes | [Link](https://www.conrad.de/de/p/extron-modellbau-lipo-safety-bag-1-st-x6670-1930097.html) |
| RC Car Stand | 1      | 24.954299999999996 | | yes | [Link](https://www.conrad.de/de/p/absima-1-10-1-8-montagestaender-schwarz-1537809.html) |
| DisplayPort Dummy | 1      | 8.924999999999999  | | yes | [Link](https://www.conrad.de/de/p/dp-displayport-dummy-plug-displayport-dummy1-818237411.html#productDescription) |
| Wire ferrules for LiDAR cables | 1 | 29.99 | set                                                                         | yes                  | [Link](https://www.conrad.de/de/p/quadrios-2005ca001-aderendhuelsen-sortiment-teilisoliert-mehrfarbig-1200-st-2452883.html) |
| XT90 plug female for power connection VESC | 1 | 1.9872999999999998 | | yes | [Link](https://www.conrad.de/de/p/reely-re-6702315-akku-buchse-xt90-vergoldet-1-st-2234105.html?hk=SEM&WT.mc_id=google_pla&gclid=EAIaIQobChMI9e2O5_6XgQMVBQsGAB08HgCrEAQYASABEgKG_PD_BwE) |


Updated: 2025-06027.

---

## Notes

- Prices are listed in EUR and include 19% German federal tax.
- Prices are subject to change. 
- Links point to suggested vendors but can be substituted.
- Ensure quantities are double-checked before ordering.
