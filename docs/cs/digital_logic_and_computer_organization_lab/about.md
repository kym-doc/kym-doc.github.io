# 数字逻辑与计算机组成原理实验

> 编写人：2024级 计算机科学与技术 罗嘉恒
>
> 上课学期：2025 秋季
>
> 教师：王玮，李婷
>
> 课程网站：https://nju-projectn.github.io/dlco-lecture-note/index.html

我在说明里标记的课程网站仅仅是一个通用的链接，但是实验的内容每年变化应该不算大，至少笔者当时做的实验和这个网站给出的是一致的。但是具体上课的时候，我们当时使用的是：http://114.212.10.241/。

## 课程简介

这门课能够提供给你非常好的理解硬件和软件协调的直觉。课程主要分为两个阶段，第一阶段主要用来熟悉 FPGA 板的使用，最后的任务是跑通 RV32 的指令集，通过虚拟实验；第二阶段是大实验，将第一阶段的内容组合起来搭建一个 RV32 的计算机系统，最终上机演示。

第一阶段内容包括且不限于：利用 FPGA 实现一个数字时钟，理解 VGA、PS/2 协议并且将 FPGA 板和显示器、键盘连接起来。

第二阶段时间靠近期末，要把之前做过的事情全部串接在一起，搭建硬件抽象，然后写软件与自己的硬件协同。

课程几乎不会**讲授**任何的知识（一个同学要入门这门课，首先需要学习 Verilog 基本语法和 Vivado 软件的使用），基本依赖自学和实验指南。但是王玮老师和李婷学姐会提供非常的仔细的指导和帮助。

## 考核方式

每周一次上板实验，并且有配套的 OJ 实验。如果前面实验按时验收，但不做最后的大实验，好像只能得到 80 分。

## 资源合集 

- Verilog 入门推荐（笔者当时花了一个下午就看完了，基本能够完全掌握 Verilog 语法）：https://hdlbits.01xz.net/wiki/Main_Page
- 笔者的实验报告：https://box.nju.edu.cn/d/6683b28cb53d4ac0a660/

!!! tip "老师在课程网站上挂出的讲解链接，可供选课/预习参考"

    实验零 Vivado入门分步骤演示 http://114.212.10.241/api/attachments/d2JKUElmY1ZGOXdWeGpRN3g1ZnRBZz09

    往届Vivado语法讲解视频（供参考） http://114.212.10.241/api/attachments/Yi81dm5VZ2M2a2NBUW5WT2c2QVdWUT09

    Vivado语法重点讲解视频 http://114.212.10.241/api/attachments/VHlIaEtFNVRTRHVOMVBiMW1uVzhpZz09

    习题课讲解(组合逻辑部分，2021年内容略有差异) http://114.212.10.241/api/attachments/WlFGQTRwbG1pWnNCdW5Gb0g4aTdDdz09

    习题课视频2（时序逻辑部分） http://114.212.10.241/api/attachments/d2RsTlpJOWF1MXlXZjFpU1lsTGRhQT09

    习题课视频3（键盘） http://114.212.10.241/api/attachments/ckNGOS9NNGVxVTN2OXdKZVlMRk13QT09

    习题课4 输入输出终端 http://114.212.10.241/api/attachments/bVZVQ3hMVXRWWWFabGRRQnBoTU5oZz09

    习题课5 单周期CPU设计 http://114.212.10.241/api/attachments/TXBxQVpiVTBVT1diWDBTV01PU0owZz09

    习题课6 计算机系统设计 http://114.212.10.241/api/attachments/cHRwQ3QwVXRxY2srSEs2cVA4ZFZCdz09

    往届第一次课讲解视频（仅供参考） http://114.212.10.241/api/attachments/R1NWa2Y3aTNOU1pNU2h6THRpMHBsQT09

    往届大实验演示视频1 http://114.212.10.241/api/attachments/U2kxWDdSbWxONXdIaFNWQXV0dlRMUT09
    
    往届大实验演示视频2 http://114.212.10.241/api/attachments/SzVYSmZnVEpRVVA4Z0ovcHN0dTA5UT09