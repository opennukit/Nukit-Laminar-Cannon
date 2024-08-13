**About the Nukit Laminar Cannon**
---
The Laminar Cannon is an experimental device for directing a cohesive stream of highly filtered air at an individual in motion.

![Nukit Open Air Purifier v1.0](https://github.com/opennukit/Nukit-Open-Air-Purifier/blob/main/Nukit-Open-Air-Purifier-3-v1.0.jpg?raw=true)

There have been ongoing efforts to build laminar flow air filters in an attempt to create a pocket of clean air around an individual. Dilution is an accepted method of reducing the pathogen load in a given space, and this can, with some difficulty, be done somewhat locally. “Somewhat” because air is a fluid and wants to mix, so this is an extremely challenging task to accomplish, and the reduction is usually modest at best.

There has been some success in creating a zone of cleaner air, only to find another problem- if the target of that cohesive air stream moves even slightly off-axis, they are no longer breathing filtered air.

What the Laminar Cannon attempts to do is solve a hardware problem with software, using modern, low-cost face-tracking hardware to ensure that the cohesive air stream is always directed at the target individual. 

While this proof of concept uses a small, low-cost, consumer face tracking device and DIY tripod-mounted laminar air purifier designed by Nukit, the output of far more powerful and silent filtration units could be directed through large bore flexible conduits to standard computer-controlled gimbals of the type already used for remote cameras. Multiple units could be mounted on lighting scaffolding and triangulated on high-profile performers to prevent missed performances (with hopefully appropriate mitigations for the audience as well).

The concept extends to 222nm Far-UVC. Depth cameras and off-the-shelf software running on low-cost hardware could easily set up multiple tracking "spotlights" to follow a performer's position on stage and adjust their power output in response to distance, ensuring the performer stays within safe TLV. This would allow for full protection in venues or on stages too large to completely saturate with Far-UVC.

**Further development of this concept will focus on three key tasks:**
---
* Using computational fluid dynamic software to create more efficient laminar nozzle geometries.
* Vetting face-tracking software packages to ensure optimal performance for this specific task.
* Examining the viability of semi-localized Far-UVC as a mitigation method if multiple emitters are triangulated on a subject, either on its own or augmenting ambient Far-UVC covering a larger area and low power.

The responsibility to safely deploy and use Nukit Open Air Purifiers lies entirely with the end user. Machinery Enchantress LLC offers no promises or warranties of any kind and is not liable for any mishaps that occur as a result of using these files.

**FAQ**
---
**Will you be offering a complete, detailed build manual?**

The STL files and BOM are sufficient for a reasonably handy person to construct one for experimentation and iteration. Given its experimental nature, and that the effectiveness of the Laminar Cannon has not been quantified, making it too accessible is not really a feature.


**Does this replace a well-fitted respirator?**

No. Almost nothing does. This device may- with some iteration, offer some level of protection in parts of the world where local regimes are passing draconian laws that prevent masking. Wearing a respirator is always preferred- it is possible.


**Where can I buy this? Will you sell it?**

They aren't for sale, and probably will never be- at least in this form. Quite a bit of testing would need to be done before it can be released for public use. But the basic concepts will may be incorporated into future Nukit products.


**Who made this?**

Nukit has a “Skunk Works” in this context refers to work done on special concept builds intended for limited deployment. These are used to gauge consumer acceptance, practicality, and technical feasibility of novel mitigation measures. The knowledge gained in that process may result in production units or simply additional data points to shape future product development. Whenever possible, we try to Open Source those designs and put them into the public domain. For one thing, to prevent others from patenting them and putting those ideas out of reach of those who need them most.

**License**
---
All Nukit Open Air Purifiers are released under GPL-3. 
https://www.gnu.org/licenses/gpl-3.0.en.html

TLDR;
(For our purposes, “software” refers to the digital files used to make Nukit Open Air Purifiers)

1. Anyone can copy, modify and distribute this software.
2. You have to include the license and copyright notice with each and every distribution.
3. You can use this software privately.
4. You can use this software for commercial purposes.
5. If you dare build your business solely from this code, you risk open-sourcing the whole code base.
6. If you modify it, you have to indicate changes made to the code.
7. Any modifications of this code base MUST be distributed with the same license, GPLv3.
8. This software is provided without warranty.
9. The software author or license can not be held liable for any damages inflicted by the software.

