# PCB Design

## Schematic Design

### Voltage Regulating Circuit

This circuit input is connected to the 3.7V Li-ion battery via a switch. A low dropout linear regulator, 
LM1117 regulates the output voltage at 3.3V. The red LED is connected parallelly to the output side to 
indicate whether the power is on.

![image](https://github.com/Nuthya27/Chef_Alarm/assets/111232856/80672c95-fcf3-4d1e-9614-bdb915579304)

### Battery Charging Circuit

This charging circuit is used to charge the 3.7V Lithium-ion cell. The MCP73831 IC works as the Li ion charge management controller. The 5V input must be supplied via the mini-USB port. The green 
LED will turn off when the battery is fully charged indicating to unplug the charger.

![image](https://github.com/Nuthya27/Chef_Alarm/assets/111232856/8cb9dbe7-2877-43a3-b674-b9aa5637e7e6)

### Main Circuit

ESP32- WROOM- 32D is the microcontroller used here since the integration of Bluetooth with the 
microcontroller IC helps with the Bluetooth mobile app connection without using an external Bluetooth 
module. There are two terminal blocks to connect two DS18B20 temperature sensor probes with a 
pulldown resistor. The buzzer is also connected to an I/O pin of the microcontroller.

![image](https://github.com/Nuthya27/Chef_Alarm/assets/111232856/a791a696-b712-4da9-b9d7-3afced40db4d)

### Programming Circuit

This part of the circuit is used to program the ESP32 microcontroller.

![image](https://github.com/Nuthya27/Chef_Alarm/assets/111232856/eca345e9-2542-483c-aa22-9901d0598892)

## PCB

### Bottom Layer

![image](https://github.com/Nuthya27/Chef_Alarm/assets/111232856/306587a2-8e99-42b3-9971-e062d4d23489)

### Top Layer

![image](https://github.com/Nuthya27/Chef_Alarm/assets/111232856/0faba177-9104-4e92-af8b-6b12be9ce78c)

### PCB after soldering

![image](https://github.com/Nuthya27/Chef_Alarm/assets/111232856/60a6d8b3-469d-40d5-951f-72715c652893)


