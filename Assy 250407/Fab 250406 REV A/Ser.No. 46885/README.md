![Name](https://img.shields.io/badge/Serial_No.-46885-white?style=plastic)
<br>
![Name](https://img.shields.io/badge/Assy-250407-white?style=plastic)
![Name](https://img.shields.io/badge/Fab-250406-white?style=plastic)
![Name](https://img.shields.io/badge/Revision-A-white?style=plastic)
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
      <a href="#initial-testing">Initial testing</a>
    </li>
    <li>
      <a href="#mainboard">Mainboard</a>
      <ul>
        <li>
          <a href="#visual-inspection">Visual inspection</a>
        </li>
        <li>
          <a href="#checking-the-voltages">Checking the voltages</a>
        </li>
        <li>
          <a href="#troubleshooting-and-repair">Troubleshooting and repair</a>
        </li>
      </ul>
    </li>    
  </ul>
</details>

# Starting point

This breadbin Commodore 64 has been sleeping in its original cardboard box for many years. But (luckily) it was found and will be taken care of by a fellow retro enthusiast. It is known to be not working, but hey, that´s just a challenge?

From the outside it appears to be complete without any damage. Yes, the "Commodore 64" metal badge is missing, but that should be easy to fix by sourcing a new one. All the keys seems to be fine, from a mechanical point of view. There is quite some dust and grease between, and below, the keycaps but that is to be expected from a machine which has been stored away several years.

Looking at the rear ports I can readily see that there is quite some dust inside (which is perfectly normal). Also, I notice that the datasette port is quite worn - so a fair guess is that this machine was used with a datasette for quite some time. The wear is caused by the datasette being inserted/removed frequently scratching the gold plated datasette port (CN3). 

There are som "burn" marks on the top rear and front side. These marks are most likely caused by either cables from the datasette, joysticks or power supply being wrapped around the machine when stored during its lifetime. You can follow the "burn" marks around the top- and front cover. Nevertheless, these marks are not severe in my opinion. Also, there are some paint residue, and some marks which I would guess is from a ball point pen.

The yellowing is quite severe, and varying in intensity in different areas on the top cover. All three Phillips screws at the bottom cover are present and does not show any signs of corrosion. There are no obvious signs that this machine was ever opened. So, who knows, maybe this is the first time opened for over 40 years?

Also, there is something I notice. There is a small "N" sticker at the bottom cover. This may of course be placed on the machine by the original owner, but could also be that Commodore placed this during manufacturing? This "N" sticker represents the Norwegian organisation "Nemko" which is a notified body for national electrical compliance. 

Below are some pictures of the machine before refurbish (click to enlarge).

<p align="center">
    <img src="Images/Start07.jpeg" alt="Description" width="600">
    <img src="Images/Start05.jpeg" alt="Description" width="600">
    <img src="Images/Start06.jpeg" alt="Description" width="600">
    <img src="Images/Start04.jpeg" alt="Description" width="600">
    <img src="Images/Start03.jpeg" alt="Description" width="600">
    <img src="Images/Start02.jpeg" alt="Description" width="600">
    <img src="Images/Start01.jpeg" alt="Description" width="600">
</p>


# Refurbish activities

The planned refurbishment activites for this Commodore 64 (Order may vary. Several of them in parallell):

- [ ] Refurbish the casing
- [ ] Refurbish the keyboard
- [ ] Refurbish mainboard
- [ ] Testing and validation

The plan can be updated during the refurbishment process. Sometimes I discover areas that needs special attention.
<br>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Initial testing

Before the refurbish commence, the Commodore 64 is connected to a TV set and powered on. This is to get an understanding of health of the machine. It is not meant as a complete test, but as an initial test.

The results are shown in the table below:

<div align="center">
  
| Test area | Test criteria | Result | Comment |
|:----------|:----------|:----------:|:----------|
| Boot up | Default blue screen showing 38911 BASIC Bytes Free | FAILED | Garbled screen <br>Screen varies on each power on |
| DeadTest | Passing all tests | FAILED | Garbled screen |
| Diagostics Cartridge| Passing all tests | FAILED | Garbled screen <br>Screen varies on each power on|
| DesTestMAX | Passing all memory tests | FAILED | Garbled screen <br>Appears to be running|
| DesTestFULL | Passing all memory tests | FAILED | Garbled screen <br>Appears to be running|

</div>

Below are some pictures from the initial testing (click to enlarge).

**Boot up:**

<p align="center" float="left">
    <img src="Images/Init01.jpeg" alt="Description" width="300">
    <img src="Images/Init02.jpeg" alt="Description" width="300">
    <img src="Images/Init02.jpeg" alt="Description" width="300">
</p>

**Dead test:**

<p align="center" float="left">
    <img src="Images/Init05.jpeg" alt="Description" width="500">
</p>

**Diagnostics cartridge:**

<p align="center" float="left">
    <img src="Images/Init04.jpeg" alt="Description" width="500">
</p>

**DesTestMAX:**

A video from the DesTestMAX test: https://youtu.be/WOMNB_J3-R4

**DesTestFULL:**

<p align="center" float="left">
    <img src="Images/Init06.jpeg" alt="Description" width="500">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

Disassembling the Commodore 64 starts with removing the three Phillips screws from the bottom cover[^1].

<p align="center">
    <img src="Images/Dis01.jpeg" alt="Description" width="800">
</p>

The machine is flipped back to upright position, and the top cover is tilted/lifted about 30 degrees while wiggling it off from the bottom cover. It is important to do this carefully to avoid breaking the brittle plastic clips at the rear.

With the top cover lifted away the interior is revealed. As can be seen from the picture below the mainboard is covered with a cardboard RF-shield. The RF-shield seems to be in very good condition. This shield does not have any real function anymore - quite the opposite - it will only accumulate heat. So this shield will be removed during refurbish. But to see that the RF-shield is not damaged by moist is a good sign. This machine has probably been stored in a dry place with quite stable temperature.

<p align="center">
    <img src="Images/Dis02.jpeg" alt="Description" width="800">
</p>

Oh my... this warms my heart! None of the brittle plastic clips are broken! That is something I don´t see often. That said, I will try my best to be very, VERY, careful, but it is likely that some of these clips will break during cleaning since they are so brittle.

<p align="center">
    <img src="Images/Dis03.jpeg" alt="Description" width="800">
</p>

Look at that! The RF-shield is lifted, and the mainboard is revealed in all its glory. And this looks very nice! There are some dust and grease, which is to be expected, but other than that is looks in great condition. The RF-modulator, VIC-II shield and the cartridge port shield show almost no sign of corrosion. There is something I notice though: the ROM ICs (U3, U4, U5) have some kind of coating on the top of chips.

Another thing I see immediately is that all the customs ICs are socketed. This is something which is not common in the Commdore64, unless it is previously repaired which I highly doubt. I will find out later, but I think that the 250407 Rev A board was equipped with sockets when manufactured.

<p align="center">
    <img src="Images/Dis04.jpeg" alt="Description" width="800">
</p>

The seven Phillips screws holding the mainboard PCB to the bottom cover are removed carefully[^2]. It is good practice to use a low torque screwdriver when removing these to reduce the risk of breaking the plastic stand-offs below. Now the mainboard is lifted away exposing the bottom cover. As can be seen from the picture below the bottom cover appears to be in fine condition (ignoring the dust and grease).

<p align="center">
    <img src="Images/Dis05.jpeg" alt="Description" width="800">
</p>


# Mainboard

The mainboard is the Assy 250407/Fab 250406 Rev A. Also marked with "H.E.C. GEA 94HB". This is one of the early revisions of the mainboard which is characterised by having the full PLL clock circuitry and the VIC-II positioned vertically. It is not the earliest revision though, so the A/V connector is full eight pin with LUMA and CHROMA output.

## Visual inspection

The mainboard appears to be in very good condition. I can not see any signs of either damage or repair. There is of course the normal amount of dust laying around on the mainboard, but that is to be expected after so many years. On the backside of the mainboard there is very little flux residue, which is not so common. Commodore mainboards often contain quite some flux residue - likely a sign that Commodore were in a hurry when manufacturing and not had time to clean properly. 

I can not see any obvious signs of rework. I can not see any obvious reason why the mainboard should be faulty. As mentioned earlier there is some kind of paint, or coating, on the ROM ICs. I do not see any reason why someone should need to paint these?

In the table below all the major custom IC found on the mainboard are listed. As can be seen from the table the custom MOS chips were produced during a time interval from week 09 in 1983 to week 17 in 1983. I think it is a fair guess that this Commodore 64 were manufactured sometime during spring 1983 - and that the workers prodcuing this were listening to Michael Jacksons "Billie Jean".

| Chip/Area | Manufactor | Version | Date code | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU | MOS | 6510 | W17 Y1983 | Yes |  |
| SID | MOS | 6581 | W12 Y1983 | Yes |  |
| VIC-II | MOS | 6589R1 | W09 Y1983 | Yes | First revision. Ceramic. Gold plated pins. |
| PLA | SIGNETICS | N82S100N | W07 Y1983 | Yes | Acclaimed to be more reliable than MOS |
| CIA #1 | MOS | 6526 | W09 Y1983 | Yes | |
| CIA #2 | MOS | 6526 | W09 Y1983 | Yes | |
| ROM - BASIC | MOS | 901226-01 | Unknown | Yes | |
| ROM - Kernal | MOS | 901227-02 | Unknown | Yes | 2nd revision - Known to be buggy |
| ROM - Character | MOS | 901225-01 | W13 Y1983 | Yes | |
| RAM | HITATCHI | HM4864P-3 | Unknown | No | |
| Glue logic | No MOS glue logic<br> Fairchild, OKI, Texas Instruments, Hitatchi, Fujitsu, Motorola|  |  |  | |

Below are some pictures of the mainboard before refurbish.

<p align="center">
    <img src="Images/Main01.jpeg" alt="Description" width="1000">
    <img src="Images/Main02.jpeg" alt="Description" width="1000">
    <img src="Images/Main04.jpeg" alt="Description" width="800">
</p>

The red paint/coating can be (partially) removed with some isopropanol. These ICs will be cleaned during the refurbish.

<p align="center">
    <img src="Images/Main03.jpeg" alt="Description" width="600">
</p>

## Checking the voltages

Voltages are measured before - and after - refurbishment. This is to make sure that all voltages are within acceptable levels. This table is updated after refurbishment is completed. All voltages are measured according to the article Checking C64 voltages. 

As seen in the table below all voltages are within acceptable levels, but I think PSU (9V AC) is a bit on the low side. It is normal to see this voltage about 9.5 - 10 V AC. An AC voltage measuring 8.3 V does not directly mean that there is something wrong, but it could be an indicator. It will be interesting to see if this voltage will increase slightly after refurbishment.

<div align="center">
  
| Measure point | Target voltage | Measured voltage<br>Before refurbish| Measured voltage<br>After refurbish | Note |
|:----------:|:----------:|:----------:|:----------|:----------|
| PSU (5V) | 5 V DC | 5.042 V |  | User port |
| PSU (9V) | 9 V AC | 8.350 V |  | User port |
| Vvid (+5 CAN)| 5 V DC | 4.948 V | | Pin #40 VIC-II |
| Vc (+5 CAN) | 5 V DC | F4.943 V | | Pin #14 4044 |
| Regulated (12V) | 12 V DC | 11.88 V | | Pin #28 SID |
| Unregulated (9V) | 9 V DC | 8.852 V | | R2 |

</div>

## Troubleshooting and repair

***What could cause this fault?***

Based on the initial testing it is fair to assume:

- The CPU and RAM are working. Even if the DesTestMAX only show a garbled screen it does seem that the machine is running the RAM test. This should indicate that the CPU is executing code, and that the RAM is tested.

- The VIC-II is working. The border and background colors seems to be correct. This can only happen if the VIC-II is at least partly working. Also, the DeadTestMAX does show the "@" sign all over the screen - something only the VIC-II can achieve.

- Most of the glue logic is working. Since we can see that the DesTestMAX does seem to run, this can only happen if most of the glue logic is functional.

***Removing socketed custom ICs***

Having all the custom MOS ICs in sockets is of great help when troubleshooting. The following ICs can be removed and the DeadTest cartridge can still operate if the rest of the ICs are working:

- CIA #1 (MOS 6526) [U1]
- CIA #2 (MOS 6526) [U2]
- ROM: BASIC (MOS 901226-01) [U3]
- ROM: Kernal (MOS 901227-02) [U4]
- ROM: Character (MOS 901225-01) [U5]
- SID (MOS 6581) [U18]

These ICs are removed before the machine is powered back on again with the DeadTest cartridge installed.

<p align="center">
    <img src="Images/Main05.jpeg" alt="Description" width="500">
</p>

The result is very promising, and strengthen the assumptions made during initial testing. Below is a picture of the screen with the Dead Test cartridige running without the custom ICs listed above.

<p align="center">
    <img src="Images/Main06.jpeg" alt="Description" width="600">
</p>

This result should mean that:

- The CPU, VIC-II, PLA, most glue logic and at least the first 4k of RAM are all OK

There is (obviously) no sound since the SID chip is removed. And the both CIA #1 and CIA #2 are showing corrupt timings since they are also not installed yet.

To confirm that the first 4k of RAM actually are OK the DesTestMAX cartridge is installed. This cartridge will utilise the March B memory check which is way more powerful when it comes to identifying RAM faults. As can be seen from the picture below all of the 4k RAM is tested OK.

<p align="center">
    <img src="Images/Main07.jpeg" alt="Description" width="600">
</p>

***Re-inserting the custom ICs***

The custom ICs previously removed are now re-inserted one-by-one. And there are two faults identified:

- The CIA #2 (MOS 6526) [U2] is causing the machine to show the corrupt screen
- The SID (MOS 6581) [U18] is not causing the machine to crash, but it produce a corrupt noise

**Footnotes**
[^1]: Phillips pan head (5.5mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 10.0 mm
[^2]: Phillips pan head (5.5mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 6.5 mm

