<h1 align="center">Sysinternals 社区汉化版工具集合</h1>

## 使用说明

1. 本仓库仅提供 64 位版本，x86_32 和 ARM 暂不提供。
2. 在使用过程中如果发现未汉化或翻译错误的地方，欢迎提 issue。
3. 因 Sysinternals 为专有软件（封闭源码），本仓库拒绝附带二进制文件的 PR 以防止病毒传播。
4. 已发现但本人无法解决的问题会列在[已知问题](#已知问题)区域。

## 下载链接

点击应用名称跳转至微软产品页面跟踪最新版本信息。

| 应用名称 | 已汉化版本 | 最新版本 | Patch 版本号 | 下载链接 | 
|--|--|--|--|--|
| [**Process Explorer**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/process-explorer) | v17.06(2024.??.??) | **v17.08(2025.11.20)** | v17.06.008 | [EXE 文件](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v17.06.008-procexp/procexp64.exe)    [7z 文件](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v17.06.008-procexp/procexp64.7z) |
| [**Process Monitor**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/procmon) | v4.00(2024.??.??) | **v4.01(2024.6.20)** | v4.01.001 | [EXE 文件](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v4.00.001-procmon/procmon64.exe) |
| [**WinObj**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/winobj) | v3.14(2022.1.27) | v3.14(2022.1.27) | v3.14.003 | [EXE 文件](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v3.14.003-winobj/Winobj64.exe) |
| [**RAMMap**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/rammap) | v1.61(2022.5.11) | v1.61(2022.5.11) | v1.61.001 | [EXE 文件](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v1.61.002-rammap/RAMMap64.exe) [7z 文件](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v1.61.002-rammap/RAMMap64.7z) |
| [**Desktops**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/desktops) | v2.1(2021.10.12) | v2.1(2021.10.12) | v2.1.001 | [EXE 文件](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v2.1.001-desktops/Desktops64.exe) |
| [**Not My Fault**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/notmyfault) | v4.21(2022.9.29) | v4.21(2022.9.29) | v4.21.001 | [EXE 文件](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v4.21.001-notmyfault/notmyfault64.exe) |
| [**Autoruns**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/autoruns) | v14.11(2024.2.6) | v14.11(2024.2.6) | v14.11.001 | [EXE 文件](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v14.11.001-autoruns/Autoruns64.exe) |


## 已知问题

### Process Explorer

- [#1(v17.06.008)：Process Explorer 打开 Process Explorer 进程显示 ASLR 状态有误，其他进程没有此问题](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/1)
- [#2(v17.06.*)：强制完整性级别字符串 (`*** Mandatory Level`) 无法翻译](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/2)
- [#3(v17.06.*)：句柄类型无法翻译，类型描述翻译后不显示](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/3)

### WinObj

- [#4(v3.14.*)：翻译 Directory 字符串会导致对象目录无法正常显示](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/4)

### RAMMap

- [#11(v1.61.*)：MS936 编码导致预留空间不足，OK 无法翻译为“确定”](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/11)

### Not My Fault

- [#14(v4.21.*)（纠正策略，无需修复）：MS936 编码导致翻译空间不足，删除后一位后注册表原配置路径失效。](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/14)
