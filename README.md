# Haobo Wang's Paper Writing Skill (Not Official)

这是一个面向计算机科学研究论文的小型 Agent Skill，帮助作者把核心问题、方法的实际机制与支持主张的证据连接起来。适合处理引言循环论证、方法出现得突兀、benchmark 特点说不清楚、实验没有回应论文主线等问题。Skill 中保留了具体写作建议和自检问题，包括标题聚焦、主次贡献、前后呼应，以及 *fortunately*、*moreover* 和连接词使用比例的建议。

## 安装

告诉你的 Agent：

```text
安装 https://github.com/QMMMS/writing_skill/tree/main/wang-paper-logic 这个 skill。
```

## 使用

提供论文或章节，并说明希望检查什么。例如：

```text
请使用 $wang-paper-logic 检查我的引言和方法是否围绕同一个核心问题。找出“先有方案、再倒推问题”的表述，给出修改提纲。
```

```text
请使用 $wang-paper-logic 检查我的 benchmark 设计和实验，是否足以支持引言宣称的能力缺口。
```

写作建议按[核心主线](wang-paper-logic/references/storyline.md)、[章节写法](wang-paper-logic/references/sections.md)、[表达与检查](wang-paper-logic/references/style-and-checks.md)、[研究节奏与工作取舍](wang-paper-logic/references/workflow.md)、[论文示例](wang-paper-logic/references/writing-example.md)分类，便于查找和维护。[示例论文 PDF](writing_example.pdf)也在仓库中。

## 贡献

新增建议、修改现有分类或添加案例，请参阅[贡献指南](CONTRIBUTING.md)。
