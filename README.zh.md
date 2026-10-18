[English](README.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · **中文**

# Plain copy

一个 AI 代理技能（skill），用来把应用和网站上的文字写成简单、自然的英文。它删掉多余的话，去掉 AI 写作的常见套路，并从一条规则出发：屏幕上已经能看到的，就不用再说。

技能文件在 [`skills/plain-copy/SKILL.md`](skills/plain-copy/SKILL.md)。适用于 Claude Code、Codex 以及其他能读取 `SKILL.md` 的代理。

## 安装

使用 [skills CLI](https://github.com/vercel-labs/skills)：

```sh
npx skills add Hysterelius/plain-copy
```

或手动复制：

```sh
git clone https://github.com/Hysterelius/plain-copy
cp -r plain-copy/skills/plain-copy ~/.claude/skills/
```

## 使用

让代理写或检查界面文字，或者直接点名："Use plain-copy on the settings screen."

这些规则是针对英文写的。背后的思路（少说、用常见的词、一个东西只用一个名字）也适用于其他语言。

## 致谢

改编自 [b1rdmania/claude-plain-english-skill](https://github.com/b1rdmania/claude-plain-english-skill) 和维基百科的 [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing)。

## 许可证

[CC0 1.0](LICENSE)。公有领域，随意使用。
