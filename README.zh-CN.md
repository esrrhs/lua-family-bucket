# Lua全家桶

[English](README.md) | [简体中文](README.zh-CN.md)

> 精选且实用的 Lua 开源工具链全家桶（绑定、调试、性能分析、优化与监控）

---

## 选型表

按需求选择工具；各项目的简要说明见下方列表。

| 需求场景 | 工具 | 用途或选型提醒 |
| --- | --- | --- |
| 把 Lua 与 C++ 绑定 | [bLua](https://github.com/esrrhs/bLua) | Lua 与 C++ 绑定库 |
| 统计代码覆盖率 | [cLua](https://github.com/esrrhs/cLua) | Lua 代码覆盖率统计工具 |
| 调试 Lua 程序 | [dLua](https://github.com/esrrhs/dLua) | Lua 调试器 |
| 计算 diff 与 patch | [fLua](https://github.com/esrrhs/fLua) | Lua 计算 diff 和 patch 工具 |
| 优化或分析内存 | [mLua](https://github.com/esrrhs/mLua) | Lua 内存优化与分析工具 |
| 优化字节码 | [oLua](https://github.com/esrrhs/oLua) | Lua 字节码优化工具 |
| 分析程序性能热点 | [pLua](https://github.com/esrrhs/pLua) | Lua 性能分析工具 (Profiler) |
| 分析虚拟机内部性能与指令 | [vLua](https://github.com/esrrhs/vLua) | Lua 虚拟机内部性能与指令分析 |
| 监控运行时状态与指标 | [wLua](https://github.com/esrrhs/wLua) | Lua 状态与指标监控工具 |

**如何区分 pLua / vLua，以及 mLua / wLua**

- **pLua** 与 **vLua**：pLua 面向 Lua 程序的性能分析（Profiler）。vLua 面向虚拟机内部性能与指令分析，可将选定 Lua VM C 函数的 CPU 耗时归因到 Lua 源码行。
- **mLua** 与 **wLua**：mLua 用于内存优化与分析。wLua 用于监控运行中的 Lua 状态与指标（watcher/monitor）。

---

### [bLua](https://github.com/esrrhs/bLua)
- Lua 与 C++ 绑定库

### [cLua](https://github.com/esrrhs/cLua)
- Lua 代码覆盖率统计工具

### [dLua](https://github.com/esrrhs/dLua)
- Lua 调试器

### [fLua](https://github.com/esrrhs/fLua)
- Lua 计算 diff 和 patch 工具

### [mLua](https://github.com/esrrhs/mLua)
- Lua 内存优化与分析工具

### [oLua](https://github.com/esrrhs/oLua)
- Lua 字节码优化工具

### [pLua](https://github.com/esrrhs/pLua)
- Lua 性能分析工具 (Profiler)

### [vLua](https://github.com/esrrhs/vLua)
- Lua 虚拟机内部性能与指令分析

### [wLua](https://github.com/esrrhs/wLua)
- Lua 状态与指标监控工具
