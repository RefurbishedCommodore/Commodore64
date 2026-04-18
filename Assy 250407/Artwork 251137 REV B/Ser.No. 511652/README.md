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

There are some things to notice from the visual inspection which will be taken care of:

> **Noticeable areas:**
>
> * Emerging corrosion - On the backside of the PCB there seems to be some emerging corrosion between U14 and U16
> 
> * Flux residue - On the backside of the PCB there are some old flux residue from a hand soldering of R27
> 
> * Ceramic capacitor and thermal paste - The ceramic capacitor C54 is leaning towards the VIC-II chip. Also the thermal paste on the VIC-II is dried out and is spilled over the pins



[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

**Footnotes**
[^1]: Phillips pan head (6.8mm), Sheet metal screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 10.0 mm
[^2]: Phillips pan head (5.5mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 6.0 mm
