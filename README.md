# Pacemaker
Coded a FRDM-K64F ARM development board to simulate a pacemaker using *Matlab's Simulink*. Followed the *software development life cycle* to create a *modular and readbale* design. Created stateflows to perform tasks such as sensing heart paces and delivering artifical paces. Traversed different stateflows using conditionals. Implemented pacing modes VOO, VOOR, AOO, AOOR, VVI, VVIR, AAI, AAIR, DOO, DOOR by adding logic for sending paces and detecting paces in both the ventricle and atrium of the heart. Used *serial communication* to send a recieve data from DCM. More information in Documenation 

## Toolboxes Used
- MATLAB®
- Simulink®
- Embedded Coder®
- Fixed-Point DesignerTM MATLAB CoderTM
- Simulink® CheckTM
- Simulink CoderTM
- Simulink CoverageTM
- Simulink Design VerifierTM Simulink Desktop Real-TimeTM Simulink TestTM
- Stateflow®
- Simulink® Coder Support Package for NXP FRDM-K64F -> Segger’s J-Link OpenSDA V2 firmware
- DSP Toolbox

## Model
The following is overall model which includes Input, Logic, and Output:
![](Images/Main%20Stateflow.png)
