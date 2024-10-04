# moss-robot-arms
moss-robot-arms Beta version 1.0.

A repository for affordable, easy-to-assemble robot arms designed for teleoperation applications. Note: This initial version arm uses the [SO-100 Arm](https://github.com/TheRobotStudio/SO-ARM100) Gripper. Future iterations will have an off the shelf gripper.

## Assembly Instructions

![Follower Arm](./pictures/Render.png)


## Sourcing Parts
Note: The follower and leader arm for this teleoperation setup will have the same off the shelf parts. If you plan on creating the classic teleoperation set up to be used with the `LeRobot` library please buy from the Parts for 2 arms below. Note prices and items may vary slightly depending on geographic location.

/!\ Warning: We only have links for US and EU for now. If you find links for other countries, please create an issue or PR so that we add them to the list.

### Parts For Two Arms (Standard Teleoperation Setup):
<img src="./pictures/Leader_Arm.jpg" alt="Leader Arm" style="width: 45%;"/> <img src="./pictures/Follower_Arm.jpg" alt="Follower Arm" style="width: 45%;"/>
| Part | Amount | Unit Cost (US) | Buy US | Unit Cost (EU) | Buy EU |
|---|---|---|---|---|---|
| STS3215 Servo<sup>[1](#myfootnote1)</sup> | 12 | $14 | [Alibaba](https://www.alibaba.com/product-detail/_1601053797763.html) | 13€ | [Alibaba](https://www.alibaba.com/product-detail/_1601053797763.html) |
| Motor Control Board | 2 | $5 | [Waveshare](https://www.waveshare.com/bus-servo-adapter-a.htm) - [Amazon](https://www.amazon.com/Control-Circuit-Suitable-Supports-Controlling/dp/B0CKT8BN73/ref=asc_df_B0CKT8BN73/) | 4€ | [Waveshare](https://www.waveshare.com/bus-servo-adapter-a.htm)-[Amazon](https://www.amazon.fr/-/en/dp/B0CJ6RYC9J/ref=sr_1_3)|
| Bracket Set | 18 | $3 | [Alibaba](https://www.alibaba.com/product-detail/STS3215-Metal-brackets-for-FEETECH-7_1600836829515.html) | 2€ | [Alibaba](https://www.alibaba.com/product-detail/STS3215-Metal-brackets-for-FEETECH-7_1600836829515.html) |
| USB-C Cable 2 pcs | 1 | $7 | [Amazon](https://www.amazon.com/Charging-etguuds-Charger-Braided-Compatible/dp/B0B8NWLLW2/?th=1) | 7€ | [Amazon](https://[www.amazon.com/Charging-etguuds-Charger-Braided-Compatible/dp/B0B8NWLLW2/?th=1](https://www.amazon.fr/dp/B07BNF842T/)) |
| Power Supply<sup>[2](#myfootnote2)</sup> | 2 | $10 | [Amazon](https://www.amazon.com/Facmogu-Switching-Transformer-Compatible-5-5x2-1mm/dp/B087LY41PV/) | 13€ | [Amazon](https://www.amazon.fr/-/en/dp/B01HRR9GY4/) |
| Table Clamp 2pcs | 2 | $9 | [Amazon](https://www.amazon.com/Mr-Pen-Carpenter-Clamp-6inch/dp/B092L925J4/) | 8€ | [Amazon](https://www.amazon.fr/-/en/dp/B08HZ1QRBF/)|
| Lowstrength Threadlocker<sup>[3](#myfootnote3)</sup> | 1 | $9 | [Amazon](https://www.amazon.com/Loctite-Threadlocker-Automotive-High-Temperature-Non-Corrosive/dp/B0002KKTT0/)| 11€ | [Amazon](https://www.amazon.fr/-/en/dp/B000HBGHFY/) |
| Screwdriver Set (includes Phillips #000, #00, #0, #1) | 1 | $6 | [Amazon](https://www.amazon.com/Precision-Phillips-Screwdriver-Electronics-Computer/dp/B0DB227RTH) | 10€ | [Amazon](https://www.amazon.fr/dp/B08ZXVMVYD/) |
| Wrench<sup>[4](#myfootnote5)</sup> | 1 | $5 | [Amazon](https://www.amazon.com/uxcell-Metric-Double-Wrench-5-5mm/dp/B07D4B8GWW/) | 4€ | [Amazon](https://www.amazon.fr/-/en/dp/B075DML8KB/) |
| M3 Washers<sup>[5](#myfootnote5)</sup> | 1 | $2 | [Amazon](https://www.amazon.com/Hillman-Group-7606-Washers-10-Pack/dp/B00G5IZWQS/) | 4€ | [Amazon](https://www.amazon.fr/-/en/dp/B0CVNBW6RL/) |
| Total |---| $299 |---| 278€ |---|

### Parts for One Arm:
| Part | Amount | Unit Cost (US) | Buy US | Unit Cost (EU) | Buy EU |
|---|---|---|---|---|---|
| STS3215 Servo<sup>[1](#myfootnote1)</sup> | 6 | $14 | [Alibaba](https://www.alibaba.com/product-detail/_1601053797763.html) | 13€ | [Alibaba](https://www.alibaba.com/product-detail/_1601053797763.html) |
| Motor Control Board | 1 | $5 | [Waveshare](https://www.waveshare.com/bus-servo-adapter-a.htm) - [Amazon](https://www.amazon.com/Control-Circuit-Suitable-Supports-Controlling/dp/B0CKT8BN73/ref=asc_df_B0CKT8BN73/) | 4€ | [Waveshare](https://www.waveshare.com/bus-servo-adapter-a.htm)-[Amazon](https://www.amazon.fr/-/en/dp/B0CJ6RYC9J/ref=sr_1_3)|
| Bracket Set | 9 | $3 | [Alibaba](https://www.alibaba.com/product-detail/STS3215-Metal-brackets-for-FEETECH-7_1600836829515.html) | 2€ | [Alibaba](https://www.alibaba.com/product-detail/STS3215-Metal-brackets-for-FEETECH-7_1600836829515.html) |
| USB-C Cable 2 pcs | 1 | $7 | [Amazon](https://www.amazon.com/Charging-etguuds-Charger-Braided-Compatible/dp/B0B8NWLLW2/?th=1) | 7€ | [Amazon](https://[www.amazon.com/Charging-etguuds-Charger-Braided-Compatible/dp/B0B8NWLLW2/?th=1](https://www.amazon.fr/dp/B07BNF842T/)) |
| Power Supply<sup>[2](#myfootnote2)</sup> | 1 | $10 | [Amazon](https://www.amazon.com/Facmogu-Switching-Transformer-Compatible-5-5x2-1mm/dp/B087LY41PV/) | 13€ | [Amazon](https://www.amazon.fr/-/en/dp/B01HRR9GY4/) |
| Table Clamp 2pcs | 1 | $9 | [Amazon](https://www.amazon.com/Mr-Pen-Carpenter-Clamp-6inch/dp/B092L925J4/) | 8€ | [Amazon](https://www.amazon.fr/-/en/dp/B08HZ1QRBF/)|
| Lowstrength Threadlocker<sup>[3](#myfootnote3)</sup> | 1 | $9 | [Amazon](https://www.amazon.com/Loctite-Threadlocker-Automotive-High-Temperature-Non-Corrosive/dp/B0002KKTT0/)| 11€ | [Amazon](https://www.amazon.fr/-/en/dp/B000HBGHFY/) |
| Screwdriver Set (includes Phillips #000, #00, #0, #1) | 1 | $6 | [Amazon](https://www.amazon.com/Precision-Phillips-Screwdriver-Electronics-Computer/dp/B0DB227RTH) | 10€ | [Amazon](https://www.amazon.fr/dp/B08ZXVMVYD/) |
| Wrench<sup>[4](#myfootnote4)</sup> | 1 | $5 | [Amazon](https://www.amazon.com/uxcell-Metric-Double-Wrench-5-5mm/dp/B07D4B8GWW/) | 4€ | [Amazon](https://www.amazon.fr/-/en/dp/B075DML8KB/) |
| M3 Washers<sup>[5](#myfootnote5)</sup> | 1 | $2 | [Amazon](https://www.amazon.com/Hillman-Group-7606-Washers-10-Pack/dp/B00G5IZWQS/) | 4€ | [Amazon](https://www.amazon.fr/-/en/dp/B0CVNBW6RL/) |
| Total |---| $165 |---| 157€ |---|

## Printing the Parts
A variety of 3D printers are acceptable to print the parts necessary of the follower and leader arm. Follow the steps below to ensure a good print.

1. Choose a printer: The STL files provided ready to print on many FDM printers. Below are the tested and suggested settings though others may work.
   1. Material: PLA
   2. Nozzle Diameter and Precision: 0.4mm nozzle diameter at 0.2mm layer height or 0.6mm nozzle at 0.4mm layer height.
   3. Infill Density: 13%
   4. Sample Printers: [Prusa Mini+](https://www.prusa3d.com/product/original-prusa-mini-semi-assembled-3d-printer-4/), [UP Plus 2](https://shop.tiertime.com/product/tiertime-up-plus-2-3d-printer/), [Ender3](https://www.amazon.com/Comgrow-Creality-Ender-Aluminum-220x220x250mm/dp/B07BR3F9N6/).
2. Set up the printer
   1. Setup and Takedown
      1. Ensure that the printer is calibrated and the bed level is correctly set using the printer specific instructions.
      2. Clean the print bed, making sure it is free from dust, or grease. If cleaning the bed using water, or other liquid, dry the bed.
      3. If your printer recommends it, use a standard glue stick and apply a thin, even layer of glue across the print area of the bed. Avoid clumping or uneven application.
      4. Load the printer filament using printer specific instructions.
      5. Ensure the printer settings match the ones suggested above (most printers have multiple settings so choose the ones that most closely match).
      6. Set for supports everywhere but ignore slopes greater than 45 degrees to the horizontal.
      7. There should be no supports in the screw holes with horizontal axes.
3. Print the two files found in `so_100_gripper_parts`, which are listed below.
   1. `Print_Follower_SO_ARM100_08k_Gripper.STL`
   2. `Print_Leader_SO_ARM100_08k_Gripper.STL`
4. Take Down
   1. After the print is done, use the putty knife to scrape the the parts off the print bed.
   2. Remove any support material from parts.
   3. Reapply the glue stick before starting the next print.

## Assembling the Parts
Construct the leader and follower arms using the Assembly Video linked below. After you assemble the two arms from the video, power the leader and follower arm using the 5V power supplies. In addition, plug each arm into your computer using a USB-C cable.

TODO(jess-moss): Add assembly video.

## Configure
While this robot can be programmed in a variety of manners, it is suggested to use with [LeRobot](https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md).


Join the project for support and development on the [discord server](https://discord.gg/ggrqhPTsMe).

## Footnotes
<a name="myfootnote1">1</a>: The STS3215 arm comes in two sizes. The 7.4V has a stall torque of 16.5kg.cm at 6V (and likely slightly less for a 5V power supply). The 12V version has a stall torque of 30kg.cm. While we found the 7.4V to be sufficient, if you would like more powerful motors you can buy the 12V version [here](https://www.alibaba.com/product-detail/12V-30KG-STS3215-High-Torque-Intelligent_1601251263977.html). Note if you do this, you will also have to buy a 12V 5A+ power supply instead of a 5V one above, but all other components will remain the same.\
<a name="myfootnote2">2</a>: IMPORTANT: If you buy the 12V STS3215 motors, you should buy the [12V 5A+ power supply](https://www.amazon.com/Converter-100-220V-Transformer-5-5x2-1mm-Accessories/dp/B08C594VNP/) instead of the 5V power supply provided. \
<a name="myfootnote3">3</a>: While Loctite is not strictly necessary, it does help to ensure screws do not loosen overtime, and is recommended whenever you have a the M3 screw fastening into the M3 nut. You only need a small dot of it. \
<a name="myfootnote4">4</a>: You can either use a 5.5mm or 7/32" wrench, as they are both compatible with the M3 nuts. In a pinch you can also use needle-nose or other pliers but a wrench does help with assembly. \
<a name="myfootnote5">5</a>: The screws provided with the Bracket Set are actually slightly too long for the motor horn on the idler side. You can buy M3 washer (they do not need to be these exact ones) to ensure a tight fit. \