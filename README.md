# enable-it Bionic Boards - Third iteration

**This project is part of e-Nable.it Bionic Platform**

An open-source project for developing prosthetic and assistive devices through frugal innovation, designed to be part of e-Nable's open-source prosthetics. The project focuses on building electronic solutions that enable mechanical devices to achieve advanced functionalities, enhancing the community's designs with sophisticated, human-integrated electronic control while maintaining simplicity, affordability, and accessibility.

This project is developed and maintained by the volunteers of the e-Nable Italia community. Our group consists of passionate individuals, including biomedical engineers, mechatronics engineers, and makers, who collaborate to create innovative and accessible solutions. Through our collective efforts, we aim to empower users with open-source, affordable, and customizable assistive devices.

Additional details and information about the **e-nable.it Bionic Platform** can be found in [e-nable.it Bionic Plaform Wiki](https://dev.e-nableitalia.it/wiki/spaces/enableit/pages/2195549/e-Nable.it+bionic+platform).

# Project roadmap

The project unfolds in three development iterations, each aimed at validating, prototyping, and engineering innovative solutions for low-cost bionic devices.

1. Ideas Validation
The first phase involves conducting experiments and tests to validate initial ideas. This phase focuses on identifying the most promising solutions, exploring various options for controlling actuators and sensors, and collecting data to establish guidelines for the prototype.

2. Prototyping & Custom Solutions
During the prototyping phase, custom solutions are developed using commercial components integrated with specialized electronic boards. The most promising ideas are implemented into physical prototypes to validate architectural and structural concepts. The focus is on simplicity and reliability, ensuring the solutions can be easily replicated and adapted for various bionic devices.

3. Frugal Innovation Engineering
The final phase focuses on engineering the solutions based on frugal innovation principles. Prototypes are optimized to make them accessible, scalable, and practical, with a strong emphasis on cost-effectiveness and real-world applicability. The engineering process also involves creating an open-source hardware platform that enables the creation of modular systems easily combined to build bionic devices.

This repository relates to Iteration #3.

The objective of this iteration is to develop the first reusable deliverables of the project, a set of electronic modules that empower mechanical devices with advanced functionalities. 

By integrating sophisticated, human-centered electronic control, we strive to enhance the capabilities of the e-Nable community's designs while ensuring they remain simple, affordable, and accessible.


> [!CAUTION]
> **The boards published in this repository are still under development and, until fully completed and thoroughly validated, they are intended solely as technological demonstrators and are not designed for practical use.**

## Initial Release Boards

This initial release includes the following boards:

**1. Bionic Controller**  
The Bionic Controller is a custom control board designed to house and expand the capabilities of the M5Stack Atom S3 board. It connects seamlessly to its daughter boards via an 8+8 pin expansion slot.

**This module serves as the foundation for flexible, low-cost prosthetic and assistive device applications.**

Key features:  
- **Size:** 25x50mm  
- **Layers:** 2-layer board  
- **Power Management:** Provides battery management and charging, delivering three power outputs (+3.3V, +5V, and a variable voltage between 5V and 12V for powering multiple motors simultaneously).  
- **Expansion Slot:** Includes a 8+8 pin expansion slot for a daughter board.  
- **Housing:** Designed to house the [M5Stack Atom S3](https://docs.m5stack.com/en/core/AtomS3) board.  

Latest version:
- **Files:** Atom S2 Module Rev. C

**2. ActuatorSense Module**  
The ActuatorSense module is a compact, low-cost H-bridge daughter board designed to connect seamlessly to the expansion slot of the Bionic Controller board.

Key features:  
- **Size:** 25x25mm  
- **Layers:** 2-layer board  
- **Capabilities:**  
  - Can control two linear actuators (or two motors).  
  - Supports a combination of one actuator and one sensor (myoelectric or pressure). 

Latest version:
- **Files:** DRV8441A Module Rev A  

**3. Advanced Control Board**  
An enhanced version of the basic control board with added features:  
- Includes three slots for daughter boards, enabling control of multiple actuators.  
- Retains all capabilities of the Bionic Controller.  

**4. Daughter Board with TI ADS1298**  
A specialized board for EMG signal acquisition:  
- **Functionality:** Designed to acquire up to eight simultaneous myoelectric signals.


## Project updates
240110 - Initial file upload

240113 - Updated to latest release, changes:
- fixed mechanical issue (wrong housing position for Atom S3 board, moved the connectors 4.5 mm below)
- reworked board polygons (cleaner design)
- completed 3d board models
- replaced single pin 2.54 headers with wirepad

## KNOWN ISSUES

N/A

## Authors

Alberto Navatta - alberto@e-nableitalia.it / alberto.navatta@gmail.com

e-Nable Italia - info@e-nableitalia.it 

Check for further information, updates and information on this and other e-Nable Italia’s projects on our website: [https://e-nableitalia.it/](https://e-nableitalia.it/)

## License

This material is released under *Creative Commons - Attribution - Non-Commercial - Share Alike license*

## LIMITATION OF LIABILITY.
UNDER NO CIRCUMSTANCES AND UNDER NO LEGAL THEORY, WHETHER TORT (INCLUDING NEGLIGENCE), CONTRACT, OR OTHERWISE, SHALL YOU, THE INITIAL DEVELOPER, ANY OTHER CONTRIBUTOR, OR ANY DISTRIBUTOR OF COVERED CODE, OR ANY SUPPLIER OF ANY OF SUCH PARTIES, BE LIABLE TO ANY PERSON FOR ANY INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY CHARACTER INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF GOODWILL, WORK STOPPAGE, COMPUTER FAILURE OR MALFUNCTION, OR ANY AND ALL OTHER COMMERCIAL DAMAGES OR LOSSES, EVEN IF SUCH PARTY SHALL HAVE BEEN INFORMED OF THE POSSIBILITY OF SUCH DAMAGES. THIS LIMITATION OF LIABILITY SHALL NOT APPLY TO LIABILITY FOR DEATH OR PERSONAL INJURY RESULTING FROM SUCH PARTY'S NEGLIGENCE TO THE EXTENT APPLICABLE LAW PROHIBITS SUCH LIMITATION. SOME JURISDICTIONS DO NOT ALLOW THE EXCLUSION OR LIMITATION OF INCIDENTAL OR CONSEQUENTIAL DAMAGES, SO THIS EXCLUSION AND LIMITATION MAY NOT APPLY TO YOU.
