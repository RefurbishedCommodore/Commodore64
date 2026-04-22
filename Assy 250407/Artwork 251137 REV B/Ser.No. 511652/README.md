<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

![Name](https://img.shields.io/badge/Serial_No.-511652-white?style=plastic)
<br>
![Name](https://img.shields.io/badge/Assy-250407-white?style=plastic)
![Name](https://img.shields.io/badge/Artwork-251137-white?style=plastic)
![Name](https://img.shields.io/badge/Revision-B-white?style=plastic)
![Name](https://img.shields.io/badge/Video_format-PAL-white?style=plastic)


# Table of contents

<!-- TABLE OF CONTENTS -->
<details>
<summary>TOC - Click to enlarge</summary>
  <ul>
    <li>
      <a href="#starting-point">Starting point</a>
    </li>
    <li>
      <a href="#refurbish-activities">Refurbish activities</a>
    </li>
    <li>
      <a href="#disassembly">Disassembly</a>
    </li>
    <li>
      <a href="#mainboard">Mainboard</a>
      <ul>
        <li>
          <a href="#visual-inspection">Visual inspection</a>
        </li>
        <li>
          <a href="#initial-testing">Initial testing</a>
        </li>
        <li>
          <a href="#checking-the-voltages">Checking the voltages</a>
        </li>
        <li>
          <a href="#remediation-of-problem-areas">Remediation of problem areas</a>
        </li>
      </ul>
    <li>
      <a href="#keyboard">Keyboard</a>
      <ul>
        <li>
          <a href="#removing-the-keycaps">Removing the keycaps</a>
        </li>
      </ul>
    </li>
    <li>
      <a href="#casing">Casing</a>
      <ul>
        <li>
          <a href="#removing-the-power-LED">Removing the power LED</a>
        </li>
        <li>
          <a href="#removing-the-metal-badges">Removing the metal badges</a>
        </li>
        <li>
          <a href="#cleaning-and-retrobrighting-the-covers">Cleaning and retrobrighting the covers</a>
        </li>     
      </ul>
    </li>
  </ul>
</details>

# Starting point

This breadbin Commodore 64 is in for some refurbish. I do not know if it works or not, but from the outside it looks to be in quite good condition. I can not see any real damage to it at all. There are some minor "burn marks" on the casing which is a result of cables which probably have been wrapped around the machine at some point.

At the underside there are some scratches, but this is also quite minor. Also, since this is on the underside of the machine no one will notice anyway. The keycaps are a bit dirty, but I would not expect otherwise after so many years. And both the top- and bottom cover are quite yellowed. The keyboards feels good also. The topside of the keycaps are a bit yellowed.

The "Commodore 64" metal badge is a bit loose at the left hand side. And the serial sticker has fallen off the bottom cover. All of the four rubber feet are intact.

All in all this machine seems to have been taken good care of!

Below are some pictures of the breadbin Commodore 64 before refurbish.

<p align="center">
    <img src="Images/Start07.jpeg" alt="Description" width="800">
    <img src="Images/Start06.jpeg" alt="Description" width="600">
    <img src="Images/Start05.jpeg" alt="Description" width="600">
    <img src="Images/Start03.jpeg" alt="Description" width="600">
    <img src="Images/Start04.jpeg" alt="Description" width="600">
    <img src="Images/Start02.jpeg" alt="Description" width="600">
    <img src="Images/Start01.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Refurbish activities

The planned refurbishment activites for this Commodore 64 (Order may vary. Several of them in parallell):

- [ ] Refurbish mainboard
- [ ] Refurbish the keyboard
- [ ] Refurbish the casing
- [ ] Testing and validation

The plan can be updated during the refurbishment process. Sometimes I discover areas that needs special attention.
<br>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

First step in the disassembly is to remove the three Phillips screws[^1] on the underside. These are the most common type for the breadbin model. I notice a fine "cracking" sound when the screws are removed (with a low torque screwdriver). This is a good sign - it can be that this machine is not opened before. Not guaranteed though, but that "cracking" sound is often an indication that these screws have been sitting there for many years.

<p align="center">
    <img src="Images/Dis01.jpeg" alt="Description" width="800">
</p>

With the screws out of the way the machine is flipped over again, and the top cover is carefully lifted 30 degrees and wiggled off. Now the interior is exposed. It looks to be in very good condition. I can not see any signs of moisture on the cardboard RF-shield (the RF-shield is wrinkled, but I do not think this is caused by moisture). I think it is fair to assume that his Commodore 64 has been stored in a dry storage with quite stable temperatures.

<p align="center">
    <img src="Images/Dis02.jpeg" alt="Description" width="800">
</p>

I notice something during disassembly: the LED connector is not properly attached to the three pins on the PCB. The three pins seems to be slighly bent actully which could make the installation of the connector difficult. Does this mean that the hypothesis that no one has opened this Commodore 64 before fail? No, I don´t think so. It is possible that the LED connector was installed this way during assembly sometime during assembly. Neverheless, this should be easy to fix.

<p align="center">
    <img src="Images/Dis03.jpeg" alt="Description" width="400">
</p>

The rear plastic clips are in good condition - none of them are partly broken or missing. This kind of plastic clips are also way more robust than the small, thin clips found in (earlier) case versions. The top cover has an embossed number on it: "326113".

<p align="center">
    <img src="Images/Dis04.jpeg" alt="Description" width="800">
</p>

The cardboard RF-shield is lifted away, and the PCB is exposed in all its glory. And this is a very good sight. The PCB looks to be in really good condition! There is very - VERY - little dust and grease inside here. Something I notice: there is a lighter squared area on the cartridge port. This is an area where it is quite common that a sticker from the assemly is placed. It is likely that this sticker has dried and fallen out - or it being removed during a repair inspection many years later. Nevertheless, this is a sign that someone might have been here before.

There are no sign of corrosion, neither on the PCB itsef nor the metal parts (VIC-II shield, cartridge connector and RF-modulator). Another indication that this Commodore 64 has been stored in a dry and tempered room.

All the seven Phillips screws are in place holding the PCB to the bottom cover. They are removed with a low torque screwdriver to free the PCB from the bottom cover.

<p align="center">
    <img src="Images/Dis05.jpeg" alt="Description" width="1000">
</p>

With the PCB out of the way the inside of bottom cover is visible. It seems to be in fine condition. There are some slightly yellowing around the port- and cartridge areas, but that is to be expected. The bottom cover has an embossed number on it: "326114".

<p align="center">
    <img src="Images/Dis06.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Mainboard

The mainboard is the Assy 250407/Artwork 251137 Rev B. Also marked with "W-18 94HB". This is one of the early revisions of the mainboard which is characterised by having the full PLL clock circuitry and the VIC-II positioned vertically. It is not the earliest revision though, so the A/V connector is full eight pin with LUMA and CHROMA output.

## Visual inspection

The mainboard appears to be in very good condition. And I can not see any signs of rework from previous repair(s). There are some dust and grease on the PCB close to the port openings, but this to be expected.

Notice that most of the custom MOS ICs are in socket. But for some reason the character ROM (MOS 901225-01) is not socketed. Why? Not sure, but I think it is fair to assume that Commodore we running low on stock on sockets - or would like to save a little bit of money.

Below are some pictures of the mainboard before refurbish.

<p align="center">
    <img src="Images/Main01.jpeg" alt="Description" width="1000">
    <img src="Images/Main02.jpeg" alt="Description" width="1000">
    <img src="Images/Main08.jpeg" alt="Description" width="600">
</p>

There are some things to notice from the visual inspection which will be inspected further and taken care of:

> **Areas:**
>
> * LED connector - The LED connector CN10 is bent
>   
> * Emerging corrosion - On the backside of the PCB there seems to be some emerging corrosion between U14 and U16
> 
> * Flux residue - On the backside of the PCB there are some old flux residue from a hand soldering of R27
> 
> * Ceramic capacitor and thermal paste - The ceramic capacitor C54 is leaning towards the VIC-II chip. Also the thermal paste on the VIC-II is dried out and is spilled over the pins
>
> * Datasette port - The datasette port (CN3) is heavily oxidized and it looks like there is a broken trace?

Below are some pictures of these noticeable areas. Click to enlarge.

<p align="center">
    <img src="Images/Main03.JPG" alt="Description" width="500">
    <img src="Images/Main04.JPG" alt="Description" width="500">
</p>

<p align="center">
    <img src="Images/Main06.JPG" alt="Description" width="500">
    <img src="Images/Main05.JPG" alt="Description" width="500">
</p>

In the table below all the major custom IC found on the mainboard are listed. As can be seen from the table the custom MOS chips were produced during a time interval from week 03 in 1983 to week 04 in 1984. I think it is a fair guess that this Commodore 64 were manufactured sometime during winter of 1984.

| Chip/Area | Manufactor | Version | Date code | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU | MOS | 6510 | W49 Y1983 | Yes |  |
| SID | MOS | 6581 | W03 Y1983 | Yes |  | 
| VIC-II | MOS | 6589R3 | 30 Y1983 | Yes | Third revision. Ceramic. Gold plated pins. |
| PLA | COMMODORE | 251064-01 | W45 Y1983 | Yes | |
| CIA #1 | MOS | 6526R4 | W32 Y1983 | Yes | |
| CIA #2 | MOS | 6526R4 | W32 Y1983 | Yes | |
| ROM - BASIC | MOS | 901226-01 | W27 Y1983 | Yes | |
| ROM - Kernal | MOS | 901227-03 | W04 Y1984 | Yes | 3nd revision - Latest version |
| ROM - Character | MOS | 901225-01 | Unknown | No | |
| RAM | OKI | M3764-15RS | Unknown | No | |
| Glue logic | Fairchild, Texas Instruments, Fujitsu, Motorola, Toshiba, Hitachi, OKI, National Semiconductor|  |  |  | No MOS glue logic |

## Initial testing

Some initial tests are performed to check the health of the machine. This is to see if the basic functions work as they should, and if they do not, see if any useful can be gathered from these diagnostic tools.

When running the Diagnostic Cartridge the full test harness is installed. 

<p align="center">
    <img src="Images/Main07.jpeg" alt="Description" width="1000">
</p>

The results on the initial testing is shown in the table below (screen thumbnails below) - click to enlarge:

<div align="center">
  
| Test ID | Test area | Test criteria | Result | Comment |
|:---------:|:----------|:----------|:----------:|:----------|
| #1 | Boot up | Default blue screen showing 38911 BASIC Bytes Free | PASSED | Flashing cursor present |
| #2| DeadTest | Passing all tests | PASSED |  |
| #3| Diagostics Cartridge| Passing all tests | PASSED | |
| #4| DesTestMAX | Passing all memory tests | PASSED | |
| #5| DesTestFULL | Passing all memory tests | PASSED | |

</div>

<p align="center" float="left">
    <img src="Images/InitTest01.jpeg" alt="Description" width="170">
    <img src="Images/InitTest02.jpeg" alt="Description" width="170">
    <img src="Images/InitTest03.jpeg" alt="Description" width="170">
    <img src="Images/InitTest04.jpeg" alt="Description" width="170">
    <img src="Images/InitTest05.jpeg" alt="Description" width="170">    
</p>

## Checking the voltages

Voltages are measured before - and after - refurbishment. This is to make sure that all voltages are within acceptable levels. This table is updated after refurbishment is completed. All voltages are measured according to the article Checking C64 voltages [(HOWTO-Checking the Commodore 64 voltages)](https://refurbished-commodore.com/checking-c64-voltages).

As seen in the table below all voltages are within acceptable levels.

<div align="center">
  
| Measure point | Target voltage | Measured voltage<br>Before refurbish| Measured voltage<br>After refurbish | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| PSU (5V) | 5 V DC | 5.0372 V |  | User port |
| PSU (9V) | 9 V AC | 8.227 V |  | User port |
| Vvid (+5 CAN)| 5 V DC | 5.030 V | | Pin #40 VIC-II |
| Vc (+5 CAN) | 5 V DC | 5.029 V | | Pin #14 4044 |
| Regulated (12V) | 12 V DC | 11.96 V | | Pin #28 SID |
| Unregulated (9V) | 9 V DC | 8.604 V | | R2 |

</div>


## Remediation of problem areas

**LED connector CN10** 

The LED connector (CN10) pins are bent. It seems like the pins have been forcefully bent when the connector housing was installed. With a pair of needle-nose pliers the pins are straightened.

<p align="center" float="left">
    <img src="Images/Main09.jpeg" alt="Description" width="450">
    <img src="Images/Main10.jpeg" alt="Description" width="508">
</p>

**Emerging corrosion U14/U16** 

There are some odd-looking residue seeping around the backside of the PCB (in the area of U14/U16). Not sure what this is really, but it does seem to be corrosive. The area is cleaned with some vinegar which will prevent any further corrosion. Finally the area is cleaned with properly with isopropanol.

As can be seen from the "after" picture some of the solder mask is gone, but all the metal traces and pads seems to be ok. The missing solder mask is repaired by applying some transparent nail polish.

<p align="center" float="left">
    <img src="Images/Main12.jpeg" alt="Description" width="500">
    <img src="Images/Main11.jpeg" alt="Description" width="500">
</p>

**Flux residue R27**

Flux is usually non-corrosive. But the issue with old flux is that it can get "sticky" after several years (40+) making it a collector of dust and moist. Therefore it is good practice to remove most of this flux in critical areas. The R27 is a 2k trimmer potensiometer used to calibrate the color displayed by the VIC-II. The flux is removed with isopropanol and some careful scraping with a plastic spudge.

<p align="center" float="left">
    <img src="Images/Main13.jpeg" alt="Description" width="500">
    <img src="Images/Main14.jpeg" alt="Description" width="500">
</p>

**Ceramic capacitor and thermal paste**

The ceramic capacitor C54 is leaning towards the VIC-II IC. That itself is not causing any issue with e.g. short circuits, but the VIC-II is one of the hottest ICs on the mainboard. And all components, such as capacitors, can derate faster is extraordinary heat is applied. Also, thermal paste can be conductive. When old and crusty thermal paste are spilled over the pins on the VIC-II this can cause problems.

<p align="center" float="left">
    <img src="Images/Main16.jpeg" alt="Description" width="500">
    <img src="Images/Main15.jpeg" alt="Description" width="500">
</p>

**Datasette port**

The datasette (CN3) port is heavily oxidized and there is some corrosion which might have caused a broken trace. It is very common that the datasette port is oxidized (and dirty) since the Commodore 64 was often used together with the datasette in Europe.

First, the port is cleaned with some isopropanol. Then a rubber eraser is used to carefully rub away the stuck grease. Note that these ports are gold plated so DO NOT USE a glassfiber pen unless strictly required. Most of the oxidation is gone after this cleaning operation.

Removing the corrosion is done by first applying some vineager. This will stop the on-going corrosion. Some scraping with a sharp picking tool and a glassfibre pen is required around the solder pad. Note that the glassfiber pen is not used on the gold plated area. The old solder is removed and the via is replenished with new solder. Luckily, it turns out that the trace was not completely broken. The cleaning, and repair, should now have fixed this and prevent it from any further corrosion. Finally, some transparent nail-polish is applied to function as a solder mask.

<p align="center" float="left">
    <img src="Images/Main17.jpeg" alt="Description" width="500">
    <img src="Images/Main18.jpeg" alt="Description" width="500">
</p>

The user port (CN2) is also cleaned with some isopropanol and a rubber eraser.

<p align="center">
    <img src="Images/Main19.jpeg" alt="Description" width="800">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


# Keyboard

To start refurbishing the keyboard it is disassembled from the front cover first. There are eight Pozidrive screws[^3] attaching the keyboard to the front cover. Note that care must be taken when removing these. The screws have been sitting there for 43 years and the standoffs can eaily crack.

<p align="center">
    <img src="Images/Keyb01.jpeg" alt="Description" width="1000">
</p>

The keyboard seems to be in good condition. All the keycaps are without any significant scratches or damage, and the springs beneath the keycaps also appears to be functioning. The SHIFT-LOCK key also locks in position. There are some dust, and the top of the keycaps are slightly yellowed.

<p align="center">
    <img src="Images/Keyb02.jpeg" alt="Description" width="1000">
</p>

## Removing the keycaps

All the 66 keycaps are removed with a keycap puller [(Tools).](https://refurbished-commodore.com/tools) Using a keycap puller will both reduce the probability of damaging the keycaps and breaking the plungers. When removing the keycaps make sure to store the spring for the SPACEBAR in a separate place. This spring is slightly larger than the rest of the springs.

<p align="center">
    <img src="Images/Keyb03.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Casing

The plan is to clean and retrobright the casing. But before the top- and bottom covers are cleaned the LED, metal badge and rubber feet are removed. 

## Removing the power LED

To remove the LED the inner plastic ring is removed first. Then the LED is pressed firmly from the outside (by pressing it towards a flat area) until it pops out. Finally, the last plastic clip is pried outwards.

<p align="center" float="left">
    <img src="Images/Case01.jpeg" alt="Description" width="300">
    <img src="Images/Case02.jpeg" alt="Description" width="358">
</p>

<p align="center" float="left">
    <img src="Images/Case04.jpeg" alt="Description" width="300">  
    <img src="Images/Case05.jpeg" alt="Description" width="326">  
</p>

<p align="center">
    <img src="Images/Case03.jpeg" alt="Description" width="600">
</p>

## Removing the metal badges

The metal badges embossed with "C= commodore 64" and "POWER" is the very symbol of this nostalgic machine. Removing them is straightforward, but it requires some patience to avoid damaging them. With some hot air from a hair dryer the badges are carefully pried off the top cover.

To make sure that the old glue on the badges are also removed the badges are placed in a box of mild soap water for about 24 hours. Then the first layer of glue is removed with a flat spudger. The second layer is removed in the same way. First 24 hours of water then scraping the glue away with a flat spudger.

<p align="center">
    <img src="Images/Case06.jpeg" alt="Description" width="800">
</p>

## Cleaning and retrobrighting the covers

Both the top- and bottom covers are quite dirty so they have to be cleaned properly. The way to do this is to leave them in mild soap water for a few days. This will remove the dust and dissolve the grease.

Also, the four rubber feet are removed before the cleaning. The reason for this is that these rubber feet will become "sticky" if they are exposed to retrobrighting chemicals.

After cleaning the top- and bottom cover looks way better. There are some cable burn marks (and marks in general) on the covers. I will leave these as they are as they do not degrade the aesthetics in any significant way.

Below are some pictures of the covers after cleaning - but before retrobrighting.

<p align="center">
    <img src="Images/Case07.jpeg" alt="Description" width="800">
</p>

**Footnotes**
[^1]: Phillips pan head (6.8 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 10.0 mm
[^2]: Phillips pan head (5.5 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 6.0 mm
[^3]: Pozidrive pah head (6.8 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 9.5 mm
