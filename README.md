# CAMEL Agent Tutorial

> 目前教程还处于迭代中，可前往飞书文档进行学习; 有疑问和运行不通的地方欢迎在github提issue和在教程添加评论信息~

教程完整版在线阅读链接: https://fmhw1n4zpn.feishu.cn/docx/AF4XdOZpIo6TOaxzDK8cxInNnCe?from=from_copylink

教程速通版在线阅读链接: https://fmhw1n4zpn.feishu.cn/docx/U3PwdA2utoafCIxChmbcPymnngh?from=from_copylink

CAMEL-AI项目地址: https://github.com/camel-ai/camel

## 项目简介

- 课程说明：CAMEL 是最早的[基于 LLM 的多智能体框架](https://arxiv.org/pdf/2303.17760.pdf)，现在是一个通用框架，用于构建和使用基于 LLM 的智能体来解决实际任务。**camel-agent-tutorial** 是一套专为那些期望深入了解并实践多智能体系统的开发者设计的实用指南。本教程基于国内领先的多智能体框架 CAMEL-AI（NeruIPS'2023），从最基本的单个Agent开发，逐渐尝试构建复杂的Multi Agent应用。
- 面向人群：
  - 本项目侧重点在实践和动手构建Agent应用的层面，但会将理论部分结合。适于对多智能体系统、大模型应用或人工智能领域有研究兴趣、希望通过实践了解并探索LLM在多智能体系统中应用的同学。
  - 通过这个项目，我们希望帮助开发者：
    1. **理解基础**：掌握CAMEL框架的使用方法，理解Agent的基本概念，为后续的学习使用打下坚实的基础。
    2. **提升技能**：设置一系列实践项目，涉及(RAG,Memory,Multi Agent)等，逐步提高开发者在构建和管理智能体方面的技能。
    3. **应用实践**：鼓励开发者将所学知识应用于解决实际问题，培养他们的实践能力和创新思维。
  - 技术基础：
    - 适合拥有**Python编程基础**
    - 能**尝试阅读和理解项目源代码和理论**的学习者
  - 兴趣与动机：适合对AI智能体领域充满热情的学习者，特别是那些希望从代码层面对智能体进行个性化能力开发的小伙伴。我们的课程旨在帮助学习者将理论知识转化为实际应用。



## 目录


# CAMEL Multi-Agent Tutorial

- ## 第零章：序言
  - 0.1 加入我们
  - 0.2 如何贡献？

- ## 第一章：环境配置
  - 1.1 获取CAMEL
    - 1.1.1 通过 PyPI 安装
    - 1.1.2 通过源码安装
      - 1.1.2.1 使用Conda和Pip从源码安装
      - 1.1.2.2 使用Poetry工具从源码安装
  - 1.2 API设置
    - 1.2.1 获取API KEY
    - 1.2.2 使用API调用模型
  - 1.3 Hello CAMEL!
    - 1.3.1 尝试RolePlaying
    - 1.3.2 使用其他模型以及不同的输出语言
  - 1.4 第一章课程作业

- ## 第二章：Agent 的构成组件
  - 2.1 智能体概述
  - 2.2 Agent设计原则与方法
  - 2.3 Models
    - 2.3.1 目前支持的模型
    - 2.3.2 通过API调用模型
    - 2.3.3 使用开源模型
  - 2.4 Messages
    - 2.4.1 概述
    - 2.4.2 创建和使用Message
    - 2.4.3 不同类型消息的处理
    - 2.4.4 与ChatAgent协作
    - 2.4.5 Responses
    - 2.4.6 实践练习
  - 2.5 Prompt Engineering
    - 2.5.1 概述
    - 2.5.2 怎么写好提示词？
    - 2.5.3 上下文学习（ICL）
    - 2.5.4 思维链（CoT）
    - 2.5.5 CAMEL中的prompt
  - 2.6 Memory
  - 2.7 Tools
    - 2.7.1 工具说明
    - 2.7.2 动手实践
    - 2.7.3 进阶案例
  - 2.8 第二章课程作业

- ## 第三章：CAMEL框架简介及实践
  - 3.1 CAMEL框架简介
    - 3.1.1 Multiple Agent基本概念
    - 3.1.2 什么是CAMEL？
    - 3.1.3 ChatAgent 简介
    - 3.1.4 Role Playing机制
      - 3.1.4.1 基本概念
      - 3.1.4.2 经典案例：股票交易机器人详解
    - 3.1.5 Workforce 简介
  - 3.2 创建你的第一个Agent Society
    - 3.2.1 准备工作
    - 3.2.2 配置Role-Playing会话
  - 3.3 创建你的Workforce
    - 3.3.1 简单实践
    - 3.3.2 利用Workforce组建hackathon评审团
  - 3.4 第三章课程作业

- ## 第四章：CAMEL框架下的RAG应用
  - 4.1 RAG的组件介绍
    - 4.1.1 RAG简介
    - 4.1.2 Loaders
    - 4.1.3 Embeddings
    - 4.1.4 Storages
    - 4.1.5 Retrievers
  - 4.2 向量数据库介绍
  - 4.3 搭建知识库
    - 4.3.1 Embedding模型选择
    - 4.3.2 数据预处理
  - 4.4 构建RAG应用
    - 4.4.1 Basic RAG
    - 4.4.2 Rewriting
    - 4.4.3 Rerank
    - 4.4.4 进阶案例
  - 4.5 RAG应用的评估
  - 4.6 Graph RAG应用实战
    - 4.6.1 Graph RAG以及与传统RAG的优劣
    - 4.6.2 图数据库介绍
    - 4.6.3 构建三元组并上传图数据库
    - 4.6.4 实践案例
    - 4.6.5 进阶案例

- ## 第五章：综合案例
  - 5.1 应用概览
    - 5.1.1 目标和交互形式
    - 5.1.2 模块化设计
      - 5.1.2.1 信息收集模块
      - 5.1.2.2 攻略生成模块
      - 5.1.2.3 反馈优化模块
  - 5.2 用户意图识别模块
  - 5.3 旅游信息检索
  - 5.4 攻略生成模块
  - 5.5 反馈优化模块
  - 5.6 搭配知识集用
    - UI在线交互模块
    - 个人信息输入模块
    - 模型选择
  - 5.7 CAMEL的特色功能——数据合成

- ## 附录
  - 支持的模型

- ## 结语
  - 关注我们





## Roadmap

- [x] 发布第一版内容内测
- [ ] 发布第一版内容公测
- [ ] 飞书内容迁移仓库
- [ ] 更新案例源代码文件
- [ ] 补充更多实例和新特性讲解。


## 参与贡献

- 如果你想参与到项目中来欢迎查看项目的 [Issue](https://github.com/datawhalechina/camel-agent-tutorial/issues) 查看没有被分配的任务。
- 如果你发现了一些问题，欢迎在 [Issue](https://github.com/datawhalechina/camel-agent-tutorial/issues) 中进行反馈🐛。
- 如果你对本项目感兴趣想要参与进来可以通过 [Discussion]() 进行交流💬
- 如果有任何想法可以联系我们 DataWhale&CAMEL 社区开发者，也欢迎大家多多提出 issue
- 特别感谢以下为教程做出贡献的同学！



## 贡献者名单

**核心贡献者**
- [陈思州-项目负责人](https://github.com/jjyaoao) (Datawhale成员-CAMEL-AI成员)
- [孙韬-项目负责人](https://github.com/fengju0213) (Datawhale意向成员-湖南大学研究生)
- [姜舒凡-核心贡献者](https://github.com/Tsumugii24) (Datawhale成员-华东理工大学本科生)
- [范文栋-核心贡献者](https://github.com/Wendong-Fan) (CAMEL-AI成员-算法工程师)

**主要贡献者**
- [李川-内容创作者](https://github.com/MrLIChuan) (CAMEL-AI成员-索邦大学/巴黎理工学院 博士/助教)
- [小川-内容创作者](https://github.com/) (CAMEL-AI宣传大使)
- [豆腐酱-内容创作者](https://github.com/Tofu0142) (CAMEL-AI宣传大使)
- [王小为-内容创作者](https://github.com/cswangxiaowei) (小米NLP算法工程师)
- [任信行-内容创作者](https://github.com/renxinxing123) (CAMEL-AI宣传大使)
- [陆崇喜-内容创作者](https://github.com/Lucas-CX) (软件工程师)
- [邢硕-内容创作者](https://github.com/Susan2048) (Datawhale意向成员)
- [康婧淇-内容创作者](jkan0031@student.monash.edu) (Datawhale成员)


特别感谢[@Sm1les](https://github.com/Sm1les)对项目的帮助和支持~

## 关注我们

<div align="center">
  <div style="display: inline-block; text-align: center; margin: 10px;">
    <p>扫描下方二维码关注公众号：Datawhale</p>
    <img src="https://raw.githubusercontent.com/datawhalechina/pumpkin-book/master/res/qrcode.jpeg" width="180" height="180">
  </div>
  <div style="display: inline-block; text-align: center; margin: 10px;">
    <p>扫描下方二维码关注公众号：CAMEL-AI</p>
    <img src="images/CAMEL-AI.png" width="180" height="180">
  </div>
</div>


## LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。

*注：默认使用CC 4.0协议，也可根据自身项目情况选用其他协议*
