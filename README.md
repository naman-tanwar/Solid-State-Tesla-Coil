# Solid State Tesla Coil (SSTC)
![N|TeslaCoil](https://live.staticflickr.com/65535/52919984034_5087448f26_b.jpg)

## Introduction
Solid State Tesla Coil uses transistor based swiching devices (instead of Spark Gap) to resonate the secondary coil with or without feedback. 
The both kinds of circuits (with and without feedback) were designed and tested.
The features of the SSTC are:
1. Feedback and without feedbnack Circuits
2. Variable duty cycle Interrupter
3. Music Interrupter to play music from SSTC
4. PCB Design

## Design
The design of the tesla coil is described below,
### Coil Design
1. Primary Coil  <br>
Primary Coil consist of 5mm copper pipe with 6 turns wound around the secondary with 3D printed support.  <br>
2. Secondary Coil  <br>
The secondary winding are wound around a 2-inch PVC water pipe with 36 gauge copper moter winding wire. The length of the pipe is around 25cm with winding height of 20cm. 5cm of PVC pipe is kept as a margin.
Around 1200 turns of described wire was winded.  <br>
3. Top Load  <br>
The top load was 3D printed in two halves and then aluminium tape was wrapped around it. The tape was wrapped with as much wrinkles as possible to reduce charge loss. The 3D files are availabe to download on this github page  <br>
5. 3D printed holder for coils  <br>
Using Fusion 360, the coil holder was designed. The files for the holder can also be downloaded from this github page.  <br>

### Circuit Design
As described in the Introduction section, the different circuits were designed to incoperate all the features. Before actually implementing tho, these were simulated using LTSpice. <br>
The Complete circuit diagram and all the simulation files are available on this page.

### PCB Design
A PCB was also designed using Altium. The PCB is a 4 layer board with 100mm x 100mm dimentions. All generic parts THT parts were used in this design.
The features of the PCB are:
1. It uses tunable non-feedback ciruit
2. Can also play music. The music input can be given using 3.5mm mobile AUX cable.
3. Circuit is tested with voltages from 12V to 15V  
<br>
The gerber files, Bill Of Material (BOM), Altium project files and other related documents are available to download from this page.
