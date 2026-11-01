**English** · [Français](README.fr.md) · [Deutsch](README.de.md) · [中文](README.zh.md)

# Plain copy

An agent skill for writing app and website text in plain, human English. It cuts filler, drops AI writing tics, and starts from one rule: if the screen already shows it, leave it unsaid.

The skill itself is in [`skills/plain-copy/SKILL.md`](skills/plain-copy/SKILL.md). It works with Claude Code, Codex and other agents that read `SKILL.md` files.

## Install

With the [skills CLI](https://github.com/vercel-labs/skills):

```sh
npx skills add Hysterelius/plain-copy
```

Or copy it by hand:

```sh
git clone https://github.com/Hysterelius/plain-copy
cp -r plain-copy/skills/plain-copy ~/.claude/skills/
```

## Use

Ask your agent to write or review copy, or name it: "Use plain-copy on the settings screen."

The rules are written for English. The ideas behind them (say less, use common words, one name per thing) carry over to other languages.

## Credits

Adapted from [b1rdmania/claude-plain-english-skill](https://github.com/b1rdmania/claude-plain-english-skill) and Wikipedia's [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing).

Rules also draw on the Australian Government [Style Manual](https://www.stylemanual.gov.au/), the [NSW Government content style guide](https://www.digital.nsw.gov.au/delivery/digital-service-toolkit/resources/writing-content/content-style-guide), the [NSW Department of Education content style guide](https://education.nsw.gov.au/about-us/how-we-communicate/content-style-guide) and ISO 24495-1 (plain language).

## License

[CC0 1.0](LICENSE). Public domain. Use it however you like.
