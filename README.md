# ImageRecognition
获取摄像头视频流，对获取的每一帧图片进行图像识别



## 编译环境

Windows + Qt5.9.1 + MinGW 5.3.0 32bit



## 视频流解码

使用ffmpeg解码摄像头视频流

Windows编译ffmpeg

​		1、安装msys，用于模拟linux bash的命令行；

​		2、将QT安装目录下的mingw530_32(我的路径是D:\Qt\Qt5.9.1\Tools\mingw530_32) 复制到 msys的安装目录(我的是D:\msys64)；

​		3、打开mingw32.exe，编译ffmpeg时需提前安装几个工具

​				pacman -S diffutils 

​				pacman -S pkg-config 

​				pacman -S make

​		4、设置环境变量，用于找到gcc等编译器；

​			![image-20220801164529191](C:\Users\chengqian\AppData\Roaming\Typora\typora-user-images\image-20220801164529191.png)  

​		4、编译ffmpeg；

​			![image-20220801164832772](C:\Users\chengqian\AppData\Roaming\Typora\typora-user-images\image-20220801164832772.png)

![image-20220801165258175](C:\Users\chengqian\AppData\Roaming\Typora\typora-user-images\image-20220801165258175.png)
