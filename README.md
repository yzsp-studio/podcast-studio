<div align="center">

# 🎬 podcast-studio

## 长文直接变成进棚就能录的播客脚本，cue 都标好了
## Turn any article into a studio-ready podcast script with music and SFX cues

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

把任意长文（文章、博客、专栏、简报）改写成可直接进棚的播客脚本，附带朗读时长、音乐 cue、音效点和制作备注，制作人拿给声优和音频工程师即可开录。它按约 150 词/分钟估算朗读时长，把文章拆成 cold open、intro、2—5 个正文章节、广告位与 outro，为每段标注音乐 bed 指令（合成音色、调、tempo、淡入淡出）和 SFX 触发名加时间码，最后附 Cue Sheet 汇总表和声优交付备注。为浏览器端交付栈设计，音乐 bed 假设由 Tone.js 合成、离散音效与环境循环由 Howler.js 触发，但本技能只出 cue 表、不跑音频引擎。原文可直接从工作区读取，不必整段重贴；正文过长时也无需用户重复粘贴。适合文章转播客、给稿件加音乐 cue、规划片头片尾音乐或设计口播声音铺底。

### ✨ 能做什么

- 长文 → 结构化播客脚本，按约 150 词/分钟估算每段朗读时长
- 自动切段骨架：Cold open / Intro / 2—5 个章节 / 广告位 / Outro
- 音乐 bed 指令：合成音色、调、tempo、淡入淡出时长逐段写清
- SFX cue：触发名 + 时间码，环境音与场景切换严格对齐
- Cue Sheet 汇总表 + 声优交付备注，制作人拿到即可执行
- 纯文本产出不合成音频；原文可从工作区读取，无需重复粘贴

### 📦 包含的技能

- `podcast-studio` —— 见 [`podcast-studio/SKILL.md`](podcast-studio/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/podcast-studio.git
cp -r podcast-studio/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Rewrites any long-form text — article, blog post, column or briefing — into a podcast script that can go straight into the booth, complete with read time, music cues, sound-effect points and production notes so a producer can hand it to a voice actor and an audio engineer. It estimates read time at roughly 150 words per minute and splits the text into a cold open, intro, 2–5 body chapters, sponsor breaks and an outro, annotating each segment with music-bed instructions (synth patch, key, tempo, fades) and SFX trigger names with timecodes, then closes with a Cue Sheet summary and voice-talent delivery notes. It targets a browser-side delivery stack where music beds are synthesised with Tone.js and discrete SFX and ambience loops are fired through Howler.js — but the skill only writes the cue sheet and never runs the audio engine. Source text can be read straight from the workspace instead of being pasted again. Best for converting articles to podcasts, adding music cues to a script, planning intro and outro music, or designing sound beds under narration.

### ✨ What it does

- Long-form text to a structured podcast script, with per-segment read time estimated at about 150 words per minute
- Automatic segment skeleton: cold open, intro, 2–5 chapters, sponsor breaks and outro
- Music-bed instructions spelling out synth patch, key, tempo and fade length for every segment
- SFX cues with trigger names and timecodes, keeping ambience and scene transitions tightly aligned
- A Cue Sheet summary table plus voice-talent delivery notes that a producer can execute directly
- Plain-text output with no audio rendering, reading source files from the workspace instead of re-pasting them

### 📦 Skills included

- `podcast-studio` — [`podcast-studio/SKILL.md`](podcast-studio/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/podcast-studio.git
cp -r podcast-studio/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
