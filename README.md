# robsys_kadai_1
# ロボットシステム学課題１
## 概要
LEDを1で点灯，0で消灯する．
## デバイスドライバの作成
・手順
```
$ git clone https://github.com/ryuichiueda/raspberry_pi_kernel_build_scripts.git
$ cd raspberry_pi_kernel_build_scripts
$ sudo ./karnel_build_and_install_for_pi2_pi3.bash
$ sudo reboot
```
## デモ動画
<https://youtu.be/Y-SjDVwOp6M>

## 使用方法
```
$ git clone https://github.com/yukias/robsys_kadai_1.git
$ cd robsys_kadai_1
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
```
LEDを点灯させる．
`$ echo 1 > /dev/myled0`
LEDを消灯させる．
`$ echo 1 > /dev/myled0`
