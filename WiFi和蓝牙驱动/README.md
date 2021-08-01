我是20年7月入手的ipad，之前就使用过黑苹果，后来发现在学习中需要电脑端和ipad端之间频繁的信息交流，如果能够共享粘贴板就好了，就不用疯狂自己和自己qq聊天了。
但是在网上了解了一下需要完美的wifi和蓝牙驱动，我的wifi已经可以正常驱动，但是蓝牙还不是很完美，所以接力功能不能正常使用，加上这学期比较忙，没有时间折腾了。
现在放假，我就腾出手来完善蓝牙驱动。
### 0.将驱动文件（kext）加入到路径中
下载opencore修改软件
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210715214331498.png)
下载驱动文件
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210715214417226.png)
将驱动文件复制到分区的Kexts文件夹下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210715214459842.png)
将驱动文件添加到路径中（直接拖到指定位置）：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210715214624222.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2pvZXlfcm8=,size_16,color_FFFFFF,t_70)
重启电脑即可！
### 1.确保wifi驱动正常
[教程](https://www.youtube.com/watch?v=kJAz92cqavA)
[驱动GitHub网址](https://github.com/OpenIntelWireless/itlwm)
正常后的效果：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210715213906909.png)
能够正常关闭，与原生wifi一样使用。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210715213948683.png)
### 2.确保蓝牙正常使用
[教程](https://www.bilibili.com/video/BV1LJ41157Gs?t=124)
[驱动GitHub网址](https://github.com/zxystd/IntelBluetoothFirmware/releases)
能够正常关闭、和原生蓝牙一样正常使用
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210715214042973.png)
### 3.在设备之间使用接力
#### 3.1在mac电脑打开接力
系统偏好设置-通用：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210715214743369.png)
#### 3.2在ipad端打开接力
通用-隔空播放与接力：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210715215000773.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2pvZXlfcm8=,size_16,color_FFFFFF,t_70)
#### 3.3 效果
两个设备之间共用剪贴板。