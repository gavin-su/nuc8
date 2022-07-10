# nuc8
硬改94360cs2网卡

# U盘目录结构

```
|-- com.apple.recovery.boot
    |-- .contentDetails
    |-- BaseSystem.chunklist
    |-- BaseSystem.dmg 
|-- EFI
```

这可由下面的“EFI”工具获得。
但该工具未包含macOS最新版本，macOS最新版本的BaseSystem.* 可由macrecovery获得。

# EFI
https://github.com/Jiangmenghao/NUC8i5BEH

# macrecovery
https://github.com/luchina-gabriel/macrecovery

（比 https://github.com/acidanthera/OpenCorePkg 下的 Utilities/macrecovery 要新。）

获取最新的macOS，执行：

python3.8.exe macrecovery.py -b Mac-E43C1C25D4880AD6 -m 00000000000000000 download

# 参考
安装指引：https://zhuanlan.zhihu.com/p/165608087
