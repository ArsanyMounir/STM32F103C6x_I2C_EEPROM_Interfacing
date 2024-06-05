# STM32F103C6x and Simulated EEPROM Communication via I2C Protocol Project

This project demonstrates communication between an STM32F103C6x microcontroller (MCU) and <br>
an emulated Electrically Erasable Programmable Read-Only Memory (EEPROM)<br>
using the Inter-Integrated Circuit (I2C) protocol within the Keil MDK environment.<br>
The STM32F103C6x acts as the master, transmitting data to and reading data from the simulated EEPROM slave device.

## **Project Overview:**

* **Hardware:**
    * STM32F103C6x development board
* **Software:**
    * Keil MDK (Microvision Development Kit)
* **Simulated Device:**
    * EEPROM functionality emulated within Keil MDK environment (no physical EEPROM required)
* **Communication Protocol:**
    * I2C: Used for data transfer between MCU and simulated EEPROM

### **Data Flow:**

1. User programs data to be written to the EEPROM on the master MCU.
2. Master MCU transmits the data to the simulated EEPROM using I2C.
3. Simulated EEPROM stores the received data.
4. User initiates a read operation on the master MCU.
5. Master MCU sends a read request to the simulated EEPROM via I2C.
6. Simulated EEPROM transmits the stored data back to the master MCU.
7. Master MCU displays or processes the received data.

### **Features:**

* Master-slave I2C communication between STM32F103C6x MCU and simulated EEPROM.
* Data writing functionality from MCU to EEPROM.
* Data reading functionality from EEPROM to MCU.
* Keil MDK environment for code development and simulation.

### **Developed and Simulated in:**

* Keil MDK (Microvision Development Kit)

### **Getting Started:**

The project files (source code, Keil project files, etc.) are required to run this project. These files are found in Driver Folder.

### **Further Information:**

* This project demonstrates I2C communication principles for data exchange with an emulated EEPROM device.
* The code can be adapted to work with real I2C-based EEPROMs for physical data storage.
## Simulation
![STM32F103C6x I2C Master Interfacing with EEPROM Slave](https://github.com/ArsanyMounir/STM32F103C6x_I2C_EEPROM_Interfacing/blob/main/I2C_EEPROM.gif)
