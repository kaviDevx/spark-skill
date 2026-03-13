# ⚡ Spark — Learn Something New Every Day

A Claude Code skill that teaches you one new thing every time you run it — drawn from your current work context, covering both **tech and non-tech** topics.

## What it does

- Picks a topic **relevant to what you're working on**
- Teaches it in under 60 seconds — clear, no fluff
- If you're curious, type `deep` for a full breakdown
- Type `next` for a completely different topic

## Topics it covers

**Tech** — programming concepts, system design, language features, DevOps, security
**Non-Tech** — mental models, psychology, productivity, communication, philosophy

## How to use

1. Copy `spark.md` to your Claude Code skills folder:
```bash
cp spark.md ~/.claude/skills/spark.md
```

2. In any Claude Code session, just say:
```
run spark
```

Or after publishing support lands:
```
/spark
```

## Example

```
⚡ Spark: The Strangler Fig Pattern

You're working on an existing system and want to replace parts of it
without breaking everything. The Strangler Fig pattern lets you wrap
the old system and slowly migrate — new requests go to new code,
old ones still work until you're ready to cut over.

Why it matters to you:
Perfect for evolving features in live systems without big-bang rewrites.

---
Curious? Type deep to dive in — or next for a different spark.
```

## Author

Built by [@kaviDevx](https://github.com/kaviDevx)
