# Sysinternals Tools Chinese
一些 Sysinternals 工具的汉化版（自己使用 [wxMEdit](https://github.com/wxMEdit/wxMEdit) 和 [Resource Hacker](https://www.angusj.com/resourcehacker/) 修改，未加壳）

仅提供 64 位版本，x86_32 和 ARM 不提供。 

## 下载链接

点击应用名称跳转至微软产品页面跟踪最新版本信息。

- [**Process Explorer**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/process-explorer)：https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v17.06.006-procexp/procexp64.exe
- [**WinObj**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/winobj)：https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v3.14.003-winobj/Winobj64.exe
- [**Process Monitor**](https://learn.microsoft.com/zh-cn/sysinternals/downloads/procmon)：~~https://github.com/Anonymous220623/sysinternals-tools-chinese/releases/download/v4.01.006-procmon/Procmon64.exe~~ 

## 已知问题

### Process Explorer

- [#1：Process Explorer 打开 Process Explorer 进程显示 ASLR 状态有误，其他进程没有此问题](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/1)
- [#2：强制完整性级别字符串 (`*** Mandatory Level`) 无法翻译](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/2)
- [#3：句柄类型无法翻译，类型描述翻译后不显示](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/3)

### WinObj

- [#4：翻译 Directory 字符串会导致对象目录无法正常显示](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/4)

### Process Monitor

- [**#10（严重）：选择列失败**](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/10)
- [#7：详细信息列翻译导致与原来 Process Monitor 进程信息数据库的兼容性问题](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/7)
- [#8：翻译“备份文件”中的 “Name” 会导致详细信息页面中的注册表查询值更改为“名称”](https://github.com/Anonymous220623/sysinternals-tools-chinese/issues/8)
