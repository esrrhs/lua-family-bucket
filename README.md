# Lua全家桶 / Lua Family Bucket

> 精选且实用的 Lua 开源工具链全家桶（绑定、调试、性能分析、优化与监控）
> A curated collection of essential Lua tools and libraries (binding, debugging, profiling, optimization, and monitoring).

---

## 选型表 / Selection Guide

按需求选择工具；各项目的简要说明见下方列表。
Pick a tool by need. Short descriptions of each project are in the list below.

| 需求场景 / Scenario | 工具 / Tool | 用途或选型提醒 / Purpose / tip |
| --- | --- | --- |
| 把 Lua 与 C++ 绑定 / Bind Lua and C++ | [bLua](https://github.com/esrrhs/bLua) | Lua 与 C++ 绑定库 / Lua and C++ binding library |
| 统计代码覆盖率 / Measure code coverage | [cLua](https://github.com/esrrhs/cLua) | Lua 代码覆盖率统计工具 / Lua code coverage tool |
| 调试 Lua 程序 / Debug Lua programs | [dLua](https://github.com/esrrhs/dLua) | Lua 调试器 / Lua debugger |
| 计算 diff 与 patch / Compute diffs and patches | [fLua](https://github.com/esrrhs/fLua) | Lua 计算 diff 和 patch 工具 / Lua diff and patch tool |
| 优化或分析内存 / Optimize or analyze memory | [mLua](https://github.com/esrrhs/mLua) | Lua 内存优化与分析工具 / Lua memory optimization and analysis tool |
| 优化字节码 / Optimize bytecode | [oLua](https://github.com/esrrhs/oLua) | Lua 字节码优化工具 / Lua optimizer |
| 分析程序性能热点 / Profile program performance | [pLua](https://github.com/esrrhs/pLua) | Lua 性能分析工具 (Profiler) / Lua performance profiler |
| 分析虚拟机内部性能与指令 / Analyze VM internals and instructions | [vLua](https://github.com/esrrhs/vLua) | Lua 虚拟机内部性能与指令分析 / Lua VM profiler and analysis tool |
| 监控运行时状态与指标 / Watch runtime state and metrics | [wLua](https://github.com/esrrhs/wLua) | Lua 状态与指标监控工具 / Lua state and metrics watcher/monitor |

**如何区分 pLua / vLua，以及 mLua / wLua**

- **pLua** 与 **vLua**：pLua 面向 Lua 程序的性能分析（Profiler）。vLua 面向虚拟机内部性能与指令分析，可将选定 Lua VM C 函数的 CPU 耗时归因到 Lua 源码行。
- **mLua** 与 **wLua**：mLua 用于内存优化与分析。wLua 用于监控运行中的 Lua 状态与指标（watcher/monitor）。

**How to tell pLua / vLua and mLua / wLua apart**

- **pLua** vs **vLua**: pLua is a performance profiler for Lua programs. vLua profiles and analyzes Lua VM internals and instructions, attributing CPU time in a chosen Lua VM C function back to Lua source lines.
- **mLua** vs **wLua**: mLua is for memory optimization and analysis. wLua watches and monitors a running Lua state's metrics.

---

### [bLua](https://github.com/esrrhs/bLua)
- **中文**: Lua 与 C++ 绑定库
- **English**: Lua and C++ binding library

### [cLua](https://github.com/esrrhs/cLua)
- **中文**: Lua 代码覆盖率统计工具
- **English**: Lua code coverage tool

### [dLua](https://github.com/esrrhs/dLua)
- **中文**: Lua 调试器
- **English**: Lua debugger

### [fLua](https://github.com/esrrhs/fLua)
- **中文**: Lua 计算 diff 和 patch 工具
- **English**: Lua diff and patch tool

### [mLua](https://github.com/esrrhs/mLua)
- **中文**: Lua 内存优化与分析工具
- **English**: Lua memory optimization and analysis tool

### [oLua](https://github.com/esrrhs/oLua)
- **中文**: Lua 字节码优化工具
- **English**: Lua optimizer

### [pLua](https://github.com/esrrhs/pLua)
- **中文**: Lua 性能分析工具 (Profiler)
- **English**: Lua performance profiler

### [vLua](https://github.com/esrrhs/vLua)
- **中文**: Lua 虚拟机内部性能与指令分析
- **English**: Lua VM profiler and analysis tool

### [wLua](https://github.com/esrrhs/wLua)
- **中文**: Lua 状态与指标监控工具
- **English**: Lua state and metrics watcher/monitor
