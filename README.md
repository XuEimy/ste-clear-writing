# ste-clear-writing｜清楚表达与文案

让读者直接理解文字的意思，少花时间猜模型在说什么。

这是一份面向 AI Agent 的中文 Skill，借鉴 ASD-STE100 的清晰表达原则。凡涉及文案都适用：标题、按钮、提示语、界面、网页、宣传、社交内容、邮件、说明和研究表述。文案只是设计或开发任务的一部分时，也适用。

## 写作规则

- 写清主体、动作和对象。
- 一句围绕一个主题，明确条件、原因和结果。
- 同一概念固定叫法。
- 用具体过程说明抽象判断。
- 先给答案，再补必要依据。
- 保留原意、必要细节与不确定性，不补造事实。

短文案应让人看懂动作、状态或价值，不必写成完整句。品牌文案可以保留语气和风格。

## 安装到 Codex

将仓库克隆到本机 Skills 目录：

```sh
git clone https://github.com/XuEimy/ste-clear-writing.git ~/.codex/skills/ste-clear-writing
```

如果该目录已经存在，请先检查其中的文件，避免覆盖自己的修改。在能够发现本机 Skills 的 Codex 会话中使用。

## 使用

显式调用：

```text
使用 $ste-clear-writing 改写这段文字，让读者直接理解具体意思，并保留原意与不确定性。
```

Skill 允许自动选用。具体触发方式取决于宿主如何加载 Skills。

## 文件

- [SKILL.md](SKILL.md)：适用范围、表达规则、使用方法和示例。
- [agents/openai.yaml](agents/openai.yaml)：Codex 显示信息和自动选用配置。

## 参考与边界

本 Skill 是中文适配规则，不是 ASD-STE100 官方标准、完整翻译或合规检查工具。涉及英语标准合规时，应核对 [ASD-STE100 官方规范](https://www.asd-ste100.org/assets/files/ASD-STE100_ISSUE9.pdf)。
