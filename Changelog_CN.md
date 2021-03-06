# S200H EFI 更新日志

[English](https://github.com/EngLearnsh/S200H-NUC-Hackintosh/blob/master/Changelog.md) | 中文

- 2019-12-22 v1.2
  - 更新 `Clover` 5101
  - 更新 `Lilu` 1.4.0
  - 更新 `AppleALC` 1.4.4
  - 更新 `Whatevergreen` 1.3.5
  - 更新 `VirtualSMC` 1.0.9，包括两个传感器驱动
  - 更新 `ApfsDriverLoader.efi`，解决部分分区引导问题
  - 支持4K分辨率输出
  - 移除 `framebuffer-fbmem` 和 `framebuffer-stolenmem` 以改善显卡的稳定性
  - 移除无用的主题

- 2019-11-19 v1.2 Beta 2
  - 更新 `Clover` 5098
  - 更新 `Lilu` 1.3.9
  - 更新 `AppleALC` 1.4.3
  - 更新 `Whatevergreen` 1.3.4
  - 更新 `VirtualSMC` 1.0.9，包括两个传感器驱动
  - 更新 `ApfsDriverLoader.efi`，解决部分分区引导问题
  - 移除无用的主题

- 2019-09-04 v1.2 Beta 1
  - 支持4K分辨率
  - 移除 `framebuffer-fbmem`, `framebuffer-stolenmem` 和 `framebuffer-unifiedmem` 以测试显卡的稳定性

- 2019-08-16
  - 更新 `Clover` 5045
  - 更新 `Lilu` 1.3.8
  - 更新 `AppleALC` 1.4.0
  - 更新 `Whatevergreen` 1.3.1
  - 更新 `VirtualSMC` 1.0.7, 包括两个传感器驱动
  - 修复系统启动到第二阶段时的花屏
  - 修复 Display port, 现在HDMI和DP都可以使用了 (感谢 kkzzhizhou)
  - 改善高分辨率屏幕的显示效果
  - 移除 `SSDT-DEHCI`, `SSDT-DEH01`, `SSDT-DEH02`, `SSDT-IMEI` 因为它们会引发ACPI错误
  - 移除 DSDT 重命名项目 `Change HECI to IMEI` 因为它并无实质性作用
  - 增加 `AddDTGP` 和 `AddIMEI` 的修复, 现在启动速度会比之前快一半
  - 增加 PCI 设备属性, 从而让macOS可以更好地识别它们
  - 减少Clover启动等待时间到2秒

- 2019-08-07
  - 初版发布