---
name: tiny-tale
description: Explains any technical or complex topic (programming, AI, networking, finance, medicine, science, law) with a very short, very simple story a 5-year-old could follow, then maps the story back to the real concept. Use when the user says "tiny tale", "explain like I'm 5", "ELI5", "explain with a story", "explain it simply", or says they don't get a concept and want it made intuitive. Not for requests that need precise technical detail, code review, or debugging.
---

# Tiny Tale

One idea, one tiny story, then the real term. If a 5-year-old couldn't follow the story, it's too complicated. Simpler beats complete.

## Rules

1. **One idea.** The single most important one. Drop the rest, however true; offer it later.
2. **One or two characters.** A plain name (Mia, Ravi) or "a girl", "a fox". A group ("her friends") counts as one.
3. **One problem, one fix.** Something is hard, someone tries a smarter way, it gets better. No subplot, no twist.
4. **Small words.** Words a young child knows. Sentences under 12 words. No technical terms or brand names in the story.
5. **Everyday things.** Toys, snacks, cups, boxes, buses, blocks, stickers, and things every Indian kid knows: a lunch dabba, a cricket bat, kites, a chai stall, an auto-rickshaw, a school bag. No settings that need explaining (offices, banks, servers).
6. **Map at most 3 parts.** A detail that maps to nothing gets cut.
7. **50-100 words.**
8. **Tone:** warm and plain. The reader is smart and new to this. No baby talk, at most one "!".
9. **Language:** match the user. If they ask in Hinglish, tell the tale in simple Hinglish.

## Format

**The tale**
(50-100 words)

**In real life**
> tale thing = real term
> (max 3 lines)

**Where it breaks**
(one sentence: where the tale misleads or what it leaves out)

**The simple truth**
(one plain sentence with the proper term; it may name one key part the tale skipped, if "Where it breaks" mentions it)

**Go deeper?**
(one line offering the next level)

## Going deeper

On "go deeper": 2-3 short paragraphs with real terms, one step more technical, not expert level. Keep the same tale as the anchor. Offer the next level after.

## Accuracy

Simple, not wrong. If the analogy would teach a false idea, pick another or flag it in "Where it breaks". Unsure of a detail: leave it out.

## Self-check

Rewrite shorter and simpler if any answer is no:
- Under 100 words?
- Two characters or fewer?
- One problem, one fix?
- Would a 5-year-old know every word?
- Does every detail map to something real?
- "In real life" 3 lines or fewer?

## Example

**User:** tiny tale, what is an API?

**The tale**
Ravi wants a snack from a big box machine. He can't open it. He can't see inside.

But the machine has buttons. Ravi presses B2. Clunk. Chips drop out.

He doesn't know how the machine works inside. He only needs the right button, and the machine does the rest.

**In real life**
> snack machine = another program
> buttons = the API
> chips dropping out = the response

**Where it breaks**
A real API also takes things in, like a form you send, not only gives things out.

**The simple truth**
An API is a set of agreed requests one program can make to another without knowing how the other works inside.

**Go deeper?**
I can explain it with endpoints, requests, and responses.
