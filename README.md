# 少女前线人型壁纸

## 让你的人型跑在你的电脑桌面

需要wallpaper engine来运行（你问我为什么不上架创意工坊？我的we编辑器打不开这个项目啊我能怎么办QAQ）

### **如何使用**

- 你需要有wallpaper engine（没有请自行购买2333）
- 将项目文件拉取到本地
- 打开we编辑器，然后把项目文件夹里的HTML文件拖到“创建壁纸”上
- 项目名称随便起，正常情况下项目文件夹下的文件结构会出现在窗口上，点击确定（然后编辑器窗口就卡死了，估计是we的bug，建议强制关闭2333）
- 壁纸会出现在已安装里，可以开始愉快地使用了

### **使用注意事项**

- 关于项目的所有配置，全部放在了**config**文件中（别问我为什么不用json配置，似乎we不能读取json，就8知道为什么），请严格按照给出的格式使用**英文输入法**修改参数（大佬直接改代码也行2333）
- 请尽量使用1920*1080这种平民能用得起的屏幕运行此壁纸（因为没适配，鬼知道会出现什么奇怪的问题）
- 由于我的任务栏是放在右边的，人型的高度直接贴在底部刚刚好，任务栏在下面人型会只显示上半身（下半身卡在任务栏里），出现这种问题就按提示修改config文件就好了

### **已知的问题**

- 似乎偶尔会报错，表现出来的样子是人型全都不见或者少了一两个。如果发生了这种意外的情况，请点击右上角的刷新图标自行刷新（概率不大，我也懒得排错了2333）
- 有些人型会变成扭曲的样子（？）请按提示在config文件中修改全局js变量进行更改