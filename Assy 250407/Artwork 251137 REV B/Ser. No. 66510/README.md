<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Commodore 64 Breadbin

![Name](https://img.shields.io/badge/Serial_No.-66510-white?style=plastic)
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
      <a href="#refurbishment-activities">Refurbishment activities</a>
    </li>
    <li>
      <a href="#disassembly">Disassembly</a>
    </li>
    <li>
      <a href="#mainboard">Mainboard</a>
    </li>
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
      </ul>

      
  </ul>
</details>

# Starting point

Yet another lovely Commodore 64 on the bench for some TLC! Does it work? I have no idea. Does it look beautiful? Yes, all Commodore 64 looks beautiful. But, yes, there are quite some dust, grease and yellowing.

There are some substantial *cable burn marks* on the top and bottom cover. These marks come as a result of soft cables, typically from a datasette, which has been wrapped around the machine during storage. It is not possible to remove these unfortunately, but some proper cleaning and retrobrighting should make it way better I think.

As mentioned I do not know if this machine work from the beginning, but it looks to be in good overall condition. Peeking from the outside, through the rear ports, I can see cobwebs and dust.

The keyboard also seems to be in good condition. Yes, it is very dirty, but beside that I can not see any mechanical damage to it.

Below are some pictures of the breadbin Commodore 64 before refurbishment.

<p align="center">
    <img src="Images/Start_01.jpeg" alt="Description" width="800">
    <img src="Images/Start_02.jpeg" alt="Description" width="800">
    <img src="Images/Start_03.jpeg" alt="Description" width="800">
    <img src="Images/Start_04.jpeg" alt="Description" width="800">
    <img src="Images/Start_05.jpeg" alt="Description" width="800">
    <img src="Images/Start_06.jpeg" alt="Description" width="800">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Refurbishment activities

The planned refurbishment activites for this Commodore 64 (Order may vary. Several of them in parallel):

- [ ] Refurbish mainboard
- [ ] Refurbish the keyboard
- [ ] Refurbish the casing
- [ ] Testing and validation

The plan can be updated during the refurbishment process. Sometimes I discover areas that needs special attention.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

<!-- MARK START -->

# Disassembly

The first step in the disassembly is to remove the three Phillips screws[^1] on the underside. These are considered to be the narrow type of screws for the breadbin model. I notice a faint, but nice, "cracking" sound from two of the screws when removed (using a low-torque screwdriver). This is a good sign—it may indicate that this machine has not been opened before. It is not guaranteed, but that "cracking" sound is often an indication that the screws have been sitting in place for many years.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="800">
</p>

The machine is flipped over again, and the top cover is carefully lifted about 30 degrees and wiggled off. Now the interior is exposed and it appears to be in good condition. There are some dust (and small dead insects) close to the joystick port area. As can be seen from the picture below the cardboard RF-shield is wrinkled. But I do not think this is caused by extensive moisture. I think it is fair to assume that this Commodore 64 has been stored in a dry environment with relatively stable temperatures.

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="800">
</p>

The rear plastic clips are in good condition—none of them are broken or missing. This is not something you see every day, as these are VERY fragile and will easily break. Further on, this is also pointing in the direction that this Commodore 64 has not been opened frequently, or not opened at all since manufactuing. Other models of the Commodore 64 casing have the more thick / rugged versions of these rear clips.

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="800">
</p>

The cardboard RF shield is lifted away, and the PCB is exposed in all its glory. Several of the ICs are in socket, and the PCB appears to be in good general condition. There are some dust and grease inside - and also some proper cobwebs!

There are no signs of corrosion, neither on the PCB itself nor on the metal parts (VIC-II shield, cartridge connector, and RF modulator). This is another indication that this Commodore 64 has been stored in a dry, temperature-stable environment.  

All seven Phillips screws[^2] are in place, holding the PCB to the bottom cover. They are removed with a low-torque screwdriver to free the PCB from the bottom cover.

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="800">
</p>

With the PCB out of the way, the inside of the bottom cover is visible. It seems to be in fine condition. 
<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Mainboard

The mainboard is Assy 250407 / Artwork 251137 Rev B, also marked Fab No. 250406 Rev A "KU-14194 HB". This is one of the early revisions of the mainboard, characterized by having the full PLL clock circuitry and the VIC-II positioned vertically. It is not the earliest revision, though, so the A/V connector is a full eight-pin version with LUMA and CHROMA output.

## Visual inspection

The mainboard appears to be in good condition. I cannot see any signs of rework from previous repairs. There is a significant layer of dust and grease on the PCB. This is to be expected, but I will clean the PCB properly to prevent dust from accumulating moisture - which will evenutally lead to corrosion. A few of the ceramic capacitors have some surrounding residue. I see this from time to time on Commodore 64 machines, and I do not classify these as "leakage". This residue is easily cleaned from the PCB - and does not harm either the capacitor or the traces surronding the ceramic capacitors as far as I know (in stark contrast to electrolytic capacitors).

Something to notice: there is a significant dent in the RF-modulator. At first glance, it is easy to think that this due to some external force, but I don´t think that is the case. My assumption is that this one has been under tension and has given way - almost imploded. The top lid of the RF-modulator is soldered to the inner parts. This create tension to the top lid. This does not affect the function, or performance, of the Commodore 64 in a any way.

Below are some pictures of the mainboard before refurbishment.

<p align="center">
    <img src="Images/Main_01.jpeg" alt="Description" width="1000">
    <img src="Images/Main_02.jpeg" alt="Description" width="1000">
</p>

The table below lists all major custom ICs found on the mainboard. As shown, the MOS chips were produced between week 03 of 1983 and week 23 of 1983, suggesting this Commodore 64 was likely manufactured during the summer of 1983. The same year as Michael Jackson released the magnificent *Billie Jean*.

<div align="center">
    
| Chip/Area | Manufactor | Version | Date code | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU | MOS | 6510 | W17 Y1983 | Yes |  |
| SID | MOS | 6581 | W03 Y1983 | Yes |  | 
| VIC-II | MOS | 6569R1 | W24 Y1983 | Yes |  |
| PLA | COMMODORE | 251064-01 | W22 Y1983 | Yes | |
| CIA #1 | MOS | 6526 | W23 Y1983 | Yes | |
| CIA #2 | MOS | 6526 | W23 Y1983 | Yes | |
| ROM - BASIC | MOS | 901226-01 | Unknown | No | |
| ROM - Kernal | MOS | 901227-02 | Unknown | Yes | 2nd revision |
| ROM - Character | MOS | 901225-01 | Unknown | No | |
| RAM | NEC | D4164C-2 | W18-20 Y1983 | No | No MT RAM |
| Glue logic | Mitsubishi, OKI, Texas Instruments, Fairchild, Fujitsu, Hitachi |  |  |  | No MOS glue logic |

</div>

After cleaning, and drying, the mainboard with mild soapy water I notice that there are several areas which have some liquid material residue. I still do not think that this is caused by electrolytic leaking capacitors as this looks different. Nevertheless, these areas are cleaned properly with isopropanol to make sure no corrosion will happen. Below are some pictures before/after the final cleaning. 

<p align="center">
    <img src="Images/Main_03.jpeg" alt="Description" width="500">
    <img src="Images/Main_04.jpeg" alt="Description" width="500">
</p>

<p align="center">
    <img src="Images/Main_05.jpeg" alt="Description" width="500">
    <img src="Images/Main_06.jpeg" alt="Description" width="500">
</p>

<p align="center">
    <img src="Images/Main_07.jpeg" alt="Description" width="500">
    <img src="Images/Main_08.jpeg" alt="Description" width="500">
</p>

## Initial testing

Some initial tests are performed to check the health of the machine, determining whether the basic functions work as they should and, if not, whether any useful information can be gathered from these diagnostic tools.

When running the Diagnostic Cartridge, the full test harness is used.

<p align="center">
    <img src="Images/Main_09.jpeg" alt="Description" width="1000">
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
    <img src="Images/InitTest_01.jpeg" alt="Description" width="170">
    <img src="Images/InitTest_02.jpeg" alt="Description" width="170">
    <img src="Images/InitTest_03.jpeg" alt="Description" width="170">
    <img src="Images/InitTest_04.jpeg" alt="Description" width="170">
    <img src="Images/InitTest_05.jpeg" alt="Description" width="170">    
</p>

## Checking the voltages

Voltages are measured before—and after—refurbishment. This is to ensure that all voltages are within acceptable levels. The table is updated after the refurbishment is completed. All voltages are measured according to the article Checking C64 Voltages [(HOWTO-Checking the Commodore 64 voltages)](https://refurbished-commodore.com/checking-c64-voltages).

The Commodore 64 is powered using a Ray Carlsen PSU.

As seen in the table below, all voltages are within acceptable levels.

<div align="center">
  
| Measure point | Target voltage | Measured voltage<br>Before refurbish| Measured voltage<br>After refurbish | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| PSU (5V) | 5 V DC | 5.050 V | TBD V | User port |
| PSU (9V) | 9 V AC | 8.641 V | TBD V | User port |
| Vvid (+5 CAN)| 5 V DC | 4.916 V | TBD V | Pin #40 VIC-II |
| Vc (+5 CAN) | 5 V DC | 4.914 V | TBD V | Pin #14 4044 |
| Regulated (12V) | 12 V DC | 12.04 V | TBD V| Pin #28 SID |
| Unregulated (9V) | 9 V DC | 9.277 V | TBD V | R2 |

</div>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

<!-- MARK STOP -->

**Footnotes**
[^1]: Phillips pan head (5.6 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.0 mm
[^2]: Phillips pan head (5.5 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 6.6 mm


