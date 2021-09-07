![](imgs/rae-header-image.PNG)
>[>> Fusion 360 - WebViewer](https://a360.co/2W6mHcp)

## About the Rae Project
Rae stays for *Robot-autonomy-
effector* and is an __OpenSource__ based modular end-of-arm tool with integrated __eye-in-hand__ depth camera which enables researchers, AI-enthusiasts and engineers to develop and deploy autonomous applications for robot manipulators. The 6 different module-types helps to solve various modern challenges in Robotics as for example bin-picking, packaging or tool-based automation. The design originates from the Bachelor-thesis created by Roman Baur in cooporation with Festo SE & Co. KG and the University of applied Sciences in Esslingen.

## [Table of content](#table-of-content)

- [Getting Started](#getting-started)
- [Base-System](#base-system)
- [Realsense System](#realsense-system)
- [Kinect System](#kinect-system)
- [Gripper Fingers](#gripper-fingers)
  - [Festo DAHS-80 Radialgripper](#festo-dahs-80-radialgripper)
  - [Festo DAHS-120 Radialgripper](#festo-dahs-120-radialgripper)
- [Flanges](#flanges)
- [Vacuum Module](#vacuum-module)
  - [double-pump](#double-pump)
  - [big-pump](#big-pump)
- [Suction modules](#suction-modules)
  - [Angular compensation](#angular-compensation)
  - [Linear compensation](#linear-compensation)
- [Electrical Circuit](#electrical-circuit)
- [Credits](#credits)
  - [Bachelors thesis and extension by Roman Baur:](#bachelors-thesis-and-extension-by-roman-baur)
  - [Supervisors Festo SE & Co. KG:](#supervisors-festo-se--co-kg)
  - [Supervisors HS Esslingen:](#supervisors-hs-esslingen)
    - [Bachelors Thesis RAE v 1.0:](#bachelors-thesis-rae-v-10)
    - [RAE v 2.0:](#rae-v-20)

# Getting Started

How I get an working rae:

1. Download the .stl files from the [base-system](base-system) including drive and guide parts
2. Choose whether you want a [realsense](perception-modules/realsense) or a [kinect](perception-modules/kinect) perception system and download the according .stl files.
3. Print it with a high-quality SLS-Printer.
4. Assemble the the printed parts and the electric components with the appropriate screws.
5. Download the Image for the embedded linux called raeos and flash it on an SD-Card. Then boot the system.


> If you want to have an assembled and preinstalled rae, please contact [themakeservice](#)

How to set up my rae:
1. Install the raeros-client on your host system and setup an ethernet or wireless based connection to the rae-system.

# Base-System
![](imgs/rae-base-system.png)

> [>> base-system](base-system)

# Realsense System

![](imgs/rae-realsense-system.PNG)

> [>> realsense-system](perception-modules/realsense)


# Kinect System
![](imgs/rae-kinect-system.PNG)
> [>> kinect-system](perception-modules/kinect)

# Gripper Fingers
## Festo DAHS-80 Radialgripper
![](gripper-modules/radialgripper80/imgs/radialgripper80-with-base.PNG)
> [>> radialgripper80](gripper-modules/radialgripper80)
> 
## Festo DAHS-120 Radialgripper
![](gripper-modules/radialgripper120/imgs/radialgripper120-with-base.PNG)
> [>> radialgripper120](gripper-modules/radialgripper120)
# Flanges
![](flanges/imgs/panda-flange.PNG)
> [>> Franka-Panda-Flange](flanges)

# Vacuum Module
## double-pump
![](vacuum-modules/double/imgs/double-vacuum-module.PNG)
> [>> double-vacuum-module](vacuum-modules/double)

## big-pump
![](vacuum-modules/big/imgs/big-vacuum-pump.PNG)
> [>> big-vacuum-module](vacuum-modules/big)


# Suction modules
## Angular compensation
![](tool-modules/suction-holders/angular-compensation/angular-compensation.png)
> [>> angular-compensation-module](tool-modules/suction-holders/angular-compensation)
> 
## Linear compensation
![](tool-modules/suction-holders/linear-compensation/linear-compensation.png)
> [>> linear-compensation-module](tool-modules/suction-holders/linear-compensation)


# Electrical Circuit
![](imgs\electrical-circuit.png)

# Credits

## Bachelors thesis and extension by Roman Baur:
* Modular Concept
* Mechanical-, Electrical- and Software-Design

## Supervisors Festo SE & Co. KG:

Daniel Brauchle, Dionysios Satikidis, Timo Schwarzer

## Supervisors HS Esslingen:

### Bachelors Thesis RAE v 1.0:
Prof. Clemens Klöck, Dionysios Satikidis

### RAE v 2.0:
Prof. Thao Dang




