# Table of contents
1. [MACH PCB Adapter final version](#MACH-PCB-Adapter)
2. [Why a such adapter](#Why-a-such-adapter)
3. [Pictures of the assembled adapter](#Pictures)
4. [Adapter onto the ALL-11 programmer](#Adapter-onto-the-ALL-Lab3-programmer)
5. [About the project files](#About-the-project-files)
6. [BOM](#BOM)


# MACH PCB Adapter final version <a name="MACH-PCB-Adapter"></a>

![PCB-Front](https://user-images.githubusercontent.com/80821708/202574285-531f18d1-5516-402e-ab55-a56485f13b92.png)

Final version of the pcb's adapter.

# Why a such adapter <a name="Why-a-such-adapter"></a>
This adapter is made for programming MACH chips with HiLo programmers. It has been designed specialy for programming the MACH210 used onto the MEGit Module of the Zorro Predule Audio board for Amiga Computers.

The schematic of the adapter has been made by tinhead from eevblog.com. Many thanks to him for his great work.

For informations about the HI-LO universal parallel programmer, you can visit the following very interesting resources page made by Matthieu Benoit:
http://matthieu.benoit.free.fr/hilosystem_all-07_universal_programmer.htm


# Pictures of the assembled adapter <a name="Pictures"></a>
Thanks to Lolof for the following pictures
![IMG_2651](https://user-images.githubusercontent.com/80821708/210116885-259e9300-7596-43a1-a419-6d15f55e6e42.jpg)

![IMG_2649](https://user-images.githubusercontent.com/80821708/210117119-f3bfe88e-e814-48a1-95f8-e56985fac8d9.jpg)


# Adapter onto the ALL-11 programmer <a name="Adapter-onto-the-ALL-Lab3-programmer"></a>
Please pay attention to the orientation of the adapter onto the programmer.
A wrong orientation will destroy the MACH chip.

Here is the adapter used for programming a MACH210 for the Amiga Prelude board.
![IMG_3053-reduc](https://user-images.githubusercontent.com/80821708/210118731-970982cf-ae43-4902-892c-2062c8205040.jpg)

And a picture of the software in action !
![IMG_2536](https://user-images.githubusercontent.com/80821708/210118881-bd16d831-c185-4a89-8f06-48e049256196.jpg)



# About the project files <a name="About-the-project-files"></a>
The complete project is available here for downloading (Kicad files + Gerber archive archive file ready for production).

It's a Free project, so:

----- PRODUCTION FOR COMMERCIAL PURPOSES STRICTLY FORBIDDEN -----

The project has been made with Kicad 5.1.12 under Linux: https://www.kicad.org/

If you use Kicad, you can make the rooting of your pcb with FreeRooting: https://github.com/freerouting/freerouting.

Oneline manual: https://freerouting.org/freerouting/using-with-kicad

# BOM <a name="BOM"></a>
Will be here soon. :-)

|Id	|Designator	|Type	|Value  |Quantity	|Link  |
|---|---|---|---|---|---|
|1	|C5      |	1206 CMS capacitor	|10nF  |1	| https://www.reichelt.com/fr/fr/index.html?ACTION=446&LA=0&nbc=1&q=x7r-g1206%2010n |
|2	|IC1   |	PLCC44 socket	| - | 1	|https://www.reichelt.com/fr/fr/socles-plcc-44-plcc-44-p14701.html?search=PLCC&&r=1 |
|3	|RN1 to RN3	    | Network 1206 CMS resistors		|10K |3 |https://www.reichelt.com/fr/fr/r-seau-de-r-sistances-cms-1206-4x10-kohm-5-3-2x1-6x0-6-mm-bcn16-10k-p42471.html?search=+BCN16+10K&&r=1 |
|4	|C1    |3225 CMS Tantalum capacitor	|10µF |1	|https://www.reichelt.com/fr/fr/smd-tantal-lowesr-10-f-10-20-v-case-b-0-5-ohm-tps-3225-10-20-p167050.html?search=+TPS+3225+10%2F20&&r=1 |
|5  |C2 to C4 | 1206 CMS Capacitor  | 100nF | 3 |https://www.reichelt.com/fr/fr/condensateur-c-ramique-multicouche-cms-100-nf-10--x7r-g1206-100n-p22889.html?search=X7R-G1206+100N&&r=1|
|6  | - | Pin array 2.54mm  | - | 1 |https://www.reichelt.com/fr/fr/barrette-m-le-2-54-mm-1-x-50-droite-mpe-087-1-050-p119891.html?search=MPE+087-1-050&&r=1|
