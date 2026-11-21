<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Commodore 64 Breadbin

![Name](https://img.shields.io/badge/Serial_No.-752109-white?style=plastic)
<br>
![Name](https://img.shields.io/badge/Assy-250407-white?style=plastic)
![Name](https://img.shields.io/badge/Artwork-251137-white?style=plastic)
![Name](https://img.shields.io/badge/Revision-C-white?style=plastic)
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
        <li>
          <a href="#investigating-and-troubleshooting-audio-issues">Investigating and troubleshooting audio issues</a>
        </li>
        <li>
          <a href="#cleaning-the-user-and-datasette-port">Cleaning the user and datasette port</a>
        </li>
        <li>
          <a href="#adding-heatsinks">Adding heatsinks</a>
        </li>
        <li>
          <a href="#replacing-mos-glue-logic">Replacing MOS glue logic</a>
        </li>
      </ul>
    </li>
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
          <a href="#replacing-the-rear-clips">Replacing the rear clips</a>
        </li>     
      </ul>
    </li>
    <li>
      <a href="#testing">Testing</a>
      <ul>
        <li>
          <a href="#basic-functionality-and-chips">Basic functionality and chips</a>
        </li>
        <li>
          <a href="#diagnostics-test-with-harness">Diagnostics test with harness</a>
        </li>
        <li>
          <a href="#testing-the-full-64k-of-ram">Testing the full 64k of RAM</a>
        </li>
        <li>
          <a href="#extended-testing">Extended testing</a>
        </li>
      </ul>
    </li>
    <li>
      <a href="#final-result">Final result</a>
    </li>
  </ul>
</details>

# Starting point

This Commodore 64 breadbin is reportedly having issues with the sound, but otherwise it looks really nice. There is some dust and dirt, especially in the grooves beneath the metal badges, but I can not see any mechanical damage to the covers. Also, there is almost no yellowing on the covers which is quite rare these days.

I notice that this Commodore 64 have been repaired before as there is a sticker from the service shop: retroservice.no which is no longer operational. Also, I notice that different screws have been used to mount the bottom cover. One Phillips screw, and two Pozidrive screws. 

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

# Disassembly

The first step in the disassembly is to remove the two Pozidrive screws, and the single Phillips screw[^1][^2] on the underside. The Phillips screw is the middle screw, and the two Pozidrive screws are to the right and left.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="800">
</p>

<p align="center" float="left">
    <img src="Images/Dis_07.jpeg" alt="Description" width="300">
    <img src="Images/Dis_08.jpeg" alt="Description" width="300">
</p>

The machine is flipped over again, and the top cover is carefully lifted about 30 degrees and wiggled off. Now the interior is exposed, and I can see immediately that this machine has been stored in a good place. There is hardly any sign of moisture on the RF-shield cardboard. Usually, these RF-shields show sign of moist due to been stored in humid environments. 

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="800">
</p>

Also, I notice that three out of the six the rear clips, which are used to mount the backside of the top cover to the bottom cover, are broken. This is very normal. These clips are very brittle and break easily.

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="400">
</p>

The cardboard RF shield is lifted away, and the PCB is exposed in all its glory. Now it is clear to me why this Commodore 64 has been repaired before: there is a modern PLA replacement installed (PLAnkton), and a nice sticker from "retroservice.no" (no longer in service). There are some dust and grease inside, but nothing significant. There are no signs of corrosion, neither on the PCB itself nor on the metal parts (VIC-II shield, cartridge connector, and RF modulator). This is another indication that this Commodore 64 has been stored in a dry, temperature-stable environment.  

<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="800">
</p>

All seven Phillips screws[^3] are in place, holding the PCB to the bottom cover (see arrows in picture above). They are removed with a low-torque screwdriver to free the PCB from the bottom cover. With the PCB out of the way, the inside of the bottom cover is visible. It seems to be in fine condition. 

<p align="center">
    <img src="Images/Dis_06.jpeg" alt="Description" width="800">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Mainboard

The mainboard is Assy 250407 / Artwork 251137 Rev C. This is one of the early revisions of the mainboard, characterized by having the full PLL clock circuitry and the VIC-II positioned vertically. It is not the earliest revision, though, so the A/V connector is a full eight-pin version with LUMA and CHROMA output.

## Visual inspection

The mainboard appears to be in good condition. This board has been repaired repaired before, and the sticker with "retroservice.no" is not the only sign of repair. There are three areas which points to previous repair(s):

- PIN #1 - #8 on the keyboard connector (CN1) have been re-soldered. Unsure why this is done.
- The BASIC ROM in position U3 is replaced. Significant flux residue.
- The PLA in position U17 is replaced. Significant flux residue.

And in addition I notice that there is quite some flux residue, and something that looks like re-work, around PIN #5 - #8 on the RF-modulator. Further on, one of the anchor point is not soldered, and one of the metal tabs are not bent in position.  I don´t actually think this is re-work, but a result of a busy day at the factory in 1984.

None of the capacitors show sign of bulging or leakage.

There are also some more things I notice:

- There is a MOS 7707 chip. These MOS logic chip are notorious for failing and should be replaced.
- Both the USER-PORT and the DATASETTE-PORT are a bit worn
- The thermal paste on the VIC-II is dried out

The table below lists all major custom ICs found on the mainboard. As shown, the MOS chips were produced between week 11 of 1984 and week 20 of 1984, suggesting this Commodore 64 was likely manufactured during the summer of 1984. The same summer that the movie Ghostbuster was released!

<div align="center">
    
| Chip/Area | Manufactor | Version | Date code | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU | MOS | 6510 | W17 Y1984 | No |  |
| SID | MOS | 6581 | W20 Y1984 | Yes | Replaced with: MOS 6581 W33 Y1984 | 
| VIC-II | MOS | 6569R3 | W13 Y1984 | Yes |  |
| PLA | PLAnkton | V1.08 | Unknown | Yes | From a previous repair|
| CIA #1 | MOS | 6526 | W14 Y1984 | No | |
| CIA #2 | MOS | 6526 | W14 Y1984 | No | |
| ROM - BASIC | MOS | 901226-01 | W11 Y1987 | No | From a previous repair |
| ROM - Kernal | MOS | 901227-03 | W17 Y1984 | No | 3rd revision |
| ROM - Character | MOS | 901225-01 | W17 Y1984 | No | |
| RAM | NEC | D4164C-2 | W11 Y1984 | No | No MT RAM |
| Glue logic | MOS, EXAR, Signetics, Texas Instruments, Motorola, National Semiconductor, Fairchild and RCA |  |  |  | MOS glue logic(!) |

</div>

Below are some pictures of the mainboard before refurbishment.

<p align="center">
    <img src="Images/Main_01.jpeg" alt="Description" width="1000">
    <img src="Images/Main_02.jpeg" alt="Description" width="1000">
</p>

Close-up of the VIC-II can area.

<p align="center">
    <img src="Images/Main_03.jpeg" alt="Description" width="600">
</p>

Below are some pictures taken with a microscope of the mainboard before refurbishment.

<p align="center" float="left">
    <img src="Images/Main_04.jpeg" alt="Description" width="300">
    <img src="Images/Main_07.jpeg" alt="Description" width="300">
</p>

<p align="center" float="left">
    <img src="Images/Main_08.jpeg" alt="Description" width="300">
    <img src="Images/Main_06.jpeg" alt="Description" width="300">
</p>

<p align="center" float="left">
    <img src="Images/Main_05.jpeg" alt="Description" width="300">
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
    <img src="Images/InitTest_01.png" alt="Description" width="170">
    <img src="Images/InitTest_02.png" alt="Description" width="170">
    <img src="Images/InitTest_03.png" alt="Description" width="170">
    <img src="Images/InitTest_04.png" alt="Description" width="170">
    <img src="Images/InitTest_05.png" alt="Description" width="170">    
</p>

**NOTE:** The 6581 SID chip works as it should both with the Dead Test cartridge and Diagnostics cartridge. But, this does not mean that the SID fully works. Later investigation will check that.  

## Checking the voltages

Voltages are measured before—and after—refurbishment. This is to ensure that all voltages are within acceptable levels. The table is updated after the refurbishment is completed. All voltages are measured according to the article Checking C64 Voltages [(HOWTO-Checking the Commodore 64 voltages)](https://refurbished-commodore.com/checking-c64-voltages).

The Commodore 64 is powered using a Ray Carlsen PSU.

As seen in the table below, all voltages are within acceptable levels. The 9 V, both AC and DC, is slightly low, but is probably caused by an oxidised power connector.

<div align="center">
  
| Measure point | Target voltage | Measured voltage<br>Before refurbish| Measured voltage<br>After refurbish | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| PSU (5V) | 5 V DC | 5.054 V | 5.049  V | User port |
| PSU (9V) | 9 V AC | 8.363 V | 8.496 V | User port |
| Vvid (+5 CAN)| 5 V DC | 4.928 V | 4.947 V | Pin #40 VIC-II |
| Vc (+5 CAN) | 5 V DC | 4.963 V | 4.962 V | Pin #14 4044 |
| Regulated (12V) | 12 V DC | 12.03 V | 12.03 V| Pin #28 SID |
| Unregulated (9V) | 9 V DC | 8.785 V | 8.945 V | R2 |

</div>

## Investigating and troubleshooting audio issues

This machine is expected to have audio issues. Even if the initial testings pass with flying colours, it does not mean that there still could be problems.

A very good software tool for testing the 6581 SID chip is the [Commodore SID Tester.](https://refurbished-commodore.com/tools) And with this tool something interesting is noticed: there are problems with the PULSE signal on the SIDs voice #3. 

In the video below you can hear the issue. Sometimes the PULSE signal on voice #3 is completely silent, other times it is hardly audible or corrupted.

[Commodore SID Tester - Marginal SID Voice #3](https://youtu.be/UkZKyLgVE6U)

In the video below you can hear how the "Donkey Kong" SID tune sound on this marginal SID. Comparing this SID tune with the proper working version of the Donkey Kong tune it is obvious that this SID chip is marginal.

[Donkey Kong tune - Marginal SID Voice #3](https://youtu.be/lZJbZ3RNU7Y)

All of the three voices are output on PIN #27. That implies that this is in fact a fault with the SID chip itself, and not the surrounding amplification and/or filtering. See schematics below.

<p align="center">
    <img src="Images/Main_10.png" alt="Description" width="600">
</p>

A new MOS 6581 SID chip is sourced and installed (from another Commodore 64 from the same owner). This SID chip is also from 1984, but a little later in that year: week 33.

<p align="center">
    <img src="Images/Main_10.jpeg" alt="Description" width="400">
</p>

With the "new" SID chip in place the SID tester and Donkey Kong tune is played again. This time there are no audible fault. **SUCCESS!**

[Commodore SID Tester - Working SID Voice #3](https://youtu.be/HZm4tRnIPTs)

[Donkey Kong tune - Working SID Voice #3](https://youtu.be/2_kNRrfyz3k)

## Cleaning the user and datasette port

For the datasette, and any peripheral connected to the user port, to work flawlessy, the ports needs to be clean. Cleaning the datasette- and user port is done by rubbing them with an old-school rubber eraser. The rubber eraser will remove the grease and oxidation without damaging the the gold plated contacts. Finally, the ports are cleaned with isopropanol.

<p align="center" float="left">
    <img src="Images/Main_12.jpeg" alt="Description" width="500">
    <img src="Images/Main_11.jpeg" alt="Description" width="500">
</p>

<p align="center" float="left">
    <img src="Images/Main_13.jpeg" alt="Description" width="500">
    <img src="Images/Main_14.jpeg" alt="Description" width="500">
</p>

## Adding heatsinks

Heat can cause ICs to fail faster. A simple but effective measure to reduce the risk of IC failure is to add heatsinks to the warmest ICs. The following ICs are fitted with heatsinks:

- CPU MOS 6510 [U7]
- SID MOS 6581 [U18]

<p align="center">
    <img src="Images/Main_15.jpeg" alt="Description" width="600">
</p>

The VIC-II MOS 6569 is also fitted with a heatsink. However, this is done using the existing metal can, which functions as both an RF shield and a heatsink. New thermal paste is applied to the VIC-II before the metal lid is placed on top of the can. Note that the old, crusty, thermal paste is removed first. And only a small drop of thermal paste is required.

<p align="center">
    <img src="Images/Main_16.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Main_17.jpeg" alt="Description" width="600">
</p>

NOTE: The RF cardboard shield has been removed and will not be reinstalled. This RF shield does not serve much purpose in a modern setting and only contributes to additional heat inside the Commodore 64.

## Replacing MOS glue logic

Although the MOS 7707 chip in position U8 is working fine, the MOS glue logic is notorious for failing. So, it is good practice to replace these with modern equivalents. The MOS 7707 is a hex inverter (6x) which can be replaced with a normal 7406 TTL chip.

The MOS 7707 [U8] is desoldered without any damage to traces or pads. And a socket is installed for easy service later.

<p align="center">
    <img src="Images/Main_18.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Main_19.jpeg" alt="Description" width="800">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)


# Keyboard

To start refurbishing the keyboard, it is first disassembled from the front cover. There are eight Pozidriv screws[^4] attaching the keyboard to the front cover. Note that care must be taken when removing these. The screws have been sitting in place for over 40 years, and the standoffs can easily crack.

<p align="center">
    <img src="Images/Keyb_01.jpeg" alt="Description" width="1000">
</p>

The keyboard is not very dirty, and it seems to be in very good condition. All the keycaps are free of any significant scratches or damage, and the springs beneath the keycaps also appear to be functioning. The SHIFT-LOCK key locks in position as expected. The top of the keycaps are almost not yellowed at all.

<p align="center">
    <img src="Images/Keyb_02.jpeg" alt="Description" width="1000">
</p>

One thing I notice is that there is quite some moist (and dust and grime) under the transparent tape covering the SHIFT-LOCK key. This is something that needs to be taken care of, and the tape will be removed. Such moist can easily lead to corrosion inside the SHIFT-LOCK key.

<p align="center">
    <img src="Images/Keyb_03.jpeg" alt="Description" width="500">
</p>

## Removing and cleaning the keycaps

All 66 keycaps are removed using a keycap puller [(Tools).](https://refurbished-commodore.com/tools) Using a keycap puller reduces the risk of damaging the keycaps or breaking the plungers. When removing the keycaps, make sure to store the spring for the SPACEBAR separately, as this spring is slightly larger than the others.

<p align="center">
    <img src="Images/Keyb_04.jpeg" alt="Description" width="600">
</p>

The keycaps are placed in a container filled with mild soapy water for 24 hours. This helps dissolve any grease and dirt on the keycaps.

<p align="center">
    <img src="Images/Keyb_05.jpeg" alt="Description" width="500">
</p>

## Cleaning the keyboard PCB

To prepare the keyboard PCB (Mitsumi Assy 326166-02 / Ser. No. 21840309) for cleaning, the 23 small Phillips screws[^5] are removed.

<p align="center">
    <img src="Images/Keyb_06.jpeg" alt="Description" width="1000">
</p>

The SHIFT-LOCK needs to be desoldered before it can be removed from the keyboard. Once the two uninsulated wires are desoldered, the SHIFT-LOCK key can be easily removed by pushing it forward from the rear side. Notice that there are sign of corrosion on the solder.

<p align="center" float="left">
    <img src="Images/Keyb_07.jpeg" alt="Description" width="400">
    <img src="Images/Keyb_08.jpeg" alt="Description" width="400">
</p>

The SHIFT-LOCK is cleaned using isopropanol. And now I notice something: there is a small gap on one of the sides of the switch. It does not seem to impact the function though.

<p align="center" float="left">
    <img src="Images/Keyb_10.jpeg" alt="Description" width="400">
    <img src="Images/Keyb_09.jpeg" alt="Description" width="400">
</p>

To investigate what is causing this gap, the SHIFT-LOCK key is disassembled. There are two areas which protrude: a small square plastic area and some PCB material. The small plastic area is cut, which reduce the gap slightly, but the small PCB can´t be reduced. Nevertheless, the SHIFT-LOCK key works as it should.

<p align="center" float="left">
    <img src="Images/Keyb_11.jpeg" alt="Description" width="400">
    <img src="Images/Keyb_12.jpeg" alt="Description" width="400">
</p>

It is very nice to see that this is the KSR-A66YF 56 4021**A** keyboard PCB from Mitsumi. These keyboard PCBs are special, as all 66 contact pads are **GOLD** plated. Later models (such as the **B** variant) have carbon pads. Since the pads are gold-plated, the entire PCB is thoroughly cleaned with isopropanol. It looks as good as new!

<p align="center">
    <img src="Images/Keyb_13.jpeg" alt="Description" width="1000">
</p>

At the same time, the plastic bracket holding the PCB is cleaned with mild soapy water.

<p align="center">
    <img src="Images/Keyb_14.jpeg" alt="Description" width="1000">
</p>

## Reviving the keyboard plungers

A very common issue with the Commodore 64 is that the keys stop working—or, to put it another way, they work only intermittently, requiring you to press REALLY hard to get any response. Fortunately, fixing this issue is straightforward.

All plungers have a piece of conductive rubber at the end of a small plastic rod. This conductive rubber can easily become contaminated with dust and grease, preventing the plunger from working as it should.

By **carefully** rubbing the conductive rubber on a clean sheet of paper, the plungers can be revived.

<p align="center">
    <img src="Images/Keyb_15.jpeg" alt="Description" width="600">
</p>

Finally, the keyboard is reassembled. The tops of the keycaps are a bit yellowed, but the risk of damage when retrobrighting brown keycaps is too high, in my opinion. The keyboard is now in very good condition.

<p align="center">
    <img src="Images/Keyb_16.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Casing

The covers are in very good condition already, but it is need of some cleaning. Both top and bottom cover are cleaned with some mild soapy water. Below is a picture of the covers after cleaning.

<p align="center">
    <img src="Images/Case_01.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/Case_02.jpeg" alt="Description" width="1000">
</p>

## Replacing the rear clips

As with many other Commodore 64 the rear clips are partly broken. These clips are incredible fragile, and will snap by the smallest force. One pair of these clips are intact, but the other two clips are broken. To repair this, two new 3D printed clips are glued to the case.

<p align="center">
    <img src="Images/Case_03.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Testing

<!-- IMAGE SIZE: 590x450 -->

The proof is in the pudding—does it work?

Testing is carried out in three main stages:

1. Testing the basic functionality and chips
2. Testing the complete set of custom ICs and I/O ports
3. Testing the machine by running demos, games, etc., accessed via both floppy and datasette, to verify correct operation

**NOTE:** The image quality is poor, but this is not due to problems with the machine—it is caused by a poor video monitor.

## Basic functionality and chips

The first test is performed using the Dead Test Cartridge. This test does not cover all the functionality of the Commodore 64, but it does verify the basic operation of the major chips, such as the CIA #1/2, CPU, VIC-II, PLA, RAM, and SID. As shown in the picture below, the test is passed.

<p align="center">
    <img src="Images/Test_01.png" alt="Description" width="600">
</p>

The next test is to power up the Commodore 64 to the blue startup screen and check the keyboard to ensure all keys work as they should. The test is passed; all keys work, and 38911 BASIC Bytes Free is displayed.

<p align="center" float="left">
    <img src="Images/Test_02.png" alt="Description" width="400">
    <img src="Images/Test_03.png" alt="Description" width="400">
</p>

The basic functions of the VIC-II, SID, and RAM are tested using the 64 Doctor, Commodore 64 SID Tester, and DesTest cartridges. Note that this should be considered basic functionality—more advanced features such as sprite handling, collision detection, and advanced audio will be tested later.

<p align="center" float="left">
    <img src="Images/Test_04.png" alt="Description" width="220">
    <img src="Images/Test_05.png" alt="Description" width="220">
    <img src="Images/Test_06.png" alt="Description" width="220">
    <img src="Images/Test_07.png" alt="Description" width="220">
</p>

<p align="center" float="left">
    <img src="Images/Test_08.png" alt="Description" width="220">
    <img src="Images/Test_09.png" alt="Description" width="220">
    <img src="Images/Test_10.png" alt="Description" width="220">
    <img src="Images/Test_11.png" alt="Description" width="220">
</p>

## Diagnostics test with harness

To test all the custom ICs and I/O ports, the Diagnostics cartridge is used. The Diagnostics cartridge is very valuable when the complete test harness is installed, as virtually everything is tested thoroughly. As can be seen from the picture below, no issues are identified.

<p align="center">
    <img src="Images/Test_12.png" alt="Description" width="600">
</p>

## Testing the full 64k of RAM

To ensure that all 64k of RAM is functioning correctly, the DesTestFull cartridge is used. This software uses the March-B algorithm to test the RAM extensively. No issues are identified.

<p align="center">
    <img src="Images/Test_13.png" alt="Description" width="600">
</p>

## Extended testing

Knowing that the basic functionality of the machine works, I continue testing by using the Commodore 64 for normal operation: playing games, watching demos, loading from datasette and floppy, and using cartridges. I cannot find any issues with this machine. I also pay special attention to the video to ensure that there are no glitches in the graphics—I cannot see any abnormalities.

Below is a gallery with pictures from the testing. **NOTE:** The colours in the pictures are completely off, and the image quality is poor. However, this is due to my TV and not the machine.

<p align="center" float="left">
    <img src="Images/Test_11.jpeg" alt="Description" width="180">
    <img src="Images/Test_12.jpeg" alt="Description" width="180">
    <img src="Images/Test_13.jpeg" alt="Description" width="180">
    <img src="Images/Test_14.jpeg" alt="Description" width="180">
    <img src="Images/Test_15.jpeg" alt="Description" width="180">
</p>

<p align="center" float="left">
    <img src="Images/Test_16.jpeg" alt="Description" width="180">
    <img src="Images/Test_17.jpeg" alt="Description" width="180">
    <img src="Images/Test_18.jpeg" alt="Description" width="180">
    <img src="Images/Test_19.jpeg" alt="Description" width="180">
    <img src="Images/Test_20.jpeg" alt="Description" width="180">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

**Footnotes**
[^1]: Phillips pan head (5.5 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.0 mm
[^2]: Pozidrive pan head (6.8 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 9.0 mm
[^3]: Phillips pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 6.0 mm
[^4]: Pozidrive pan head (6.6 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 9.5 mm
[^4]: Phillips pan head (3.2 mm), Sheet metal screw, Partially threaded, Thread diameter: 2.0 mm, Fastener length: 6.0 mm





