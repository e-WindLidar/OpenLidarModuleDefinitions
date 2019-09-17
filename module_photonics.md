# Synopsis
_A short introduction to the module's purpose_
The photoics module is the source of emitted light that will be used for the measurements.

# Glossary of Terms
_A list of terms that are specific to this module_

# Interfaces
_How the module is linked to other parts of the OpenLidar architecture_

# Safety
_A list of possible safety issues related to the module and suggestions for mitigating any possible risks_

The photonics module is a source of potentially harmful laser radiation.

To ensure that no radiation leaves the photonics module before the optics and/or scanner modules are installed, the Laser module should receive its power through outlets on the optics and optional scanner modules. In this case, if any component in either the optics or scanner module is removed or malfunctioned, the power to the laser will be cut off and the photonics unit will not emit any radiation. Furthermore, the Laser module should be isolated from the outside world so that no possibly reflective surface can find its way into the beam path, deflecting the harmful radiation into the outside world.

N.B. **Always consult a qualified laser safety specialist before starting work!** This is not a complete list of possible safety risks associated with the photonics module. There may also be other ways to mitigate those risks.

# This module is...
_A list of things that do belong to the module_

# This module is not...
_A list of things that are not part of the module. Use issues, etc. for evidence_

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
