# Tai
👻 在 Windows 上统计软件使用时长

<img src="index.jpg" width=600 />

类似于 iPhone 的屏幕使用时长一样，Tai 负责统计你每一个软件的使用时长。需要注意的是，使用时长并不是软件的存活时间，而是软件从获得焦点时开始到失去焦点后这段时间

## 开始使用

#### 环境

使用之前，你的电脑可能需要安装 [.NET Framework](https://dotnet.microsoft.com/en-us/download/dotnet-framework) `4.6.1` 或更高的版本

#### 使用

在 [releases](https://github.com/Planshit/Tai/releases) 中可以下载已经编译好的 exe 可执行文件压缩包，如果你了解 `WPF` 也可以下载源码自行编译

进入根目录找到 `Tai.exe` 启动程序，成功启动后可以在状态栏看到 👻 图标

双击图标可以进入程序主界面，右击显示退出菜单

## 了解更多

#### 为什么使用 Tai

帮助你了解自己把时间花在了什么地方，从而更好地做一些计划。或者，为了每周回顾自己的摸鱼成果

#### 关联进程

如果你希望在多屏工作时将其他屏幕所使用的软件同时记录使用时长，可以在设置中添加关联。需要注意，一个进程只能关联一次，不能重复与其他进程关联

#### 忽略应用

可以通过进程名称或者正则表达式对不需要统计的软件进行忽略

#### 数据储存和导出

Tai 使用不加密 `SQLite` 数据库将统计数据存储在本地 `运行目录\Data\data.db` 中，你可以随意迁移、备份、修改。并且可以在设置中将所有统计的数据以 `.xlsx` 和 `.csv` 两种文件格式导出

#### 隐私和联网

除了检查更新/升级软件时（需要主动在设置中点击）之外完全没有其他网络请求。Tai 并不会收集和上传你的任何信息
