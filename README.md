# 联想小新锐7000黑苹果EFI

### Lenovo XiaoXin RUI7000 Hackintosh

#### 电脑配置

| 部件      | 信息                                            |
| --------- | :---------------------------------------------- |
| 型号      | 联想80WB笔记本电脑                              |
| 处理器    | Intel Core i5-7300HQ @ 2.50GHz 四核             |
| 内存      | 16GB （Samsung 8GB✖️2）                          |
| 硬盘      | WDS500G3X0C-00SJG0（西数SN750 M.2固态硬盘500G） |
| 显卡      | NVIDIA GeForce GTX 1050（2GB）/Intel HD 630集显 |
| 网卡      | Intel AX200 WiFi6                               |
| OC版本    | 0.6.5                                           |
| MacOS版本 | macOS 11.2.3 BigSur                             |

#### 使用说明

⚠️使用此EFI安装需要**解锁**笔记本电脑的**CFG Lock**，参考教程：[联想拯救者Y7000P 2019款bios高级教程——解锁CFG+修改DVMT/其他高级选项](http://bbs.pcbeta.com/viewthread-1845189-1-1.html)，解锁偏移地址直接在此列出`CFG：0x3C，DVMT：0xDF`

#### HDMI

HDMI使用基本正常，可以插着开机，也可以开机后在插。插着开机时只有外接显示器能点亮，笔记本内屏会黑屏，解决办法是使系统进入睡眠状态（待键盘指示灯熄灭），然后再唤醒即可点亮内屏（唤醒时外接设备可能会无效，需要使用笔记本内置键盘唤醒）

#### 网卡

无线网卡更换成了Intel AX200 WiFi6网卡，但目前Intel网卡在黑苹果中的带宽最高只有55Mbps左右，介意的建议还是使用博通方案

#### 系统支持

本人直接安装BigSur可以成功，其他版本没有测试，Catalina和Mojave应该也能正常使用，具体还请自测

#### 截图

![image-20210410160441128](/Users/baymrx/Library/Application Support/typora-user-images/image-20210410160441128.png)

![image-20210410160646557](/Users/baymrx/Library/Application Support/typora-user-images/image-20210410160646557.png)

![image-20210410160727625](/Users/baymrx/Library/Application Support/typora-user-images/image-20210410160727625.png)