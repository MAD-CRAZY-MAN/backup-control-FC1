[![thepeach logo](http://gabom1.pagei.gethompy.com/data/editor/2005/ae065791211b1de95f89a5c5c9f796b7_1589185049_9675.png)](http://thepeach.kr)

[🇰🇷](/README-ko.md "Korean")



## 우분투에서 빌드환경 설정

* PX4-Autopilot 리포지토리 clone

```bash
$ mkdir ~/thepeach_drone
$ cd ~/thepeach_drone
$ git clone https://github.com/ThePeach-Drone/PX4-Autopilot.git --recursive
```



 * Nuttx/Pixhawk toolchain 설치

```bash
$ bash ./PX4-Autopilot/Tools/setup/ubuntu.sh
```



## THE PEACH K1 Board

![THEPEACH K1](./boards/thepeach/k1/THEPEACH_K1.png)
 * THE PEACH K1's firmware를 빌드하는 방법
```bash
$ cd ~/thepeach_drone/PX4-Autopilot

$ make thepeach_k1_default
```
-- 빌드한 thepeach_k1_default.px4 파일은 ~/thepeach_drone/PX4-Autopilot/build/thepeach_k1_default  폴더에 생성되어진다.



## THE PEACH R1 Board

![THEPEACH R1](./boards/thepeach/r1/THEPEACH_R1.png)
 * THE PEACH R1's firmware를 빌드하는 방법
```bash
$ cd ~/thepeach_drone/PX4-Autopilot

$ make thepeach_r1_default
```
-- 빌드한 thepeach_r1_default.px4 파일은 ~/thepeach_drone/PX4-Autopilot/build/thepeach_r1_default  폴더에 생성되어진다.