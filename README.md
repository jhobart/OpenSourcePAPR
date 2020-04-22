# OpenSourcePAPR
An open-source, powered, air purifying respirator.

## Overview
The device is intended to be connected to a wide variety of off-the-shelf reusable or disposable PAPR hoods from existing systems. Filtered air is fed into the hood through a 3D printed, belt-mounted assembly. 

![PAPR](Assy.JPG)

The assembly is composed of:

* An off-the-shelf P100 filter made from readily-sourced HEPA filters (see Parts List, below)
* An airtight fan intake manifold assembly
* An off-the-shelf 12V centrifugal fan rated for a minimum of 15 cfm at 12V
* A battery receiver that accepts the ubiquitous Milwaukee M18 18V Li-Ion battery
* A high-quality voltage 12V regulator from Polou
* A protective fuse

The goal is to provide a minimum 10 CFM of filtered air supply at all times to provide positive pressure in the hood. A requirement is that the battery needs to last 8 hours. We have validated the design using established NIOSH procedures for field testing respirators as well as quantitative particulate and air velocity testing.

## Parts List
* Fan: https://www.sparkfun.com/products/11270
* 12V regulator: https://www.pololu.com/product/3786
* Fuse: https://digikey.com/product-detail/en/schurter-inc/8020.0518.PT/486-3818-ND/2644301
* Spade terminal for battery connection: https://www.digikey.com/product-detail/en/te-connectivity-amp-connectors/66024-2/A139237-ND/297840
* Switch: https://smile.amazon.com/dp/B07931ZKC1 (These are available from a variety of sellers on Banggood, etc.)
* M2 x 3mm screws: https://smile.amazon.com/gp/product/B00W96Z5RQ (to hold regulator to base)
* CPAP Hose: https://smile.amazon.com/gp/product/B01MU5XLUC/ (many similar available from different vendors)

## Hoods
* 3M Versaflow: https://industrialsafety.com/3m-s-133s-5-versaflo-headcover-w-integrated-head-suspension.html (Small/Med)
  https://industrialsafety.com/3m-s-133l-5-headcover-with-integrated-head-suspension.html (Large)
* Allegro: https://www.allegrosafety.com/product/maintenance-free-tyvek-hood/ (These are better suited for people wearing "bunny suits" where the bib vents airflow into the suit.)

## Wiring
![Circuit Diagram](circuit.png)

## TODO: 
* Assembly instructions
* Testing/QA process

## Disclaimer

This is important, not just for the protection of the volunteers on the project but for *you*.  

You acknowledge and understand that these improvised PAPR kits are not certified by any lab, government agency, industry association or other certifying body including but not limited to NIOSH, CDC, FDA, nor by any other organization for any use. You understand that the improvised PAPR kit has not been demonstrated to provide any protective value or liquid barrier protection whatsoever, and is solely intended for general, non-medical purposes. You understand that the improvised PAPR kit design is being provided as-is, without warranty of any kind nor representation of fitness for any purpose. 

If it is your intention to use this as improvised Personal Protective Equipment (PPE) in a regulated, medical setting under the revised guidance from The Joint Commission and the CDC, you specifically understand that this improvised PAPR kit may not work in the manner in which you expect it to, and it may not work at all. You understand that you assume any and all risk arising from the use of the improvised PAPR kit as a last resort after exhausting all other duly-certified Personal Protective Equipment supplies and other options, and you  waive any and all claims against the volunteers who provided it.  

If you do not agree with any of the statements above, do not build, use, give, distribute or share the improvised PAPR kit.
