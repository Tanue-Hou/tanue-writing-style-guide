# Tanue 技术史叙事写作 Skill 集

[Eng](#english) · [中文](#chinese)

---

<a name="english"></a>

## English

Two installable [Claude](https://claude.ai) skills distilled from @Tanue's long-form Chinese technical narrative writing style. The skills package Tanue's approach—engineering history storytelling, causal-chain accident analysis, parameter-to-meaning translation, authorial presence, and restrained emotional closure—into executable rules, templates, style guides, and generation workflows.

### Skills

This repository contains two skills under `skills/`:

| Skill | Mode | File | Size | What it does |
|-------|------|------|------|-------------|
| `tanue-writing-from-scratch` | **Generate** | `skills/tanue-writing-from-scratch/SKILL.md` | ~788 lines | Generate long-form Chinese articles from scratch in Tanue's style: technical history, accident analysis, biography tributes, personal narratives |
| `tanue-writing-style` | **Rewrite** | `skills/tanue-writing-style/SKILL.md` | ~437 lines | Rewrite existing Chinese drafts into Tanue's style: tone transformation, structural refinement, language de-AI-ification |

### Quick Start

#### Option A: Install via `.skill` file

1. Download the `.skill` file you want (from [Releases](../../releases) or build it yourself).
2. Open Claude desktop app → click the Skills button → "Install Skill" → select the `.skill` file.

#### Option B: Manual install

1. Open Claude desktop app.
2. Click the Skills button → "Install from File".
3. Navigate to this repo's `skills/` directory and select the SKILL.md you want.

#### Option C: Use the slash menu

If installed, type `/tanue-writing-from-scratch` or `/tanue-writing-style` in any Claude chat.

### How to Use Each Skill

#### `tanue-writing-from-scratch` — Generate New Articles

```text
请使用 Tanue Technical Narrative Writing Skill，围绕[主题]写一篇中文技术史长文。

要求：
1. 不要百科式开头，从历史场景、时代压力或反常问题切入；
2. 文章结构采用：背景—发展时间线—技术机制—关键瓶颈—项目结果—历史意义；
3. 技术参数必须解释其工程意义；
4. 结尾进行克制收束，不要空泛煽情。
```

Or for accident analysis:

```text
请使用 Tanue Technical Narrative Writing Skill，复盘[事故名称]。

要求：
1. 从事故现场或反常问题切入；
2. 按时间线还原事故过程；
3. 解释关键技术机制；
4. 不做单点归因，必须分析多因素叠加；
5. 区分事实、推断和观点；
6. 最后总结工程教训，语言克制。
```

#### `tanue-writing-style` — Rewrite Existing Drafts

```text
请使用 Tanue Writing Style 改写以下文章。

要求：
1. 不改事实、不改结构、不改图片、不改格式；
2. 开头改为从历史场景/事故瞬间/反常问题切入；
3. 打破均匀段落，增加微段和短段；
4. 删除70%以上非必要引号；
5. 删除禁止句式（不是……而是/这说明/这标志着/从某种意义上说）；
6. 参数附意义，事故因果链化；
7. 输出风格：成熟科普风
```

### Article Types Covered

| Type | Examples | Template |
|------|----------|----------|
| Technical History | V-2 rocket, Tu-64, Lada, Moon-25, Soviet/Russian industrial projects | Background → Timeline → Mechanism → Bottlenecks → Outcome → Significance |
| Accident Analysis | Chernobyl, Challenger, 737MAX, SSJ100, aviation/nuclear accidents | Scene → Timeline → Tech mechanism → Multi-factor overlay → Lessons |
| Biography Tribute | Leonov, Gagarin, Korolev, scientists, engineers | Memorial → Era context → Key contribution → Risk → Legacy |
| Personal Narrative | Station farewell, distance, youth, rain, moonlight | Scene → Third-person → Imagery buildup → First-person reveal → Restrained closure |

### Core Writing Philosophy

1. **Put technology back in its era.** Never describe a machine in isolation—explain the industrial capacity, political pressure, and engineering constraints of its time.
2. **Write accidents as causal chains.** Single-factor explanations are forbidden. Present the multi-factor overlay: how design, operations, organization, and human judgment converged at the same moment.
3. **Translate parameters into meaning.** Every number should answer: what does this mean in engineering terms? What constraint does it impose? What problem does it solve (or create)?
4. **Restrained closure.** Emotion must be earned through facts, mechanisms, and human context—never through slogans.

### What These Skills Are NOT

- ❌ Not an encyclopedia — facts serve the narrative, not the other way around
- ❌ Not clickbait — no "shocking truth" or "mind-blowing" language
- ❌ Not an academic paper — no "this paper first analyzes... then studies..."
- ❌ Not overly colloquial — no heavy internet slang or stream-of-consciousness

### Output Style Levels

Both skills support three output levels:

| Level | Tone | Author Presence | Best for |
|-------|------|----------------|----------|
| 知乎长文风 (Zhihu-style) | Conversational, more transitions | Can use "笔者" freely | Zhihu answers, draft blog posts |
| 成熟科普风 (Mature science) | Structured, restrained | "笔者" used sparingly | Published articles, personal brand |
| 准学术叙事风 (Semi-academic) | Rigorous, minimal emotion | Avoid "笔者" | Lectures, reports, course materials |

---

<a name="chinese"></a>

## 中文

本项目包含两个可安装的 Claude Skill，源于 @Tanue（后天雨）中文技术史叙事写作风格。这套风格的核心是：**工程技术史叙事 + 因果链解释 + 作者现场感 + 克制情绪收束**。

### Skill 列表

| Skill | 模式 | 文件 | 用途 |
|-------|------|------|------|
| `tanue-writing-from-scratch` | **从头创作** | `skills/tanue-writing-from-scratch/SKILL.md` | 生成技术史、事故复盘、人物致敬、个人叙事类中文长文 |
| `tanue-writing-style` | **改写润色** | `skills/tanue-writing-style/SKILL.md` | 将已有中文草稿改写为 Tanue 风格 |

### 安装方法

**方法一：.skill 文件安装**
下载对应的 `.skill` 文件 → 打开 Claude 桌面端 → 点击 Skills 按钮 → "Install Skill" → 选择文件。

**方法二：手动安装**
打开 Claude 桌面端 → 点击 Skills 按钮 → "Install from File" → 选择本仓库 `skills/` 目录下的 SKILL.md。

**方法三：斜杠菜单**
安装后，在 Claude 对话中输入 `/tanue-writing-from-scratch` 或 `/tanue-writing-style` 即可调用。

### 核心写作哲学

1. **把技术对象放回时代里**——技术对象必须被放回它所处的时代、工业体系、政治压力和工程限制之中
2. **把事故写成因果链**——拒绝单点归因，呈现多因素在同一时间窗口的叠加效应
3. **把参数翻译成意义**——每个数字都要回答"这意味着什么"
4. **用克制的方式完成情绪收束**——情绪必须来自事实和逻辑，不空喊口号

### 不建议用本 Skill 写什么

- 百度百科式的参数罗列
- 营销号式的震惊体
- 论文摘要式的"本文首先……其次……"
- 过度口语化的网络聊天体

### 输出风格三档

| 档位 | 特点 | 适用场景 |
|------|------|----------|
| 知乎长文风 | 口语转场较多、作者存在感较强 | 知乎、公众号初稿 |
| 成熟科普风 | 结构清晰、语言克制、技术解释准确 | 公众号正式稿 |
| 准学术叙事风 | 保留叙事入口、资料严谨、减少情绪 | 讲稿、报告、课程材料 |

---

Both skills are documented in full at `skills/{skill-name}/SKILL.md`.
