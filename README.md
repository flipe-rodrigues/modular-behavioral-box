# Modular behavioral box
Drawings for cutting all the necessary pieces for assembling a modular behavioral box for rats and mice using 5-mm-thick acrylic.

> missing a proper intro/motivation (mention wall modularity);

<!--
## Project structure
- **drawings/**: Contains vector graphics files for all components of the box (i.e., walls & modules).
- **media/**: Contains photos, videos & sketches illustrating some of the mechanisms and assembly steps.
- **print/**: Contains all laser-cutter-ready .pdf files.
-->

## Parts list

- General across all walls & modules:
  - 5-mm-thick acrylic;
  - 20-mm M3 spacers;
  - 10-mm M3 screws;
  - M3 nuts;
  - acrylic glue + brush;

- Specific to poke & light modules:
  - NeoPixel 16-LED RGB rings;

> [!CAUTION]
> Be sure to always wear a mask and gloves whenever handling acrylic glue, and to do it in a well-ventilated place.

## Assembly

<!--### I. One box, one wall at a time-->

**1.** Print/cut the three files under [print/wall](print/wall/), each in a 450x450 mm sheet of 5-mm-thick acrylic of your chosen color for the _inner_, _middle_ and _outer_ layers of the wall (_white_, _black_ and _crystal_ in all examples below);

> missing media

**2.** Screw the outer pieces of the three layers together to create a jig for gluing _walls_.
> [!TIP]
> Glue the three layers of the jig itself after aligning them with the screws.

> missing media

**3.** Glue the three main layers of the wall together using acrylic glue;

<img src="https://github.com/user-attachments/assets/703faaff-8ef2-4cdd-a877-18dca83c7b4f" width="400">

**4.** Repeat steps 1-2 for a total of 6 walls;

> missing media

**5.** Place M3 nuts in all nut sockets of all walls;

> missing media

**6.** Screw walls together with 10-mm M3 screws at all wall joints;

<img src = "https://github.com/user-attachments/assets/37f7c9cb-f71d-437d-adc9-434d30e29ade" width="400">

**7.** Using a wall as a jig, glue the three layers of all your modules (cutouts from step 1) together using acrylic glue;

> missing a step by step guide on assembling a poke module;

<img src = "https://github.com/user-attachments/assets/a88496cf-0ec7-4dcf-afcb-167fad5ca199" width="400">

**8.** Print/cut the two files under [print/locks](print/locks/);

> missing media

**9.** Assemble each module's four locks by putting together two _handle_ pieces (from the previous step) and a 20-mm M3 spacer;

> missing media

**10.** Place all lock _feet_ inside their corresponding slots in all walls, and then insert all lock _handles_;

![locks](https://github.com/user-attachments/assets/bb2df25e-8a3e-4305-8b54-04f5ab7d51aa)

**11.** Populate the box with modules (i.e., place & lock them);

<img src = "https://github.com/user-attachments/assets/772f6224-1d22-4d6e-9ab9-e0341415e778" width="400">

**12.** Plug in your preferred system for interfacing with sensors and actuators. Below I'm showcasing a hybrid approach using a custom PCB (thanks to the Hardware Platform at Champalimaud Research) and an Arduino Mega;

<img src = "https://github.com/user-attachments/assets/901709b5-a7c0-4837-b496-896086428e98" width="400">

**13.** Put a rat inside:)

<img src = "https://github.com/user-attachments/assets/8f1606f9-b176-494c-8f52-d81dfaa19538" width="400">

**14. (optional)** Build a support rig using custom-cut aluminum profiles.

<img src = "https://github.com/user-attachments/assets/ac34d82c-6810-4175-870f-e7a0f0f9fd26" width="400">
