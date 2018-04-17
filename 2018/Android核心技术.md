# Android核心技术
---
[原文链接](https://source.android.com/devices/tech/)

* [ART and Dalvik](#ART-and-Dalvik)
* [Configuration](#Configuration)
* [Connectivity](#Connectivity)
* [Data Usage](#Data-Usage)
* [Debugging](#Debugging)
* [Device Administration](#Device-Administration)
* [Display Settings](#Display-Settings)
* [OTA Updates](#OTA-Updates)
* [Performance](#Performance)
* [Power](#Power)
* [Settings](#Settings)
* [Trade Federation Testing Infrastructure](#Trade-Federation-Testing-Infrastructure)
* [Vendor Test Suite (VTS)](#Vendor-Test-Suite-(VTS))

欢迎来到本站的`Android`核心技术区域.这里你可以找到有关常用功能的信息,这些功能适用于希望修改,贡献或移植`Android`软件的人员和组织.这是面向工程师的隐藏的信息.

### ART and Dalvik

安卓运行时(ART)是Android的心脏.它是一个面向扩展,带有现代垃圾回收器的,快速,提前编译的运行时.`Android`应用程序被编译成虚拟机字节码并且运行在`ART`上.本节包含详细信息,比如虚拟机可执行文件格式规范,运行时本身的设计信息.

[ART and Dalvik Information](https://source.android.com/devices/tech/dalvik/index.html)

### Configuration

充分利用`Android`需要调整[kernel](https://source.android.com/devices/architecture/kernel/config),[OpenGLRender](https://source.android.com/devices/graphics/renderer)等.查看关于该区域的子页面的更多详情.

[Configuration Information](https://source.android.com/devices/tech/config/index.html)

### Connectivity

本节包含了`Android`所支撑的`NFC`标准,提供了无线电接口层(RIL)的细节,描述了调用通知行为,并且给出了面向用户功能的实现说明比如数据保护程序和电话号码拦截.

[Connectivity Information](https://source.android.com/devices/tech/connect/index.html)

### Data Usage

`Android`的数据用例功能允许用户理解和控制他们的设备是如何使用网络数据的.本小节是为系统集成商和移动运营商设计的,帮助他们定制特定的`Android`系统时,解释他们需要理解的技术细节.

[Data Usage Information](https://source.android.com/devices/tech/datausage/index.html)

### Debugging

`Android`是个大型复杂的系统.本小节包含了在平台级别调试的提示和技巧.

[Debugging Information](https://source.android.com/devices/tech/debug/index.html)

### Device Administration

自从`Android 5.0`起,平台在各个公司的`IT`部门主持下支持企业环境中的用例.

[Device administration information](https://source.android.com/devices/tech/admin/index.html)

### Display Settings

本小节包含了`AOSP`一系列的`Android`显示设置的实现,包括应用快捷方式,圆角登陆图标,勿扰模式(DND),多窗口(分屏,自由格式,画中画),高动态范围(HDR)视频,夜间模式,零售演示模式.

[Display settings information](https://source.android.com/devices/tech/display/index.html)

### OTA Updates

`Android`设备在此领域可以以`OTA`方式接受和安装更新系统和软件应用.这小节描述了更新包的结构和构建他们的工具.它旨在为开发者为新的和发布的`Android`设备构建`OTA`更新.

[OTA Information](https://source.android.com/devices/tech/ota/index.html)

### Performance

本节提供了确保你`Android`设备最小化资源使用和优化性能的指导.他包含了优化启动时间,管理闪光灯磨损,配置低`ram`设备等等的细节.

[Performance Information](https://source.android.com/devices/tech/perf/index.html)

### Power

这框架提供了电池使用统计,保持追踪不同状态不同系统组件下的时间消耗.本节包含了电池管理功能(比如`Doze`),为精确测量设备和组件的功率提供了指导(和如何确定功率值),详细介绍了`batterystats`命令和输出.

[Power Information](https://source.android.com/devices/tech/power/index.html)

### Settings

本节提供了实现`Android`设置菜单的功能的指导.他包含了模式,组件和设置应用的架构的细节,如何组织个人的设置,如何增加设置到全局搜索.

[Settings Information](https://source.android.com/devices/tech/settings/index.html)

### Trade Federation Testing Infrastructure

`Trade Federation`是用于在`Android`设备上运行测试的持续测试框架.`Trade Federation`的模块化使其可以直接插入到具有现有构建,测试和报告基础架构的环境中.

[Trade Federation Testing Infrastructure Overview](https://source.android.com/devices/tech/test_infra/tradefed/index.html)

### Vendor Test Suite (VTS)

`Android`供应商测试套件(VTS)为`Android`测试提供了广泛的新功能,并促进了测试驱动的开发过程.本节描述了测试工具和可用的资源来帮助`Android`开发者和测试数据相互作用.

[VTS Information](https://source.android.com/devices/tech/vts/index.html)
