# N64-IGR-NUS-CPU01-05
N64 In Game Reset using 328P Atmega Arduino Nano board, wires and a 120R 1/4W Resistor to prevent ghost pressing.


## IGR COMBO: L+R+A+B+Z
To reset the console press this combo buttons.


##  4 wires only (from NUS-CPU01 to NUS-CPU05 MODELS follow the example below, it's the same pinnout)
![NUS-CPU-04 IGR Pinouts for Arduino Nano atMega328P](https://github.com/user-attachments/assets/580960df-e8f5-4b84-b69d-99f9a401972b)

Inside image folder there's some instructions for other models too because the serial controller pinout is different, the rest is gonna be the same for all NUS-CPU models.


## Common place to install the board
![P_20221113_2339061](https://github.com/user-attachments/assets/9aa4a7dd-e1d4-44c3-8c47-9203e04e3a37)



## Flashing Arduino

// Flashing on already bootloaded ATmega328P (Nano)
--Open Arduino IDE Run
![image](https://github.com/user-attachments/assets/e31cf2ce-d2da-4d75-9ec3-f0b5c2ba2411)

 
--Install board library as image above
--Plug your Arduino on USB

--Select correct board (Arduino NANO) them the COM PORT where Arduino is connected, as image below.
![image](https://github.com/user-attachments/assets/c670dcbb-ddf7-47df-a2a7-ea4cd66ed107)


Copy all the three files inside "Files for Arduino IDE" folder to a new sketch folder, compile and upload it to the board.

DONE! Enjoy.
Cheers for [L10N37](https://github.com/L10N37) for making this.
