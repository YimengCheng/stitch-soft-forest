# 林间布语 · Stitch Soft Forest

一套把照片、旅行记忆、自然物、动物与日常小物，转化为清新自然、温暖安心的手缝布艺拼贴与贴布绣图像的 ChatGPT / Codex Skill。

它强调真实的棉麻织纹、旧碎布、手剪轮廓、可见针脚、柔和自然色和克制留白。参考照片只用于保留主体、动作与空间关系，不会被逐像素复制；参考作品只定义工艺气质，不定义具体图案。

> A gentle ChatGPT / Codex skill for turning photos and memories into tactile, hand-stitched textile collages with soft natural colors and a quiet forest-inspired mood.

## 可以做什么

- 把旅行照片分别转化成独立的贴布绣作品
- 根据一句灵感原创布艺画面
- 设计布包、书封、挂布、徽章或服装贴布图案
- 在明确提出时，给出布片分层、布料选择与针法参考

## 安装

在支持个人 Skills 的 Codex 环境中，调用 `$skill-installer`，并让它从这个仓库安装：

```text
使用 $skill-installer 安装这个 GitHub 仓库中的 Skill：
https://github.com/YimengCheng/stitch-soft-forest
```

安装后如果没有立即出现，请重启 Codex。

根据 OpenAI 当前文档，独立 Skill 可用于 ChatGPT 桌面端、Codex CLI 和 IDE 扩展；若要让其他人直接在 ChatGPT 网页端或手机端安装，需要进一步把 Skill 打包为 Plugin。这个 GitHub 仓库目前是公开源码与安装来源。

## 使用

可以明确调用：

```text
使用 $stitch-soft-forest，把这张旅行照片变成林间布语风格的手缝布艺拼贴。
```

也可以直接描述需求：

```text
把一只小羊走过鼠尾草绿山坡的画面，做成真实完成后实拍的贴布绣作品。
```

## 文件结构

```text
stitch-soft-forest/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── assets/
│   └── icon.svg
└── references/
    └── visual-language.md
```

`SKILL.md` 定义工作方式；`references/visual-language.md` 规定材质、配色、造型、针脚、构图与排除项。

## 原创与参考原则

每次重新安排轮廓、比例、布纹与叙事关系。不要复制参考作品里的具体物件组合、构图或配色对应关系；不擅自加入人物、品牌、口号或水印。

