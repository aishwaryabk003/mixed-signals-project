# mixed-signals-project
Design and Performance Analysis of high gain, Low-power Two stage Folded Cascode Opamp
# Abstract
In this project, we aim to design and analyze a two-stage folded cascode operational amplifier using 90 nm CMOS technology. The main goal is to achieve high gain, wide bandwidth, and low power consumption. The folded cascode topology is chosen for its ability to work efficiently at low supply voltages. The design will be simulated to observe key parameters such as gain, bandwidth, phase margin, and power dissipation.
# Introduction to Folded Cascode Configuration
Before understanding the folded cascode configuration, it is important to first understand what a cascode stage means. A cascode is essentially a combination of Common Source (CS) and Common Gate (CG) stages connected together. This type of configuration is widely used in analog circuit design due to its ability to achieve:

1)High voltage gain in operational amplifiers

2)Increased output impedance and transconductance

3)Cascode configurations are mainly of two types:

4)Normal Cascode

5)Folded Cascode
# Overview of Folded Cascode
The two-stage folded cascode operational amplifier is a widely used architecture in analog circuit design, combining high gain, wide bandwidth, and low power consumption. The first stage, a folded cascode, enhances gain and input common-mode range by “folding” the signal path, allowing both NMOS and PMOS transistors to operate effectively even under low supply voltages. The second stage, typically a common-source amplifier, provides additional gain and output drive capability. This topology achieves excellent stability, slew rate, and common-mode rejection, while maintaining low distortion and good linearity. Due to its balanced trade-off between performance and efficiency, it is well-suited for high-speed, low-voltage, and precision analog applications such as data converters, filters, and sensor interfaces.
# Design Specification
![spec_1](https://github.com/user-attachments/assets/064c62ee-eec9-4974-a782-2448f1f7b49d)

# Schematic
<img width="1731" height="856" alt="cascode" src="https://github.com/user-attachments/assets/bf635bfc-9b66-4e7e-bf09-591e6fefae65" />



# Symbol
<img width="537" height="394" alt="test" src="https://github.com/user-attachments/assets/4da0e01f-32f5-4b72-98db-6e3cef833381" />
