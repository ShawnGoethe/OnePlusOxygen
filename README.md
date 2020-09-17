# OnePlusOxygen
record some story oxygen OS正常使用钱包公交卡,谷歌相机，加密门禁等 make oneplus more fun

## Oneplus 7T
在论坛查找到方式可以非root方式，正常使用钱包

1. 退出一加账户（设置-账号-一加账号-右上角三个点-退出账号）
2. 设置-app-中找到一加账户停用(设置-应用和通知-查看全部xx个应用-右上角三个点-显示系统程序-搜索一加-点击一加账号，停用)
3. 安装氢提取的一加账户apk，或者在本repository  `/app/wallet/Account.apk` 目录下载
4. 打开钱包app，登陆即跳转到国内一加账户app

我的手机参数

- oneplus 7t
- oxygenOS OP7T_O2_BATE_07

links:
- [root方式](https://github.com/kiritoxkiriko/HookOPAccount)
- [一加论坛](https://www.oneplusbbs.com/thread-5503658-1.html)



## Google Camera

以下示例为7T

- [camera.apk](https://f.celsoazevedo.com/file/cfiles/gcm1/GCam_7.2.010_Urnyx05-v2.3.apk)
- [config](https://www.celsoazevedo.com/files/android/p/f/2020/02/nameless-v6_urnyx-v2.2.xml)

1. 下载apk以及配置文件
2. 建立目录***\**\*/GCam/Configs/\**\****
3. 把xml配置文件放入刚建的configs目录下
4. 安装apk
5. 打开谷歌相机app，加载配置文件（加载两次，双击快门键黑色区域，会弹出加载选项）
6. 如果需要长焦和超广角，需要刷入[Magisk Module for AUX](https://forum.xda-developers.com/oneplus-7-pro/themes/gcam-enabling-aux-camera-t3935086)

link：[更多机型访问XDA](https://www.xda-developers.com/google-camera-port-hub/)，又名google camera port hub



## NFC门禁

首先门禁主要分为

- IC卡 滴，线圈矩形，钥匙扣（雨滴型蓝色）门禁上无数字
- ID卡 滴滴，线圈圆形，钥匙扣（雨滴型蓝色）门禁上有数字，（00开头的10位）或者（18位）
- IC+ID复合卡 滴滴滴，线圈矩形圆形叠加

正常来说所有手机以及手环只能模拟IC卡（也有一些ID卡复制成功的文章，不过我没看懂，也没记下来地址）



## 刷入 Magisk获取更多功能

- 去掉开屏广告
- 开启移植谷歌相机的[超广角、长焦](## Google Camera)

Link:[Magisk官网](https://magiskmanager.com/)