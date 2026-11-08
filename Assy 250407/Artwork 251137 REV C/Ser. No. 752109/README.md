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
          <a href="#cleaning-the-user-and-datasette-port">Cleaning the user and datasette port</a>
        </li>
        <li>
          <a href="#adding-heatsinks">Adding heatsinks</a>
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
          <a href="#removing-the-power-led">Removing the power LED</a>
        </li>
        <li>
          <a href="#cleaning-the-covers">Cleaning the covers</a>
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

All seven Phillips screws[^2] are in place, holding the PCB to the bottom cover (see arrows in picture above). They are removed with a low-torque screwdriver to free the PCB from the bottom cover.

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="800">
</p>

With the PCB out of the way, the inside of the bottom cover is visible. It seems to be in fine condition. 

<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="1000">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)



**Footnotes**
[^1]: Phillips pan head (5.5 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.0 mm
[^2]: Pozidrive pan head (6.8 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 9.0 mm
[^3]: Phillips pan head (5.5 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 10.0 mm
[^4]: Phillips pan head (3.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 2.0 mm, Fastener length: 5.5 mm
