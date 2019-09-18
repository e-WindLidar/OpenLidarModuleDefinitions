# Synopsis
_A short introduction to the module's purpose_

The signal processing module is used to convert the data acquired by the lidar into a data product.

This module has two main functions, which are interfacing with PC (the External Controller) and data processing.
 - Interfacing with PC includes the ability to be reprogrammed and the ability to receive commands, which it can then send off to various modules. These tasks can be accomplished with either a DSP, MCU, or an FPGA, based on the decisions of the designer (2, 3, 4). This aspect of the Control Module is what connects it to the rest of the lidar system, and a protocol must be set up for all peripheral modules to be able to receive and understand the signals sent to them by the Internal Controller.
- Data processing involves the ability to collect and manipulate data sent by the Detector Module into useful information which can be used to determine various parameters such as wind speed and direction. In order to accomplish this, an FPGA or DSP can be used, but an FPGA would be favoured, both for its ability to be reprogrammed and its strong parallel computing capabilities. Whichever device is used must, at the very least, be able to handle an FFT with a 50 MHz bandwidth, meaning the clock speed must be at least 100 MHz.

N.B. this module is optional; it could be replaced by storing level 0 or raw data (e.g., spectral) data and then converting it to another level (e.g. line-of-sight wind speeds) externally or later. For more information about wind lidar data levels, see Figure 4.3 of [DOI: 10.5281/zenodo.2478051](https://doi.org/10.5281/zenodo.2478051).

# Glossary of Terms

_A list of terms that are specific to this module_

1. DSP: Digital Signal Processor

2. FFT: Fast Fourier Transform

3. FPGA: Field Programmable Gate Array

4. MCU: Microcontroller

5. GUI: Graphical User Interface

6. PC: Personal Computer (a system with a processor, operating system, inputs and outputs, as well as a programmable GUI)
# Interfaces
_How the module is linked to other parts of the OpenLidar architecture_

# Safety
_A list of possible safety issues related to the module and suggestions for mitigating any possible risks_

# FAQ
## This module is...
_A list of things that do belong to the module_

## This module is not...
_A list of things that are not part of the module. Use issues, etc. for evidence_

## Other questions
_Relevant questions in an FAQ format_

# Documentation
_How a specific implementation of this module should be documented. It should be adjusted for each module as required._

The following documentation is required (marked with a star) or suggested.
- **High Level Overview** discusses the main functions of the module and its constituent components.
- **Contacts** information about the contact person or organzation responsible for this module.
- **Design Space** discusses the operating conditions for the module.
- **Detailed Information** discusses the details of the module, including suggestions that may be implemented to accomplish its roles in the lidar system.
- **Interfaces** discusses how the module is connected to other parts of the OpenLidar architecture.
- **Safety** includes all applicable safety information
- **References** provide links to articles and other relevant information.

# Known examples of this module
_A list of projects or products that have implemented this module_
