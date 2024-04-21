# CAMEL Agent Tutorial

## 项目简介

- 课程说明：CAMEL 是最早的[基于 LLM 的多智能体框架](https://arxiv.org/pdf/2303.17760.pdf)，现在是一个通用框架，用于构建和使用基于 LLM 的智能体来解决实际任务。**camel-agent-tutorial** 是一套专为那些期望深入了解并实践多智能体系统的开发者设计的实用指南。本教程基于国内领先的多智能体框架 CAMEL-AI（NeruIPS'2023），从最基本的单个Agent开发，逐渐尝试构建复杂的Multi Agent应用。
- 面向人群：
  - 本项目侧重点在实践和动手构建Agent应用的层面，但会将理论部分结合。适于对多智能体系统、大模型应用或人工智能领域有研究兴趣、希望通过实践了解并探索LLM在多智能体系统中应用的同学。
  - 通过这个项目，我们希望帮助开发者：
    1. **理解基础**：掌握CAMEL框架的使用方法，理解Agent的基本概念，为后续的学习使用打下坚实的基础。
    2. **提升技能**：设置一系列实践项目，涉及(RAG,Memory,Multi Agent)等，逐步提高开发者在构建和管理智能体方面的技能。
    3. **应用实践**：鼓励开发者将所学知识应用于解决实际问题，培养他们的实践能力和创新思维。
  - 技术基础：
    - XXXX
    - 适合拥有**Python编程基础**
    - 能**尝试阅读和理解项目源代码和理论**的学习者
  - 兴趣与动机：适合对AI智能体领域充满热情的学习者，特别是那些希望从代码层面对智能体进行个性化能力开发的人。我们的课程旨在帮助学习者将理论知识转化为实际应用。

项目在线教程：https://fmhw1n4zpn.feishu.cn/docx/AF4XdOZpIo6TOaxzDK8cxInNnCe?from=from_copylink

CAMEL:https://github.com/camel-ai/camel

## 目录（暂定）

**第一章：环境配置**

**1.1 安装准备**

> - **通过 PyPI 安装**
> - **通过 Conda 和 Pip 从源代码安装**

**1.2 API 课程**

> **1.2.1 使用 OpenAI API**
>
> > - **1.2.1.1 获取 OpenAI API**
> > - **1.2.1.2 适 Unix 系统 (Linux / MacOS)**
> > - **1.2.1.3 Windows**
>
> **1.2.2 使用本地模型**
>
> > - **本地模型的配置与使用**
>
> - **1.3 快速开始**

**第二章：Agent与CAMEL框架简介**

**2.1 框架概述**

> - **Agent设计原则与方法**
> - **CAMEL框架基础**
> - **Role Playing介绍**

**第三章：CAMEL框架的构成组件**

**3.1 Hello CAMEL**

> - **3.2 Models**
> - **3.3 Data Connection**
>
> > - **3.3.1 用户数据的存储，加载，向量化，检索**
> > - **3.3.2 进阶RAG框架的实现**
>
> - **3.4 Prompts**
> - **3.5 Memory**
> - **3.6 Callbacks**
>
> **3.7 Agents**
>
> > - **3.7.1 Single-Agent的实现**
> > - **3.7.2 Multi-Agent的实现**
>
> - **3.8 Advanced Topics**
>
> > - **3.8.1 Callbacks**
> > - **3.8.2 Messages**
> > - **3.8.3 Responses**

**第四章：CAMEL框架下的多智能体协同**

**4.1 创建你的第一个Agent Society**

> - **4.2 CAMEL.AI多Agent系统介绍**
> - **4.3 模块一：任务驱动**
> - **4.4 模块二：动态环境/缓存维护**
> - **4.5 多智能体系统中的角色扮演**
> - **4.6 用户界面和演示**




## Roadmap

- [ ] 发布第一版内容内测
- [ ] 发布第一版内容公测
- [ ] 飞书内容迁移仓库
- [ ] 更新案例源代码文件
- [ ] 补充更多实例和新特性讲解。


## 参与贡献

- 如果你想参与到项目中来欢迎查看项目的 [Issue]() 查看没有被分配的任务。
- 如果你发现了一些问题，欢迎在 [Issue]() 中进行反馈🐛。
- 如果你对本项目感兴趣想要参与进来可以通过 [Discussion]() 进行交流💬
- 如果有任何想法可以联系我们 DataWhale&CAMEL 社区开发者，也欢迎大家多多提出 issue
- 特别感谢以下为教程做出贡献的同学！



## 贡献者名单

| 姓名   | 职责       | 简介                     |
| :----- | :--------- | :----------------------- |
| 陈思州 | 项目负责人 | Datawhale成员、CAMEL成员 |
| 姜舒凡 | 核心贡献者 | Datawhale意向成员        |
| 葉子瑜 | 核心贡献者 | CAMEL成员                |
| 范文栋 | 核心贡献者 | CAMEL成员                |
| 潘笃驿 | 核心贡献者 | Datawhale成员、CAMEL成员 |
| 杨子熠 | 核心贡献者 | CAMEL成员                |
| xxx    | 贡献者     |                          |
| xxx    | 贡献者     |                          |

特别感谢[@Sm1les](https://github.com/Sm1les)对项目的帮助和支持~

## 关注我们

<div align=center>
<p>扫描下方二维码关注公众号：Datawhale</p>
<img src="https://raw.githubusercontent.com/datawhalechina/pumpkin-book/master/res/qrcode.jpeg" width = "180" height = "180">
</div>

<div align=center>
<p>扫描下方二维码关注公众号：CAMEL-AI</p>
<img src="images/CAMEL-AI.png" width = "180" height = "180">
</div>

## LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。

*注：默认使用CC 4.0协议，也可根据自身项目情况选用其他协议*
