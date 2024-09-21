# moss-robot-arms
moss-robot-arms Beta version 1.0.

A repository for affordable, easy-to-assemble robot arms designed for teleoperation applications. Note: This initial version arm uses the [SO-100 Arm](https://github.com/TheRobotStudio/SO-ARM100) Gripper. Future iterations will have an off the shelf gripper.

## Assembly Instructions
![Arm](./pictures/Render.png)


### Sourcing Parts
Note: The follower and leader arm for this teleoperation setup will be the same. Order all parts for either one arm or for two arms if you plan on using teleop using the links below. Note prices and items may vary slightly depending on geographic location.


TODO(jess-moss): Add a picture when you can.

/!\ Warning: We only have links for US for now. If you find links for other countries, please create an issue or PR so that we add them to the list.

| Part | Amount | Unit Cost (US) | Buy US |
|---|---|---|---|
| STS3215 Servo | 6 | $15 | [Alibaba](https://www.alibaba.com/product-detail/6PCS-12V-30KG-STS3215-High-Torque_1601216757543.html?) |
| Motor Control Board | 1 | $5 | [Waveshare](https://www.waveshare.com/bus-servo-adapter-a.htm) |
| Bracket Set | 8 | $3 | [Alibaba](https://www.alibaba.com/product-detail/STS3215-Metal-brackets-for-FEETECH-7_1600836829515.html) |
| Total |---| $117 |---|


Below are some necessary tools you might need.
| Tool | Amount | Unit Cost (US) | Buy US |
|---|---|---|---|
| Lowstrength Threadlocker | 1 | $9 | [ThreadLocker](https://www.amazon.com/Loctite-Threadlocker-Automotive-High-Temperature-Non-Corrosive/dp/B0002KKTT0/)|
| Screwdriver |---|---|---|
| Combination Wrench | - | - |---|
| Total |---| --- |---|

### Assembling the Parts
Construct the leader and follower arms using the Assembly Video linked below. After you assemble the two arms from the video, power the leader arm using the 5V power supply, and the follower arm using the 12V power supply. In addition, plug each arm into your computer using a USB-C cable.

TODO(jess-moss): Add assembly video.

### Configure
While this robot can be programmed in a variety of manners, it is suggested to use with [LeRobot](https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md).


Join the project for support and development on the [discord server](https://discord.gg/ggrqhPTsMe).