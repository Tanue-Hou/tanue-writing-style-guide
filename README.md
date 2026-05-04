# Tanue Technical Narrative Writing Skills

[中文见下](#chinese)

Two [Claude](https://claude.ai) skills distilled from @Tanue's long-form Chinese writing style — engineering history, accident analysis, biography tribute, and personal narrative. The complete style guide and usage rules live inside each skill's `SKILL.md`.

| Skill | What it does | Command |
|-------|-------------|---------|
| `tanue-writing-from-scratch` | Generate articles from scratch in Tanue's style | `/tanue-writing-from-scratch` |
| `tanue-writing-style` | Rewrite existing drafts into Tanue's style | `/tanue-writing-style` |

### Get the files

```
git clone https://github.com/Tanue-Hou/tanue-writing-style-guide.git
cd tanue-writing-style-guide
```

The skills live in `skills/{name}/SKILL.md`.

### Install

Open Claude → Skills → Install Skill / Install from File → select `skills/{name}/SKILL.md`.

### Usage Examples

**Write a technical history article:**
```
请用 Tanue Technical Narrative Writing Skill 写一篇关于[主题]的技术史长文，成熟科普风。
```

**Rewrite an existing draft:**
```
请用 Tanue Writing Style 改写下面这篇文章，成熟科普风。
[粘贴原文]
```

**Prompt templates** and detailed rules → `skills/{name}/SKILL.md`.

### Core Philosophy

- Put technology back in its era
- Write accidents as causal chains, not single-cause blame
- Translate every parameter into meaning
- Restrained closure — earn the emotion

---

<a name="chinese"></a>

## 中文

两个可安装的 Claude Skill，源于 @Tanue（后天雨）的中文技术史叙事写作风格。详细规则和用法在各 Skill 的 `SKILL.md` 中，此处只列概要和安装方式。

| Skill | 用途 | 命令 |
|-------|------|------|
| `tanue-writing-from-scratch` | 从零生成技术史/事故复盘/人物致敬/个人叙事类长文 | `/tanue-writing-from-scratch` |
| `tanue-writing-style` | 将已有中文草稿改写为 Tanue 风格 | `/tanue-writing-style` |

### 获取文件

```
git clone https://github.com/Tanue-Hou/tanue-writing-style-guide.git
```

Skill 文件在 `skills/{name}/SKILL.md`。

### 安装

Claude 桌面端 → Skills → Install Skill / Install from File → 选择 `skills/{name}/SKILL.md`。

### 快速上手

**生成文章：**
```
请用 Tanue Technical Narrative Writing Skill 写一篇关于[主题]的技术史长文，成熟科普风。
```

**改写文章：**
```
请用 Tanue Writing Style 改写下面这篇文章，成熟科普风。
[粘贴原文]
```

**完整 Prompt 模板和规则参数** → 见 `skills/{name}/SKILL.md`。

### 核心四句话

- 把技术对象放回时代里
- 把事故写成因果链
- 把参数翻译成意义
- 克制收束，不空喊口号
