# Synopsis
_A short introduction to the module's purpose_

The scanner is the module that orients the beam with respect to the housing and other parts of the lidar system.

The scanner may be capable of one or more degrees of freedom.

# Glossary of Terms
_A list of terms that are specific to this module_
1. 

# Interfaces
_How the module is linked to other parts of the OpenLidar architecture_

# Safety
_A list of possible safety issues related to the module and suggestions for mitigating any possible risks_

The scanner is a moving item and there are therefore risks of pinching or trapping. These can be mitigated through torque feedback or protection to prevent users reaching the lidar.

Removing the scanner may expose a user to laser light. The scanner should be integrated with the interlock system to prevent this from occuring.

# FAQ
## This module is...
_A list of things that do belong to the module. Use issues, etc. for reference_

- any lenses, mirrors, or other devices designed to direct the transmitted or received beam
- any device intended to keep the optical path clear and clean, such as a wiper, air jet, or other method
- sometimes combined with the optics in a single housing

## This module is not...
_A list of things that are not part of the module. Use issues, etc. for reference_

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
