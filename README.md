# 🔍 Emoji Finder

> 文字描述 → Emoji 表情匹配 | Hermes Agent Skill

根据中文/英文文字描述，智能匹配最合适的 emoji 表情符号。支持语义理解、多候选项、组合 emoji。

## 安装

### 通过 Hermes Skills Hub

```bash
hermes skills install sunailian/hermes-emoji-finder
```

### 手动安装

```bash
git clone https://github.com/sunailian/hermes-emoji-finder.git ~/.hermes/skills/emoji-finder
```

## 使用

在 Hermes Agent 对话中，自然语言描述你想要表达的情绪、场景或概念：

```
帮我给这段话配个emoji：支持多版本管理
```

```
有没有表示"在线调试"的emoji？
```

```
我想表达"周五下班前删掉300行无用代码的爽感"，用什么emoji？
```

## 特性

- 🧠 **语义理解**：不只匹配字面，理解意图和语气
- 🎯 **多候选项**：提供 2-3 个备选，标注适用场景
- 🔗 **组合 emoji**：复杂概念自动给出最佳组合
- 🇨🇳 **中文友好**：深度支持中文描述的语义解析
- 📋 **速查表**：内置情绪、技术、思维、动作四大类映射

## 效果示例

| 输入 | 输出 |
|------|------|
| 支持多版本管理 | 🔀🏷️ — 切换 + 标签 |
| 支持在线调试 | 🐛🌐 — 捉虫 + 在线 |
| 独立沙箱执行 | 📦🔒 — 封闭容器 + 权限锁定 |

## 许可

MIT © 灼沅
