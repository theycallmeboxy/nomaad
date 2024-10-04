# Nomaad
*A 11 column ortho/alpha gaming keyboard for gamers*

<img src="https://github.com/theycallmeboxy/nomaad/blob/main/img/nomaad-01.jpg" alt="keyborb" width="600"/>

<img src="https://github.com/theycallmeboxy/nomaad/blob/main/img/nomaad-02.jpg" alt="keyborb" width="600"/>

**[KLE](https://www.keyboard-layout-editor.com/##@_name=Nomaad%20Vial&author=theycallmeboxy%3B&@_x:0.5%3B&=0,1&=0,2&=0,3&=0,4&=0,5%3B&@=1,0&=1,1&=1,2&=1,3&=1,4&=1,5&=1,6&=1,7&=1,8&=1,9&=1,10%3B&@=2,0&=2,1&=2,2&=2,3&=2,4&=2,5&=2,6&=2,7&=2,8&=2,9&=2,10%3B&@_c=%2300c5ff%3B&=3,0%0A%0A%0A0,0&=3,1%0A%0A%0A0,0&=3,2%0A%0A%0A0,0&=3,3%0A%0A%0A0,0&=3,4%0A%0A%0A0,0&=3,5%0A%0A%0A0,0&=3,6%0A%0A%0A0,0&=3,7%0A%0A%0A0,0&=3,8%0A%0A%0A0,0&=3,9%0A%0A%0A0,0&=3,10%0A%0A%0A0,0%3B&@_c=%23cccccc%3B&=4,0&_x:1&c=%23ffb80c%3B&=4,1%0A%0A%0A1,0&_w:3%3B&=4,3%0A%0A%0A1,0&_w:2%3B&=4,6%0A%0A%0A1,0&=4,7%0A%0A%0A1,0&_x:1&c=%23cccccc%3B&=4,10%3B&@_y:0.5&c=%2300c5ff&w:1.5%3B&=3,0%0A%0A%0A0,1&=3,1%0A%0A%0A0,1&=3,2%0A%0A%0A0,1&=3,3%0A%0A%0A0,1&=3,4%0A%0A%0A0,1&=3,5%0A%0A%0A0,1&=3,6%0A%0A%0A0,1&=3,7%0A%0A%0A0,1&=3,8%0A%0A%0A0,1&_w:1.5%3B&=3,10%0A%0A%0A0,1%3B&@_y:0.25&x:2&c=%23ffb80c&w:7%3B&=4,3%0A%0A%0A1,1)**

## Production Files:
> [!CAUTION]
> I will assume no responsibility for any cost, damage, or sads resulting from trying to make one of my dumb projects. This project has no implicit support, neither moral nor technical.
> 
> **I'm not a doctor. This is not medical advice. I'm also only a network engineer. You assume all liability in using or reproducing these files.**

Case:
- [Case .stl file](https://github.com/theycallmeboxy/nomaad/blob/main/models/case/nomaad-case.stl)
- [Case .step file](https://github.com/theycallmeboxy/nomaad/blob/main/models/case/nomaad-case.step)

Plate:
- [Ortho stagger plate .dxf file](https://github.com/theycallmeboxy/nomaad/blob/main/models/plate/nomaad-plate_ortho.dxf)
- [Alpha stagger plate .dxf file](https://github.com/theycallmeboxy/nomaad/blob/main/models/plate/nomaad-plate_alpha.dxf)

PCB:
> [!NOTE]
> Version 1 was produced (as prototype 1) without any identified issues.  The gerbers were regenerated to indicate version 1 on the silk and the bom and positions files should be fixed to order as-is.  I have not produced these files yet, but they should be good to go.

- [PCB gerbers .zip file](https://github.com/theycallmeboxy/nomaad/blob/main/pcb/nomaad%20v1/production/nomaad.zip)
- [BOM .csv file](https://github.com/theycallmeboxy/nomaad/blob/main/pcb/nomaad%20v1/production/bom.csv)
- [Positions .csv file](https://github.com/theycallmeboxy/nomaad/blob/main/pcb/nomaad%20v1/production/positions.csv)

Firmware:
- [VIAL Firmware .bin file](https://github.com/theycallmeboxy/nomaad/blob/main/firmware/vial/binary/boxy_nomaad_vial.bin)
  
## Build Notes:

I have made with FDM and CNC aluminum to good effect.  Another 40s member had a resin version manufactured successfully.

**Additional materials:**
 
  - About 18" of .139" (3.53mm) diameter o-ring cord [like this 50A cord](https://www.theoringstore.com/store/index.php?main_page=product_info&cPath=117_527&products_id=18618) or [this 70A cord](https://www.theoringstore.com/store/index.php?main_page=product_info&cPath=117_119&products_id=5058); if you don't want to buy bulk cord, you can cut up an o-ring of like 6" or bigger diameter.
  - 4 SKUF feet like these  [like these](https://keeb.io/products/skuf-silicone-rubber-keyboard-feet).

**Build instructions:**

1. Apply feet to the cutouts.
2. Install stabs if you're into that. 
3. Install switches into the plate and PCB.
4. Solder it up.
5. Friction fit the o-ring cord between the plate and PCB in the positions highlighted in red:

<img src="https://github.com/theycallmeboxy/nomaad/blob/main/img/nomaad-cord-path.png" alt="keyborb" width="600"/>

<img src="https://github.com/theycallmeboxy/nomaad/blob/main/img/nomaad-cord-friction-fit.jpg" alt="keyborb" height="600"/>

6. Insert the assembled PCB number keys first into the case at an angle while aligning the USB port with the cutout
7. Press the top of the PCB in place, then press in the bottom side
8. If you need to remove the PCB, pull a few caps off and use a switch puller on the soldered switches
