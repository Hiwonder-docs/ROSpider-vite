# 1. ROSpider User Manual

## 1.1 Product Introduction

### 1.1.1 Getting to Know ROSpider

::: Starter Kit

ROSpider Starter Kit is a comprehensive hexapod robot engineered for ROS education scenarios, operating on Ubuntu 22.04 and equipped with the ROS2 Humble robotic system.

It features high-performance hardware configurations including the NVIDIA Jetson Nano, Jetson Orin Nano, Jetson Orin NX, or Raspberry Pi 5 as the controller, alongside high-voltage bus servos, LiDAR, and a monocular camera. It supports diverse applications such as robot motion control, mapping and navigation, target tracking and obstacle avoidance, autonomous cruising, human feature recognition, and somatosensory interaction.

Integrating the monocular camera with the robotic arm enables operation as both a desktop visual robotic arm and a mobile visual robotic arm. The robot performs tasks such as navigation handling, autonomous grasping, and waste sorting, fully satisfying the requirements for learning and verifying ROS2 and machine vision.

In terms of locomotion, the robot utilizes a hexapod ripple gait. The body posture, height, and moving speed are adjustable, delivering an optimized control experience.

:::

::: Standard Kit

ROSpider Standard Kit is a comprehensive hexapod robot engineered for ROS education scenarios, operating on Ubuntu 22.04 and equipped with the ROS2 Humble robotic system.

It features high-performance hardware configurations including the NVIDIA Jetson Nano, Jetson Orin Nano, Jetson Orin NX, or Raspberry Pi 5 as the controller, alongside high-voltage bus servos, LiDAR, and a depth camera. It supports diverse applications such as robot motion control, mapping and navigation, target tracking and obstacle avoidance, autonomous cruising, human feature recognition, and somatosensory interaction.

Integrating the depth camera with the robotic arm enables operation as both a desktop visual robotic arm and a mobile visual robotic arm. The robot performs tasks such as navigation handling, autonomous grasping, waste sorting, and 3D visual object recognition and grasping, fully satisfying the requirements for learning and verifying ROS2 and machine vision.

In terms of locomotion, the robot utilizes a hexapod ripple gait. The body posture, height, and moving speed are adjustable, delivering an optimized control experience.

:::

::: Advanced Kit

ROSpider Advanced Kit is a comprehensive hexapod robot engineered for ROS education scenarios, operating on Ubuntu 22.04 and equipped with the ROS2 Humble robotic system.

It features high-performance hardware configurations including the NVIDIA Jetson Nano, Jetson Orin Nano, Jetson Orin NX, or Raspberry Pi 5 as the controller, alongside high-voltage bus servos, LiDAR, a depth camera, and an AI voice interaction box. It supports diverse applications such as robot motion control, mapping and navigation, target tracking and obstacle avoidance, autonomous cruising, human feature recognition, somatosensory interaction, voice control, and large AI model applications.

Integrating the depth camera with the robotic arm enables operation as both a desktop visual robotic arm and a mobile visual robotic arm. The robot performs tasks such as navigation handling, autonomous grasping, waste sorting, and 3D visual object recognition and grasping, fully satisfying the requirements for learning and verifying ROS2 and machine vision.

In terms of locomotion, the robot utilizes a hexapod ripple gait. The body posture, height, and moving speed are adjustable, delivering an optimized control experience.

:::

::: Ultimate Kit

ROSpider Ultimate Kit is a comprehensive hexapod robot engineered for ROS education scenarios, operating on Ubuntu 22.04 and equipped with the ROS2 Humble robotic system.

It features high-performance hardware configurations including the NVIDIA Jetson Nano, Jetson Orin Nano, Jetson Orin NX, or Raspberry Pi 5 as the controller, alongside high-voltage bus servos, LiDAR, a depth camera, and a 6-channel microphone array. It supports diverse applications such as robot motion control, mapping and navigation, target tracking and obstacle avoidance, autonomous cruising, human feature recognition, somatosensory interaction, and large AI model applications.

Integrating the depth camera with the robotic arm enables operation as both a desktop visual robotic arm and a mobile visual robotic arm. The robot performs tasks such as navigation handling, autonomous grasping, waste sorting, and 3D visual object recognition and grasping, fully satisfying the requirements for learning and verifying ROS2 and machine vision.

In terms of locomotion, the robot utilizes a hexapod ripple gait. The body posture, height, and moving speed are adjustable, delivering an optimized control experience.

:::

### 1.1.2 Packing List

::: Starter Kit

| Item Name | Image | Qty | Item Name | Image | Qty |
| :---: | :---: | :---: | :---: | :---: | :---: |
| ROSpider (assembled, LiDAR included) | <img src="../_static/media/chapter_1/section_1/image208.png" class="common_img" style="width:200px;"/> | 1 | Red block (30×30 mm) | <img src="../_static/media/chapter_1/section_1/image215.png" class="common_img" style="width:100px;"/> | 1 |
| Robotic arm | <img src="../_static/media/chapter_1/section_1/image209.png" class="common_img" style="width:200px;"/> | 1 | Tag cards (65×65 mm) | <img src="../_static/media/chapter_1/section_1/image216.png" class="common_img" style="width:200px;"/> | 3 |
| 12.6 V 2 A charger (DC5.5×2.5 mm) | <img src="../_static/media/chapter_1/section_1/image210.png" class="common_img" style="width:200px;"/> | 1 | Waste sorting cards (40×40 mm) | <img src="../_static/media/chapter_1/section_1/image217.png" class="common_img" style="width:200px;"/> | 12 |
| Wireless controller + receiver | <img src="../_static/media/chapter_1/section_1/image211.png" class="common_img" style="width:200px;"/> | 1 | PH2.0 servo cable (200 mm) | <img src="../_static/media/chapter_1/section_1/image218.png" class="common_img" style="width:200px;"/> | 3 |
| Card reader | <img src="../_static/media/chapter_1/section_1/image212.png" class="common_img" style="width:100px;"/> | 1 | 5264 servo cable (160 mm / 200 mm) | <img src="../_static/media/chapter_1/section_1/image219.png" class="common_img" style="width:200px;"/> | 6 |
| Monocular camera | <img src="../_static/media/chapter_1/section_1/image213.png" class="common_img" style="width:100px;"/> | 1 | Accessory bag | <img src="../_static/media/chapter_1/section_1/image220.png" class="common_img" style="width:200px;"/> | 1 |
| Data cable (650 mm) | <img src="../_static/media/chapter_1/section_1/image214.png" class="common_img" style="width:100px;"/> | 1 | User manual | <img src="../_static/media/chapter_1/section_1/image221.png" class="common_img" style="width:150px;"/> | 1 |

:::

::: Standard Kit

| Item Name | Image | Qty | Item Name | Image | Qty |
| :---: | :---: | :---: | :---: | :---: | :---: |
| ROSpider (assembled, LiDAR included) | <img src="../_static/media/chapter_1/section_1/image208.png" class="common_img" style="width:200px;"/> | 1 | Red block (30×30 mm) | <img src="../_static/media/chapter_1/section_1/image215.png" class="common_img" style="width:100px;"/> | 1 |
| Robotic arm | <img src="../_static/media/chapter_1/section_1/image209.png" class="common_img" style="width:200px;"/> | 1 | Tag cards (65×65 mm) | <img src="../_static/media/chapter_1/section_1/image216.png" class="common_img" style="width:200px;"/> | 3 |
| 12.6 V 2 A charger (DC5.5×2.5 mm) | <img src="../_static/media/chapter_1/section_1/image210.png" class="common_img" style="width:200px;"/> | 1 | Waste sorting cards (40×40 mm) | <img src="../_static/media/chapter_1/section_1/image217.png" class="common_img" style="width:200px;"/> | 12 |
| Wireless controller + receiver | <img src="../_static/media/chapter_1/section_1/image211.png" class="common_img" style="width:200px;"/> | 1 | PH2.0 servo cable (200 mm) | <img src="../_static/media/chapter_1/section_1/image218.png" class="common_img" style="width:200px;"/> | 3 |
| Card reader | <img src="../_static/media/chapter_1/section_1/image212.png" class="common_img" style="width:100px;"/> | 1 | 5264 servo cable (160 mm / 200 mm) | <img src="../_static/media/chapter_1/section_1/image219.png" class="common_img" style="width:200px;"/> | 6 |
| Aurora930 Pro depth camera | <img src="../_static/media/chapter_1/section_1/image222.png" class="common_img" style="width:200px;"/> | 1 | Accessory bag | <img src="../_static/media/chapter_1/section_1/image220.png" class="common_img" style="width:200px;"/> | 1 |
| Depth camera bracket | <img src="../_static/media/chapter_1/section_1/image223.png" class="common_img" style="width:200px;"/> | 1 | User manual | <img src="../_static/media/chapter_1/section_1/image221.png" class="common_img" style="width:150px;"/> | 1 |
| Data cable (550 mm) | <img src="../_static/media/chapter_1/section_1/image224.png" class="common_img" style="width:200px;"/> | 1 | | | |

:::

::: Advanced Kit

| Item Name | Image | Qty | Item Name | Image | Qty |
| :---: | :---: | :---: | :---: | :---: | :---: |
| ROSpider (assembled, LiDAR included) | <img src="../_static/media/chapter_1/section_1/image208.png" class="common_img" style="width:200px;"/> | 1 | Red block (30×30 mm) | <img src="../_static/media/chapter_1/section_1/image215.png" class="common_img" style="width:100px;"/> | 1 |
| Robotic arm | <img src="../_static/media/chapter_1/section_1/image209.png" class="common_img" style="width:200px;"/> | 1 | Tag cards (65×65 mm) | <img src="../_static/media/chapter_1/section_1/image216.png" class="common_img" style="width:200px;"/> | 3 |
| 12.6 V 2 A charger (DC5.5×2.5 mm) | <img src="../_static/media/chapter_1/section_1/image210.png" class="common_img" style="width:200px;"/> | 1 | Waste sorting cards (40×40 mm) | <img src="../_static/media/chapter_1/section_1/image217.png" class="common_img" style="width:200px;"/> | 12 |
| Wireless controller + receiver | <img src="../_static/media/chapter_1/section_1/image211.png" class="common_img" style="width:200px;"/> | 1 | PH2.0 servo cable (200 mm) | <img src="../_static/media/chapter_1/section_1/image218.png" class="common_img" style="width:200px;"/> | 3 |
| Card reader | <img src="../_static/media/chapter_1/section_1/image212.png" class="common_img" style="width:100px;"/> | 1 | 5264 servo cable (160 mm / 200 mm) | <img src="../_static/media/chapter_1/section_1/image219.png" class="common_img" style="width:200px;"/> | 6 |
| Aurora930 Pro depth camera | <img src="../_static/media/chapter_1/section_1/image222.png" class="common_img" style="width:200px;"/> | 1 | Accessory bag | <img src="../_static/media/chapter_1/section_1/image220.png" class="common_img" style="width:200px;"/> | 1 |
| Depth camera bracket | <img src="../_static/media/chapter_1/section_1/image223.png" class="common_img" style="width:200px;"/> | 1 | User manual | <img src="../_static/media/chapter_1/section_1/image221.png" class="common_img" style="width:150px;"/> | 1 |
| Data cable (550 mm) | <img src="../_static/media/chapter_1/section_1/image224.png" class="common_img" style="width:200px;"/> | 1 | Type-C data cable (280 mm) | <img src="../_static/media/chapter_1/section_1/image227.png" class="common_img" style="width:300px;"/> | 1 |
| WonderEcho Pro AI voice interaction box | <img src="../_static/media/chapter_1/section_1/image225.png" class="common_img" style="width:200px;"/> | 1 | | | |

:::

::: Ultimate Kit

| Item Name | Image | Qty | Item Name | Image | Qty |
| :---: | :---: | :---: | :---: | :---: | :---: |
| ROSpider (assembled, LiDAR included) | <img src="../_static/media/chapter_1/section_1/image208.png" class="common_img" style="width:200px;"/> | 1 | Red block (30×30 mm) | <img src="../_static/media/chapter_1/section_1/image215.png" class="common_img" style="width:100px;"/> | 1 |
| Robotic arm | <img src="../_static/media/chapter_1/section_1/image209.png" class="common_img" style="width:200px;"/> | 1 | Tag cards (65×65 mm) | <img src="../_static/media/chapter_1/section_1/image216.png" class="common_img" style="width:200px;"/> | 3 |
| 12.6 V 2 A charger (DC5.5×2.5 mm) | <img src="../_static/media/chapter_1/section_1/image210.png" class="common_img" style="width:200px;"/> | 1 | Waste sorting cards (40×40 mm) | <img src="../_static/media/chapter_1/section_1/image217.png" class="common_img" style="width:200px;"/> | 12 |
| Wireless controller + receiver | <img src="../_static/media/chapter_1/section_1/image211.png" class="common_img" style="width:200px;"/> | 1 | PH2.0 servo cable (200 mm) | <img src="../_static/media/chapter_1/section_1/image218.png" class="common_img" style="width:200px;"/> | 3 |
| Card reader | <img src="../_static/media/chapter_1/section_1/image212.png" class="common_img" style="width:100px;"/> | 1 | 5264 servo cable (160 mm / 200 mm) | <img src="../_static/media/chapter_1/section_1/image219.png" class="common_img" style="width:200px;"/> | 6 |
| Aurora930 Pro depth camera | <img src="../_static/media/chapter_1/section_1/image222.png" class="common_img" style="width:200px;"/> | 1 | Accessory bag | <img src="../_static/media/chapter_1/section_1/image220.png" class="common_img" style="width:200px;"/> | 1 |
| Depth camera bracket | <img src="../_static/media/chapter_1/section_1/image223.png" class="common_img" style="width:200px;"/> | 1 | User manual | <img src="../_static/media/chapter_1/section_1/image221.png" class="common_img" style="width:150px;"/> | 1 |
| Data cable (550 mm) | <img src="../_static/media/chapter_1/section_1/image224.png" class="common_img" style="width:200px;"/> | 1 | Type-C data cable (280 mm) | <img src="../_static/media/chapter_1/section_1/image227.png" class="common_img" style="width:300px;"/> | 1 |
| 6-microphone array | <img src="../_static/media/chapter_1/section_1/image226.png" class="common_img" style="width:200px;"/> | 1 | | | |

:::

## 1.2 Assembly and Wiring

This chapter introduces the hardware components of the ROSpider robot, including the electronic control system, Jetson series and Raspberry Pi 5 controllers, LiDAR, depth camera, and related sensors.

### 1.2.1 Assembly Instructions

For details, refer to the **[Video Tutorial](https://www.youtube.com/playlist?list=PLFbzd0m6AcmKRgvwlMZkxmDms8BGc_XYk)** in the same directory to perform robot assembly.

#### 1.2.1.1 Controller Installation - Optional

> [!NOTE]
>
> **When purchasing a robot without a controller, review this section first to install the controller onto the chassis. Skip this section directly if the robot is already equipped with a controller.**

First, unscrew the four black M3x6 screws on the top sheet metal part, then remove the sheet metal bracket.

<img src="../_static/media/chapter_1/section_1/image194.png" class="common_img" style="width:700px;"/>

* **Jetson Nano Controller**

1. Secure the Jetson Nano onto the chassis using two M2.5 screws and two M2.5 single-pass copper standoffs.

<img src="../_static/media/chapter_1/section_1/image185.png" class="common_img" style="width:700px;"/>

2. Insert the expansion board into the pin header on the right side of the controller, then secure the antenna onto the copper standoffs using two M2.5 screws.

<img src="../_static/media/chapter_1/section_1/image186.png" class="common_img" style="width:700px;"/>

3. Reattach and secure the top sheet metal part back to its original position.

> [!NOTE]
>
> **Before securing the sheet metal part, connect and route the device data cables in advance according to [Section 1.2.1.2 Robot Body Assembly and Wiring Instructions](#p1.2.1.1).**

<img src="../_static/media/chapter_1/section_1/image187.png" class="common_img" style="width:700px;"/>

* **Jetson Orin Nano/NX Controller**

1. Secure the Jetson Orin Nano/NX onto the chassis using two M2.5 screws and two M2.5 single-pass copper standoffs.

<img src="../_static/media/chapter_1/section_1/image188.png" class="common_img" style="width:700px;"/>

2. Insert the expansion board into the pin header on the right side of the controller, then secure the antenna onto the copper standoffs using two M2.5 screws.

<img src="../_static/media/chapter_1/section_1/image189.png" class="common_img" style="width:700px;"/>

3. Reattach and secure the top sheet metal part back to its original position.

> [!NOTE]
>
> **Before securing the sheet metal part, connect and route the device data cables in advance according to [Section 1.2.1.2 Robot Body Assembly and Wiring Instructions](#p1.2.1.1).**

<img src="../_static/media/chapter_1/section_1/image190.png" class="common_img" style="width:700px;"/>

* **Raspberry Pi 5 Controller**

1. Secure the Raspberry Pi 5 onto the chassis using four white double-pass nylon standoffs.

<img src="../_static/media/chapter_1/section_1/image191.png" class="common_img" style="width:700px;"/>

2. Insert the expansion board into the pin header on the right side of the controller.

<img src="../_static/media/chapter_1/section_1/image192.png" class="common_img" style="width:700px;"/>

3. Reattach and secure the top sheet metal part back to its original position.

> [!NOTE]
>
> **Before securing the sheet metal part, connect and route the device data cables in advance according to [Section 1.2.1.2 Robot Body Assembly and Wiring Instructions](#p1.2.1.1).**

<img src="../_static/media/chapter_1/section_1/image193.png" class="common_img" style="width:700px;"/>

<p id="p1.2.1.1"></p>

#### 1.2.1.2 Robot Body Assembly and Wiring Instructions

* **Depth Camera Assembly and Wiring Diagram**

1. Secure the depth camera and its bracket using four black M3x6 screws.

<img src="../_static/media/chapter_1/section_1/image196.png" class="common_img" style="width:800px;"/>

2. Taking the Jetson controller as an example, connect the depth camera data cable to the upper-left USB port of the controller. The port location on the Raspberry Pi 5 is identical.

<img src="../_static/media/chapter_1/section_1/image198.png" class="common_img" style="width:900px;"/>

* **Robotic Arm Assembly Diagram**

1. Secure the robotic arm onto the robot body using four black M3x6 screws.

<img src="../_static/media/chapter_1/section_1/image197.png" class="common_img" style="width:700px;"/>

2. Connect the servo cable of the robotic arm to the 3-pin port on the STM32 control board.

<img src="../_static/media/chapter_1/section_1/image199.png" class="common_img" style="width:700px;"/>

* **STM32 Control Board Wiring Diagram**

1. Connect one end of the Type-C data cable to the front Type-C port on the control board.

<img src="../_static/media/chapter_1/section_1/image200.png" class="common_img" style="width:700px;"/>

2. Taking the Jetson controller as an example, connect the other end to the upper-right USB port of the controller. The port location on the Raspberry Pi 5 is identical.

<img src="../_static/media/chapter_1/section_1/image201.png" class="common_img" style="width:700px;"/>

* **Voice Device Installation and Wiring Diagram**

1. Align the 6-channel microphone with the four outer M4 holes on the top sheet metal part, then secure it using four M4x16 screws. Ensure the Type-C end of the data cable is connected underneath the microphone before installation.

<img src="../_static/media/chapter_1/section_1/image204.png" class="common_img" style="width:700px;"/>

<img src="../_static/media/chapter_1/section_1/image205.png" class="common_img" style="width:600px;"/>

2. Align the WonderEcho Pro voice box with the four inner M4 holes on the top sheet metal part, then secure it using four M4x10 screws.

<img src="../_static/media/chapter_1/section_1/image206.png" class="common_img" style="width:700px;"/>

<img src="../_static/media/chapter_1/section_1/image207.png" class="common_img" style="width:600px;"/>

3. Taking the Jetson controller as an example, connect the data cables of both voice devices to the lower-right USB port of the controller. The port location on the Raspberry Pi 5 is identical.

<img src="../_static/media/chapter_1/section_1/image202.png" class="common_img" style="width:700px;"/>

* **Wireless Controller Receiver Connection Diagram - Pre-connected before delivery**

The wireless controller receiver connects to the USB controller receiver port on the STM32 controller.

<img src="../_static/media/chapter_1/section_1/image203.png" class="common_img" style="width:700px;"/>

<p id="p1221"></p>

### 1.2.2 Port Descriptions - Key Focus

#### 1.2.2.1 Jetson Nano Controller

The figure below shows the ports connecting various modules to the Jetson Nano controller in the Ultimate Kit. Wiring can be performed according to the standards in the table below. Skip any port if the purchased package does not include the corresponding module.

<img src="../_static/media/chapter_1/section_1/image181.png" class="common_img" style="width:600px;"/>

| No. | Port Name |
| :---: | :--- |
| ① | Depth camera / monocular camera port |
| ② | STM32 controller communication port |
| ③ | Custom expansion port |
| ④ | Microphone array module / WonderEcho Pro AI voice box port |
| ⑤ | LCD display HDMI / DP port |
| ⑥ | Jetson Nano controller power supply port |
| ⑦ | Ethernet port |

#### 1.2.2.2 Jetson Orin Nano/Orin NX Controller

The figure below shows the ports connecting various modules to the Jetson Orin Nano controller in the Ultimate Kit. Wiring can be performed according to the standards in the table below. Skip any port if the purchased package does not include the corresponding module.

<img src="../_static/media/chapter_1/section_1/image1.png" class="common_img" style="width:600px;"/>

| No. | Port Name |
| :---: | :--- |
| ① | Jetson Orin Nano controller power supply port |
| ② | Virtual display emulator HDMI / DP port |
| ③ | Depth camera / monocular camera port |
| ④ | STM32 controller communication port |
| ⑤ | Custom expansion port |
| ⑥ | Microphone array module / WonderEcho Pro AI voice box port |
| ⑦ | Ethernet port |

#### 1.2.2.3 Raspberry Pi 5 Controller

<img src="../_static/media/chapter_1/section_1/image161.png" class="common_img" style="width:600px;"/>

| No. | Port Name |
| :---: | :--- |
| ① | Depth camera / monocular camera port |
| ② | STM32 controller communication port |
| ③ | Custom expansion port |
| ④ | Microphone array module / WonderEcho Pro AI voice box port |

#### 1.2.2.4 STM32 Controller

<img src="../_static/media/chapter_1/section_1/image150.png" class="common_img" style="width:600px;"/>

| No. | Function Description |
| :---: | :--- |
| ① | 5 V output port for Jetson Nano and Raspberry Pi 5 power supply |
| ② | UART serial port for controller communication |
| ③ | Jetson Orin Nano / Orin NX power supply port and robotic arm servo port |
| ④ | USB wireless controller receiver port |
| ⑤ | 12.6 V charger port |
| ⑥ | Lithium battery power supply port |
| ⑦ | Power switch |

## 1.3 Basic Robot Usage

This section covers the power-on status and function verification of each robot module. After completing these checks, proceed to the subsequent sections to learn app control and wireless controller operation.

To connect remote tools to the robot for advanced application learning and code inspection, refer to the content under **[Section 1.4 Development Environment Setup](#14-development-environment-setup)**.

### 1.3.1 Charging Instructions

Because power must be disconnected during transportation and the battery is not fully charged upon arrival, connect the battery mating connector before initial use, then charge it. Charging the battery from 10 V to approximately 12.3 V takes about 2 to 3 hours.

#### 1.3.1.1 Lithium Battery Precautions

> [!NOTE]
>
> * **Always use the dedicated charger provided in the kit and charge the battery only when the robot is powered off.**
>
> * **Never operate the robot while charging. The indicator light remains red during charging and turns green once fully charged, at which point the charging cable should be unplugged promptly.**
>
> * **When the battery voltage drops below 10 V, or the buzzer emits consecutive beeping tones, immediately stop operation and recharge the battery.**
>
> * **When storing for extended periods, charge the battery fully, disconnect all cables, and store the unit in a cool, dry place free from strong static electricity and magnetic fields, away from high temperatures and liquids.**
>
> * **Never strike, throw, step on, disassemble, modify, or weld the battery and charger.**
>
> * **Never connect the battery directly to a wall power outlet or short-circuit the positive and negative terminals with metal objects, as this can cause battery damage, overheating, or fire.**

> [!NOTE]
>
> **Important Statement: Hiwonder assumes no liability for product damage, economic losses, or safety accidents resulting from failure to adhere strictly to the above operational guidelines and battery safety rules.**

#### 1.3.1.2 Charging Method

> [!NOTE]
>
> **Before the first power-on, ensure the battery and mating connector at the bottom of the robot are properly connected. Unscrew the two bottom screws to detach the sheet metal cover for inspection.**
>
> <img src="../_static/media/chapter_1/section_1/image153.png" class="common_img" style="width:600px;"/>

1. Ensure the power switch on the robot is toggled to **OFF**.

<img src="../_static/media/chapter_1/section_1/image12.png" class="common_img" style="width:600px;"/>

2. Insert the charging connector of the 12.6 V charger into the charging port on the side of the STM32 control board.

<img src="../_static/media/chapter_1/section_1/image13.png" class="common_img" style="width:600px;"/>

3. Observe the indicator light on the charger to monitor the charging state. Red indicates charging in progress, while green indicates charging is complete.

<img src="../_static/media/chapter_1/section_1/image14.png" class="common_img" style="width:600px;"/>

> [!NOTE]
>
> **Once charging is complete, promptly unplug the charger to prevent battery overcharging.**

### 1.3.2 Initial Power-on and Inspection

#### 1.3.2.1 Pre-Power-on Precautions

> [!NOTE]
>
> **Before powering on, check whether each joint of the robotic arm is installed properly and clear all obstacles within its motion range. After power-on, never force joint movement by hand, and avoid grasping excessively heavy objects, maintaining extreme angles for long durations, or running under blocked conditions. If lagging, continuous shaking, abnormal noise, positional deviations, or noticeable servo overheating, smoke, or odor occur during operation, immediately terminate the program, cut off power, inspect the hardware, and contact technical support if needed to prevent servo burnout from sustained stalling or high loads.**

#### 1.3.2.2 Power-on Status and Inspection Instructions

> [!NOTE]
>
> **Place the robot in the correct posture prior to powering on. Incorrect starting posture may lead to servo stalling.**

**Correct Starting Posture:**

<img src="../_static/media/chapter_1/section_1/image159.png" class="common_img" style="width:600px;"/>

**Incorrect Starting Posture:**

<img src="../_static/media/chapter_1/section_1/image160.png" class="common_img" style="width:600px;"/>

1. Place the robot on a flat, smooth surface and toggle the switch on the right side of the robot to **ON**. At this time, the red LED labeled PWR and the blue LED on the STM32 control board light up and stay solid.

<img src="../_static/media/chapter_1/section_1/image12.png" class="common_img" style="width:600px;"/>

2. The blue LED labeled LED1 on the lower right of the expansion board lights up and starts flashing. At this stage, only the network configuration service is active, while the ROS system and other services are still initializing. Wait for the buzzer to emit a short beep and the robot to reset its posture, signaling that system startup is complete.

**Jetson Series Controller:**

<img src="../_static/media/chapter_1/section_1/image15.png" class="common_img" style="width:600px;"/>

**Raspberry Pi 5 Controller:**

<img src="../_static/media/chapter_1/section_1/image164.png" class="common_img" style="width:600px;"/>

**Robot Reset Posture:**

<img src="../_static/media/chapter_1/section_1/image154.png" class="common_img" style="width:600px;"/>

> [!NOTE]
>
> **If the buzzer fails to emit a short beep, onboard hardware such as the IMU, buzzer, or buttons may have encountered an issue. This rarely happens during normal usage. If this problem occurs, contact technical support for assistance.**

3. The device defaults to AP Direct Connection mode from the factory. After successful boot, a Wi-Fi hotspot starting with **WN** is generated. When connecting via app or remote desktop, enter the default password **12345678**.

> [!NOTE]
>
> **If the device hotspot cannot be discovered, troubleshoot using the following points:**
>
> * **Check step 2 above to verify whether LED1 on the expansion board is blue and flashing.**
> * **Connect a Type-C cable to the Type-C port on the Jetson board, then remotely access the robot system desktop to verify whether the system booted normally. For remote access procedures, refer to [Section 1.4.2.3 Type-C Cable Fixed IP Connection](#p1423).**

4. Hardware module inspection can be performed according to the table below:

| Module | Inspection Step | Expected Behavior |
| :--- | :--- | :--- |
| Expansion board LED | Observe LED illumination and flashing pattern | Factory default is AP Direct Connection mode. LED is blue and flashing, indicating network service configuration is complete. |
| Buzzer | Check for the initial short beep | A short beep sounds, indicating onboard expansion board hardware functions normally. |
| Button KEY1 on expansion board | Switch network state | After connecting to STA LAN mode via app, press and hold KEY1 to verify if indicator LED1 flashes. |
| 6-channel microphone | Voice broadcast announces Ready in Chinese upon boot | Responds to wake-up word. Saying the Chinese wake-up phrase after boot yields a voice prompt response. |
| Depth camera + robotic arm | 1. Open app and connect robot.<br>2. Open Robot Control to inspect live depth camera video feed.<br>3. Call up robotic arm control buttons and drag each joint servo in sequence. | Live video feed displays in real time and servos rotate smoothly. |
| STM32 controller | Control the robot using wireless controller or app Robot Control after boot. | Robot body responds and moves normally. |

<p id="p133"></p>

### 1.3.3 App Installation and Connection

The robot can be operated using the app **WonderAi**. This section explains how to obtain and install the app.

> [!NOTE]
>
> * **Grant all system permissions requested by the app to ensure proper functionality.**
> * **Before opening the app, enable GPS location and Wi-Fi on the mobile device, and turn off cellular data.**

#### 1.3.3.1 App Installation

**Scan the QR code below to download and install the app:**

<img src="../_static/media/chapter_1/section_1/image184.png" class="common_img" style="width:300px;"/>

#### 1.3.3.2 Connection Modes Overview

After installing the app, connect to the robot. The robot supports two network modes:

1. AP Direct Connection Mode: The development board broadcasts a Wi-Fi hotspot for direct mobile phone connection, without routing through an external network.

2. STA LAN Mode: The development board connects directly to a designated local Wi-Fi router or hotspot, enabling external network connectivity.

**The robot defaults to AP Direct Connection mode. All robot features and control functions remain identical regardless of whether AP Direct Connection or STA LAN mode is selected.**

Configuring AP Direct Connection mode first is recommended to explore corresponding features, while LAN mode can be configured later as needed.

#### 1.3.3.3 Direct Connection Mode - Required

The following demonstration uses an Android device as an example, and the operational steps apply equally to iOS devices.

1. Open the app **WonderAi** and tap **ROSpider**.

<img src="../_static/media/chapter_1/section_1/image152.png" class="common_img" style="width:600px;"/>

2. Tap the **+** button in the lower-right corner of the interface and select **Direct Connection Mode**.

<img src="../_static/media/chapter_1/section_1/image21.png" class="common_img" style="width:600px;"/>

> [!NOTE]
>
> **To connect using LAN mode, refer to [Section 1.3.3.4 LAN Mode Connection - Optional](#p1334).**

3. Tap **Go to connect device hotspots** to open the system Wi-Fi settings page, then connect to the hotspot generated by the robot.

<img src="../_static/media/chapter_1/section_1/image22.png" class="common_img" style="width:600px;"/>

4. The hotspot name begins with **WN**, and the default password is **12345678**.

> [!NOTE]
>
> **On iOS devices, wait until the Wi-Fi icon** <img src="../_static/media/chapter_1/section_1/image24.png" class="inline-icon" style="width:50px;"/> **appears in the system status bar before returning to the app, otherwise the device search may fail. If the device cannot be found, tap the refresh icon** <img src="../_static/media/chapter_1/section_1/image25.png" class="inline-icon" style="width:50px;"/> **in the upper-right corner of the app interface.**

5. Return to the app and tap the corresponding robot icon to enter the mode selection interface.

<img src="../_static/media/chapter_1/section_1/image111.png" class="common_img" style="width:600px;"/>

> [!NOTE]
>
> **If a system prompt appears stating Internet not available, tap Keep Connection.**

6. If a prompt appears asking **Whether to switch and enter the searched product interface?**, an incorrect product model was selected in step 1. Tap **OK** to switch directly to the correct model selection interface.

<img src="../_static/media/chapter_1/section_1/image26.png" class="common_img" style="width:500px;"/>

7. The mode selection interface is shown below:

<img src="../_static/media/chapter_1/section_1/image111.png" class="common_img" style="width:600px;"/>

For detailed usage instructions on each mode, refer to **[Section 1.3.4.2 App Features Overview](#p1342)**.

<p id="p1334"></p>

#### 1.3.3.4 LAN Mode Connection - Optional

1. Connect the mobile device to a 5 GHz Wi-Fi network, such as Hiwonder_5G. On dual-band routers with separate SSIDs, the 2.4 GHz and 5 GHz bands are distinguished by name.

<img src="../_static/media/chapter_1/section_1/image27.png" class="common_img" style="width:500px;"/>

2. Open the app **WonderAi** and tap **ROSpider**.

3. Tap the **+** button in the lower-right corner and select **LAN Mode**.

<img src="../_static/media/chapter_1/section_1/image28.png" class="common_img" style="width:600px;"/>

4. When prompted by the app, enter the password for the connected Wi-Fi network. Double-check that it is entered accurately to prevent connection failures, then tap **OK**.

<img src="../_static/media/chapter_1/section_1/image29.png" class="common_img" style="width:300px;"/>

5. Tap **Go to connect device hotspots**.

<img src="../_static/media/chapter_1/section_1/image30.png" class="common_img" style="width:600px;"/>

6. The phone automatically navigates to the Wi-Fi settings page. Connect to the hotspot starting with **WN**, enter password **12345678**, then tap the back button to return to the app.

7. The app starts establishing the connection.

<img src="../_static/media/chapter_1/section_1/image32.png" class="common_img" style="width:600px;"/>

8. After a brief wait, the main interface displays the robot icon and device name, while LED1 on the expansion board stays solid blue.

9. Press and hold the robot icon in the app to inspect the assigned IP address and Device ID.

<img src="../_static/media/chapter_1/section_1/image112.png" class="common_img" style="width:400px;"/>

10. Search for this IP address in a remote desktop tool to establish a connection. Specific connection methods are detailed in **[Section 1.4 Development Environment Setup](#14-development-environment-setup)**.

11. To switch back to AP Direct Connection mode from LAN mode, press and hold button **KEY1** on the expansion board until the blue LED flashes.

### 1.3.4 App Control

The robot can be operated via the **WonderAi** app to experience select AI vision capabilities. This section explains the operation methods for each feature. The demonstration uses an iOS device as an example, and the procedures apply equally to Android systems.

#### 1.3.4.1 Preparation

1. Power on the robot. To review the startup state, refer to **[Section 1.3.2 Initial Power-on and Inspection](#132-initial-power-on-and-inspection)**.

2. Install the **WonderAi** app and connect to the robot according to **[Section 1.3.3 App Installation and Connection](#p133)**.

<p id="p1342"></p>

#### 1.3.4.2 App Features Overview

The app provides 6 functional modes: Robot Control, Robot Performance, Lidar, Line Following, Auto Shooting, and Gesture Control.

<img src="../_static/media/chapter_1/section_1/image111.png" class="common_img" style="width:600px;"/>

The table below outlines each functional mode:

| Icon | Mode Name | Description |
| :---: | :---: | :--- |
| <img src="../_static/media/chapter_1/section_1/image113.png" /> | Robot Control | Controls robot movement, gait switching, step amplitude, speed, pitch angle, and related motion parameters. |
| <img src="../_static/media/chapter_1/section_1/image114.png" /> | Robot Performance | Executes preset and custom action groups, and enables self-balancing capabilities. |
| <img src="../_static/media/chapter_1/section_1/image115.png" /> | Lidar | Provides Avoid obstacle, Lidar following, and Lidar guarding modes. |
| <img src="../_static/media/chapter_1/section_1/image116.png" /> | Line Following | Follows laid tape tracks by selecting track color as the target recognition hue. |
| <img src="../_static/media/chapter_1/section_1/image117.png" /> | Auto Shooting | Selects target ball color for tracking and kicking execution. |
| <img src="../_static/media/chapter_1/section_1/image118.png" /> | Gesture Control | Recognizes designated hand gestures to trigger corresponding robotic response actions. |

#### 1.3.4.3 Robot Control

* **Interface Introduction**

Tap **Robot Control** on the mode selection screen to access the control interface.

<img src="../_static/media/chapter_1/section_1/image119.png" class="common_img" style="width:600px;"/>

* **Function Description**

| Icon | Function Description |
| :---: | :--- |
| <img src="../_static/media/chapter_1/section_1/image120.png" style="width:50%; height:auto;" /> | Side buttons rotate the robot left and right, while the **Attention** button restores the initial posture. |
| <img src="../_static/media/chapter_1/section_1/image121.png" style="width:50%; height:auto;" /> | Dragging the virtual joystick moves the hexapod robot forward, backward, left, and right. |
| <img src="../_static/media/chapter_1/section_1/image122.png" style="width:50%; height:auto;" /> | Selects the locomotion gait. |
| <img src="../_static/media/chapter_1/section_1/image123.png" style="width:50%; height:auto;" /> | Displays real-time camera video stream. |
| <img src="../_static/media/chapter_1/section_1/image124.png" style="width:50%; height:auto;" /> | Adjusts step amplitude from 10 to 60 and adjusts movement speed from 10 to 100. |
| <img src="../_static/media/chapter_1/section_1/image125.png" style="width:50%; height:auto;" /> | Adjusts robot chassis height. |
| <img src="../_static/media/chapter_1/section_1/image126.png" style="width:50%; height:auto;" /> | From the robot's perspective, button **Z+** twists the body left, and button **Z-** twists the body right. |
| <img src="../_static/media/chapter_1/section_1/image127.png" style="width:50%; height:auto;" /> | From the robot's perspective, button **Y+** tilts the front down and rear up, button **Y-** tilts the front up and rear down, button **X-** tilts the left side down and right up, and button **X+** tilts the left side up and right down. |
| <img src="../_static/media/chapter_1/section_1/image183.png" style="width:50%; height:auto;" /> | Adds executable action groups. |
| <img src="../_static/media/chapter_1/section_1/image128.png" style="width:50%; height:auto;" /> | Controls robotic arm joint motion. |

#### 1.3.4.4 Robot Performance

* **Interface Introduction**

Tap **Robot Performance** on the mode selection screen to enter the interface.

1. The left section contains action group selection for preset actions and custom actions.
2. The right section contains the self-balancing function toggle.

<img src="../_static/media/chapter_1/section_1/image129.png" class="common_img" style="width:600px;"/>

| Icon | Function Description |
| :---: | :--- |
| <img src="../_static/media/chapter_1/section_1/image130.png" style="width:60%; height:auto;"/> | Tap buttons to execute preset and custom action groups. |
| <img src="../_static/media/chapter_1/section_1/image131.png" style="width:200px;"/> | Enables or disables hexapod self-balancing. |

#### 1.3.4.5 Lidar

* **Interface Introduction**

Tap **Lidar** on the mode selection screen to enter the control interface. The interface consists of two sections:

1. The left section contains mode toggles and parameter adjustments.
2. The right section displays the live camera stream.

<img src="../_static/media/chapter_1/section_1/image132.png" class="common_img" style="width:600px;"/>

| Icon | Function Description |
| :---: | :--- |
| <img src="../_static/media/chapter_1/section_1/image133.png" /> | Enables or disables Avoid obstacle. |
| <img src="../_static/media/chapter_1/section_1/image134.png" /> | Enables or disables Lidar following. |
| <img src="../_static/media/chapter_1/section_1/image135.png" /> | Enables or disables Lidar guarding. |
| <img src="../_static/media/chapter_1/section_1/image136.png" /> | Adjusts radar detection distance from 0.5 to 1.5 meters. |
| <img src="../_static/media/chapter_1/section_1/image137.png" /> | Adjusts robot movement speed from 0.02 to 0.1 meters per second. |

* **Operation Steps and Effects**

> [!NOTE]
>
> **In this mode, the LiDAR detection area is an unobstructed forward fan-shaped zone. After starting a mode, place obstacles within the effective detection area to ensure proper operation.**

1. Avoid obstacle: Tap the switch to the right of **Avoid obstacle** to start the mode. The hexapod robot marches continuously forward, turning automatically to steer clear when detecting obstacles.
2. Lidar following: Tap the switch to the right of **Lidar following** to start the mode. When detecting a target obstacle, the hexapod robot adjusts its position to maintain a set distance from the object.
3. Lidar guarding: Tap the switch to the right of **Lidar guarding** to start the mode. When detecting an obstacle, the hexapod robot rotates to keep facing toward the obstacle.

#### 1.3.4.6 Line Following

> [!NOTE]
>
> * **Before starting, lay out a track using colored tape and place the robot directly on the track.**
> * **Select a moderate color recognition range. Too broad a range captures extraneous environmental colors, while too narrow a range causes tracking loss. Keep objects with similar colors out of the camera view.**
> * **Ensure no other objects containing the target color exist within the camera field of view during tracking.**

* **Interface Introduction**

Tap **Line Following** on the mode selection screen to enter the interface. It consists of two sections:

1. The left section contains mode switches and color picker settings.
2. The right section displays the live camera stream.

<img src="../_static/media/chapter_1/section_1/image138.png" class="common_img" style="width:600px;"/>

* **Function Description**

| Icon | Function Description |
| :---: | :--- |
| <img src="../_static/media/chapter_1/section_1/image139.png" /> | Starts or stops the feature |
| <img src="../_static/media/chapter_1/section_1/image140.png" /> | Adjusts color threshold range from 0.05 to 1.00. |
| <img src="../_static/media/chapter_1/section_1/image141.png" /> | Samples color from a designated region in the camera stream. |
| <img src="../_static/media/chapter_1/section_1/image142.png" /> | Displays currently sampled color. |
| <img src="../_static/media/chapter_1/section_1/image143.png" /> | Tapping the pick button toggles it to Confirm Pick to lock in the sampled color. |
| <img src="../_static/media/chapter_1/section_1/image144.png" style="width:300px"/> | Displays live camera feed. |

* **Operation Steps and Effects**

1. Tap **Pick**, then drag the circular selector in the video stream over the track to sample its color.
2. Tap **OK**, and the selected hue appears under **Selected Color**.
3. Tap **Start** to begin tracking. The robot navigates autonomously along the colored line.

#### 1.3.4.7 Auto Shooting

> [!NOTE]
>
> * **Place the target ball on the same level ground as the robot and translate the target smoothly across the floor for optimal tracking performance.**
> * **Select a moderate color recognition range. Too broad a range captures extraneous background colors, while too narrow a range causes tracking loss. Keep objects with similar colors out of the camera view.**

* **Interface Introduction**

Tap **Auto Shooting** on the mode selection screen to enter the interface. It consists of two sections:

1. The left section contains mode switches and color picker controls.
2. The right section displays the live camera stream.

<img src="../_static/media/chapter_1/section_1/image145.png" class="common_img" style="width:600px;"/>

* **Function Description**

| Icon | Function Description |
| :---: | :--- |
| <img src="../_static/media/chapter_1/section_1/image139.png" /> | Starts or stops the feature |
| <img src="../_static/media/chapter_1/section_1/image140.png" /> | Adjusts color threshold range from 0.05 to 1.00. |
| <img src="../_static/media/chapter_1/section_1/image141.png" /> | Samples color from a designated region in the camera stream. |
| <img src="../_static/media/chapter_1/section_1/image142.png" /> | Displays currently sampled color. |
| <img src="../_static/media/chapter_1/section_1/image143.png" /> | Tapping the pick button toggles it to Confirm Pick to lock in the sampled color. |
| <img src="../_static/media/chapter_1/section_1/image146.png" style="width:300px"/> | Displays live camera feed. |

* **Operation Steps and Effects**

1. Tap **Pick**, then drag the circular selector in the video stream over the ball to sample its color.
2. Tap **OK**, and the selected hue appears under **Selected Color**.
3. Tap **Start** to begin tracking. The robot tracks the target ball and kicks it.

#### 1.3.4.8 Gesture Control

* **Interface Introduction**

Tap **Gesture Control** on the mode selection screen to enter the interface. It consists of two sections:

1. The left section contains mode switches and operational guidance.
2. The right section displays the live camera stream.

<img src="../_static/media/chapter_1/section_1/image147.png" class="common_img" style="width:600px;"/>

* **Function Description**

| Icon | Function Description |
| :---: | :--- |
| <img src="../_static/media/chapter_1/section_1/image139.png" /> | Starts or stops the feature |
| <img src="../_static/media/chapter_1/section_1/image148.png" /> | Taps to display operating help information. |

* **Operation Steps and Effects**

Tap **Start** to enable gesture recognition. Performing different hand gestures elicits specific robot movements:

| Gesture Name | Gesture Description | Example | Feedback Action |
| :---: | :--- | :---: | :--- |
| rock | Closed fist rock sign | <img class="inline-icon" src="../_static/media/chapter_1/section_1/image155.png" /> | Attack motion |
| thumbs_up | Thumbs up | <img class="inline-icon" src="../_static/media/chapter_1/section_1/image156.png" /> | Body twist |
| OK | OK sign | <img class="inline-icon" src="../_static/media/chapter_1/section_1/image157.png" /> | Wave arm greeting |
| yes | Victory or peace sign | <img class="inline-icon" src="../_static/media/chapter_1/section_1/image158.png" /> | Rapid left-right spin |

<p id="p135"></p>

### 1.3.5 Wireless Controller Remote Control

#### 1.3.5.1 Precautions

1. Confirm the wireless controller receiver is inserted prior to powering on the robot. The receiver is pre-installed on the STM32 controller at the factory.
2. When loading batteries into the controller, observe proper battery polarity.

<img src="../_static/media/chapter_1/section_1/image33.png" class="common_img" style="width:600px;"/>

3. Powering on the robot automatically launches the app auto-start service, which includes the wireless controller service. Direct control is ready without additional configuration.
4. Because wireless controller signals can cross-connect across devices, avoid using multiple controllers simultaneously in the same testing arena to prevent unintended interference.
5. After switching the controller on, if connection is not established within 30 seconds, or if the controller remains idle for 5 minutes after connecting, it enters sleep mode automatically. Press **START** to wake up the controller.

#### 1.3.5.2 Device Connection

1. Once the robot completes its boot sequence, push the controller power switch to **ON**. Both red and green LEDs on the controller flash simultaneously.
2. After several seconds, pairing completes automatically. Once paired successfully, the green LED stays solid and the red LED turns off.

<img src="../_static/media/chapter_1/section_1/image34.png" class="common_img" style="width:600px;"/>

<p id="p1353"></p>

#### 1.3.5.3 Button Descriptions

The tables below describe the button and joystick mapping from the robot first-person perspective:

> [!NOTE]
>
> * **Buttons and joysticks can be used concurrently for combined robot control.**
> * **Pressing any motion button causes the robot to step in place continuously using the most recent gait until a button is pressed again to reset the body.**
> * **Press SELECT+START to toggle between body remote control mode and robotic arm control mode. A single buzzer beep indicates body remote control mode, and two beeps indicate robotic arm control mode.**

**Robot Control Mode:**

| Button | Function in Robot Control Mode | Action Type |
| :---: | :--- | :---: |
| START | Stop and reset body posture, or exit sleep mode | Tap |
| SELECT+START | Switch control mode, one beep for body mode, two beeps for robotic arm mode | Tap |
| L1 | Increase movement speed and stepping frequency | Hold |
| L2 | Decrease movement speed and stepping frequency | Hold |
| R1 | Increase leg lift height | Hold |
| R2 | Decrease leg lift height | Hold |
| Left joystick up | Tripod gait forward, large stride | Hold |
| Left joystick down | Tripod gait backward, large stride | Hold |
| Left joystick left | Tripod gait move left, large stride | Hold |
| Left joystick right | Tripod gait move right, large stride | Hold |
| Y | Pitch body upward | Hold |
| A | Pitch body downward | Hold |
| X | Ripple gait turn left, small stride | Tap |
| B | Ripple gait turn right, small stride | Tap |
| D-pad up | Ripple gait forward, small stride | Hold |
| D-pad down | Ripple gait backward, small stride | Hold |
| D-pad left | Ripple gait move left, small stride | Hold |
| D-pad right | Ripple gait move right, small stride | Hold |
| Right joystick up | Elevate body height | Hold |
| Right joystick down | Lower body height | Hold |
| Right joystick left | Tripod gait turn left, large stride | Hold |
| Right joystick right | Tripod gait turn right, large stride | Hold |

**Robotic Arm Control Mode:**

| Button | Function in Robotic Arm Control Mode | Action Type |
| :---: | :--- | :---: |
| START | Stop and reset body posture, or exit sleep mode | Tap |
| SELECT+START | Switch control mode, one beep for body mode, two beeps for robotic arm mode | Tap |
| L1 | Servo ID 21 tilt forward | Hold |
| L2 | Servo ID 21 tilt backward | Hold |
| R1 | Servo ID 22 tilt backward | Hold |
| R2 | Servo ID 22 tilt forward | Hold |
| Left joystick up | Tripod gait forward, large stride | Hold |
| Left joystick down | Tripod gait backward, large stride | Hold |
| Left joystick left | Tripod gait move left, large stride | Hold |
| Left joystick right | Tripod gait move right, large stride | Hold |
| Y | Servo ID 24 gripper open | Hold |
| A | Servo ID 24 gripper close | Hold |
| X | Servo ID 23 rotate counterclockwise | Tap |
| B | Servo ID 23 rotate clockwise | Tap |
| D-pad up | Servo ID 20 tilt forward | Hold |
| D-pad down | Servo ID 20 tilt backward | Hold |
| D-pad left | Servo ID 19 robotic arm pan left | Hold |
| D-pad right | Servo ID 19 robotic arm pan right | Hold |
| Right joystick up | Elevate body height | Hold |
| Right joystick down | Lower body height | Hold |
| Right joystick left | Tripod gait turn left, large stride | Hold |
| Right joystick right | Tripod gait turn right, large stride | Hold |

<p id="p14"></p>

## 1.4 Development Environment Setup

> [!NOTE]
>
> * **Review this chapter first when running programs, inspecting source code, or modifying routines on a computer.**
> * **On robot models with the Jetson Orin Nano or Orin NX controller, connect the HDMI virtual display emulator to the board port so the remote desktop renders properly.**
>
> <img src="../_static/media/chapter_1/section_1/image151.png" class="common_img" style="width:600px;"/>

### 1.4.1 Remote Tool Introduction and Installation

**Jetson Series Controllers:**

NoMachine is a graphical remote desktop application that enables full computer control over the robot by connecting to its Wi-Fi network. For desktop computers, using a 5 GHz wireless network adapter is recommended for optimal connection stability.

Installation steps:

1. Navigate to the folder [2. Softwares\2. Remote Desktop Software\1. Graphical Remote Desktop Access Tool](https://drive.google.com/drive/folders/1VacQOxK3gC51wm_ntJUIE9yAadvw371t?usp=sharing) in the tutorial directory and double-click **nomachine_8.4.2_10_x64.exe**.
2. Click **Next**.

<img src="../_static/media/chapter_1/section_1/image48.png" class="common_img" style="width:600px;"/>

3. Select **English** as the installation language, check the license agreement, and click **Next**.

<img src="../_static/media/chapter_1/section_1/image49.png" class="common_img" style="width:600px;"/>

4. Retain the default installation destination path and click **Next**.

<img src="../_static/media/chapter_1/section_1/image50.png" class="common_img" style="width:600px;"/>

5. Once the installation completed window appears, click **Finish**.

<img src="../_static/media/chapter_1/section_1/image51.png" class="common_img" style="width:600px;"/>

6. Click **Yes** to reboot the computer. Do not skip this reboot step.

<img src="../_static/media/chapter_1/section_1/image52.png" class="common_img" style="width:600px;"/>

**Raspberry Pi 5 Controller:**

VNC Viewer is a graphical remote control tool allowing direct desktop management over Wi-Fi. For desktop computers, using a 5 GHz wireless network adapter is recommended.

Installation steps:

1. Navigate to [2. Softwares\2. Remote Desktop Software\1. Graphical Remote Desktop Access Tool](https://drive.google.com/drive/folders/1VacQOxK3gC51wm_ntJUIE9yAadvw371t?usp=sharing) in the tutorial directory and double-click **VNC-Viewer-6.17.731-Windows .exe**.
2. Select **English** as the installation language and click **OK**.

<img src="../_static/media/chapter_1/section_1/image165.png" class="common_img" style="width:600px;"/>

3. Click **Next**.

<img src="../_static/media/chapter_1/section_1/image166.png" class="common_img" style="width:600px;"/>

4. Accept the license terms and click **Next**.

<img src="../_static/media/chapter_1/section_1/image167.png" class="common_img" style="width:600px;"/>

5. In the next dialog, click **Install**.

<img src="../_static/media/chapter_1/section_1/image168.png" class="common_img" style="width:600px;"/>

6. When the installation finishes, click **Finish**.

<img src="../_static/media/chapter_1/section_1/image169.png" class="common_img" style="width:600px;"/>

7. Open the installed application by clicking the icon <img src="../_static/media/chapter_1/section_1/image177.png" class="inline-icon" style="width:200px;"/>.

### 1.4.2 Remote Device Connection

<p id ="p1.4.2.1"></p>

#### 1.4.2.1 Direct Connection Mode

AP Direct Connection Mode: The development board broadcasts a Wi-Fi hotspot for direct client connection without external network access.

**Jetson Series Controllers:**

1. The robot defaults to AP Direct Connection mode, generating a hotspot starting with **WN**. Search for and connect to this hotspot on the computer using the password **12345678**:

<img src="../_static/media/chapter_1/section_1/image178.png" class="common_img" style="width:500px;"/>

2. Open NoMachine, enter the IP address **192.168.149.1** in the search bar, then click **Configure connection to new host 192.168.149.1**.

<img src="../_static/media/chapter_1/section_1/image54.png" class="common_img" style="width:600px;"/>

3. Rename the connection to **ROSpider**, keep all other settings at default, and click **Connect**.

<img src="../_static/media/chapter_1/section_1/image55.png" class="common_img" style="width:600px;"/>

4. Enter `ubuntu` for Username and `ubuntu` for Password. Check the box to remember credentials, then click **OK**.

<img src="../_static/media/chapter_1/section_1/image56.png" class="common_img" style="width:600px;"/>

> [!NOTE]
>
> **When configuring the robot in STA LAN mode, follow identical steps, substituting the assigned local IP address, Username, and Password in steps 2, 3, and 4.**

<img src="../_static/media/chapter_1/section_1/image57.png" class="common_img" style="width:600px;"/>

<img src="../_static/media/chapter_1/section_1/image58.png" class="common_img" style="width:600px;"/>

<img src="../_static/media/chapter_1/section_1/image59.png" class="common_img" style="width:600px;"/>

<img src="../_static/media/chapter_1/section_1/image60.png" class="common_img" style="width:800px;"/>

**Raspberry Pi 5 Controller:**

1. The robot defaults to AP Direct Connection mode, generating a hotspot starting with **WN**. Connect to this hotspot on the computer using the password **12345678**:

<img src="../_static/media/chapter_1/section_1/image178.png" class="common_img" style="width:500px;"/>

2. Open VNC Viewer, enter the Raspberry Pi 5 IP address **192.168.149.1** in AP mode, and press **Enter**. If an unencrypted connection warning appears, click **Continue**.

<img src="../_static/media/chapter_1/section_1/image179.png" class="common_img" style="width:600px;"/>

3. Enter **pi** for Username and **raspberrypi** for Password. Check the box to remember credentials, then click **OK**.

<img src="../_static/media/chapter_1/section_1/image170.png" class="common_img" style="width:600px;"/>

> [!NOTE]
>
> **When configuring the robot in STA LAN mode, follow identical steps, substituting the assigned local IP address, Username, and Password in steps 2 and 3.**

<img src="../_static/media/chapter_1/section_1/image171.png" class="common_img" style="width:800px;"/>

#### 1.4.2.2 LAN Mode Connection

STA LAN Mode: The development board connects to a designated local Wi-Fi router or hotspot, enabling external network access.

> [!NOTE]
>
> * **When configuring LAN mode via a mobile device, enable location services first.**
> * **Do not switch network modes using standard desktop system network GUI settings because Wi-Fi routing utilizes dedicated configuration files. Follow the instructions below to configure parameters.**

<img src="../_static/media/chapter_1/section_1/image61.png" class="common_img" style="width:600px;"/>

Taking the Jetson controller as an example, perform the following steps:

1. Click the terminal icon <img src="../_static/media/chapter_1/section_1/image62.png" class="inline-icon" style="width:80px;"/> on the left side of the desktop to open a command line terminal.

> [!NOTE]
>
> **On Raspberry Pi 5, open the black terminal icon** <img src="../_static/media/chapter_1/section_1/image176.png" class="inline-icon" style="width:80px;"/>.

2. Enter the command and press **Enter** to navigate to the configuration directory:

```bash
cd wifi_manager
```

3. Enter the command and press **Enter** to open the configuration file:

```bash
gedit wifi_conf.py
```

4. Change `WIFI_MODE` to `2`. Value `1` denotes AP Direct Connection mode generating an autonomous hotspot, while value `2` denotes STA LAN mode connecting to an existing router network.

<img src="../_static/media/chapter_1/section_1/image65.png" class="common_img" style="width:600px;"/>

5. Update `WIFI_STA_SSID` and `WIFI_STA_PASSWORD` to match the local router Wi-Fi credentials. Ensure the strings remain enclosed in single quotes. The robot supports 5 GHz Wi-Fi networks.

<img src="../_static/media/chapter_1/section_1/image66.png" class="common_img" style="width:600px;"/>

6. Press **Ctrl+S** to save modifications, then close the text editor window.

7. Return to the terminal and execute the command to restart the Wi-Fi service:

```bash
sudo systemctl restart wifi.service
```

8. To switch back to Direct Connection mode, edit `wifi_conf.py` again, set `WIFI_MODE` back to `1`, and restart the Wi-Fi service.

<p id="p1423"></p>

#### 1.4.2.3 Type-C Cable Fixed IP Connection

> [!NOTE]
>
> **This connection method applies exclusively to Jetson series controllers.**

The robot can enable a remote NDIS-compatible device to enhance remote desktop smoothness using a fixed IP address `192.168.55.1`. This method eliminates the need to connect to a Wi-Fi hotspot or local router.

1. Connect the robot to the computer using a **Type-C** data cable.

<img src="../_static/media/chapter_1/section_1/image68.png" class="common_img" style="width:600px;"/>

2. Right-click **This PC** on the computer desktop and select **Manage**.

<img src="../_static/media/chapter_1/section_1/image69.png" class="common_img" style="width:500px;"/>

3. Click **Device Manager** in the left sidebar, locate the NDIS driver entry under **Network adapters**, right-click it, and select **Update driver**.

<img src="../_static/media/chapter_1/section_1/image70.png" class="common_img" style="width:600px;"/>

4. After driver installation finishes, use NoMachine to connect via the fixed IP address `192.168.55.1` by following the standard connection steps in [Section 1.4.2.1 Direct Connection Mode](#p1.4.2.1).

#### 1.4.2.4 SSH Connection

Unlike NoMachine and VNC, MobaXterm does not render the graphical desktop, providing a fast command line terminal interface. SSH conserves computational overhead and system memory on the robot by avoiding full window rendering.

1. Open the installation package located in [2. Softwares\2. Remote Desktop Software\2. SSH Remote Login Client](https://drive.google.com/drive/folders/1zBYydgiParB25K-X1pzuNjOR3T_iHSQ4?usp=sharing) in the tutorial directory and complete the one-click installation.
2. Obtain the robot IP address via AP Direct Connection mode or STA LAN mode.

**Creating a New Session:**

The following steps illustrate connecting via AP Direct Connection mode. The same procedure applies to LAN mode by replacing the IP address.

1. In the main interface, click **Session** in the upper-left corner to create a new session. Select SSH, enter the recorded IP address **192.168.149.1**, and click **OK**.

<img src="../_static/media/chapter_1/section_1/image71.png" class="common_img" style="width:600px;"/>

<img src="../_static/media/chapter_1/section_1/image72.png" class="common_img" style="width:600px;"/>

<img src="../_static/media/chapter_1/section_1/image73.png" class="common_img" style="width:600px;"/>

If prompted with a master password popup, click the third option to proceed.

<img src="../_static/media/chapter_1/section_1/image74.png" class="common_img" style="width:600px;"/>

2. When prompted on the terminal screen, enter the username and password matching the corresponding controller, which are identical to the account credentials used in Direct Connection or LAN mode, then press **Enter**. Note that entering the password produces no visual feedback on the screen, just like in standard Linux systems.

> [!NOTE]
>
> **The username must be entered in lowercase characters. Even if the configured account name contains uppercase letters, lowercase characters must be used during login.**

3. Upon entering credentials correctly, access to the command shell is granted as shown below:

<img src="../_static/media/chapter_1/section_1/image75.png" class="common_img" style="width:600px;"/>

### 1.4.3 Volume Adjustment

Under default system settings, connecting to the robot system desktop via the remote connection tool NoMachine before the robot completes its power-on boot process automatically lowers the speaker volume. Click the sound button in the upper-right corner of the system desktop to adjust the robot speaker playback volume. This adjustment method applies equally to subsequent voice control lessons.

<img src="../_static/media/chapter_1/section_1/image76.png" class="common_img" style="width:500px;"/>

### 1.4.4 Remote Connection Resolution Settings - Optional

If the display resolution appears incorrect after logging in remotely via the NoMachine remote connection tool, configure the remote connection resolution using the steps below. Note that this configuration must also be repeated upon subsequent reconnections:

1. Move the mouse cursor to the top right of the remote window until the page-curl icon appears, as indicated by the red arrow below:

<img src="../_static/media/chapter_1/section_1/image77.png" class="common_img" style="width:600px;"/>

2. Click the page-curl icon and select **Display** from the menu.

<img src="../_static/media/chapter_1/section_1/image78.png" class="common_img" style="width:600px;"/>

3. Click **Change settings**.

<img src="../_static/media/chapter_1/section_1/image79.png" class="common_img" style="width:600px;"/>

4. Adjust the **Resolution** slider to 1920x1080 or a resolution matching the local computer monitor, then click **Modify**.

<img src="../_static/media/chapter_1/section_1/image80.png" class="common_img" style="width:600px;"/>

5. Click the back button repeatedly to return to the desktop, confirming that the new display resolution has taken effect.

<img src="../_static/media/chapter_1/section_1/image81.png" class="common_img" style="width:600px;"/>

## 1.5 Quick Mapping and Navigation

> [!NOTE]
>
> **The following demonstration uses the Jetson controller as an example. Procedures for Raspberry Pi 5 mapping and navigation are identical.**

### 1.5.1 Quick Mapping Experience

This lesson provides a quick hands-on experience with mapping and navigation features. Without performing complex operations, functions can be launched simply by clicking corresponding shortcut icons on the remote desktop.

Quick mapping requires controlling robot movement via a wireless controller or keyboard. When operating a single robot, using the wireless controller provides greater convenience. In multi-robot environments, keyboard teleoperation is recommended. This is because wireless controllers are susceptible to signal cross-talk, so operating multiple controllers in the same venue is not recommended to avoid unintended connections and accidental cross-control.

After mapping is complete, the resulting map is saved, and the mapping outcome can be inspected by enabling autonomous navigation. Note that the autonomous navigation feature always loads the most recently generated map. Regardless of which mapping method is used, any newly created map overwrites the previously saved map.

Manual mapping utilizes the `slam_toolbox` algorithm. The `slam_toolbox` package combines range information from the laser distance sensor in the form of `LaserScan` messages and computes TF coordinate transformations from the `odom` to `base` link to generate a 2D occupancy grid map of the environment. This package supports full serialization of reloadable SLAM map data and pose graphs for continuous mapping, localization, map merging, and related operations. It enables `slam_toolbox` to operate in synchronous mode, which processes all valid sensor measurements regardless of processing lag, as well as asynchronous mode, which processes valid sensor measurements whenever computational capacity allows.

For comprehensive algorithmic theory, terminal command mapping, and multi-map management, consult **[1. Tutorials\Mapping and Navigation Course\Mapping Tutorial](https://wiki.hiwonder.com/projects/ROSpider/en/jetson-orin-nano-version/docs/5_Mapping_and_Navigation_Course.html#_5-1-mapping-tutorial)**.

#### 1.5.1.1 Mapping Preparation

Before starting, ensure the touchscreen or remote desktop connection is operational, the wireless controller receiver is firmly seated in the USB port, and the remote desktop is connected according to **[Section 1.4 Development Environment Setup](#14-development-environment-setup)**.

> [!NOTE]
>
> **The wireless controller receiver is pre-installed on the STM32 controller before shipping.**

For controller button definitions, refer to **[Section 1.3.5.3 Button Descriptions](#p1353)**.

Desktop shortcut icons: Quick Mapping <img src="../_static/media/chapter_1/section_1/image35.png" class="inline-icon" style="width:100px;"/> and Autonomous Navigation <img src="../_static/media/chapter_1/section_1/image36.png" class="inline-icon" style="width:100px;"/>.

> [!NOTE]
>
> **Construct an enclosed test environment on flat ground in advance. If setting up obstacles, ensure obstacle heights exceed the horizontal scanning plane of the LiDAR.**

#### 1.5.1.2 Operation Steps

1. Place the robot inside the designated mapping area.
2. Double-click the desktop shortcut icon for SLAM quick mapping.
3. Multiple terminal windows open automatically to launch background nodes. Wait briefly for initialization.

<img src="../_static/media/chapter_1/section_1/image37.png" class="common_img" style="width:600px;"/>

4. The mapping interface displays upon successful launch.

<img src="../_static/media/chapter_1/section_1/image38.png" class="common_img" style="width:600px;"/>

5. Drive the robot across the area using the wireless controller to build the map. Refer to **[Section 1.3.5.3 Button Descriptions](#p1353)** for button controls.

> [!NOTE]
>
> **Stay within reasonable range of the robot to prevent wireless signal dropouts.**

Keyboard control can also be utilized. To use keyboard teleoperation, bring the designated teleoperation terminal into active focus:

<img src="../_static/media/chapter_1/section_1/image39.png" class="common_img" style="width:600px;"/>

Keyboard teleoperation key mappings:

| Key | Function | Description |
| :---: | :--- | :--- |
| W | Forward | Short press to toggle continuous forward motion |
| S | Backward | Short press to toggle continuous backward motion |
| A | Turn left | Long press to interrupt linear motion and rotate counterclockwise in place |
| D | Turn right | Long press to interrupt linear motion and rotate clockwise in place |

Pressing **W** or **S** causes continuous forward or backward movement. Pressing **A** or **D** interrupts linear translation to rotate in place, and releasing **A** or **D** stops rotation.

6. Once exploration is complete, click **Save Map** in the mapping GUI to persist the environment map.

<img src="../_static/media/chapter_1/section_1/image40.png" class="common_img" style="width:500px;"/>

7. The generated map is shown below:

<img src="../_static/media/chapter_1/section_1/image41.png" class="common_img" style="width:600px;"/>

8. To terminate quick mapping, press **Ctrl+C** in all four terminal windows.

<img src="../_static/media/chapter_1/section_1/image42.png" class="common_img" style="width:600px;"/>

### 1.5.2 Autonomous Navigation Experience

> [!NOTE]
>
> * **Navigation loads the most recently saved manual or autonomous map.**
> * **To explore multi-map saving and advanced navigation features, refer to [1. Tutorials\Mapping and Navigation Course](https://wiki.hiwonder.com/projects/ROSpider/en/jetson-orin-nano-version/docs/5_Mapping_and_Navigation_Course.html#_5-1-mapping-tutorial).**

#### 1.5.2.1 Operation Steps

1. Place the robot near its original mapping start pose.
2. Double-click the desktop shortcut icon for Navigation.
3. Wait for the background processes to initialize until the navigation interface appears.

<img src="../_static/media/chapter_1/section_1/image43.png" class="common_img" style="width:600px;"/>

4. In the top toolbar, **2D Pose Estimate** sets the initial estimated robot pose, **2D Goal Pose** sets a single navigation target, and **Nav2 Goal** sets waypoint targets.

<img src="../_static/media/chapter_1/section_1/image44.png" class="common_img" style="width:600px;"/>

5. Click **2D Goal Pose**, then click and drag on the map to set the goal position and orientation. The robot plans a path and navigates to the target.

<img src="../_static/media/chapter_1/section_1/image45.png" class="common_img" style="width:600px;"/>

6. Click the waypoint mode icon <img src="../_static/media/chapter_1/section_1/image46.png" class="inline-icon" style="width:300px;"/> in the lower-left corner to enable multi-point navigation. Click **Nav2 Goal**, then click and drag on the map to place waypoints in sequence.

<img src="../_static/media/chapter_1/section_1/image47.png" class="common_img" style="width:600px;"/>

7. After placing waypoints, click **Start Waypoint Following** in the lower left to begin waypoint navigation. The robot autonomously navigates through the waypoints while dynamically avoiding obstacles.

## 1.6 ROS Usage Introduction

The control architecture comprises two main layers. The first layer consists of the body chassis and robotic arm driven by the low-level STM32 controller, responsible for motor kinematics and sensor acquisition. The second layer is the high-level ROS controller, running the ROS environment, high-level algorithms, and vision pipelines.

### 1.6.1 ROS Controller Hardware Connection

Standard hardware communication uses a power cable and a USB serial cable to link the onboard USB serial port with the ROS controller. The STM32 board requires a 9 V to 12 V supply, and the ROS controller draws power from the dedicated output port of the STM32 board.

### 1.6.2 ROS Serial Communication Description

Serial communication is a standard data transport mechanism in embedded systems and robotics. ROSpider utilizes serial communication for bidirectional data transfer between the high-level ROS controller and the low-level STM32 controller.

To streamline data interchange across diverse tools and modules, an official hexadecimal communication protocol named RRC is established, serving as the foundational protocol for code execution and command exchange.

## 1.7 System Software Architecture

### 1.7.1 System Desktop

Taking the Jetson Orin Nano controller as an example, which applies equally to other ROS controllers, connect via NoMachine to view the system desktop:

<img src="../_static/media/chapter_1/section_1/image82.png" class="common_img" style="width:600px;"/>

Key desktop shortcut functions are listed below:

| Icon | Function Description |
| :---: | :--- |
| <img src="../_static/media/chapter_1/section_1/image83.png" class="inline-icon" style="width:80px;"/> | Command line terminal |
| <img src="../_static/media/chapter_1/section_1/image149.png" class="inline-icon" style="width:80px;"/> | ROSpider host PC software |
| <img src="../_static/media/chapter_1/section_1/image84.png" class="inline-icon" style="width:80px;"/> | Robot version configuration tool |
| <img src="../_static/media/chapter_1/section_1/image85.png" class="inline-icon" style="width:80px;"/> | Quick mapping shortcut |
| <img src="../_static/media/chapter_1/section_1/image86.png" class="inline-icon" style="width:80px;"/> | Autonomous navigation shortcut |

### 1.7.2 File Directory Composition Introduction

1. Double-click <img src="../_static/media/chapter_1/section_1/image83.png" class="inline-icon" style="width:80px;"/> to launch the terminal, enter `ls`, and press **Enter** to inspect the home directory contents:

<img src="../_static/media/chapter_1/section_1/image87.png" class="common_img" style="width:600px;"/>

Primary home directory folders:

| Folder Name | Description |
| :--- | :--- |
| `ros2_ws` | ROS2 workspace containing feature packages |
| `third_party_ros2` | Third-party packages such as YOLOv8 models |
| `large_models` | Foundational files for large AI models |
| `wifi_manager` | Wi-Fi network configuration scripts |
| `Music` | Audio and music files |
| `Pictures` | Image storage |
| `Videos` | Video recordings |
| `Templates` | Template files |
| `Downloads` | Downloaded files |
| `Public` | Public shared files |

2. Enter the ROS2 workspace directory and inspect files with `ls`:

```bash
cd ros2_ws
ls
```

<img src="../_static/media/chapter_1/section_1/image88.png" class="common_img" style="width:600px;"/>

Workspace directory structure:

| Directory Name | Description |
| :--- | :--- |
| `build` | Build space storing intermediate compilation cache |
| `command` | Reference command files for launching various features |
| `install` | Installation space for compiled binaries and executables |
| `logs` | System and build log files |
| `src` | Source code directory for ROS2 packages |

3. Enter the `src` folder and inspect package directories:

```bash
cd src
ls
```

<img src="../_static/media/chapter_1/section_1/image89.png" class="common_img" style="width:600px;"/>

Source packages description:

| Package Directory | Type | Functional Scope |
| :--- | :--- | :--- |
| `app` | App feature packages | Gesture control, LiDAR features, line tracking |
| `example` | Vision application packages | Color sorting, waste classification, navigation transport |
| `interfaces` | Communication interface definitions | ROS message and service definitions |
| `slam` | Mapping packages | Algorithmic SLAM mapping and map saving |
| `navigation` | Navigation packages | Waypoint publishing, RViz navigation |
| `xf_mic_asr_offline` | Voice control packages | Offline voice command processing |
| `xf_mic_asr_offline_msgs` | Voice message definitions | Voice control message interfaces |
| `peripherals` | Peripheral drivers | LiDAR drivers, controller and keyboard teleoperation |
| `simulations` | Simulation models | Gazebo, MoveIt simulation, URDF models |
| `driver` | Hardware drivers | Kinematics, serial communication between controller and STM32 |

4. Taking `/ros2_ws/src/app` as an example, inspect package subdirectories containing `launch` and `app`:

```bash
cd app
ls
```

<img src="../_static/media/chapter_1/section_1/image90.png" class="common_img" style="width:600px;"/>

The `launch` folder contains startup launch files, and `app` contains application source code.

<img src="../_static/media/chapter_1/section_1/image91.png" class="common_img" style="width:600px;"/>

<img src="../_static/media/chapter_1/section_1/image92.png" class="common_img" style="width:600px;"/>

Other functional packages follow an identical organization.

### 1.7.3 Enabling and Disabling Auto-Start Services

Because the app auto-start service is enabled by default upon boot, manually disable it when developing or running standalone programs to avoid hardware resource contention.

1. Click the terminal icon <img src="../_static/media/chapter_1/section_1/image62.png" class="inline-icon" style="width:80px;"/> to open a terminal.
2. Execute either of the following commands to stop the auto-start services:

```bash
~/.stop_ros.sh
```

```bash
sudo systemctl stop start_app_node.service
```

> [!NOTE]
>
> * **The first command shuts down all ROS nodes, while the second stops only the auto-start service node.**
> * **On Raspberry Pi 5, run the second command inside the black terminal** <img src="../_static/media/chapter_1/section_1/image176.png" class="inline-icon" style="width:80px;"/>.

3. Remember to restart the auto-start service after development sessions to restore app and wireless controller functionality.

4. Execute the command below to re-enable the auto-start service: 

   **On Raspberry Pi 5, run the second command inside the black terminal** <img src="../_static/media/chapter_1/section_1/image176.png" class="inline-icon" style="width:80px;"/>.

```bash
sudo systemctl restart start_app_node.service
```

## 1.8 Hardware Introduction

This chapter introduces the hardware architecture of the ROSpider robot, detailing the electronic control system, Jetson and Raspberry Pi controllers, LiDAR, depth camera, and peripheral sensors.

### 1.8.1 Hardware System Connection Block Diagram

Hardware connection system diagram based on the Jetson Nano ROS controller:

<img src="../_static/media/chapter_1/section_1/image182.png" class="common_img" style="width:600px;"/>

Hardware connection system diagram based on the Jetson Orin Nano / Orin NX ROS controller:

<img src="../_static/media/chapter_1/section_1/image2.png" class="common_img" style="width:600px;"/>

Hardware connection system diagram based on the Raspberry Pi 5 ROS controller:

<img src="../_static/media/chapter_1/section_1/image162.png" class="common_img" style="width:600px;"/>

### 1.8.2 Electronic Control System Introduction

The electronic control system utilizes an expansion board and a Jetson Nano, Jetson Orin Nano, Jetson Orin NX, or Raspberry Pi 5 as the high-level computer connected to the LiDAR, depth camera, and audio hardware. The low-level STM32 controller manages multiple bus servos and incorporates an onboard IMU accelerometer and gyroscope sensor for motion control and kinematic feedback.

#### 1.8.2.1 ROS Controller

**Jetson Nano:**

<img src="../_static/media/chapter_1/section_1/image180.png" class="common_img" style="width:600px;"/>

**Jetson Orin Nano/Orin NX:**

<img src="../_static/media/chapter_1/section_1/image3.png" class="common_img" style="width:600px;"/>

**Raspberry Pi 5:**

<img src="../_static/media/chapter_1/section_1/image163.png" class="common_img" style="width:600px;"/>

The ROS controller comprises a Jetson or Raspberry Pi processing board combined with a dedicated expansion board. It operates as a compact single-board computer capable of accelerating mainstream deep learning frameworks and handling demanding artificial intelligence workloads.

The expansion board exposes status LEDs and control buttons for checking network status and switching modes, and provides breakout interfaces for GPIO, I2C, and LiDAR communication.

**The operating system is Ubuntu 22.04.5 LTS configured with the ROS2 Humble robotic environment.**

For foundational controller coursework, refer to **[Basic Courses\ROS Controller Tutorial](https://drive.google.com/drive/folders/1mJOYpvnyMda1xGvtPgTvoBUd1zHdh9Db?usp=sharing)**.

#### 1.8.2.2 STM32 Controller

<img src="../_static/media/chapter_1/section_1/image195.png" class="common_img" style="width:600px;"/>

The STM32 control board serves as the lower-level controller, powered by an STM32F407VET6 microcontroller alongside PWM servo drivers, serial bus servo drivers, and a QMI8658 multi-axis inertial measurement unit.

Its primary role is receiving commands from the high-level controller or wireless controller to actuate chassis and arm servos, while regulating power delivery to the upper-level controller. Multifunction programmable buttons are also provided for custom programming.

#### 1.8.2.3 Depth Camera

<img src="../_static/media/chapter_1/section_1/image4.png" class="common_img" style="width:600px;"/>

As one of the most vital sensory components in robotic systems, the camera serves as visual sensory input.

The robot integrates the Orbbec Aurora 930 binocular structured-light depth camera. The Deptrum Aurora 930 series employs 3D structured light technology to capture 3D spatial geometry, fusing RGB color imagery with depth streams to provide robust 3D perception.

On the robot, it handles OpenCV processing, deep learning pipelines, and KCF visual object tracking. For foundational courses, consult **[4. Monocular and Depth Camera Foundation Course\Depth Camera Basics Study](https://drive.google.com/drive/folders/170wPjYTfC_3B_QpXjIbL8LHh10Hh2qCQ?usp=sharing)**.

<img src="../_static/media/chapter_1/section_1/image5.png" class="common_img" style="width:600px;"/>

Camera technical specifications:

| Parameter Category | Parameter Name | Specification Value |
| :--- | :--- | :--- |
| Module parameters | Dimensions | 76.5 x 20.7 x 21.8 mm |
| Module parameters | Baseline | 40 mm |
| Module parameters | Interface | USB 2.0 Wafer connector |
| Module parameters | Depth accuracy | 8 mm at 1 m |
| Module parameters | Depth precision | 3 mm at 0.5 m, 7 mm at 1 m |
| Module parameters | Working distance | 30 to 300 cm |
| Module parameters | Operating temperature | -10 to 55 degrees Celsius |
| Module parameters | Operating humidity | 0% to 95%, non-condensing |
| Module parameters | Ambient illuminance | 3 to 6000 Lux |
| Module parameters | Power supply | 5 V plus or minus 10%, 1.5 A |
| Module parameters | Power consumption | Average below 1.6 W |
| Module parameters | Safety | Class 1 Laser Safety |
| Image performance | Depth data format | Raw 16 |
| Image performance | Depth resolution and frame rate | 640x400 or 320x240, 5 to 15 fps, H71 deg x V46 deg |
| Image performance | Color data format | NV12 |
| Image performance | Color resolution and frame rate | 640x400 or 320x240, 5 to 15 fps, H71 deg x V46 deg |
| Image performance | Infrared data format | Raw 8 |
| Image performance | Infrared resolution and frame rate | 640x400 or 320x240, 5 to 15 fps, H71 deg x V46 deg |
| System compatibility | Supported platforms | Linux, ARMv8, ROS, Windows, Android |

> [!NOTE]
>
> **Individual 3D camera units may exhibit slight variations. Specifications represent nominal values for reference.**

#### 1.8.2.4 LiDAR

LiDAR sensors acquire precise distance and spatial geometry using pulsed laser light. Common robotic applications include obstacle avoidance, target following, SLAM mapping, and path planning. For dedicated tutorials, consult **[LiDAR Course](https://wiki.hiwonder.com/projects/ROSpider/en/jetson-orin-nano-version/docs/3_LiDAR_Course.html)**.

The robot is equipped with the LD19 LiDAR, consisting of a laser ranging core, wireless power transfer unit, wireless communication unit, angle resolver, motor driver, and protective housing. Rotation speed stabilizes to 10 plus or minus 0.1 Hz within 3 seconds of power-on. An external PWM interface enables closed-loop speed regulation using a PID control loop.

The LD19 links to external controllers through a ZH1.5T-4P 1.5 mm connector for power and data transmission:

<img src="../_static/media/chapter_1/section_1/image6.png" class="common_img" style="width:600px;"/>

Interface pinout and electrical parameters:

| Pin No. | Signal Name | Type | Description | Minimum | Typical | Maximum |
| :---: | :---: | :---: | :--- | :---: | :---: | :---: |
| 1 | Tx | Output | Radar data stream | 0 V | 3.3 V | 3.5 V |
| 2 | PWM | Input | Motor speed control | 0 V | - | 3.3 V |
| 3 | GND | Power | Ground | - | 0 V | - |
| 4 | P5V | Power | Power supply positive | 4.5 V | 5 V | 5.5 V |

#### 1.8.2.5 6-Channel Microphone Array Module

This optional hardware module equips the robot with voice wake-up and acoustic command recognition. For course details, refer to **[1. Tutorials\9. Voice Control Course](https://wiki.hiwonder.com/projects/ROSpider/en/jetson-orin-nano-version/docs/9_Voice_Control_Course.html)**.

The module utilizes a planar 6-element microphone layout to sample and filter spatial sound fields. It performs sound source localization, noise suppression, beamforming, dereverberation, and acoustic echo cancellation, providing 360-degree omnidirectional audio capture.

<img src="../_static/media/chapter_1/section_1/image7.png" class="common_img" style="width:600px;"/>

Port definitions:

| Port Name | Functional Description |
| :--- | :--- |
| UAC port | Digital audio output |
| Reference signal port | Reference signal for amplifier and acoustic echo cancellation |
| Power port | External power input port |
| Microphone port | 6-channel microphone array connection |
| Serial port | High-level host computer communication port for PC or embedded systems |

<img src="../_static/media/chapter_1/section_1/image8.png" class="common_img" style="width:600px;"/>

For additional documentation, refer to **[Hardware Materials\Microphone Array](https://drive.google.com/drive/folders/1SHBySUxUyhu8klCVsFCp_3jWskAuYuTP?usp=sharing)**.

#### 1.8.2.6 WonderEcho Pro

<img src="../_static/media/chapter_1/section_1/image10.png" class="common_img" style="width:500px;"/>

WonderEcho Pro is an AI voice interaction box equipped with a high-performance noise-canceling microphone and high-fidelity speaker. It uses a driver-free USB audio module compatible across multiple platforms for recording and playback.

It integrates advanced noise-suppression algorithms to filter ambient noise, supporting the complete pipeline from voice wake-up to speech recognition and interactive responses. Modular design enables standalone development and validation of individual components including wake-up, voice activity detection, recognition, and text-to-speech synthesis.

For additional documentation, consult **[1. Tutorials\9. Voice Control Tutorial](https://wiki.hiwonder.com/projects/ROSpider/en/jetson-orin-nano-version/docs/9_Voice_Control_Course.html)**.

#### 1.8.2.7 Bus Servo

<img src="../_static/media/chapter_1/section_1/image11.png" class="common_img" style="width:700px;"/>

ROSpider incorporates 24 smart high-voltage bus servos integrated with metal chassis components. Three servo models are utilized: HX-12H bus servos, HTS-20H bus servos, and HX-35H bus servos.

For technical specifications, consult **[Hardware Materials\Bus Servo](https://drive.google.com/drive/folders/1SHBySUxUyhu8klCVsFCp_3jWskAuYuTP?usp=sharing)**.

## 1.9 Image Burning

### 1.9.1 Preparations

**Hardware Requirements:**

* **Jetson Nano and Raspberry Pi 5 Versions:** Prepare a MicroSD card with capacity matching image requirements, a USB card reader, and a computer running Windows 10.

<img src="../_static/media/chapter_1/section_1/image95.png" class="common_img" style="width:600px;"/>

* **Jetson Orin Nano and Jetson Orin NX Versions:** Prepare an M.2 NVMe SSD with capacity matching image requirements, an SSD enclosure or programmer, and a computer running Windows 10.

<img src="../_static/media/chapter_1/section_1/image96.png" class="common_img" style="width:600px;"/>

**Software Requirements:** Install the disk initialization utility **DiskGenius.exe** and the image flashing tool **Win32DiskImager**.

> [!NOTE]
>
> * **Prior to flashing, use the disk initialization tool found in [2. Softwares\3. Image Burning Tool](https://drive.google.com/drive/folders/1lb3hFy-03xOe-Hm4kyavnVE4cLW4QZtE?usp=sharing) to delete all existing partitions on the drive.**
> * **After flashing completes, Windows may display popups prompting to format unrecognized drive partitions. Cancel and ignore these prompts.**
>
> <img src="../_static/media/chapter_1/section_1/image97.png" class="common_img" style="width:500px;"/>

### 1.9.2 SD Card / SSD Formatting

> [!NOTE]
>
> **If the MicroSD card or SSD is brand new and unpartitioned, formatting can be skipped.**

1. Remove the MicroSD card from the Jetson Nano or Raspberry Pi 5, or remove the NVMe SSD from the Jetson Orin Nano or Orin NX:

* **Jetson Nano**

<img src="../_static/media/chapter_1/section_1/image108.png" class="common_img" style="width:600px;"/>

* **Raspberry Pi 5**

<img src="../_static/media/chapter_1/section_1/image109.png" class="common_img" style="width:600px;"/>

* **Jetson Orin Nano / Jetson Orin NX**

<img src="../_static/media/chapter_1/section_1/image98.png" class="common_img" style="width:550px;"/>

2. Locate and extract the archive in [2. Softwares\3. Image Burning Tool](https://drive.google.com/drive/folders/1lb3hFy-03xOe-Hm4kyavnVE4cLW4QZtE?usp=sharing) and launch **DiskGenius.exe** to format the storage media. Ensure the target drive letter corresponds to the removable storage to avoid accidental data loss on local hard drives.

3. Insert the card reader or SSD enclosure into the computer to detect the external drive.

<img src="../_static/media/chapter_1/section_1/image99.png" class="common_img" style="width:500px;"/>

4. Right-click the external drive in the list and select **Delete All Partitions**.

<img src="../_static/media/chapter_1/section_1/image100.png" class="common_img" style="width:600px;"/>

5. The disk space displays as unallocated:

<img src="../_static/media/chapter_1/section_1/image101.png" class="common_img" style="width:600px;"/>

6. Create a new partition recognized by the operating system, then click **OK** in confirmation dialogs:

<img src="../_static/media/chapter_1/section_1/image102.png" class="common_img" style="width:600px;"/>

7. Click **Save All**.

<img src="../_static/media/chapter_1/section_1/image103.png" class="common_img" style="width:600px;"/>

8. The status reflects successful initialization, completing the formatting procedure:

<img src="../_static/media/chapter_1/section_1/image104.png" class="common_img" style="width:600px;"/>

### 1.9.3 Image Burning

1. Open **Win32DiskImager**, click the folder icon <img src="../_static/media/chapter_1/section_1/image110.png" class="inline-icon" style="width:50px;"/> to select the uncompressed system image file, select the drive letter under **Device**, and click **Write** to begin flashing.

<img src="../_static/media/chapter_1/section_1/image105.png" class="common_img" style="width:600px;"/>

> [!NOTE]
>
> **The file directory path storing the system image must not contain non-ASCII characters.**

2. If a confirmation popup appears, click **Yes**.

<img src="../_static/media/chapter_1/section_1/image106.png" class="common_img" style="width:500px;"/>

3. The popup **Write Successful** confirms completion. If errors occur, disable third-party antivirus software, reconnect the storage device, and repeat the procedure.

<img src="../_static/media/chapter_1/section_1/image107.png" class="common_img" style="width:300px;"/>

> [!NOTE]
>
> **After flashing succeeds, dismiss any Windows partition formatting dialogs.**

4. Reinstall the MicroSD card or SSD into the controller. Power on the robot to boot into the refreshed system environment.
