# erLay
erLay is a ultra-portable CoreXY 3D printer made by [Evan Yu](https://evanyu.dev) and [Aaron Huang](https://runthebot.me)

This printer is built to print small parts needed fast at robotics competitions where our main limitations are space and time. This printer will mainly print spacers, shaft collars, pullies, etc.

## Goals
- Ultra-portable (for robotics competitions!!)
- CoreXY
- Pico MMU (Optional)
- Zero Click ABL
- Built-in carrying case (The printer will collapse into something like a pelican case)

## Total Time

Aaron: 6h
Evan: 2h

## Log

### Feb 12 2025

- Came up with name, specs, and design.
- Research on different 3d printer designs & parts (VORONDesign, etc...)
- Started options for BOM

Evan: 2h
Aaron: 4h

#### Both
**What was done:**
- Discussed name, specs and design
- Rabbit holing and yapping about option
- Both already have 3D printers
**Some of our other ideas:**
- 2/3 stage elevator on a bed slinger 💀
- smaller Voron v0


#### Aaron
- I'm the one that dragged other bozo onto this
- I am in the process of building a [Hex Zero](https://github.com/Alexander-T-Moss/Hex-Zero)
- Went down a printer rabbit hole

**ABL:**
- [ZeroClick](https://github.com/zruncho3d/ZeroClick)
- Seams nice and cheap
- Used on Hex Zero
- ABL needs more research

**Hotend/Toolhead:**

Requirements:
- COTS
  - We do not want to be designing a Toolhead
  - We can use a custom one if it relly came to it
- Direct drive
  - Keep it compact
  - Print filaments that are harder to print (Remember robotics!)

Options:
- [Apogee Extruder](https://www.filastruder.com/products/ldo-apogee-toolhead-for-ender-3)
  - Light 170g
  - Cheap
- [Creality Sprite](https://www.creality.com/products/sprite-extruder-pro-kit)
  - Kinda heavy 266g
  - Dual-Gear Drive for flexibles
  - Cheap
- [BIQU H2](https://biqu.equipment/products/biqu-h2-v2s-extruder-for-b1-bx-ender-3-3-v2-5-6-cr6-10?variant=40218342555746)
  - Dual-Gear Drive for flexibles
  - Weight ok 195g
  - Cheap ish
  - Big
- [**Orbiter**](https://www.3dlabtech.ca/product/ldo-smart-orbiter-extruder-kit-v3/)
  - Probably this?
  - Cheapish
  - Canadian website???
  - We are Canadian so no tarifs!!?!??!?
  - Light 175g
  - Dual-Gear Drive for flexibles
  - With a CHT nozzle??!!!?!?
  - WHAT??? for 87 USD?????? (The Canadian dollar is not doing so well)


Ok that's it for today I have school tmr

### Feb 13 2025

Aaron: 2h
Evan: 0h

**Aaron:**
Yay snow day!!! 
Ok so I was losing my mind at midnight yesterday and did not realize that the Apogee uses an orbiter
I probably need to find a better source

**Frame**
I was brainstorming frames today and I wanted the hingeing lid of the case to be the Z-axis
I started with some CAD (Bad idea) and I got almost nowhere

Anyway I do here are the current frame option( After spending 30 mins failing at CAD:
- Hingeing lid with the bed in the middle
- Linear Rods as the Z-axis support (Similar to Neutrino)

I also started a basic Onshape Part Lib and did a lot more research

I've learnt my lesson and now will spend the next hour **drawing concepts** before CADing


