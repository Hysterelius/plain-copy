[English](README.md) · [Français](README.fr.md) · **Deutsch** · [中文](README.zh.md)

# Plain copy

Ein Agent-Skill für App- und Website-Texte in einfachem, menschlichem Englisch. Er streicht Füllwörter, entfernt typische KI-Floskeln und folgt vor allem einer Regel: Was der Bildschirm schon zeigt, muss man nicht noch sagen.

Der Skill liegt in [`skills/plain-copy/SKILL.md`](skills/plain-copy/SKILL.md). Er funktioniert mit Claude Code, Codex und anderen Agents, die `SKILL.md`-Dateien lesen.

## Installation

Mit der [skills-CLI](https://github.com/vercel-labs/skills):

```sh
npx skills add Hysterelius/plain-copy
```

Oder von Hand:

```sh
git clone https://github.com/Hysterelius/plain-copy
cp -r plain-copy/skills/plain-copy ~/.claude/skills/
```

## Nutzung

Bitte deinen Agent, Texte zu schreiben oder zu prüfen, oder nenne den Skill direkt: „Use plain-copy on the settings screen.“

Die Regeln sind für Englisch geschrieben. Die Grundideen (weniger sagen, gängige Wörter, ein Name pro Sache) gelten auch in anderen Sprachen.

## Quellen

Angepasst aus [b1rdmania/claude-plain-english-skill](https://github.com/b1rdmania/claude-plain-english-skill) und der Wikipedia-Seite [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing).

Stützt sich auch auf das [Style Manual](https://www.stylemanual.gov.au/) der australischen Regierung, den [Styleguide von NSW](https://www.digital.nsw.gov.au/delivery/digital-service-toolkit/resources/writing-content/content-style-guide), den des [Bildungsministeriums von NSW](https://education.nsw.gov.au/about-us/how-we-communicate/content-style-guide) und ISO 24495-1 (einfache Sprache).

## Lizenz

[CC0 1.0](LICENSE). Gemeinfrei. Mach damit, was du willst.
