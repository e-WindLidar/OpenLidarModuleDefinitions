# Synopsis
_A short introduction to the module's purpose_

The Storage module is responsible for saving data in the lidar system which will be accessed by users at some future time. It should consist of a device which can rapidly and safely store data over a long period of time, and one which is easily interfaceable with external controllers like a PC. It has two roles: Storing Data and Saving Data, both of which need to be accomplished at speeds higher than or equal to the rate at which data is being processed to ensure that no data is lost.

# Glossary of Terms
_A list of terms that are specific to this module_

1. SSD: Solid State Drive
2. HDD: Hard Disk Drive
3. GUI: Graphical User Interface
4. SATA: Serial ATA; An interface standard for storage devices on computers
5. PCI: A standard for connecting computers and their peripherals

# Interfaces
_How the module is linked to other parts of the OpenLidar architecture_

# Safety
_A list of possible safety issues related to the module and suggestions for mitigating any possible risks_

The storage module must have insulated power outlets in order to ensure that no electrical sparking or shocks are inflicted on individuals manipulating the system.

The storage module must be robust enough to not lose any data or functionality while in the operating conditions of the lidar device.

# FAQ
## This module is...
_A list of things that do belong to the module_

- anything required to store data, for example HD, SSD, compact flash, etc.

## This module is not...
_A list of things that are not part of the module. Use issues, etc. for evidence_

- responsible for communication of the saved data outside of the lidar. This is enabled by the [communications module](module_communications.md).

## Other questions
_Relevant questions in an FAQ format_

# Documentation
_How a specific implementation of this module should be documented. It should be adjusted for each module as required._

The following documentation is required (marked with a star) or suggested.
- **High Level Overview** discusses the main functions of the module and its constituent components.
- **Contacts** information about the contact person or organzation responsible for this module.
- **Design Space** discusses the operating conditions for the module.
- **Detailed Information** discusses the details of the module, including suggestions that may be implemented to accomplish its roles in the lidar system.
  - **Hardware**
  - **Software**
  - **Controller**
  - **Interfaces** discusses how the module is connected to other parts of the OpenLidar architecture.
- **Safety** includes all applicable safety information
- **References** provide links to articles and other relevant information.

# Known examples of this module
_A list of projects or products that have implemented this module_
