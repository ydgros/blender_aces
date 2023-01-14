官网：https://opencolorio.org/  

ACES公版源码：https://github.com/AcademySoftwareFoundation/OpenColorIO  

ACES公版文件：https://github.com/imageworks/  

OpenColorIO-Configs
基于aces_1.0.3，修改方法参考了辣椒酱分支 https://www.bilibili.com/video/BV1iv4y1o721

安装方法
复制colormanagement至C:\Users\Administrator\AppData\Roaming\Blender Foundation\Blender\2.93\datafiles（将Administrator改成自己的用户名）

问题解答
Blender色彩文件有两个存放路径，一是软件安装目录Blender\2.93\datafiles，二是用户文件夹。优先调用用户文件夹colormanagement，用户文件夹没有colormanagement，接着调用软件安装目录中的colormanagement。

同理如果想要调用软件安装目录中的colormanagement，只需删除用户文件夹中的olormanagement

仍存在的问题  
3.0以上版本使用合成器中的色彩转换会出现偏色