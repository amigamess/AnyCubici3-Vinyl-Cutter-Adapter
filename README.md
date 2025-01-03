👋 Hi, I’m @amigamess (TheShark!)
👀 I’m interested in retrocomputing, music, 3D and more...
🌱 I’m currently learning Kicad, FreeCad...

# AnyCubici3-Vinyl-Cutter-Adapter
Vinyl Cutter adapter for AnyCubici3MegaS

![Cutter_01](https://github.com/user-attachments/assets/e4bc32e8-4279-4017-8f86-327af1c30f6e)

![Cutter_04](https://github.com/user-attachments/assets/2f8e582b-96eb-4056-8831-eb2f7ec3c13a)

![Cutter_02](https://github.com/user-attachments/assets/722ffc4d-e7a0-49ef-ac73-0de11ad6d00c)

Cutter from Aliexpress!
![cutter](https://github.com/user-attachments/assets/e42e61cd-3ba4-4bf2-82da-98266745216d)

Use inkscape for trace stickers, FREECAD for export .stl and CURA for CUT! 

CURA SETTING:
Create a new Printer, modify start GCode page in CURA (donwload file "gcode STAR AnycubicPLOTTER.txt" and past into config area, look photo) 

![impostazioniCURAPlotter_01](https://github.com/user-attachments/assets/afbff155-0f9d-4b5e-adb9-1cc4df3c2a1a)

DOWNLOAD ZOFFSET EXTENSION for CURA

https://marketplace.ultimaker.com/app/cura/plugins/fieldofview/ZOffsetPlugin

![zoffsetExtension](https://github.com/user-attachments/assets/6ef6a863-c994-492d-be02-4b3d4cb1255c)

you can now set ZOFFSET in Cura.

CURA SETTINGS

![impostazioniCURAPlotter_02](https://github.com/user-attachments/assets/5fe2dde3-c717-4a38-976f-8ab4dea4da0b)

![impostazioniCURAPlotter_03](https://github.com/user-attachments/assets/af9e803e-e255-481a-a075-de76314134bf)

ZOFFSET YOU NEED TO CALCULATE!!!

![impostazioniCURAPlotter_04](https://github.com/user-attachments/assets/63a53e81-f4e1-42f1-bd07-731f413673c6)


HOW TO UK:

In cura you have to create a new printer (call it PLOTTER),
modify the parameters as per the attached screen, use inkscape to draw the shapes,
import in FREECAD, make an extrusion of 0.2mm (no solid) and export in .stl
Via CURA you can do the rest...

The distance of the blade is about 6 CM from the printing nozzle, therefore calculate
the adhesive on the plate correctly.

PLATE 210x210
--------
|      |
|      | center of the plate
|      |
--------
________ <----cutting head

To take the initial z-offset measurement (download the plug-in from: https://marketplace.ultimaker.com/app/cura/plugins/fieldofview/ZOffsetPlugin),
bring the printer to HOME ALL, go up 20 mm in Z by hand, move just enough
to see the blade on the plate, insert a sheet and start to slowly go down with Z (1mm at a time)
until it touches the blade.

The difference in millimeters between the initial 20 and those needed to touch, are the millimeters to insert in z-offset.

Maybe do tests without blade, or standing higher, the risk of ruining the plate is real...

Remember to enable Z Hop movements (Z Hop during retraction) at least 4 mm,
otherwise the blade could cut unintentionally..

The pressure of the blade (Z axis), depends on the spring you use, start by step,
with my spring, at least 1.5-2 mm are needed.


ITALIANO:

In cura dovete creare una nuova stampante (chiamatela PLOTTER), 
modificare i parametri come da screen allegati, usare inkscape per disegnare la forme, 
importate in FREECAD, fate una estrusione di 0,2mm (no solido) e esportate in .stl
Via CURA potete fare il resto... 

La distanza della lama è di circa 6 CM rispetto al nozzle di stampa, pertanto calcolare
l'adesivo sul piatto in maniera corretta.

PIATTO 210x210
--------  
|      |
|      |  centro del piatto
|      |
--------
________ <----testina di talgio

Per prendere la misura del z-offset iniziale (scaricare il plug-in da:https://marketplace.ultimaker.com/app/cura/plugins/fieldofview/ZOffsetPlugin), 
portare la stampante a HOME ALL, salire di 20 mm in Z a mano, spostarsi quanto basta
per vedere la lama sul piatto, inserire un foglio e iniziare a scendere piano con Z (1mm a volta)
fino a toccare con la lama. 
La differenza dei millimetri tra 20 iniziali e quelli necessari per toccare, sono i millimetri da inserire in z-offset. 
Magari fare prove senza lama, o stando più alti, il rischio di rovinare il piatto è reale...

Ricordarsi di abilitare Z Hop spostamenti (Z Hop durante la retrazione) almeno 4 mm, 
altrimenti la lama potrebbe tagliare involontariamente.. 

La pressione della lama (asse Z), dipende dalla molla che si utilizza, iniziare per step, 
con la mia molla, servono almeno 1.5-2 mm.













