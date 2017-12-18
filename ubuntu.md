Ubuntu
===

### 1.Failed to create OpenGL context for format QSurfaceFormat

可能原因：显卡不支持OpenGL或显卡驱动问题

解决办法：重新安装驱动或或换显卡等

### 2.linux循环登录，无法进入桌面（或进入桌面过几秒又跳到登录界面）

可能原因：用户目录没有写权限，无法创建.xauthority文件

### 3.crossover安装软件乱码

可能原因：原版那个ttf是SJIS内码，没有很多简体中文的汉字，是乱码的真正起因

解决办法：打开crossover安装目录，进入wine的fonts目录（如/opt/cxoffice/share/wine/fonts/），把里面ume-ui-gothic.ttf替换成一个Windows下的中文字体。（如SIMSUN）
