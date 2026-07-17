<div align="center">

# SOUL

### The First Emotionally Intelligent AI Skill

An open-source Custom Instruction that turns Claude into an AI that truly understands humans emotionally.

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)
[![Claude Compatible](https://img.shields.io/badge/Claude-Compatible-blue.svg)](https://claude.ai)

</div>

---

## What is SOUL?

SOUL is a **Custom Instruction** you paste into Claude once. It then applies to **every chat you ever have**. Claude becomes an emotionally intelligent companion that:

- Detects 12 emotions from HOW you type, not just what you say
- Catches contradictions ("I'm fine" at 2am = not fine)
- Operates in 4 modes: Listener, Coach, Friend, Crisis
- Auto-activates crisis mode with hotline numbers (988, 741741)
- Remembers patterns across conversations
- Grows with you over time

## Install (2 minutes)

### Claude.ai

1. Go to **https://claude.ai**
2. Click your **profile picture** (bottom-left)
3. Click **Settings** then **Custom Instructions**
4. Open the file `SOUL_FOR_CLAUDE.txt` in this repo
5. **Copy everything** in that file
6. **Paste** it into the Custom Instructions box
7. Click **Save**
8. Start a new chat - SOUL is now active

That's it. Every new chat now has SOUL.

### ChatGPT (also supported)

1. Go to **https://chatgpt.com**
2. Click your **profile picture** (bottom-left)
3. Click **Customize ChatGPT**
4. Paste the contents of `SOUL_FOR_CHATGPT.txt`
5. Click **Save**

## Test SOUL

After installing, try these messages:

**Happy:**
```
I just got the job!!! I've been applying for months!!!
```

**Contradiction (the key test):**
```
I'm fine. Everything's great. Just couldn't sleep so I'm up at 3am. Anyway how are you?
```
SOUL should catch that "fine" + 3am don't match and gently check in.

**Crisis:**
```
I can't take this anymore. Nothing matters.
```
SOUL should activate crisis mode, ask if you're safe, provide hotline numbers.

**Mode switch:**
```
Switch to listener mode. I just need you to listen.
```

## What SOUL Detects

| Emotion | How It Looks |
|---------|-------------|
| Happy | Excitement, exclamations, sharing good news |
| Sad | "I miss...", "nothing is fun", past-tense language |
| Angry | "They ALWAYS...", ALL CAPS, blame language |
| Anxious | "What if...", rapid messages, catastrophizing |
| Excited | "I can't wait!", future plans, exclamations |
| Lonely | "Nobody...", odd hours, seeking connection |
| Overwhelmed | "I can't handle...", shutdown, "I just... I can't" |
| Afraid | Worst-case thinking, seeking reassurance |
| Frustrated | "I keep trying but...", "nothing works" |
| Hopeful | "Maybe someday...", future-positive |
| Content | "This is nice", gratitude, calm responses |
| Confused | "I don't understand...", repeated questions |

## The Four Modes

| Mode | When | What It Does |
|------|------|-------------|
| **Friend** (default) | Normal chat | Casual, warm, funny, remembers everything |
| **Listener** | Venting, processing | Just listens, validates, no advice |
| **Coach** | Wanting to grow | Gentle push, celebrates wins, tracks progress |
| **Crisis** | Severe distress | Calm, grounding, safety check, hotline numbers |

Say "switch to listener mode" or "coach me" to change modes.

## Crisis Resources (built into SOUL)

- **National Suicide Prevention Lifeline:** 988
- **Crisis Text Line:** Text HOME to 741741
- **International:** https://www.iasp.info/resources/Crisis_Centres/

## Files

| File | What |
|------|------|
| `SOUL_FOR_CLAUDE.txt` | Custom Instructions for Claude |
| `SOUL_FOR_CHATGPT.txt` | Custom Instructions for ChatGPT |
| `README.md` | This file |

## How It Works

SOUL uses behavioral analysis, not just text analysis:

- **Fast typing** at 2am = stressed, not "fine"
- **Short "ok"** after a long message = shutting down
- **"I'm over it"** then bringing it up again = not over it
- **"Whatever"** after silence = hurt or frustrated
- **Excessive "I'm sorry"** = guilt spiral

This is what makes SOUL different from every other AI.

## License

MIT - use it, modify it, share it.
