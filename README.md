# EchoMind

**An autonomous content twin for content creators.**

EchoMind eliminates multi-platform fatigue. Instead of manually reformatting the same video, transcript, or idea for TikTok, Instagram, YouTube, and X every time, creators hand raw content to EchoMind — a persistent Mind that remembers their voice, their audience, and their style — and it turns that content into platform-ready formats, consistently, without needing to be re-briefed each time.

Built for **Creative Minds Jam #1: Hong Kong** — Track 2: *Content Repurposing Across Platforms*.

---

## The Problem

Creators (YouTubers, bloggers, streamers, educators) lose hours every week reformatting one piece of content for multiple platforms. Every platform has its own format, length, and tone expectations — and most AI tools treat every request as a blank slate, forcing the creator to re-explain their voice and audience over and over.

## The Solution

EchoMind is not a stateless chatbot. It's a persistent Mind with:

- **Long-term memory (DNA):** learns the creator's voice, audience, and content style once, and applies it consistently across every future task — no re-briefing required.
- **Autonomous processing:** given raw material (a link, a transcript, rough notes), it independently breaks it down into platform-specific deliverables.
- **Continuity:** picks up exactly where it left off across sessions, referencing past decisions and feedback.

### Deliverables per content piece
1. A short caption/script for TikTok/Instagram (under 60 seconds read aloud)
2. A longer YouTube description
3. 2–3 pull-quotes for X

## Example Persona (Demo)

To validate the Mind's memory and consistency, EchoMind was tested against a sample creator persona:

> **Nadine** — makes short-form educational content explaining AI/tech concepts in plain language for non-technical professionals (25–35, marketing/finance/design). Voice: casual, warm, a little sarcastic about hype and jargon. Format: under-60-second clarity.

EchoMind was given this persona once, and successfully retained and applied it across multiple separate content requests and a fresh session — see `/docs/demo-transcripts.md` for full examples.

## Current Status

- ✅ Mind created and live on [Minds by Animoca Brands](https://hellominds.ai)
- ✅ Persona/DNA established and validated across sessions (memory + continuity confirmed)
- ✅ Two full content transformations tested (chatbot-vs-agent explainer, on-chain identity explainer)
- ⏳ Telegram intake bot — in progress
- ⏳ Multi-platform auto-formatting logic (beyond chat) — in progress

## Tech Stack (planned)

- **Minds API** — core agent runtime, memory, persona
- **Telegram Bot API** — content intake channel
- Backend (TBD): connects Telegram → Mind → structured output

## Mind Details

- **Mind ID:** `51a8443e-f36b-1410-8466-00039ce7df11`
- **Platform:** [hellominds.ai](https://hellominds.ai)

## Track

**Content Repurposing Across Platforms** — Creative Minds Jam #1: Hong Kong, organized by Minds by Animoca Brands, The Sandbox, and Open Campus.

## License

MIT