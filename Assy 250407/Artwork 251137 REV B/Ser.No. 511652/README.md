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
          <a href="#removing-and-cleaning-the-keycaps">Removing and cleaning the keycaps</a>
        </li>
        <li>
          <a href="#cleaning-the-keyboard-pcb">Cleaning the keyboard PCB</a>
        </li>
        <li>
          <a href="#reviving-the-keyboard-plungers">Reviving the keyboard plungers</a>
        </li>
      </ul>
    </li>
    <li>
      <a href="#casing">Casing</a>
      <ul>
        <li>
          <a href="#removing-the-power-led">Removing the power LED</a>
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

This breadbin Commodore 64 is in for some refurbishment. I do not know if it works or not, but from the outside it looks to be in quite good condition. I cannot see any real damage to it at all. There are some minor "burn marks" on the casing, which are likely the result of cables that have been wrapped around the machine at some point.

On the underside there are some scratches, but these are also quite minor. Since this is on the underside of the machine, no one will notice anyway. The keycaps are a bit dirty, but that is to be expected after so many years. Both the top and bottom covers are quite yellowed. The keyboard feels good as well. The tops of the keycaps are slightly yellowed.

The "Commodore 64" metal badge is a bit loose on the left-hand side, and the serial sticker has fallen off the bottom cover. All four rubber feet are intact.

All in all, this machine seems to have been well taken care of!

Below are some pictures of the breadbin Commodore 64 before refurbishment.

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

The planned refurbishment activites for this Commodore 64 (Order may vary. Several of them in parallel):

- [ ] Refurbish mainboard
- [x] Refurbish the keyboard
- [ ] Refurbish the casing
- [ ] Testing and validation

The plan can be updated during the refurbishment process. Sometimes I discover areas that needs special attention.
<br>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

The first step in the disassembly is to remove the three Phillips screws[^1] on the underside. These are the most common type for the breadbin model. I notice a faint "cracking" sound when the screws are removed (using a low-torque screwdriver). This is a good sign—it may indicate that this machine has not been opened before. It is not guaranteed, but that "cracking" sound is often an indication that the screws have been sitting in place for many years.

<p align="center">
    <img src="Images/Dis01.jpeg" alt="Description" width="800">
</p>

With the screws out of the way, the machine is flipped over again, and the top cover is carefully lifted about 30 degrees and wiggled off. Now the interior is exposed. It appears to be in very good condition. I cannot see any signs of moisture on the cardboard RF shield (the RF shield is wrinkled, but I do not think this is caused by moisture). I think it is fair to assume that this Commodore 64 has been stored in a dry environment with relatively stable temperatures.

<p align="center">
    <img src="Images/Dis02.jpeg" alt="Description" width="800">
</p>

I notice something during disassembly: the LED connector is not properly attached to the three pins on the PCB. The three pins seem to be slightly bent, which could make installation of the connector difficult. Does this mean that the hypothesis that no one has opened this Commodore 64 before fails? No, I don’t think so. It is possible that the LED connector was installed this way during assembly. Nevertheless, this should be easy to fix.

<p align="center">
    <img src="Images/Dis03.jpeg" alt="Description" width="400">
</p>

The rear plastic clips are in good condition—none of them are broken or missing. These types of plastic clips are also much more robust than the small, thin clips found in earlier case versions. The top cover has an embossed number: "326113".

<p align="center">
    <img src="Images/Dis04.jpeg" alt="Description" width="800">
</p>

The cardboard RF shield is lifted away, and the PCB is exposed in all its glory. This is a very good sight. The PCB appears to be in really good condition! There is very—VERY—little dust and grease inside.

One thing I notice is a lighter, square area on the cartridge port. This is an area where it is quite common for a sticker from the assembly process to be placed. It is likely that this sticker has dried out and fallen off—or that it was removed during a repair inspection many years later. Nevertheless, this is a sign that someone might have been here before.

There are no signs of corrosion, neither on the PCB itself nor on the metal parts (VIC-II shield, cartridge connector, and RF modulator). This is another indication that this Commodore 64 has been stored in a dry, temperature-stable environment.

All seven Phillips screws[^2] are in place, holding the PCB to the bottom cover. They are removed with a low-torque screwdriver to free the PCB from the bottom cover.

<p align="center">
    <img src="Images/Dis05.jpeg" alt="Description" width="1000">
</p>

With the PCB out of the way, the inside of the bottom cover is visible. It seems to be in fine condition. There is some slight yellowing around the port and cartridge areas, but that is to be expected. The bottom cover has an embossed number: "326114".

<p align="center">
    <img src="Images/Dis06.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Mainboard

The mainboard is Assy 250407 / Artwork 251137 Rev B, also marked "W-18 94HB". This is one of the early revisions of the mainboard, characterized by having the full PLL clock circuitry and the VIC-II positioned vertically. It is not the earliest revision, though, so the A/V connector is a full eight-pin version with LUMA and CHROMA output.

## Visual inspection

The mainboard appears to be in very good condition. I cannot see any signs of rework from previous repairs. There is some dust and grease on the PCB close to the port openings, but this is to be expected.

Note that most of the custom MOS ICs are socketed. However, for some reason, the character ROM (MOS 901225-01) is not socketed. Why? I am not sure, but it is reasonable to assume that Commodore was either running low on sockets or wanted to save a bit of money.

Below are some pictures of the mainboard before refurbishment.

<p align="center">
    <img src="Images/Main01.jpeg" alt="Description" width="1000">
    <img src="Images/Main02.jpeg" alt="Description" width="1000">
    <img src="Images/Main08.jpeg" alt="Description" width="600">
</p>

There are some items identified during the visual inspection that will be examined further and addressed:

> **Areas:**
>
> * LED connector – The LED connector CN10 is bent
>
> * Emerging corrosion – On the backside of the PCB, there appears to be some corrosion developing between U14 and U16
>
> * Flux residue – On the backside of the PCB, there is some old flux residue from hand soldering of R27
>
> * Ceramic capacitor and thermal paste – The ceramic capacitor C54 is leaning towards the VIC-II chip. In addition, the thermal paste on the VIC-II is dried out and has spread over the pins
>
> * Datasette port – The datasette port (CN3) is heavily oxidized, and it looks like there may be a broken trace

Below are some pictures of these areas. Click to enlarge.

<p align="center">
    <img src="Images/Main03.JPG" alt="Description" width="500">
    <img src="Images/Main04.JPG" alt="Description" width="500">
</p>

<p align="center">
    <img src="Images/Main06.JPG" alt="Description" width="500">
    <img src="Images/Main05.JPG" alt="Description" width="500">
</p>

The table below lists all major custom ICs found on the mainboard. As shown, the MOS chips were produced between week 03 of 1983 and week 04 of 1984, suggesting this Commodore 64 was likely manufactured during the winter of 1984.

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

Some initial tests are performed to check the health of the machine, determining whether the basic functions work as they should and, if not, whether any useful information can be gathered from these diagnostic tools.

When running the Diagnostic Cartridge, the full test harness is used.

<p align="center">
    <img src="Images/Main07.jpeg" alt="Description" width="1000">
</p>

The results of the initial testing are shown in the table below (see screen thumbnails)—click to enlarge:

<div align="center">
  
| Test ID | Test area | Test criteria | Result | Comment |
|:---------:|:----------|:----------|:----------:|:----------|
| #1 | Boot-up | Default blue screen showing 38911 BASIC Bytes Free | PASSED | Flashing cursor present |
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

Voltages are measured before—and after—refurbishment. This is to ensure that all voltages are within acceptable levels. The table is updated after the refurbishment is completed. All voltages are measured according to the article Checking C64 Voltages [(HOWTO-Checking the Commodore 64 voltages)](https://refurbished-commodore.com/checking-c64-voltages).

As seen in the table below, all voltages are within acceptable levels.

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

The pins of the LED connector (CN10) are bent. It appears that they were forcefully bent during installation of the connector housing. Using a pair of needle-nose pliers, the pins are carefully straightened.

<p align="center" float="left">
    <img src="Images/Main09.jpeg" alt="Description" width="450">
    <img src="Images/Main10.jpeg" alt="Description" width="508">
</p>

**Emerging corrosion U14/U16** 

There is some odd-looking residue seeping around the backside of the PCB (in the area of U14/U16). I am not sure what this is, but it does appear to be corrosive. The area is cleaned with vinegar, which will help prevent further corrosion. Finally, the area is properly cleaned with isopropanol.

As can be seen from the "after" picture, some of the solder mask is gone, but all the metal traces and pads seem to be OK. The missing solder mask is repaired by applying transparent nail polish.

<p align="center" float="left">
    <img src="Images/Main12.jpeg" alt="Description" width="500">
    <img src="Images/Main11.jpeg" alt="Description" width="500">
</p>

**Flux residue R27**

Flux is usually non-corrosive. However, the issue with old flux is that it can become "sticky" after several years (40+), making it a collector of dust and moisture. Therefore, it is good practice to remove most of this flux in critical areas.

R27 is a 2k trimmer potentiometer used to calibrate the color output of the VIC-II. The flux is removed using isopropanol and careful scraping with a plastic spudger.

<p align="center" float="left">
    <img src="Images/Main13.jpeg" alt="Description" width="500">
    <img src="Images/Main14.jpeg" alt="Description" width="500">
</p>

**Ceramic capacitor and thermal paste**

The ceramic capacitor C54 is leaning towards the VIC-II IC. This in itself is not causing any issues such as short circuits, but the VIC-II is one of the hottest ICs on the mainboard. All components, including capacitors, can degrade faster if exposed to excessive heat.

Thermal paste can also be conductive. When old and crusty thermal paste has spread over the pins on the VIC-II, it can cause problems.

<p align="center" float="left">
    <img src="Images/Main16.jpeg" alt="Description" width="500">
    <img src="Images/Main15.jpeg" alt="Description" width="500">
</p>

**Datasette port**

The datasette (CN3) port is heavily oxidized, and there is some corrosion that might have caused a broken trace. It is very common for the datasette port to become oxidized (and dirty), as the Commodore 64 was often used together with a datasette in Europe.

First, the port is cleaned with isopropanol. Then, a rubber eraser is used to carefully remove the stuck grease. Note that these ports are gold-plated, so **DO NOT USE** a glass-fiber pen unless strictly required. Most of the oxidation is removed after this cleaning process.

The corrosion is treated by first applying some vinegar. This will stop the ongoing corrosion. Some scraping with a sharp pick tool and a glass-fiber pen is required around the solder pad. Note that the glass-fiber pen is not used on the gold-plated area. The old solder is removed, and the via is replenished with new solder.

Fortunately, it turns out that the trace was not completely broken. The cleaning and repair should now have resolved the issue and prevented further corrosion. Finally, some transparent nail polish is applied to act as a solder mask.


<p align="center" float="left">
    <img src="Images/Main17.jpeg" alt="Description" width="500">
    <img src="Images/Main18.jpeg" alt="Description" width="500">
</p>

The user port (CN2) is also cleaned with isopropanol and a rubber eraser.

<p align="center">
    <img src="Images/Main19.jpeg" alt="Description" width="800">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


# Keyboard

To start refurbishing the keyboard, it is first disassembled from the front cover. There are eight Pozidriv screws[^3] attaching the keyboard to the front cover. Note that care must be taken when removing these. The screws have been sitting in place for 43 years, and the standoffs can easily crack.

<p align="center">
    <img src="Images/Keyb01.jpeg" alt="Description" width="1000">
</p>

The keyboard seems to be in good condition. All the keycaps are free of any significant scratches or damage, and the springs beneath the keycaps also appear to be functioning. The SHIFT-LOCK key locks in position as expected. There is some dust, and the tops of the keycaps are slightly yellowed.

<p align="center">
    <img src="Images/Keyb02.jpeg" alt="Description" width="1000">
</p>

## Removing and cleaning the keycaps

All 66 keycaps are removed using a keycap puller [(Tools).](https://refurbished-commodore.com/tools) Using a keycap puller reduces the risk of damaging the keycaps or breaking the plungers. When removing the keycaps, make sure to store the spring for the SPACEBAR separately, as this spring is slightly larger than the others.

<p align="center">
    <img src="Images/Keyb03.jpeg" alt="Description" width="1000">
</p>

The keycaps are placed in a container filled with mild soapy water for 24 hours. This helps dissolve any grease and dirt on the keycaps.

<p align="center">
    <img src="Images/Keyb04.jpeg" alt="Description" width="500">
</p>

## Cleaning the keyboard PCB

To prepare the keyboard PCB (Assy 326166-02 / Ser. No. 14831214) for cleaning, the 23 small Phillips screws[^4] are removed.

<p align="center">
    <img src="Images/Keyb05.jpeg" alt="Description" width="800">
</p>

The SHIFT-LOCK needs to be desoldered before it can be removed from the keyboard. Once the two uninsulated wires are desoldered, the SHIFT-LOCK key can be easily removed by pushing it forward from the rear side.

<p align="center">
    <img src="Images/Keyb08.jpeg" alt="Description" width="500">
</p>

The SHIFT-LOCK is cleaned using isopropanol.

<p align="center">
    <img src="Images/Keyb09.jpeg" alt="Description" width="500">
</p>

It is very nice to see that this is the KSR-A66YF 56 4021**A** keyboard PCB from Mitsumi. These keyboard PCBs are special, as all 66 contact pads are **GOLD** plated. Later models (such as the **B** variant) have carbon pads. Since the pads are gold-plated, the entire PCB is thoroughly cleaned with isopropanol. It looks as good as new!

<p align="center">
    <img src="Images/Keyb06.jpeg" alt="Description" width="1000">
</p>

At the same time, the plastic bracket holding the PCB is cleaned with mild soapy water.

<p align="center">
    <img src="Images/Keyb07.jpeg" alt="Description" width="1000">
</p>

(Mark begin)

## Reviving the keyboard plungers

A very common issue with the Commodore 64 is that the keys stop working. Or to put in another way: they work partially, but you have to push REALLY hard to get any key response. Luckily, fixing this common issue is straightforward.

All plungers have a piece of conductive rubber at the end of the small plastic rod. This conductive rubber is easily contaminated with dust and grease, preventing the plunger from working as it should.

By **carefully** rubbing the conductive rubber on a clean sheet of paper the plungers are revived.

<p align="center">
    <img src="Images/Keyb10.jpeg" alt="Description" width="600">
</p>

Finally, the keyboard is re-assembled. The top of the keycaps are a bit yellowed, but the risk damage when retrobrighting brown keycaps is too high in my opinion. The keyboard looks very nice now!

<p align="center">
    <img src="Images/Keyb11.jpeg" alt="Description" width="1000">
</p>

(Mark end)

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Casing

The plan is to clean and retrobright the casing. However, before the top and bottom covers are cleaned, the LED, metal badge, and rubber feet are removed. 

## Removing the power LED

To remove the LED, the inner plastic ring is removed first. Then, the LED is pressed firmly from the outside (towards a flat surface) until it pops out. Finally, the last plastic clip is pried outward.

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

(Mark)

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
[^3]: Pozidrive pan head (6.8 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 9.5 mm
[^4]: Phillips pan head (3.5 mm), Sheet metal screw, Fully threaded, Thread diameter: 2.0 mm, Fastener length: 8.0 mm
