> [!WARNING]
>
> 本项目不再更新和维护。

# Sysinternals Tools Chinese
一些 Sysinternals 工具的汉化版（自己使用 [wxMEdit](https://github.com/wxMEdit/wxMEdit) 和 [Resource Hacker](https://www.angusj.com/resourcehacker/) 修改，未加壳）

仅提供 64 位版本，x86_32 和 ARM 不提供。 

## 下载链接

点击应用名称跳转至微软产品页面跟踪最新版本信息。

| 应用名称 | 已汉化版本 | 最新版本 | Patch 版本号 | 下载链接 | 
|--|--|--|--|--|
| [**Process Explorer**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/process-explorer) | v17.06(2024.??.??) | **v17.07(2025.11.11)** | v17.06.006 | [https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v17.06.006-procexp/procexp64.exe](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v17.06.006-procexp/procexp64.exe) |
| [**WinObj**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/winobj) | v3.14(2022.1.27) | v3.14(2022.1.27) | v3.14.003 | [https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v3.14.003-winobj/Winobj64.exe](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v3.14.003-winobj/Winobj64.exe) |
| [**RAMMap**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/rammap) | v1.61(2022.5.11) | v1.61(2022.5.11) | v1.61.001 | [https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v1.61.002-rammap/RAMMap64.exe](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v1.61.002-rammap/RAMMap64.exe) |
| [**Process Monitor**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/procmon) | v4.01(2024.6.20) | v4.01(2024.6.20) | v4.01.006 | [https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v4.01.006-procmon/Procmon64.exe](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v4.01.006-procmon/Procmon64.exe)（该 Patch 存在影响正常使用的问题 [https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/10](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/10)） |
| [**Desktops**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/desktops) | v2.1(2021.10.12) | v2.1(2021.10.12) | v2.1.001 | [https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v2.1.001-desktops/Desktops64.exe](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v2.1.001-desktops/Desktops64.exe) |
| [**Not My Fault**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/notmyfault) | v4.21(2022.9.29) | v4.21(2022.9.29) | v4.21.001 | [https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v4.21.001-notmyfault/notmyfault64.exe](https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v4.21.001-notmyfault/notmyfault64.exe) |

## 已知问题

### Process Explorer

- [#1(v17.06.006)：Process Explorer 打开 Process Explorer 进程显示 ASLR 状态有误，其他进程没有此问题](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/1)
- [#2(v17.06.*)：强制完整性级别字符串 (`*** Mandatory Level`) 无法翻译](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/2)
- [#3(v17.06.*)：句柄类型无法翻译，类型描述翻译后不显示](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/3)

### WinObj

- [#4(v3.14.*)：翻译 Directory 字符串会导致对象目录无法正常显示](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/4)

### Process Monitor

- [**#10(v4.01.006)（严重）：选择列失败**](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/10)
- [#7(v4.01.006)：详细信息列翻译导致与原来 Process Monitor 进程信息数据库的兼容性问题](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/7)
- [#8(v4.01.006)：翻译“备份文件”中的 “Name” 会导致详细信息页面中的注册表查询值更改为“名称”](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/8)

### RAMMap

- [#11(v1.61.*)：MS936 编码导致预留空间不足，OK 无法翻译为“确定”](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/11)

### Not My Fault

- [#14(v4.21.*)（纠正策略，无需修复）：MS936 编码导致翻译空间不足，删除后一位后注册表原配置路径失效。](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/14)
