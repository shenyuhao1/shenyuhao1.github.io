---
permalink: /
title: "关于我 / About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## 中文

你好，我是**沈俞豪**，信息与计算科学专业在校学生。

我对系统编程、AI 应用开发和工程实践有浓厚兴趣，喜欢动手把想法变成可以跑起来的东西。目前主要使用 Python、Rust 和 C 进行开发，涉及方向包括 AI 视频生成流水线、实时物理模拟、桌面工具开发等。

**技术栈：** Python · Rust · C · Manim · FFmpeg · TTS · Dify · NumPy · Tkinter · pytest · Git/GitHub Actions · SDL2 · TCP Socket · Win32 API

**联系方式：** [15658328056@163.com](mailto:15658328056@163.com)

---

## English

Hi, I'm **Shen Yuhao**, an undergraduate student majoring in Information and Computing Science.

I'm passionate about systems programming, AI application development, and hands-on engineering. I enjoy turning ideas into working software. My main languages are Python, Rust, and C — I've built projects ranging from AI video generation pipelines to real-time physics simulations and Win32 desktop tools.

**Tech Stack:** Python · Rust · C · Manim · FFmpeg · TTS · Dify · NumPy · Tkinter · pytest · Git/GitHub Actions · SDL2 · TCP Socket · Win32 API

**Contact:** [15658328056@163.com](mailto:15658328056@163.com)

---

## 项目 / Projects

### [AI 视频自动化生成流水线](https://github.com/shenyuhao1/ai-video-pipeline)
基于 Python 的端到端视频生成系统，集成 Dify 工作流编排、Manim 动画渲染、TTS 语音合成与 FFmpeg 视频合成。使用线性回归预测渲染耗时并自动调整画质参数，提供 GUI 与命令行双入口，配备 51 项单元测试与 GitHub Actions CI。

*End-to-end AI video generation pipeline integrating Dify, Manim, TTS, and FFmpeg. Features linear regression-based render-time prediction, dual GUI/CLI interface, 51 unit tests, and GitHub Actions CI.*

---

### [Rust 2D 刚体物理沙盒](https://github.com/shenyuhao1/physics_sandbox.rs)
用 Rust 实现的实时 2D 刚体物理模拟，支持 LAN 多人联机。服务端以 60Hz 运行物理引擎并通过 TCP 广播世界状态，客户端基于 SDL2 渲染，支持碰撞检测、弹性碰撞、轨迹可视化等。

*Real-time 2D rigid-body physics sandbox with LAN multiplayer written in Rust. Server runs physics at 60Hz over TCP; SDL2 client handles rendering and user input.*

---

### [C/Win32 模拟键盘输入工具](https://github.com/shenyuhao1/cc-project)
纯 C + Win32 API 桌面工具，通过 `SendInput + KEYEVENTF_UNICODE` 将文本逐字符模拟输入到任意窗口，完整支持中文与 Unicode，使用多线程隔离 UI 与输入任务。编译产物约 66KB，无外部依赖。

*A pure C + Win32 API desktop tool that simulates keyboard input character-by-character using SendInput, supporting Chinese and full Unicode. Multi-threaded UI/input isolation, ~66KB binary, zero external dependencies.*
