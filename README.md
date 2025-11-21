# loongcat40
A 4x10 gasket mounted keyboard featuring a large OLED. A culmination of 5 years of learning.

<img src="https://github.com/ChrisChrisLoLo/loongcat40/blob/main/images/PXL_20251116_045329065.jpg?raw=true" width="500">


## status
v0.1 pcbs have been produced but not yet tested.
v0.0 pcbs have been produced. v0.0 has been been tested. The keyboard  largely works, though GPIO20 requires an external pullup resistor. This may have been due to the rp2040 dev board I was using.

## about
<img src="https://github.com/ChrisChrisLoLo/loongcat40/blob/main/images/PXL_20251116_045438397.jpg?raw=true" width="500">


## case
All of the case files you need can be found in the `case` directory.

## pcb
You can find the PCB source files in the `pcb` folder. The BOM files can be found in this folder.

## directory structure
- `case`
    You can find the files you need in this folder to print out a case for the keyboard
- `drafts`
    Stores any KLE or intermediate information used in making the case
- `pcb`
    Kicad project relating to the project

## BOM
- 1 PCB
- 40 hotswap sockets
- 40 diodes
- 1 2.08" OLED LCD (SH1122)
- 3mm poron gasket strips (80mm x 3mm x 4mm)
- 1 Raspberry Pi Pico 1
- 3D printed parts
  - 4 TPU oled standoffs
    - used to make sure that the oled is aligned when soldering
  - 2 PLA plates
  - 1 PLA case bottom
  - 1 PLA casetop
- 12 5mm M2 screws
- 4 rubber bumpons
<img src="https://github.com/ChrisChrisLoLo/loongcat40/blob/main/images/PXL_20251116_050432853.jpg?raw=true" width="500">



## assembly
- Assemble the PCB without the oled
  - the Pico should be soldered via castellated pins. Male pin headers should _not_ be used 
- Put the 4 TPU oled standoffs onto the oled module. These standoffs will help align the oled
- Solder the oled to the pcb. The oled module should be on the other side of the board such that it's on the opposite side 
- Put the poron gaskets onto the plate
- Put the keys through the plate and onto the PCB
- Put the PCB onto the top of the case
- Put the bottom of the case on
- Screw in the bottom of the case
  - Note that screwing the screws for the first time may take some force, as the screws will be threading the plastic of the top
- Put bumpers on the bottom of the case
- Done!

## firmware
You can find the QMK firmware for this project here: https://github.com/ChrisChrisLoLo/qmk_firmware/tree/loongcat40

## acknowledgements

<img src="https://github.com/ChrisChrisLoLo/loongcat40/blob/main/images/PXL_20251116_044838517.jpg?raw=true" width="500">

Thank you to [NextPCB](https://www.nextpcb.com/) and all of my Github Sponsors for sponsoring and supporting this project!

<img src="https://github.com/ChrisChrisLoLo/loongcat40/blob/main/images/sponsor_logo.png?raw=true" width="200">

Big thank you to [@suh_ga](https://x.com/suh_ga) for the fantastic artwork used and displayed on this keyboard! Please check her out at https://twitter.com/suh_ga!
