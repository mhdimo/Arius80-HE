# ZelliaFW
![ZelliaLogo](https://github.com/user-attachments/assets/5c15a9d7-56cb-4a98-9c7a-6629f6e1f4cd)
<sup>非常感谢<a href="https://www.linkedin.com/in/zilin-liang-8a77aa32b/" style="text-decoration:none">梁子琳</a>提供的免费图片</sup>

## Overview

The Zellia Hall-Effect Keyboard project is designed to use the **HAL9303SO sensors** and the **STM32F303 microcontroller** to create a highly responsive, low-latency keyboard. It integrates fast ADC channels in the STM32F303 to handle Hall-effect sensing for keypress detection.

This PCB design is compatible with the **Unified Daughterboard C5** (available from [KBDFans](https://kbdfans.com/products/tofu60-2-0-accessories?_pos=1&_sid=b8f5e035d&_ss=r&variant=41431070245003)).

## Features

- **Hall-Effect Sensors**: 
  - Uses **HAL9303SO** Hall-effect sensors for accurate key detection.
- **Microcontroller**: 
  - Based on the **STM32F303** MCU for low-latency performance and fast ADC channels.
- **Fast ADC Channels**: 
  - Uses fast channels in the MCU's ADC for rapid keyscan and accurate input reading.
- **Multiplexing**: 
  - Integrates **Nexperia multiplexers** (8 total, 2 for each ADC) to handle key matrix and expand ADC channels.
- **Debugging Interface**:
  - **SWDIO/SWCLK** for debugging and firmware updates.
  - **UART RX/TX** for serial communication.
- **Caps Lock Indicator**: 
  - Green **LED** to indicate the Caps Lock status.
- **Daughterboard Compatibility**: 
  - Compatible with the **Unified Daughterboard C5** for seamless integration.
- **Layout & Compatibility**:
  - Zellia is compatible with any daughterboard powered keyboard as long as you have a proper plate with compatible standoffs and KBDFans M2-3 Countersunk flat head screw kit (Available from [KBDFans](https://kbdfans.com/products/kbdfans-m2-3-countersunk-flat-head-screw-kit)).
(E.G. Tiger 80 Lite)

## Getting Started

### Prerequisites

To use this PCB project, you'll need:
- A **PCB fabrication service** to manufacture the board. (JLCPCB)
- A compatible **Unified Daughterboard C5** for mounting.

### Layout Compatibility
![image](https://github.com/user-attachments/assets/7f396711-c13d-41be-a183-ed1e1d9227b4)

### License

This project is licensed under the LGPL-2.1 License. See the [LGPL-2.1 License](LICENSE) file for details.

### Contributors 
Thanks to Zilin (梁子琳) Liang for the logo graphics

Huge thanks to [MaiTheSan](https://github.com/MaiTheSan) for reworking in the best possible way the keyboard.
[ChillKB](https://github.com/chillKB) for adding the green LED.
[Timass](https://github.com/Timass60) for routing the LDO / USB Back then in the 1st prototype.
[zhangqili](https://github.com/zhangqili) for improving schematic.

