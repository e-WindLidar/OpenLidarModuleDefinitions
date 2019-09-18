# Synopsis
_A short introduction to the module's purpose_

The optics module is designed to alter the original laser beam into radiation with desired specification that can be sent to the target and received by the detector properly.

# Glossary of Terms
_A list of terms that are specific to this module_

# Interfaces
_How the module is linked to other parts of the OpenLidar architecture_

# Dependencies
_How the module characteristics may be influenced by other parts of the architecture_

The lidar optics should be sized and specified according to the laser frequency, power, and other characteristics. This may influence coatings and other design requirements. N.B. Not all optics modules are interchangable!

# Safety
_A list of possible safety issues related to the module and suggestions for mitigating any possible risks_

# FAQ
## This module is...
_A list of things that do belong to the module_

- The optics module includes all optical components on the transmitted and received paths. 

## This module is not...
_A list of things that are not part of the module. Use issues, etc. for evidence_

- intended to orient the beam; this is carried out by the [scanner module](module_scanner.md).

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
  - **S oftware**
  - **Controller**
  - **Interfaces** discusses how the module is connected to other parts of the OpenLidar architecture.
- **Safety** includes all applicable safety information
- **References** provide links to articles and other relevant information.

# Known examples of this module
_A list of projects or products that have implemented this module_
