[English](README.md) · **Français** · [Deutsch](README.de.md) · [中文](README.zh.md)

# Plain copy

Une compétence (skill) d'agent pour écrire les textes d'une app ou d'un site en anglais simple et humain. Elle coupe le superflu, retire les tics d'écriture des IA, et part d'une règle : si l'écran le montre déjà, ne le dites pas.

La compétence se trouve dans [`skills/plain-copy/SKILL.md`](skills/plain-copy/SKILL.md). Elle marche avec Claude Code, Codex et les autres agents qui lisent les fichiers `SKILL.md`.

## Installation

Avec le [CLI skills](https://github.com/vercel-labs/skills) :

```sh
npx skills add Hysterelius/plain-copy
```

Ou à la main :

```sh
git clone https://github.com/Hysterelius/plain-copy
cp -r plain-copy/skills/plain-copy ~/.claude/skills/
```

## Utilisation

Demandez à votre agent d'écrire ou de relire des textes, ou nommez la compétence : « Use plain-copy on the settings screen. »

Les règles visent l'anglais. Les idées de fond (en dire moins, choisir des mots courants, un seul nom par chose) valent aussi pour d'autres langues.

## Crédits

Adapté de [b1rdmania/claude-plain-english-skill](https://github.com/b1rdmania/claude-plain-english-skill) et de la page Wikipédia [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing).

## Licence

[CC0 1.0](LICENSE). Domaine public. Faites-en ce que vous voulez.
