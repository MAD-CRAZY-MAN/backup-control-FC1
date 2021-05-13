[![thepeach logo](http://gabom1.pagei.gethompy.com/data/editor/2005/ae065791211b1de95f89a5c5c9f796b7_1589185049_9675.png)](http://thepeach.kr)

[🇰🇷](/README-ko.md "Korean")



## Development Environment for Ubuntu

* clone PX4-Autopilot repository

```bash
$ mkdir ~/thepeach_drone
$ cd ~/thepeach_drone
$ git clone https://github.com/ThePeach-Drone/PX4-Autopilot.git --recursive
```



 * To install Nuttx/Pixhawk toolchain

```bash
$ bash ./PX4-Autopilot/Tools/setup/ubuntu.sh
```



## THE PEACH K1 Board

![THEPEACH K1](./boards/thepeach/k1/THEPEACH_K1.png)
 * How to build THE PEACH K1's firmware
```bash
$ cd ~/thepeach_drone/PX4-Autopilot

$ make thepeach_k1_default
```
-- Build thepeach_k1_default.px4 files have been written to: /home/thepeach-drone/PX4-Autopilot/build/thepeach_k1_default/



## THE PEACH R1 Board

![THEPEACH R1](./boards/thepeach/r1/THEPEACH_R1.png)
 * How to build THE PEACH R1's firmware
```bash
$ cd ~/thepeach_drone/PX4-Autopilot

$ make thepeach_r1_default
```
-- Build thepeach_r1_default.px4 files have been written to: /home/thepeach-drone/PX4-Autopilot/build/thepeach_r1_default/

