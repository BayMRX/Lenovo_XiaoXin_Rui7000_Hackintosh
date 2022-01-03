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
| OC版本    | 0.7.6                                           |
| MacOS版本 | macOS 12.1 Monterey                             |

#### 使用说明[Release](https://github.com/BayMRX/Lenovo_XiaoXin_Rui7000_Hackintosh/releases)

⚠️使用此EFI安装需要**解锁**笔记本电脑的**CFG Lock**，参考教程：[联想拯救者Y7000P 2019款bios高级教程——解锁CFG+修改DVMT/其他高级选项](http://bbs.pcbeta.com/viewthread-1845189-1-1.html)，解锁偏移地址直接在此列出`CFG：0x3C，DVMT：0xDF`

⚠️需要自行生成三码！！

#### HDMI

HDMI使用基本正常，可以插着开机，也可以开机后在插。插着开机时只有外接显示器能点亮，笔记本内屏会黑屏，解决办法是使系统进入睡眠状态（待键盘指示灯熄灭），然后再唤醒即可点亮内屏（唤醒时外接设备可能会无效，需要使用笔记本内置键盘唤醒）

⚠️⚠️⚠️连接外部显示器时，笔记本合屏开机外置显示器会花屏，需要笔记本开合一次才会消失（此问题在使用bigSur时的某次升级后出现，bigSur较早版本不会有这个问题）

#### 网卡

无线网卡更换成了Intel AX200 WiFi6网卡，正常使用几乎没有问题，速度也很快。随航和隔空投送暂未实现，介意的建议还是使用白果卡方案

#### 系统支持

本人直接安装BigSur和Monterey都可以成功，其他版本没有测试，Catalina和Mojave应该也能正常使用，具体还请自测

#### 截图
![Monterey](https://raw.githubusercontent.com/BayMRX/Blog_source/9b1a6c9f59f87b7ec25deb3534ea012e6587dc3f/img/2022-01-03_21-45-52.jpg)
![image-20210410160441128](https://user-images.githubusercontent.com/41069495/114263418-ead9ce00-9a17-11eb-9cf0-d400269c4d9a.png)
![image-20210410160727625](https://user-images.githubusercontent.com/41069495/114263421-edd4be80-9a17-11eb-9f4a-cb959a30fcd6.png)
![image-20210410160646557](https://user-images.githubusercontent.com/41069495/114263425-f0371880-9a17-11eb-984e-6d216f6d230e.png)
#### 致谢
感谢[@839891627](https://github.com/839891627/Lenovo_RUI7000_Hackintosh)和[@Erf172](https://github.com/Erf172/Lenovo_XiaoXin_Rui7000_Hackintosh)两位大佬EFI的参考
