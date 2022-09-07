# snappergps-housings

This repository contains different housing designs intended to provide some protection for [a SnapperGPS PCB](https://github.com/SnapperGPS/snappergps-pcb/), a battery, and an antenna during testing.

All designs are designed to be 3D-printed.
If you want to use any of these designs for a long-term deployment, we advise you to carefully consider whether the material is suitable for the deployment environment.
It might be possible to make the housings more suitable by applying a finish to the outer surface.
Other housing options for packaging a SnapperGPS PCB for a deployment, which are not part of this repository, include:
* Heat shrink tubing (light-weight and waterproof),
* Vacuum packing (light-weight and waterproof),

### Table of contents

  * [Tray](#tray)
  * [Thin box](#thin-box)
  * [Thick box](#thick-box)
  * [Box with cut-outs](#box-with-cut-outs)
  * [Turtle case](#turtle-case)
  * [Waterproof case without threads](#waterproof-case-without-machined-threads)

## Tray

![Tray](images/snappergps-tray.png)

The tray holds a SnapperGPS PCB, a flat battery, and an *APAM1368YB13V3.0* active GNSS antenna in place.

## Thin box

![Thin box](images/snappergps-thin-box.png)

The box holds a SnapperGPS PCB, a battery, and an active GNSS antenna, e.g., an *Echo 27* or an *APAM1368YB13V3.0*, in place and can be closed with a lid.

## Thick box

![Thick box](images/snappergps-thick-box.png)

The same as the [thin box](thin-box), but with twice the wall thickness.

## Box with cut-outs

![Box with cut-outs](images/snappergps-box-with-cut-outs.png)

The same as the [thin box](thin-box), but with two cut-outs to attach a USB cable and to monitor the status LED without opening the box.

## Turtle case

![Turtle case](images/turtle_case_engineering_drawing.png)

This is a design for a waterproof enclosure (if machined out of waterproof materials). It requires 14 countersunk 10 mm M4 screws, such as [these from RS-Online](https://uk.rs-online.com/web/p/socket-screws/2328388). You will also need a 59 mm (inner diameter) x 2mm (cross-section) o-ring such as [this one from Polymax](https://www.polymax.co.uk/o-ring-59mm-id-x-2mm-cs-epdm-70-sha).

You can design your own inserts based on the antenna and battery you are using. Alternatively, you can make a cut-out from a thick piece of packaging foam. Cut it slightly oversized so the components sit snugly when the enclosure is closed. Make sure that the tag cannot jiggle around in the tag.

If you machine any piece of the housing out of metal, ensure that none of the electrical components can come in touch with it to avoid shorts.

A version machined out of polyoxymethylene (for the top) and aluminium (for the baseplate) has been successfully deployed on nesting loggerhead sea turtles.

You can find more information on deploying SnapperGPS on (sea) turtles in [this dicussion](https://github.com/orgs/SnapperGPS/discussions/4).

![Turtle tag on turtle](images/tag_on_turtle.jpg)


## Waterproof case without machined threads

![Waterproof case without machined threads](snappergps-waterproof-case-no-threads-2022/images/assembly.jpg)

This design is a smaller and simpler version of the turtle tag. Instead of using machined threads, this design uses nuts to seal the case.

For this version, I had some 15 mm M3 Phillips Pan Head screws and nuts left over [from this set](https://www.amazon.co.uk/gp/product/B08789D7M5). But if you have access to Fusion, you can also edit the .f3d file to fit other types of screws. I recommend getting nuts with nyloc inserts. They won't come undone as easily.

You will also need an o-ring with 2 mm cross-section and 48 mm internal diameter. I used [this one from Polymax](https://www.polymax.co.uk/o-ring-sizes-48mm-id-x-2mm-cs-nitrile-70-sha-fda).


As before, I recommend cutting an oversized piece of packaging foam to hold the components in place. Make sure that the electronic components cannot jiggle around or short out by touching each other. I used insulation tape and double-sided tape to glue all the parts together. This makes the components easy to handle and prevents accidental shorts as well as unnecessary stress on the antenna and battery connector.

<img src = "snappergps-waterproof-case-no-threads-2022/images/case.jpg" width ="500" /> <img src = "snappergps-waterproof-case-no-threads-2022/images/back.jpg" width ="500" />

This repo contains a version with loop holes (pictured) and one without. The photos show a model 3D-printed out of PLA. As such it won't dive-proof but it's still a very sturdy, weather-proof case that you can cable tie to your backpack/bike/boat/flying car.

For a waterproof case, we recommend CNC machining the top out of polyoxymethylene (POM) and the plate out of aluminium (beware of shorting out the electronics).

