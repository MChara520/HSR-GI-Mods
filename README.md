# HSR-GI-Mods
原神和崩铁的启动器是通用的 你可以使用gi(https://github.com/SilentNightSound/GI-Model-Importer)
也可以使用hsr(https://github.com/SilentNightSound/SR-Model-Importer)
我这里更推荐用gi注入 无论哪款游戏(原神 崩铁 崩坏三 绝区零) hsr注入器有问题 不一定对每台设备都起作用
进入releases目录
3dmgigoto分为development和playing两个版本
如果你是mod的开发者可以下载development版本 对于正常玩家下载playing版本即可
解压完成后如图所示![Screenshot_2025-02-04-15-04-23-737_bin mt plus-edit](https://github.com/user-attachments/assets/3245670a-8494-4454-8810-d14c4c7cfd02)
会出现这些文件 我们应对d3dx.ini进行编辑(主要是国际服和国服的文件名称不一样)
这里我列给大家
国际服原神:GenshinImpact.exe
国服原神:YuanShen.exe
国际服&国服崩铁:StarRail.exe
进入d3dx.ini后按Ctrl+F进行搜索exe(主要是为了定位target)
![Screenshot_2025-02-04-15-09-26-580_bin mt plus](https://github.com/user-attachments/assets/1ff65e81-33ed-4c4e-aad1-a74f2863ac1f)
找到target后 将GenshinImpact.exe改成你要注入的游戏名字(注:老版本3dmigoto-gi需要提供完整的目录 这里是新版可以直接忽视)
随后保存ini文件 将mod解压至mods 双击运行3DMigotoLoader.exe即可
