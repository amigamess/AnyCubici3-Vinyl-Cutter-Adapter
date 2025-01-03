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

