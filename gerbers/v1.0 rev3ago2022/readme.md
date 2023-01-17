# **RaSCSI Reloaded THT PCB by MrGasS aka S.E.M.M.**  
  
**Version**: 1.0  
**Revision**: 3ago2022  
**Based on**: RaSCSI Reloaded v2.4 FullSpec 68kmla Version  
**Testing status:** fully tested and working.
## 17/1/2023 ANOTHER UPDATE
I can firmly say that the problem with my IIci (and, at this point, also with my IIsi) was a missing dummy load on my ATX.  
After I connected the internal IIci hard drive (a 160MB IBM hard drive that sounds like a Boeing 747) and two external hard drive as a dummy load, everything works fine.  
I booted 7.6.1, played few games from an ISO image filled with shareware and I'm surfing the web with DynaPORT emulation and Netscape 1.12 right now :)  
_________________________________________________________________________  
###### 8/1/2023: UPDATE  
I've done a lot of tests in this months and I can confirm that this PCB is absolutely correct, I compared the KiCAD project and the physical PCB against the original RaSCSI Reloaded 2.4 schematic and everything matches.  
Yes, I have some issues when I connect it to my IIsi and IIci, but the point is that I run these Macs with a low-range ATX power supply and I suspect that it's the main cause of some instabilities, sometimes these Macs crash even with the April 2022 prototype.  
However, I tested this PCB with my LC, my Quadra 700 and my G3/266 Beige Desktop and everything seems to be fine, no instability, no crashes, everything works.  
The LC runs Mac OS 6.0.8 -> 7.5.3 without issues.  
The Quadra 700 runs 7.1.2 -> 8.1 without issues, I even installed 7.5 on the intenal BlueSCSI and everything works.  
The G3 runs 8.1 -> 9.2.2 without problems, I even installed 8.1 and 8.6 from the internal DVD unit to the RaSCSI and this computer boots from it without issues.  
You can obviously make your own PCB, but I'm not responsible for any damage you can make to your Macintosh and keep in mind that some instabilities can be related to the software side.  
If you're searching some rock-solid storage solution for your Mac go for a BlueSCSI.  
Please, leave a feedback if you're gonna use this PCB on a IIsi or a IIci.  
Thank you.  
__________________________________________________________________________  
~~31/10/2022: ISSUES DISCOVERED, PLEASE READ ME!  
While the protos from April are working perfectly, I encountered some problems with this version of the board (1.0 rev3ago2022), specifically it doesn't work with a Macintosh IIsi and I'm trying to figure out where the problem is.  
Please, avoid printing this board for now, as I'm still analyzing the scheme and the KiCad project against the printed PCB.  
If everything will be solved, this text will be cutted and an update will be published, or maybe you'll see a new 1.1 version of the board.  
I'm sorry, I'll try to solve this bullshit as soon as possible.~~
