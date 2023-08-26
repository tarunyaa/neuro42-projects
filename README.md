|[Home](https://tarunyaa.github.io) 🏠    [Penngineering Projects](https://tarunyaa.github.io/penngineering-projects/) 🦾     [Physics Projects](https://tarunyaa.github.io/physics-projects/) 🔭     [Science Communication Projects](https://tarunyaa.github.io/science-communication-projects/) 🗣  |

## Neuro42 Projects 📡

neuro42, Inc. is a medtech Company advancing futuristic technologies for screening, diagnosis, and targeted treatment of neurological conditions. Here's some information about the RF analog circuits I developed during my time there!

### Step-Up Voltage Converter
*Steps-up a 1.0 V square wave to a 5.0 V square wave.*

Researched and simulated different methods of step-up voltage conversion such as <span style="color:green">non-inverting op-amp</span>, boost converter IC, and non-inverter digital CMOS buffer. Digital CMOS buffer was considered over op-amp due to less SMD resistors requirement and lack of need for additional power supply. <span style="color:green">Selected</span> digital buffer package, <span style="color:green">soldered</span> test circuit, and <span style="color:green">tested</span> its behavior using oscilloscope and function generator.

### 90 Degree Hybrid
*Splits a signal into two with a 90 degree phase and equal (-3 dB) power split*

<span style="color:green">Selected, sourced and soldered appropriate adjustable inductors</span> for the circuit. Successfully <span style="color:green">tested and tuned</span> its behavior using an oscilloscope and function generator. <span style="color:green">Designed a PCB</span> for it. Further tested the behavior of other directional couplers in-lab using an oscilloscope and function generator.

### Active T/R Switch
Control the direction of current flow during transmit and receive mode, to protect sensitive receive components during high-power transmit mode.*

Developed <span style="color:green">understanding</span> of the circuit schematic working. Designed version 1 of PCB for it. Successfully <span style="color:green">soldered, tested and debugged </span>its behavior with regular and low power PIN diodes. <span style="color:green">Designed</span> the final version of PCB for it. Successfully <span style="color:green">soldered, tested and debugged</span> its behavior with high power PIN diodes. Used oscilloscope and function generator.

### Balun & Match
*Converts an unbalanced signal (single-ended) to a balanced signal (differential) or vice versa.*
<span style="color:green">Designed a PCB for it</span>.

### Final Project
Two amplifier versions are required: <span style="color:green">power amplifier for the transmission line and low noise amplifier for the receive line</span>. These are meant to replace the currently used amplifiers in the transmit and receive line respectively, as they’re expensive. They both are required to produce a <span style="color:green">gain of around - 18.0 dB and the low noise amplifier is required to have low noise figures of around 0.6 dB</span>. This is difficult as Amplifier ICs for the MRI’s 3 MHz operating frequency are not available on the market due to lack of demand. Most ICs operate at higher frequencies for wirless applications. To circumvent this problem, 
1. Amplifier <span style="color:green">ICs</span> whose operating frequencies are higher were investigated
2. Amplifiers were designed <span style="color:green">from scratch</span> 

#### Amplifier IC
*Produces a gain of around - 18.0 dB for low noise figures of around 0.6 dB although the signal is distorted*

<span style="color:green">Designed a PCB</span> for it. Used online calculator and network analyser for <span style="color:green">impedance matching</span>. Soldered, tested, and debugged the circuit using an oscilloscope and function generator.

#### Differential Cascode Amplifier
Read scholarly articles and textbooks to <span style="color:green">design schematic</span> for two versions of the differential cascode amplifier: power and low noise. Selected transistors for each. <span style="color:green">Designed multiple PCBs for it</span>, each for a different transistor or to investigate a different noise reduction technique. <span style="color:green">Soldered, tested, and debugged multiple amplifier boards</span> along with tune and impedance match boards using oscilloscope, function generator, and network analyser. Successfully built power single-ended cascode amplifier. Differential amplifiers and low noise amplifiers are active areas of research that were unable to be resolved by the end of the internship.
