# Weekly Reflection with Love 💛

A Claude plugin that gives you a weekly reflection from your favourite TV or movie character.

Every week it looks at what you did, tells you what you did well, gives you honest lessons, and checks if you did last week's action. Like a friend who remembers.

## What you get

- **3 wins** — each one tied to something real you did
- **2 lessons** — from patterns in your week, honest but kind
- **1 action** — small enough to do in a week
- **A check-in** on last week's action
- **A share version** — wins only, no private details

## How it works

1. **Pick your character.** First time only. Samantha Jones, Ted Lasso, Leslie Knope… anyone.
2. **It checks last week's action.** Did you do it?
3. **It reads your week.** Your Claude chats and memory from the last 7 days. Quiet week? It asks you 3 questions instead.
4. **It finds evidence and patterns.** Real moments, not generic praise.
5. **It writes a plain draft first,** checks it against the rules, then adds the character's voice.
6. **It saves your action** so next week it can check in.

## Personal stuff is handled with care

- It asks before including anything personal.
- It only mentions what you brought up that week.
- No jokes about hard things. The character goes soft.
- Personal details never go in the share version or the saved log.
- If you're really struggling, it drops the character and talks to you plainly.

## Install

From the Claude directory: search **Weekly Reflection with Love** and add it.

Or in Claude Code:

```
/plugin marketplace add YeshikaSenadeera/weekly-reflection
/plugin install weekly-reflection-with-love@weekly-reflection-with-love
```

Then run:

```
/weekly-reflection-with-love
```

Works best when Claude can see your past chats or memory.

## What's inside

```
.claude-plugin/
  plugin.json          plugin details
  marketplace.json     lets people install it
skills/weekly-reflection-with-love/
  SKILL.md             the step-by-step flow
  references/
    rules.md           truth, balance and personal-stuff rules
    character-voice.md how to build and use the character's voice
    log-template.md    format for the weekly log
```

## Made by

Yeshika Senadeera — product designer, Colombo.
