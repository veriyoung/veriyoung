## Hi there 👋

<!--
**veriyoung/veriyoung** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# whoami
focus on test.
![TryHackMe Profile](https://tryhackme-badges.s3.amazonaws.com/VeryYoung.png)

# eBPF 编程 28 天学习计划打卡表

> 适用于只懂一点 Java 的测试工程师，每天仅需投入 10 分钟。

## 🗓️ 学习计划概览

| 周数 | 主题 | 目标 |
|------|------|------|
| 第 1 周 | eBPF 入门与基础概念 | 理解 eBPF 是什么、核心术语、工具链安装和第一个程序 |
| 第 2 周 | 可观测性应用 | 掌握 tracepoint/kprobe、map 使用方式、Python 控制 eBPF |
| 第 3 周 | 网络与性能分析 | 学会使用 XDP/TC、libbpf-bootstrap、CO-RE、TCP 性能追踪 |
| 第 4 周 | 进阶与实践结合 | 探索 Go/eBPF、安全性限制、自动化测试辅助、构建自己的工具 |

## 📅 每日学习打卡表

### 第 1 周：eBPF 入门与基础概念

| 日期 | 学习内容 | 是否完成 ✅ | 笔记或疑问 |
|------|----------|-------------|--------------|
| Day 1 | [了解 eBPF 是什么](https://ebpf.io/what-is-ebpf/) | ❏ |  |
| Day 2 | 学习核心术语（bpf(), libbpf, map, program） | ❏ |  |
| Day 3 | 安装 eBPF 工具链（clang, llvm, libbpf-dev） | ❏ |  |
| Day 4 | 运行第一个 eBPF 程序（BCC 或 libbpf 示例） | ❏ |  |
| Day 5 | 理解 eBPF 程序结构（用户态 vs 内核态） | ❏ |  |
| Day 6 | 使用 BCC 工具快速上手（execsnoop, biolatency） | ❏ |  |
| Day 7 | 总结一周内容 + 提问复盘 | ❏ |  |

### 第 2 周：eBPF 在可观测性中的应用

| 日期 | 学习内容 | 是否完成 ✅ | 笔记或疑问 |
|------|----------|-------------|--------------|
| Day 8 | 跟踪 execve() 系统调用 | ❏ |  |
| Day 9 | 使用 perf 工具配合 eBPF | ❏ |  |
| Day 10 | 学习 eBPF maps 的使用方式 | ❏ |  |
| Day 11 | 使用 Python 脚本控制 eBPF 程序 | ❏ |  |
| Day 12 | tracepoint 和 kprobe 区别 | ❏ |  |
| Day 13 | eBPF 与容器监控的关系 | ❏ |  |
| Day 14 | 总结本周内容 + 练习写简单程序 | ❏ |  |

### 第 3 周：eBPF 在网络和性能分析中的实战

| 日期 | 学习内容 | 是否完成 ✅ | 笔记或疑问 |
|------|----------|-------------|--------------|
| Day 15 | XDP 和 TC 实现网络过滤 | ❏ |  |
| Day 16 | 使用 libbpf-bootstrap 快速开发 | ❏ |  |
| Day 17 | CO-RE 机制详解 | ❏ |  |
| Day 18 | 使用 CO-RE 编写跨平台程序 | ❏ |  |
| Day 19 | eBPF 对 TCP 性能分析的支持 | ❏ |  |
| Day 20 | eBPF 与 Tracepoint 的关系 | ❏ |  |
| Day 21 | 总结本周内容 + 小练习 | ❏ |  |

### 第 4 周：进阶与实践结合

| 日期 | 学习内容 | 是否完成 ✅ | 笔记或疑问 |
|------|----------|-------------|--------------|
| Day 22 | 使用 eBPF 的 Go 支持库（cilium/ebpf） | ❏ |  |
| Day 23 | eBPF 程序的安全性和限制 | ❏ |  |
| Day 24 | eBPF 辅助自动化测试的设想 | ❏ |  |
| Day 25 | eBPF Map 类型及其用途 | ❏ |  |
| Day 26 | 字符串处理技巧 | ❏ |  |
| Day 27 | 构建自己的 eBPF 工具 | ❏ |  |
| Day 28 | 总结整个月的学习成果 | ❏ |  |

## 📝 使用说明

- 每天学习完成后勾选 ☑️
- 可在“笔记或疑问”栏中记录你的思考或问题
- 建议每周总结一次，回顾掌握的内容

## 🧠 补充资源推荐

- [The eBPF Guide](https://qmonnet.github.io/ebpf-guide/)
- [BCC Tools GitHub](https://github.com/iovisor/bcc)
- [libbpf-bootstrap GitHub](https://github.com/libbpf/libbpf-bootstrap)
- [Cilium Blog - eBPF](https://isovalent.com/blog)

资源	描述
The eBPF Guide	图文并茂的 eBPF 教程
BCC Tools	实战级 eBPF 工具集合
libbpf-bootstrap	最小可运行 eBPF 项目模板
Cilium Blog - eBPF	eBPF 在生产中的落地案例
 小贴士
不要求每天写完整程序，只需理解原理 + 看懂代码即可。
可以使用 Docker 搭建一个支持 eBPF 的实验环境。
如果你是 Java 开发者，可以思考未来如何结合 eBPF 做 JVM 层面的性能追踪
