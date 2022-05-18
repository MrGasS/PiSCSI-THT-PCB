RaSCSI THT PCB by MrGasS aka S.E.M.M.  
  
RaSCSI THT is a PCB based on the original RaSCSI schematics, this PCB aims to be cheap to make and DIY friendly, especially for those who have bad SMD soldering skills (not me, hehe).  
  
I made this PCB for personal use, but I like to share it.
You're free to make your own RaSCSI THT.  
  
This PCB gives you a typical 50 pin port for internal or SCSI case use, a DB-25 port for external use and also a 2mm 50 pin port for PowerBooks.  
  
For PowerBook use: please note that stuffing my PCB into a PowerBook could require a bit of tweaking. In fact, I put the PowerBook port just to make this PCB more complete, but I'm not even sure that this stuff will fit into a PowerBook computer. Please note that I could remove it in next releases if incompatibilites will be discovered. Right now my PowerBook 145B has a broken screen and Pis are pricey, so, I'm not going to test this feature. Please, leave a feedback if you'll decide to test this feature.  
--------------------------------------------------------------------------------------------------------------------  
BOM:  
P1: 2x20 = 40 pin header  
R1: 330 ohm resistor (for led)  
1A FUSE: 1A generic 3,6x10mm fuse, maybe a fast blow one.  
RN1 - RN2: 18x 10k resistors | OR | 2x 4610X-101-103LF  
IC1 - IC2 - IC3 - IC4: 4x SN74LS641-1N  
RN3 - RN4: 18x 330 ohm resistors | OR | 2x 4610X-101-331LF  
RN5 - RN6: 18x 220 ohm resistors | OR | 2x 4610X-101-224LF  
SCSI - 50 pin: 2x25 = 50 pin header  
SCSI DB-25: female DB-25 angle port  
SCSI - PB: 2x25 = 50 pin header with 2mm pitch  
OLED: 128x32 3.3V OLED screen  
--------------------------------------------------------------------------------------------------------------------  
JUMPERS:  
TERM_GND and TERM_5V: short them with a jumper to enable termination.  
  
Enable TPWR: enable termination power to other SCSI device from the Raspberry Pi. Could be useful when daisy chaining devices with a Macintosh Plus, a IIsi, or a PowerBook: in general, with a computer that doesn't serve termination power through the SCSI port.  
  
Short to Enable PB LED: short this if you're installing my RaSCSI into a PowerBook. On the original RaSCSI PCB this is connected from factory, but you'll need to short it on mine.  
