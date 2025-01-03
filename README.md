# Proteus仿真STM32超声波测距与四位数码管显示

## 项目描述

经过两天的努力，我成功实现了Proteus 8.7与Keil 5环境下STM32F103C6的联调，并完成了超声波测距与四位数码管显示的功能。在此过程中，我借鉴了不少资料，最终实现了这一目标。（之前丢失的hc-sr04.hex文件已经重新上传）

## 功能介绍

本项目通过Proteus仿真平台，实现了以下功能：

1. **超声波测距**：利用STM32F103C6微控制器与HC-SR04超声波模块进行测距，并将测距结果实时显示在四位数码管上。
2. **数码管显示**：通过四位数码管直观地展示测距结果，方便用户查看。

## 使用说明

1. **环境配置**：
   - Proteus 8.7
   - Keil 5
   - STM32F103C6微控制器
   - HC-SR04超声波模块
   - 四位数码管

2. **仿真步骤**：
   - 打开Proteus 8.7，加载项目文件。
   - 在Keil 5中编译并生成HEX文件。
   - 将生成的HEX文件加载到Proteus中的STM32F103C6微控制器中。
   - 运行仿真，观察超声波测距结果在数码管上的显示。

3. **注意事项**：
   - 确保Proteus和Keil的版本兼容。
   - 在仿真过程中，注意检查硬件连接是否正确。
   - 如有问题，请参考相关资料或联系作者。

## 文件说明

- `hc-sr04.hex`：重新上传的超声波模块HEX文件。
- `main.c`：Keil 5项目中的主程序文件。
- `Proteus仿真文件.pdsprj`：Proteus仿真项目文件。

## 致谢

感谢在此过程中提供帮助和参考的资料及社区成员。

## 联系方式

如有任何问题或建议，欢迎通过以下方式联系我：

- 邮箱：[your-email@example.com]
- GitHub：[your-github-profile]

希望这个项目能对你有所帮助！

## 下载链接

[Proteus仿真STM32超声波测距与四位数码管显示](https://pan.quark.cn/s/21518173384a)