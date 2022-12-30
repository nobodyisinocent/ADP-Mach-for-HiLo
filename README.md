# Table of contents
1. [MACH PCB Adapter final version](#MACH-PCB-Adapter)
2. [Why a such adapter](#Why-a-such-adapter)
3. [Pictures of the assembled adapter](#Pictures)
4. [Adapter onto the ALL-03 programmer](#Adapter-onto-the-ALL-03-programmer)
5. [About the project files](#About-the-project-files)
6. [BOM](#BOM)


# MACH PCB Adapter final version <a name="MACH-PCB-Adapter"></a>

![PCB-Front](https://user-images.githubusercontent.com/80821708/202574285-531f18d1-5516-402e-ab55-a56485f13b92.png)

Final version of the pcb's adapter.

# Why a such adapter <a name="Why-a-such-adapter"></a>
This adapter is made for programming MACH chips with ALL-03 & ALL-07 programmers. It has been designed specialy for programming the MACH210 used onto the MEGGIT Module of the Zorro Predule Audio board for Amiga Computers.

The schematic of the adapter has been made by tinhead. Many thanks to him for his autorization of the publication of this adapter.

For informations about the HI-LO universal parallel programmer, you can visit the following very interesting resources page made by Matthieu Benoit:
http://matthieu.benoit.free.fr/hilosystem_all-07_universal_programmer.htm


# Pictures of the assembled adapter <a name="Pictures"></a>
Thanks to Lolof for the following pictures
![IMG_2651](https://user-images.githubusercontent.com/80821708/210116885-259e9300-7596-43a1-a419-6d15f55e6e42.jpg)

![IMG_2649](https://user-images.githubusercontent.com/80821708/210117119-f3bfe88e-e814-48a1-95f8-e56985fac8d9.jpg)


# Adapter onto the ALL-03 programmer <a name="Adapter-onto-the-ALL-03-programmer"></a>
Please pay attention to the orientation of the adapter onto the programmer. This orientation is the same for the ALL-07 programmer.
A wrong orientation will destroy the MACH chip.


# About the project files <a name="About-the-project-files"></a>
The complete project is available here for downloading (Kicad files + Gerber archive archive file ready for production).

The project has been made with Kicad 5.1.12 under Linux: https://www.kicad.org/

and FreeRooting: https://github.com/freerouting/freerouting under Linux.

# BOM <a name="BOM"></a>
Here be here soon. :-)

|Id	|Designator	|Package	|Quantity	|Designation	|Reichelt part number	|Link  |
|---|---|---|---|---|---|---|
|1	|D1,D2      |	D_DO-41_SOD81_P7.62mm_Horizontal	|2	|UF10-005	|UF 4003	|https://www.reichelt.de/de/fr/diode-de-redressement-ultrarapide-do41-200-v-1-a-uf-4003-p42034.html |
|2	|D3 to D8   |	D_DO-35_SOD27_P7.62mm_Horizontal	|6	|1N4150	|1N 4148	|https://www.reichelt.de/de/fr/diode-de-commutation-100-v-150-ma-do-35-1n-4148-p1730.html |
|3	|Q1,Q2	    |TO-18-3	|2	|2N2222A	|2N 2222A	|https://www.reichelt.de/de/fr/transistor-npn-to-18-40-v-0-8-a-0-5-w-2n-2222a-p1968.html |
|4	|R1,R3	    |R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal	|2	|1K	METALL |1,00K	|https://www.reichelt.de/de/fr/r-sistance-film-m-tallique-de-1-00-kohms-metall-1-00k-p11403.html?r=1 |
|5	|R2,R4	    |R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal	|2	|3K3	METALL |3,30K	|https://www.reichelt.de/de/fr/r-sistance-film-m-tallique-de-3-30-kohms-metall-3-30k-p11693.html?&trstct=pos_0&nbc=1 |
|6	|U1 |DIP-40_W15.24mm	|1	|ZIF HEADER| |  |
|7	|ZIF-HEADER	|DIP-28_W15.24mm	|1	|ZIF|	|  |
