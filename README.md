# 86BUTTDROP

86BUTTDROP is my attempt at gaining headroom on the "gen2" Subaru BRZ and Toyota GR86 cars by lowering the stock seat.

After multiple iterations, I settled on a design that lowers the seat by about 18 mm, which provides a very
noticable increase in headroom. It might be possible to modify the parts to lower the seat a bit further,
but will require cutting OEM parts, so I've decided to not do it for now.

Here's how the seat looks like with the kit installed:

![Assembled view](images/seat_front.png)

Here's how low the seat goes with this kit. In this GIF, the light from a flashlight positioned
behind the seat is obstructed by the plastic panel on the side of the seat, which normally sits 19+ mm
above the floor. Note that this GIF was recorded with an earlier prototype that had ~20 mm lowering;
I have decided to reduce the amount of lowering by 2 mm to avoid contact between the plastic panel
and the floor that could cause squeaks.

![Lowering demo](images/gap_under_height_adjustment_lever.gif)

## License

I'm publishing what I created under the following license:
```
86BUTTDROP by Timur Iskhodzhanov is marked with CC0 1.0 Universal.
To view a copy of this license, visit https://creativecommons.org/publicdomain/zero/1.0/
```

In particular, I'd like to call out that I make no warranties about the work, and disclaim liability for
all uses of the work, to the fullest extent permitted by applicable law.\
**I'm not a mechanical engineer, I'm practically just a random dude on the internet. While I tried my best,
I can't make any promises about the safety/strength/etc. of this design. No crash testing or finite element
analysis has been performed for this kit. Use at your own risk!**

## Support the project

I've spent over $750 on multiple iterations of prototype parts, and countless hours pulling the seat out,
measuring things, testing fitment, and putting the seat back in back in. I also had to go to a chiropractor
a few times \:)

While I'm sharing the results with you for free, I would really appreciate donations to help me offset
the costs, and motivate me to work on more projects like this in the future.

Here's a convenient button you can use to donate via PayPal:

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?business=ZKULAWZFJKCES&item_name=Donation+to+support+the+86BUTTDROP+project+on+GitHub&currency_code=USD)

## Overview

The kit consists of three metal brackets bolted together, to the factory seat, and to the floor.

The kit replaces the factory seat slider mechanism, so you will need to use different parts depending
on the amount of legroom you need. The seat will retain the height adjustment mechanism, and moves the
seat a bit forward as it raises it, so if you share the car with someone within an inch or two from you,
you might be able to adjust the legroom down a bit for the shorter person.

To figure out which kit you need, set up the seat as you normally drive, then use
a millimeter tape measure or a ruler, and measure how much space there is
between the the front of the stock slider and the front edge of the stock rail
on the door side of the seat. See picture:

![Measuring the desired legroom](images/measuring_legroom.png)

Double-check that you're measuring the right thing, as sometimes the level for
the sliders gets in the way of the L-shaped end of the tape measure. The factory
rail moves in 10 mm steps, so you should get something like 50 mm, 60 mm, 70 mm,
80 mm, 90 mm or 100 mm (max). This measurement is the number I'm going to refer
to as "legroom" throughout the rest of the instructions.

"Legroom", mm | Links | Notes
----------------- | ------------- | -----
30-60 | TBD | Not tested yet, but should be doable
70 | TBD | Verified, not published yet
80 | [Download](https://github.com/timurrrr/86buttdrop/raw/main/kits/86buttdrop_80.zip) | Verified
90 | --- | Will not be offered due to challenging geometry. Use 80 or 100 instead.
100 | TBD | Work in progress

## Ordering the parts from SendCutSend

Download the ZIP file for the desired "legroom" and unzip it.

Go to https://sendcutsend.com/ (SCS) and create an account.

Upload each `.eps` file from the unzipped folder int SCS one by one, performing the following steps:

### Door side and transmission side L brackets
* Confirm "Inches" as measurement units (I don't know why SCS thinks it's inches as I made the design in mm, but whatever).
* Use "Metals > Steel > A36/1008 Mild steel > **3** mm CRS".
* On the "Add services" page, set both bends to 90 degrees.\
  TODO: add images showing how brackets should look.
* On the "Add finishing" page, choose "Gloss black".

### Floor bracket
* Use "Metals > Steel > A36/1008 Mild steel > **3.4** mm CRS".
* On the "Add services" page, make
  * the two bends at the front of the bracket **down** 5 degrees,
  * the bend at the top of the seatbelt tab 35 degrees up,
  * and at the bottom of the seatbelt tab 55 degrees up.\
  TODO: add images showing how the bracket should look.
* On the "Add finishing" page, choose "Gloss black" (send me photos if you decide to add a splash of color!)

### Seatbelt bolt sleeve
* Use "Metals > Steel > 4130 Chromoly > 4.8 mm".
* No services, no finishing.

## Additional hardware

You will need:

* 8x Class 10.9 M10x1.25 _flange_ bolts, 25 mm thread length.
* 5x Class 10.9 M10x1.25 _flange_ nuts.
* 1x Grade 8 7/16”-20 bolt, 3/4" thread length.

I got all of these at a local ACE Hardware store.

## Installation instructions

TODO

## FAQ

TODO
