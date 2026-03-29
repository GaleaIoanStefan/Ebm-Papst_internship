# Ebm-Papst_internship
This project contains the PCB design for a equipment that measures contact heat transfer rates.

# The Block Diagram of the Project

<img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/1ed45e6d-66d2-4b1b-8018-75bb5fbbd8e0" />

In here we can see the main parts of the project namely the supply, a feedback control loop of the ventilator and another feedback control loop of the metal plate. Everything that is contained in the colored frame sits on the actual PCB.

An Arduino Nano Esp32 microcontroller is the brain of the board, which will control the speed of the fan on the left of the schematic with a voltage switch, through a Hall speed sensor to complete a feedback loop. Similarly, on the right side, the esp32 will control the temperature of a hob with a 120W resistor with a voltage switch, and the feedback communication is done by 2 NTC thermistors


# The electrical schematic of the PCB

<img width="975" height="670" alt="image" src="https://github.com/user-attachments/assets/c30acb64-5ae8-48dd-8e28-fc3d2478f6e5" />

# The layout of the PCB

<img width="1046" height="741" alt="image" src="https://github.com/user-attachments/assets/a2a6844d-2177-44fd-a3af-c1f57c845c1c" />


