<h1 align="center">JimuChatBI（Chat2BI）</h1>

<p align="center">
  <b>对话式 AI 数据分析平台 —— 用一句话生成图表，从「问数据」到「出图表」端到端打通</b>
</p>

<p align="center">
  <a href="https://jeecg.com/chat2bi">官网</a> ·
  <a href="https://github.com/jeecgboot/JeecgBoot">JeecgBoot 主仓库</a> ·
  <a href="#快速开始">快速开始</a> ·
  <a href="#功能特性">功能特性</a>
</p>

---

## 简介

**JimuChatBI（Chat2BI / Chart2BI）** 是 [JeecgBoot](https://github.com/jeecgboot/JeecgBoot) 企业级 AI 低代码平台中的**对话式数据分析（AI BI）**模块。它让用户通过自然语言对话即可完成数据查询与可视化：智能体自动解析查询意图、连接数据源、生成分页表格、报表和图表配置，实现从 **「问数据」到「出图表」** 的端到端打通，无需手工拖拽配置。

> 一句话生成图表，让数据分析像聊天一样简单。

## 功能特性

### 🗣️ 自然语言生成图表
- 用户用自然语言描述分析需求，智能体自动解析并生成对应图表
- 支持「数据驱动」生成：直接输入数据即可智能分析出图
- 内置于 AI 应用平台，具备上下文感知的图表生成能力

### 📊 丰富的图表类型
支持多种可视化形式：

| 类型 | 说明 |
|------|------|
| 柱状图 | 单列 / 多列柱状图 |
| 折线图 | 单行 / 多行折线图 |
| 饼图 | 占比分析 |
| 折柱图 | 折线+柱状组合图 |
| 面积图 | 趋势填充展示 |
| 雷达图 | 多维度对比 |
| 仪表盘 | 指标监控 |

### 🔌 多数据源查询
- 系统中配置的**任意数据源**均可用于图表查询
- 不指定数据源时，默认使用系统数据库
- 与 Online 表单打通，一句话生成分页表格、报表与图表配置

### 🤖 AI 应用门户集成
作为 AI 应用门户的一部分，与以下智能体协同：
- Chat2BI 图表生成智能体
- AI 绘图智能体
- 图片描述 / 图片识别
- 写作助手

## 技术架构

JimuChatBI 构建于 JeecgBoot AI 生态之上：

- **大模型集成**：基于 **LangChain4j**，支持 **DeepSeek / ChatGPT** 等主流大模型一键切换
- **知识增强**：接入 **RAG（检索增强生成）** 知识库，提升分析准确性
- **底层平台**：依托 JeecgBoot（Spring Boot + Ant Design Vue + Mybatis-Plus）低代码能力
- **数据打通**：与 Online 表单、报表、图表配置无缝集成

## 快速开始

> ⚠️ 当前仓库为初始化状态，代码尚未发布。以下为通用接入方式，请以官方最新发布为准。

```bash
# 克隆仓库
git clone https://github.com/jeecgboot/JimuChatBI.git
cd JimuChatBI
```

JimuChatBI 作为 JeecgBoot AI 模块的一部分，建议先部署 JeecgBoot 主平台：

```bash
git clone https://github.com/jeecgboot/JeecgBoot.git
```

具体的环境要求、大模型配置（API Key、模型选择）、数据源接入步骤，请参考 [JeecgBoot 官方文档](https://help.jeecg.com)。

## 使用示例

在 AI 聊天界面中直接输入自然语言，例如：

```
帮我统计各部门今年的销售额，用柱状图展示
近三个月的用户增长趋势，画一张折线图
展示男女用户比例的饼图
```

智能体将自动解析意图 → 选择数据源 → 执行查询 → 生成对应图表。

## 相关链接

- 🌐 产品官网：<https://jeecg.com/chat2bi>
- 📦 JeecgBoot 主仓库：<https://github.com/jeecgboot/JeecgBoot>
- 📖 官方文档：<https://help.jeecg.com>

## 联系与支持

- QQ：69893005 / 418799587
- 微信（商务）：jeecg_winter
- 商务热线：010-64808099（5×8 小时）

## 许可证

本项目隶属于 JeecgBoot 生态，许可证以官方仓库声明为准。

---

<p align="center">由 JEECG 团队出品 · 让 AI 数据分析触手可及</p>
