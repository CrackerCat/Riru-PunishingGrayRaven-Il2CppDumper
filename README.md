# Riru-战双帕弥什Il2CppDumper
基于Riru的战双帕弥什哔哩哔哩版Il2CppDumper，在游戏运行时dump数据，用于绕过保护，加密以及混淆。

## 如何使用
1. 安装[Magisk](https://github.com/topjohnwu/Magisk)和[Riru](https://github.com/RikkaApps/Riru)
2. [下载源码](https://github.com/GodLeaveMe/Riru-PunishingGrayRaven-Il2CppDumper/releases)
3. 使用Android Studio运行gradle任务`:module:assembleRelease`编译
4. 在Magisk里安装模块
5. 启动游戏，会在`/data/data/com.kurogame.haru.bilibili/files/`目录下生成`dump.cs`

## TODO
- [x] 使用`il2cpp_image_get_class`进行dump
- [ ] 完善dump.cs输出
- [ ] 泛型相关输出
- [ ] 生成IDA脚本
- [ ] 生成头文件
