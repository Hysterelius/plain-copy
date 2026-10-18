---
name: plain-copy
description: Write or review user-facing text (app UI strings, buttons, errors, empty states, onboarding, website copy, docs) so it reads as plain, human English and drops AI writing tics. Use when writing any string a person will read in a product, or when asked to make copy shorter, plainer, or "more human".
---

# Plain copy

Every string should read the way a helpful friend talks. These rules adapt two sources for product text: [b1rdmania/claude-plain-english-skill](https://github.com/b1rdmania/claude-plain-english-skill) (Orwell and Gowers, plus common AI tics) and Wikipedia's [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing).

## Leave it unsaid

This rule comes first. If the screen shows something, don't also describe it.

- Cut helper text that explains how a control works, what happens next, or why a feature exists. Keep it only if a first-time user would get stuck without it.
- Most rows need a title only, no subtitle.
- Don't label what is plain to see: no "Type: QR" under a QR code, no "Name" above a name. A value that explains itself goes on screen bare.
- Don't narrate behaviour the user will notice anyway. If the screen gets brighter, it needs no "Full brightness" badge.

## Write it

1. Short. If a word can go without changing the meaning, cut it. "Add item", not "Add a new item to your list".
2. Active, with someone doing it. "We saved your changes", not "Your changes have been saved".
3. In everyday words: use, start, end, help, about.
4. As facts. "3 tasks left", not "You're crushing it". Praise only what really happened.
5. With verbs on buttons: Save, Add set, Import. Dialog buttons say what they do ("Discard", "Keep editing"), not "OK".
6. With errors that say what happened and what to do next. "That file is too big. Pick one under 10 MB." No codes in the main text, and no blame.
7. Condition first. "If you skip this, we use the default."
8. With numbers, not adjectives. "6 steps · ~5 min", not "a quick, easy setup".
9. In sentence case, for titles and headings too: "Account settings", not "Account Settings".
10. With one name per thing. Pick a word for each concept and never swap in synonyms. If the project has a glossary, it is the dictionary.

## Don't write

- AI words: seamless, effortless, leverage, robust, crucial, vital, key (as an adjective), enhance, elevate, empower, unlock, streamline, journey, showcase, testament, vibrant, notably, delve, landscape, comprehensive.
- "Not just X, it's Y" lines, or "No X, no Y, just Z" lines. State the thing itself.
- Trailing "-ing" clauses that comment on the sentence ("…, making it easier to stay on track").
- False ranges ("from beginners to pros").
- Lists padded to three. If there are two points, write two.
- Vague sources ("experts recommend"). Name the source or cut the claim.
- Em dashes in prose, or exclamation marks. Use full stops, commas, and "·" between data. Save an exclamation mark for a real win, if anywhere.
- Bold or emoji as decoration. Emoji are fine only where the user chose them.
- Guilt. Missed days, broken streaks and time away are stated plainly or not at all.

## Check

Before you finish, give every new or changed string one pass against this list. Cut first, then rewrite what's left.
