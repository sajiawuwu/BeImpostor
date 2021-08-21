# 运行服务器

目前有两种模式可以运行 BeImpostor 服务器。第一种方式，单服务器，是最简单的方式，最多可以同时处理几百个玩家，也是您可能应该使用的方式。多服务器模式将玩家分布在其他服务器上，适用于高级用户。

## 单台服务器

### 不适用 Docker

1. 安装.[.NET 5.0 runtime](https://dotnet.microsoft.com/download). 运行安装 SDK 也可以，但不是必需的，除非您计划开发 BeImpostor 或 Impostor 插件。如果要求您在控制台、桌面或服务器运行时之间进行选择，控制台运行时就足够了。
2. 下载最新版本
3. 下载适用于您的操作系统 (linux/win/osx) 的版本。BE Impostor 是多线程的，您很可能需要 x64 版本，除非您在 Raspberry Pi 或其他带有 ARM 处理器的设备上运行。
4. 解压.
5. config.json根据自己的喜好修改。
6. 运行Impostor.Server(Linux/macOS) 或Impostor.Server.exe(Windows)

