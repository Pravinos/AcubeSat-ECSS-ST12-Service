# Thesis: Analysis and Implementation of Fault Detection, Isolation and Recovery Architecture for the AcubeSAT nanosatellite

## About
The original AcubeSAT ECSS Services repository is open-source and continuously updated by the AcubeSAT team. However, to maintain the integrity of my thesis work and to provide a stable reference point, I have created this copy. This allows me to demonstrate the specific contributions I made without them being affected by ongoing updates from other team members.

# Thesis Contributions
In this repository, you will find the specific files and code sections that I developed as part of my thesis work, focusing on the implementaion of the **ST[12]** ECCS Service. Below is a list of the key files and directories where my contributions are located:

- **inc/Helpers/PMON.hpp​**
  - Contains the declarations of classes and functions related to the parameter monitoring (PMON) definitions, following the ECSS standards for parameter monitoring in spacecraft systems.

- **inc/Services/OnBoardMonitoringService.hpp​**
  - Defines the interface and declarations for the OnBoard Monitoring Service, which handles the monitoring and evaluation of on-board parameters according to predefined criteria.  

- **src/Services/OnBoardMonitoringService.cpp​**
  - Implements the functionality declared in OnBoardMonitoringService.hpp. This includes the logic for enabling/disabling monitoring, adding, deleting, modifying and reporting PMON definitions.

- **test/Services/OnBoardMonitoringServiceTests.cpp​**:
  - Contains unit tests for the OnBoard Monitoring Service. These tests verify the correct implementation of parameter monitoring, check logic, and compliance with ECSS standards.

- **inc/Helpers/TypeDefinitions.hpp**:
  - Acts as a central repository for type definitions used across the various services.
  - 
## Additional Resources
The original ECSS Services repository can be found [here](https://gitlab.com/acubesat/obc/ecss-services) along with instructions on how to use the project.

Feel free to explore the repository and examine the specific contributions in each file. These files collectively represent the implementation of the parameter monitoring services in compliance with the ECSS standards, forming a crucial part of my thesis work.
