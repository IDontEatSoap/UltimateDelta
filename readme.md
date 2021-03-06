# Ultimate Delta


https://user-images.githubusercontent.com/7333418/119433936-4d3e2200-bd6b-11eb-8358-e7f44a853b8b.mp4

Delta 3D printers are underrated.

This project aims to develop a delta 3D printer that follow strict engineering principles:

1) Quality: The printer must outclass cheap I3 style printers, such as Ender 3's and Prusa's
2) Speed: The printer must print faster than cheap I3 style printers, such as Ender 3's and Prusa's
3) Materials: The printer must print 'durable' materials such as ABS better than cheap I3 style printers, such as Ender 3's and Prusa's


The end goal is to make a Delta printer that is simpler than a Voron 2.4, with equal or superior printing quality and simpler design and cheaper materials.  


Materials, parts and rationale:

This section will define the principles for design. If you'd like to contribute, please follow these guidelines before changing parts. Principles are flexible - if you think we should change these to get better at quality/speed/materials; please add your comments and rationale.

- Structual Profiles: 2020's. Cheap, solid, easy to use, popular. 
- Linear Motion: MGN12's. Cheap, solid, precise, good match to 2020 profiles, easy to source and use.
- Motors: Nema 17's. Cheap, they're everywhere and have enought holding power and torque for our goal.
- Belts: Typical of Deltas. Initial design is based on 6mm. We could move to 9mm Gates once the author can source them.
- Controllers: Klipper + SKR. Simple, cheap, easy to use. This level of Delta quality is only archivable with Klipper.
- PSU: 24v. Meanwell prefered. But other cheap models and 12v may be supported.
- Extruder: Bowden style extruder. The Delta effector must be as light as possible.
- Hot End: V6 Volcano. They have a bad rep at the moment, but with mounts that fix their weakneses they're a great option. As long as they design mounts them firmly and close to the nozzle, they perform. If V6's phase out, we can try new stuff as long as they have price/performance.

