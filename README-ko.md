[![thepeach logo](http://gabom1.pagei.gethompy.com/data/editor/2005/ae065791211b1de95f89a5c5c9f796b7_1589185049_9675.png)](http://thepeach.kr)

[๐ฐ๐ท](/README-ko.md "Korean")



## ์ฐ๋ถํฌ์์ ๋น๋ํ๊ฒฝ ์ค์ 

* PX4-Autopilot ๋ฆฌํฌ์งํ ๋ฆฌ clone

```bash
$ mkdir ~/thepeach_drone
$ cd ~/thepeach_drone
$ git clone https://github.com/ThePeach-Drone/PX4-Autopilot.git --recursive
```



 * Nuttx/Pixhawk toolchain ์ค์น

```bash
$ bash ./PX4-Autopilot/Tools/setup/ubuntu.sh
```



## THE PEACH K1 Board

![THEPEACH K1](./boards/thepeach/k1/THEPEACH_K1.png)
 * THE PEACH K1's firmware๋ฅผ ๋น๋ํ๋ ๋ฐฉ๋ฒ
```bash
$ cd ~/thepeach_drone/PX4-Autopilot

$ make thepeach_k1_default
```
-- ๋น๋ํ thepeach_k1_default.px4 ํ์ผ์ ~/thepeach_drone/PX4-Autopilot/build/thepeach_k1_default  ํด๋์ ์์ฑ๋์ด์ง๋ค.



## THE PEACH R1 Board

![THEPEACH R1](./boards/thepeach/r1/THEPEACH_R1.png)
 * THE PEACH R1's firmware๋ฅผ ๋น๋ํ๋ ๋ฐฉ๋ฒ
```bash
$ cd ~/thepeach_drone/PX4-Autopilot

$ make thepeach_r1_default
```
-- ๋น๋ํ thepeach_r1_default.px4 ํ์ผ์ ~/thepeach_drone/PX4-Autopilot/build/thepeach_r1_default  ํด๋์ ์์ฑ๋์ด์ง๋ค.