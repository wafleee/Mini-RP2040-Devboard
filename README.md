# Mini RP2040 Devboard

<img width="1047" height="849" alt="Screenshot 2026-10-09 213617" src="https://github.com/user-attachments/assets/6d8be6ca-692c-4b31-b255-373b99b661a8" />
I made a mini devboard that uses the RP2040 as the MCU. It is slightly bigger than the XIAO esp32 s3 but it features 4 extra pins

# Features 
1. ESD protection(protection against electrostatic discharge from body )
2.  Dual-core Arm Cortex-M0+ running up to 133 MHz
3.  18 GPIO pins| 3 ADC pins| GPIO 4- SDA | GPIO 5 - SCL
4.  


# SCHEMATIC
<img width="835" height="796" alt="image" src="https://github.com/user-attachments/assets/56b45cc9-fbc1-4405-bb1f-ce97889e3aa6" />

# PCB
<img width="785" height="850" alt="image" src="https://github.com/user-attachments/assets/5c7ad17b-5978-4d17-a65c-44fe65cc2600" />

#BOM



| Designator                                     | Footprint                                               | Qty | Value                       | Link                                                                                                                                                               |
| ---------------------------------------------- | ------------------------------------------------------- | --- | --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| C10, C12, C13, C14, C15, C16, C17, C19, C3, C9 | 603                                                     | 10  | 100nF                       | Already owned                                                                                                                                                      |
| C11, C18, C7, C8                               | 603                                                     | 4   | 1µF                         | [Robu](https://robu.in/product/06033d105kat2a-kyocera-avx-cap-smd-mlcc-1-%c2%b5f-25-v-0603-pack-of-1/)                                                             |
| C4, C5                                         | 603                                                     | 2   | 15pF                        | [Robu](https://robu.in/product/0603n150j500ct-walsin-cap-smd-mlcc-15-pf-50-v-0603-pack-of-10/)                                                                     |
| C6                                             | 805                                                     | 1   | 10µF                        | [Robu](https://robu.in/product/cc0805kkx5r8bb106-yageo-cap-smd-mlcc-10-%c2%b5f-25-v-0805-2012-metric10-x5r-cc-series/)                                             |
| D1                                             | LED_WS2812B-2020_PLCC4_2.0x2.0mm                        | 1   | WS2812B-2020                | [Robu](https://robu.in/product/sme-ws2812b-2020-addressable-rgb-pixel-led-worldsemi/)                                                                                                                                                                 |
| D2                                             | 603                                                     | 1   | LED                         | [Robu](https://robu.in/product/19-217-r6c-al1m2vy-3t-everlight-red-528nm-led-indication-discrete-3-3v-0603-1608-metric/)                                           |
| J1                                             | USB_C_Receptacle_GCT_USB4105-xx-A_16P_TopMnt_Horizontal | 1   | USB_C_Receptacle_USB2.0_14P | [Robu](https://robu.in/product/type-c-31-m-12-hroparts-5a-1-16p-female-type-c-smd-usb-connectors-rohs/)                                                            |
| J4, J5                                         | PinHeader_1x10_P2.54mm_Vertical                         | 2   | Conn_01x10_Pin              | [Robu](https://robu.in/product/ds1021-1x10sf11-b-connfly-1x10-pin-2-54mm-pin-header-v-t-type/)                                                                     |
| R1, R2                                         | 603                                                     | 2   | 5.1kΩ                       | [Robu](https://robu.in/product/rt0603fre075k1l-yageo-100mw-thin-film-resistor-75v-%c2%b150ppm-%e2%84%83-%c2%b11-5-1k%cf%89-0603-chip-resistor-surface-mount-rohs/) |
| R3, R6                                         | 603                                                     | 2   | 1kΩ                         | [Robu](https://robu.in/product/1k-ohm-1-4w-0603-surface-mount-chip-resistor-pack-of-100/)                                                                          |
| R4, R5                                         | 603                                                     | 2   | 27Ω                         | [Robu](https://robu.in/product/rc0603jr-0727rl-yageo-smd-chip-resistor-27-ohm-%c2%b1-5-100-mw-0603-1608-metric-thick-film-general-purpose/)                        |
| SW1                                            | SW_SPST_B3U-1000P                                       | 1   | SW_MEC_5G                   | [Robu](https://robu.in/product/1-month-warranty-470/)                                                                                                              |
| U1                                             | QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm                     | 1   | RP2040                      | [Robu](https://robu.in/product/raspberry-pi-rp2040/)                                                                                                               |
| U3                                             | SOIC-8_5.3x5.3mm_P1.27mm                                | 1   | W25Q128JVS                  | [Lion Circuits](https://www.lioncircuits.com/parts/W25Q128JVSIQ)                                                                                                   |
| U4                                             | SOT-23-5                                                | 1   | AP2112K-3.3                 | [Lion Circuits](https://www.lioncircuits.com/parts/AP2112K-3.3TRG1)                                                                                                |
| U5                                             | SOT-23-6                                                | 1   | USBLC6-2SC6                 | [Robu](https://robu.in/product/usblc6-2sc6-ms-msksemi-4-5a-15v-150w-6v-5v-sot-23-6-esd-and-surge-protection-tvs-esd-rohs/)                                         |
| Y2                                             | Crystal_SMD_Abracon_ABM8AIG-4Pin_3.2x2.5mm              | 1   | Crystal_GND3                | [Robu](https://robu.in/product/cm4012m00008001-huaxindianzi/)                                                                                                      |


# Credits
Kicad

