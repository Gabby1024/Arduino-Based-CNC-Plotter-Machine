# Arduino-Based-CNC-Plotter-Machine
Description
|* Designing of Arduino based computer numeric control machine specifically for plotting purposes *|
#############################################################################################################
Software used include:
        - Proteus v8.6
        - Arduino IDE v1.8.19
        - Gcode loader (Universal GCode Sender v1.0.9)
        - Virtual Serial Port Emulator
        - CAMotics
        - LaserGRBL
        - Universal Code Sender 
###############################################################################################################
Interconnection of components,
        - Virtual Serial Port Emulator is started and specific port is selected in this case is COM1 
        - GCode were generated by LaserGRBL by inputting the picture, then LaserGRBL convert picture into Gcode.
        - Arduino IDE used for writing controlling codes and then code are saved in form of .hex so as to be linked on Arduino UNO device in Proteus for simulation purpose
        - Proteus consist circuit which connects all components and simulation starts.
NB: All files are available on _Add.Inn folder
###############################################################################################################


