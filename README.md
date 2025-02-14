> [!IMPORTANT]
> For use with [LeRobot](https://github.com/huggingface/lerobot)  we now recommend building or purchasing the [SO100](https://github.com/TheRobotStudio/SO-ARM100) arm instead. While the Moss v1 robot is still supported, it will be deprecated. Additionally, 3D-printed parts for the SO100 are now available for purchase if you don't have a printer. If you already have a Moss v1, you could disassemble it and create a SO100 using the same motors. 
>
> For instructions on building and setting up the SO100, follow this [tutorial](https://github.com/huggingface/lerobot/blob/main/examples/10_use_so100.md).

# moss-robot-arms
moss-robot-arms Beta version 1.0.

A repository for affordable, easy-to-assemble robot arms designed for teleoperation applications. 

## Assembly Instructions

![Follower Arm](./pictures/Render.png)


## Sourcing Parts
Note: The follower and leader arm for this teleoperation setup will have the same off the shelf parts. If you plan on creating the classic teleoperation set up to be used with the `LeRobot` library please buy from the Parts for 2 arms below. Note prices and items may vary slightly depending on geographic location.

/!\ Warning: We only have links for US, EU and CN for now. If you find links for other countries, please create an issue or PR so that we add them to the list.

### Parts For Two Arms (Standard Teleoperation Setup):
<img src="./pictures/Leader_Arm.jpg" alt="Leader Arm" style="width: 45%;"/> <img src="./pictures/Follower_Arm.jpg" alt="Follower Arm" style="width: 45%;"/>

| Part | Amount | Unit Cost (US) | Buy US | Unit Cost (EU) | Buy EU | Unit Cost (RMB) | Buy CN |
|---|---|---|---|---|---|---|---|
| STS3215 Servo<sup>[1](#myfootnote1)</sup> | 12 | $14 | [Alibaba](https://www.alibaba.com/product-detail/Top-Seller-Low-Cost-Feetech-STS3215_1600999461525.html) | 13€ | [Alibaba](https://www.alibaba.com/product-detail/Top-Seller-Low-Cost-Feetech-STS3215_1600999461525.html) | ￥97.72 | [TaoBao](https://item.taobao.com/item.htm?id=712179366565&skuId=5268252241438) |
| Motor Control Board | 2 | $5 | [Waveshare](https://www.waveshare.com/bus-servo-adapter-a.htm) - [Amazon](https://www.amazon.com/Control-Circuit-Suitable-Supports-Controlling/dp/B0CKT8BN73/ref=asc_df_B0CKT8BN73/) | 4€ | [Waveshare](https://www.waveshare.com/bus-servo-adapter-a.htm)-[Amazon](https://www.amazon.fr/-/en/dp/B0CJ6RYC9J/ref=sr_1_3)| ￥27 | [TaoBao](https://detail.tmall.com/item.htm?id=738817173460&skuId=5096283384143) |
| Bracket Set | 20 | $3 | [Alibaba](https://www.alibaba.com/product-detail/STS3215-Metal-brackets-for-FEETECH-7_1600836829515.html?spm=a2747.product_manager.0.0.180171d2hjgWrJ) | 2€ | [Alibaba](https://www.alibaba.com/product-detail/STS3215-Metal-brackets-for-FEETECH-7_1600836829515.html?spm=a2747.product_manager.0.0.180171d2hjgWrJ) | --- | --- |
| U Bracket | 20 | --- | --- | --- | --- | ￥6 | [TaoBao](https://item.taobao.com/item.htm?id=615340872015&skuId=4472922777845) |
| Bottom Bracket | 6 | --- | --- | --- | --- | ￥6 | [TaoBao](https://item.taobao.com/item.htm?id=615340872015&skuId=4472922777847) |
| Side Bracket | 6 | --- | --- | --- | --- | ￥6 | [TaoBao](https://item.taobao.com/item.htm?id=615340872015&skuId=4472922777846) |
| USB-C Cable 2 pcs | 1 | $7 | [Amazon](https://www.amazon.com/Charging-etguuds-Charger-Braided-Compatible/dp/B0B8NWLLW2/?th=1) | 7€ | [Amazon](https://www.amazon.fr/dp/B07BNF842T) | ￥23.9*2 | [TaoBao](https://detail.tmall.com/item.htm?id=44425281296&skuId=5611379016222) |
| Power Supply<sup>[2](#myfootnote2)</sup> | 2 | $10 | [Amazon](https://www.amazon.com/Facmogu-Switching-Transformer-Compatible-5-5x2-1mm/dp/B087LY41PV/) | 13€ | [Amazon](https://www.amazon.fr/-/en/dp/B01HRR9GY4/) | ￥22.31 | [TaoBao](https://item.taobao.com/item.htm?id=544824248494&skuId=4974994129990) |
| Table Clamp 4pcs | 1 | $9 | [Amazon](https://www.amazon.com/dp/B0CY899V9V) | 8€ | [Amazon](https://www.amazon.fr/-/en/dp/B08HZ1QRBF/)| ￥7.8 | [TaoBao](https://detail.tmall.com/item.htm?id=738636473238&skuId=5505939904942) |
| Lowstrength Threadlocker<sup>[3](#myfootnote3)</sup> | 1 | $9 | [Amazon](https://www.amazon.com/Loctite-Threadlocker-Automotive-High-Temperature-Non-Corrosive/dp/B0002KKTT0/)| 11€ | [Amazon](https://www.amazon.fr/-/en/dp/B000HBGHFY/) | ￥81 | [TaoBao](https://detail.tmall.com/item.htm?id=652665229827&skuId=5125512809535) |
| Screwdriver Set (includes Phillips #000, #00, #0, #1) | 1 | $6 | [Amazon](https://www.amazon.com/Precision-Phillips-Screwdriver-Electronics-Computer/dp/B0DB227RTH) | 10€ | [Amazon](https://www.amazon.fr/dp/B08ZXVMVYD/) | ￥14.9 | [TaoBao](https://detail.tmall.com/item.htm?id=675684600845&skuId=4856851392176) |
| Wrench<sup>[4](#myfootnote5)</sup> | 1 | $5 | [Amazon](https://www.amazon.com/uxcell-Metric-Double-Wrench-5-5mm/dp/B07D4B8GWW/) | 4€ | [Amazon](https://www.amazon.fr/-/en/dp/B075DML8KB/) | ￥8.9 | [TaoBao](https://detail.tmall.com/item.htm?id=735857252241&skuId=5685349146062) |
| Total |---| $288 |---| 274€ |---|￥1631.46|---|

### Parts for One Arm:

| Part | Amount | Unit Cost (US) | Buy US | Unit Cost (EU) | Buy EU | Unit Cost (RMB) | Buy CN |
|---|---|---|---|---|---|---|---|
| STS3215 Servo<sup>[1](#myfootnote1)</sup> | 6 | $14 | [Alibaba](https://www.alibaba.com/product-detail/Top-Seller-Low-Cost-Feetech-STS3215_1600999461525.html) | 13€ | [Alibaba](https://www.alibaba.com/product-detail/Top-Seller-Low-Cost-Feetech-STS3215_1600999461525.html) | ￥97.72 | [TaoBao](https://item.taobao.com/item.htm?id=712179366565&skuId=5268252241438) |
| Motor Control Board | 1 | $5 | [Waveshare](https://www.waveshare.com/bus-servo-adapter-a.htm) - [Amazon](https://www.amazon.com/Control-Circuit-Suitable-Supports-Controlling/dp/B0CKT8BN73/ref=asc_df_B0CKT8BN73/) | 4€ | [Waveshare](https://www.waveshare.com/bus-servo-adapter-a.htm)-[Amazon](https://www.amazon.fr/-/en/dp/B0CJ6RYC9J/ref=sr_1_3)| ￥27 | [TaoBao](https://detail.tmall.com/item.htm?id=738817173460&skuId=5096283384143) |
| Bracket Set | 10 | $3 | [Alibaba](https://www.alibaba.com/product-detail/STS3215-Metal-brackets-for-FEETECH-7_1600836829515.html?spm=a2747.product_manager.0.0.180171d2hjgWrJ) | 2€ | [Alibaba](https://www.alibaba.com/product-detail/STS3215-Metal-brackets-for-FEETECH-7_1600836829515.html?spm=a2747.product_manager.0.0.180171d2hjgWrJ) | --- | --- |
| U Bracket | 10 | --- | --- | --- | --- | ￥6 | [TaoBao](https://item.taobao.com/item.htm?id=615340872015&skuId=4472922777845) |
| Bottom Bracket | 3 | --- | --- | --- | --- | ￥6 | [TaoBao](https://item.taobao.com/item.htm?id=615340872015&skuId=4472922777847) |
| Side Bracket | 3 | --- | --- | --- | --- | ￥6 | [TaoBao](https://item.taobao.com/item.htm?id=615340872015&skuId=4472922777846) |
| USB-C Cable 2 pcs | 1 | $7 | [Amazon](https://www.amazon.com/Charging-etguuds-Charger-Braided-Compatible/dp/B0B8NWLLW2/?th=1) | 7€ | [Amazon](https://[www.amazon.com/Charging-etguuds-Charger-Braided-Compatible/dp/B0B8NWLLW2/?th=1](https://www.amazon.fr/dp/B07BNF842T/)) | ￥23.9 | [TaoBao](https://detail.tmall.com/item.htm?id=44425281296&skuId=5611379016222) |
| Power Supply<sup>[2](#myfootnote2)</sup> | 1 | $10 | [Amazon](https://www.amazon.com/Facmogu-Switching-Transformer-Compatible-5-5x2-1mm/dp/B087LY41PV/) | 13€ | [Amazon](https://www.amazon.fr/-/en/dp/B01HRR9GY4/) | ￥22.31 | [TaoBao](https://item.taobao.com/item.htm?id=544824248494&skuId=4974994129990) |
| Table Clamp 2pcs | 1 | $5 | [Amazon](https://www.amazon.com/Clamp-Hanger-Storage-Clamps-Mount/dp/B0C1GYSVCS?rps=1&sr=1-2) | 8€ | [Amazon](https://www.amazon.fr/-/en/dp/B08HZ1QRBF/)| ￥7.8 | [TaoBao](https://detail.tmall.com/item.htm?id=738636473238&skuId=5505939904942) |
| Lowstrength Threadlocker<sup>[3](#myfootnote3)</sup> | 1 | $9 | [Amazon](https://www.amazon.com/Loctite-Threadlocker-Automotive-High-Temperature-Non-Corrosive/dp/B0002KKTT0/)| 11€ | [Amazon](https://www.amazon.fr/-/en/dp/B000HBGHFY/) | ￥81 | [TaoBao](https://detail.tmall.com/item.htm?id=652665229827&skuId=5125512809535) |
| Screwdriver Set (includes Phillips #000, #00, #0, #1) | 1 | $6 | [Amazon](https://www.amazon.com/Precision-Phillips-Screwdriver-Electronics-Computer/dp/B0DB227RTH) | 10€ | [Amazon](https://www.amazon.fr/dp/B08ZXVMVYD/) | ￥14.9 | [TaoBao](https://detail.tmall.com/item.htm?id=675684600845&skuId=4856851392176) |
| Wrench<sup>[4](#myfootnote4)</sup> | 1 | $5 | [Amazon](https://www.amazon.com/uxcell-Metric-Double-Wrench-5-5mm/dp/B07D4B8GWW/) | 4€ | [Amazon](https://www.amazon.fr/-/en/dp/B075DML8KB/) | ￥8.9 | [TaoBao](https://detail.tmall.com/item.htm?id=735857252241&skuId=5685349146062) |
| Total |---| $159 |---| 153€ |---|868.13|---|

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
   1. After the print is done, use the putty knife to scrape the parts off the print bed.
   2. Remove any support material from parts.
   3. Reapply the glue stick before starting the next print.

## Assembling the Parts
Construct the leader and follower arms using the [Assembly Video](https://www.youtube.com/watch?v=DA91NJOtMic). After you assemble the two arms from the video, power the leader and follower arm using the 5V power supplies. In addition, plug each arm into your computer using a USB-C cable.

## Configure
While this robot can be programmed in a variety of manners, it is suggested to use with [LeRobot](https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md).


Join the project for support and development on the [discord server](https://discord.gg/ggrqhPTsMe).

## Footnotes
<a name="myfootnote1">1</a>: The STS3215 arm comes in two sizes. The 7.4V has a stall torque of 16.5kg.cm at 6V (and likely slightly less for a 5V power supply). The 12V version has a stall torque of 30kg.cm. While we found the 7.4V to be sufficient, if you would like more powerful motors you can buy the 12V version [here](https://www.alibaba.com/product-detail/12V-30KG-STS3215-High-Torque-Intelligent_1600990786556.html). Note if you do this, you will also have to buy a 12V 5A+ power supply instead of a 5V one above, but all other components will remain the same.\
<a name="myfootnote2">2</a>: IMPORTANT: If you buy the 12V STS3215 motors, you should buy the [12V 5A+ power supply](https://www.amazon.com/Converter-100-220V-Transformer-5-5x2-1mm-Accessories/dp/B08C594VNP/) instead of the 5V power supply provided. \
<a name="myfootnote3">3</a>: While Loctite is not strictly necessary, it does help to ensure screws do not loosen overtime, and is recommended whenever you have a the M3 screw fastening into the M3 nut. You only need a small dot of it. \
<a name="myfootnote4">4</a>: You can either use a 5.5mm or 7/32" wrench, as they are both compatible with the M3 nuts. In a pinch you can also use needle-nose or other pliers but a wrench does help with assembly.
