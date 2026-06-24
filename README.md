# Writing Style Engram: Geoff Trembley

The irony wasn't lost on me. A profile of my writing voice is worthless if the page describing it reads like everyone else's. So this one doesn't.

BLUF: this repo is my public writing engram. It's a structured profile of how I actually write, built from roughly 500 of my own messages across chat, email, internal docs, and published articles. Paste it into an AI writing assistant and the output stops sounding like the default corporate hum and starts sounding like a person. Me, specifically.

## What an engram is

A reusable style profile you hand to a model so it writes in your voice instead of generic AI prose. It goes in the system prompt. The output changes.

This one captures:

1/ Tone and voice. Direct, collegial, operator-minded. Warm, never soft.

2/ Sentence structure. Short and declarative, with parentheticals when they earn their place (like this one).

3/ Vocabulary. The phrases I reach for, and the ones I never touch (no "leverage," no "circle back," no em-dashes).

4/ Document patterns. Conclusion first, numbered pillars, asks labeled and never buried.

5/ Thought leadership. Conversational authority, the way you'd talk after the conference, not the way you'd lecture during it.

6/ Anti-patterns. What this voice does NOT sound like, stated plainly so the model has a fence to stay inside.

## How to use it

Paste the contents of `engram.md` into the system prompt of any assistant (Claude, ChatGPT, Gemini, whatever you run), then give it the task. That's the whole setup.

```
You are a writing assistant. Match my voice exactly using the style guide below.

[paste engram.md here]

Now help me write: [your task]
```

One note: the engram describes patterns, not facts. It won't know your numbers, your team, or your context. Feed it those.

## Build your own

Mine is useful as a reference, but the point isn't for everyone to write like me. The point is for you to write like you, on purpose, at scale. Here's how to build your own. It takes about an hour.

1/ Gather your samples. Pull 20 to 50 real pieces of your writing, and mix the registers: quick chats and DMs, a few emails, a long document or two, anything you've published. Range matters more than volume. The model needs to see how you sound when you're casual and how you sound when the stakes are high.

2/ Generate the first draft. Paste your samples into the prompt below. You'll get back a structured profile.

```
You are a writing-style analyst. I'm going to paste a batch of my own writing.
Study it and produce a reusable style engram I can give to an AI assistant so it
writes in my voice.

Analyze across:
1/ Tone and voice
2/ Sentence structure and rhythm
3/ Vocabulary: the words and phrases I reach for, and the ones I avoid
4/ Formatting and document structure habits
5/ How I open and close messages
6/ Anti-patterns: what my writing never does

Rules:
- Quote real examples from my samples under each pattern. No generic claims.
- Be specific. "Uses short sentences" is useless. Name the actual habit and show it.
- Don't flatter the writing. Describe it straight, including the rough edges.
- End with 10 to 15 representative lines pulled verbatim from my samples.

Here are my samples:
[paste your 20 to 50 pieces here]
```

3/ Correct it. The first draft will get some things wrong. It will also miss things you know are true. Fix it.

```
Here is the engram you produced, with my edits and notes inline.
Tighten it. Cut anything that isn't actually true of how I write. Add the patterns
you missed. Keep every claim tied to a real example.

[paste the engram plus your notes]
```

4/ Test it before you trust it. Run it on a real task and make it show its work.

```
Use the engram below as your style guide. Write [a short email / a LinkedIn post]
about [topic]. Then list which engram rules you applied and where.

[paste your engram]
```

If the output sounds like you, you're done. If it sounds like an AI wearing your name, go back to step 3 and get more specific about your anti-patterns. Vague anti-patterns are where the slop sneaks back in.

5/ Anonymize before you share it. If you're putting it in public, scrub it first.

```
Scrub this engram for public sharing. Replace every company name, customer name,
person's name, and proprietary detail with a generic equivalent. Keep all style
patterns, vocabulary, and structure intact. Flag anything you're unsure about.

[paste your engram]
```

That's it. Keep the file somewhere you can grab it, and update it once or twice a year as your writing shifts.

## What it is not

No proprietary data. No company names, no customer information, nothing confidential. Every example is anonymized. It's writing patterns and nothing else.

## About

I run go-to-market and sales leadership in tech. I keep a public presence at [geofftrembley.com](https://geofftrembley.com).

Connect: [linkedin.com/in/geofftrembley](https://www.linkedin.com/in/geofftrembley/)

---

Use it freely. If it helps you build your own, that was the point.
