# Theo

## ECP5 FPGA Software Defined Radio board.
<!--- ![Front Photo](documentation/images/OrangeCrab_r0.2_front.jpeg "Front Photo") --->

## Latest Revision: 
* TBA

---

## What is it?
Theo is an OSHW SDR (Software Defined Radio) based on the ECP5 FPGA. It's main purpose is to serve as a wireless SoC development platform. It's based on Greg Davill's Orange Crab with some not-insignificant changes planned. It uses the feather form factor.

## Hardware Overview
* Lattice ECP5 FPGA
* AD9364 Transceiver
    * 70 MHz to 6 GHz
    * 1 RX chain / 1 TX chain, full duplex
    * board-space dependent
* DDR3L Memory
    * 128 Mbytes (1Gbit)
    * 64M x16
    * 1.35V low voltage operation
* USB-C connection
    * TBD
* Non-volatile Storage
    * 128Mbit QSPI FLASH Memory 
        * Bootloader (First 4Mbits)
        * User Bitstream
        * User storage (Firmware/MSC backend/etc)
        * QSPI compatible
    * MicroSD socket
        * 4bit SD interface (CK, CMD, DAT0-3)
* Power supply
    * TBD
* Oscillator
    * TBD
* JTAG
    * TBD - possibly [TagConnect](https://www.tag-connect.com/product/tc2030-ctx-nl-6-pin-no-legs-cable-with-10-pin-micro-connector-for-cortex-processors)
* User I/O
    * TBD
* Analog System
    * TBD
* Feather Format Board
    * Dimensions: 22.86mm x 50.8mm (0.9" x 2.0")

---

<!--- ![Back Photo](documentation/images/OrangeCrab_r0.2_back.jpeg "Back Photo") --->

## Licence

 * Hardware in this repository is licenced under CERN OHL v1.2
 * Gateware/Software/Firmware in this repository is licenced under MIT unless otherise indicated

## OSHW
Eventual goal is to be OSHWA approved.
<!--- This board is an OSHWA approved design: [AU000006](https://certification.oshwa.org/au000006.html) --->
