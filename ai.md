# CraftyForms — The form layer for your AI stack

> Headless, MCP-native, structured output. The form tool your vibe-coded tools deserve. Works however you build, looks however you design.

[Get API access](#) · [See how it works](#features)

---

## Core features

### 01 — Headless-first

No UI lock-in, no opinions. Pure API. Render your own frontend, wire it to your agent, or skip the interface entirely. The logic, validation, and storage are all handled. You own how it looks and feels.

### 02 — MCP-native

Your AI tools can read and write form data directly. Claude, Cursor, or anything MCP-compatible can discover your forms, submit responses, and query entries — without you writing a single integration.

### 03 — Text is 100% free

Every text-based submission is free, forever. No trial limits, no gotchas. Start building real pipelines without touching a credit card. Pay only when you add media.

### 04 — Multi-modal by nature

Not an add-on. Not a workaround. Text, voice, photo, and video are first-class input types — each transcribed, parsed, and returned in the same structured schema. Your pipeline doesn't change. The input method does.

---

## Example API response

```json
{
  "response_id": "resp_8f3a",
  "question_id": "q_01",
  "input_type": "voice",
  "transcript": "The motor cuts out after about 10 seconds...",
  "structured": {
    "category": "hardware",
    "severity": "high",
    "confidence": 0.94
  },
  "timestamp": "2026-04-23T10:41:00Z"
}
```

Any input. Always structured. Your schema.

---

## Also included

- **Webhooks & event callbacks** — Get notified the moment a response lands. Push to your pipeline, trigger your agent, or fan out to any downstream system. No polling required.
- **Structured output guarantee** — Voice note, photo, or typed text — every response arrives in the same schema. Your code handles one shape of data, always.
- **Data validation** — REGEX, custom rules, and external source checks run before a submission is accepted. Bad data gets rejected before it reaches your pipeline.
- **OpenAPI schema** — Full spec published and always up to date. Drop it into your IDE, your agent, or your API client and start building immediately.
- **Field prefill via params** — Pass context in from your agent or app via URL params or API. Pre-populate fields so respondents only answer what's actually unknown.
- **Edit responses & audit trail** — Correct a submission after the fact, issue shareable edit links, and trace every change. Pipelines need to recover from bad inputs — this is how.
- **Offline sync & auto-retry** — Every answer is saved the moment it's entered. When the connection returns, everything syncs automatically. No lost responses, no manual retry logic.
- **Sandbox & test mode** — A fully isolated environment for development. Submit test responses, inspect the schema, and break things safely before going to production.
- **Rate limiting & quota controls** — Set per-form or per-key submission limits. Protect your pipeline from runaway agents, unexpected spikes, or accidental loops.

Also includes: Draft saving · Bot protection · Conditional logic · Collaborator access · Response deduplication · Import & export · Embed anywhere · Ready templates

---

## Pricing

**API-first pricing. No seats. No nonsense.**

Text submissions are free, forever. Media uses storage — you pay for that at cost. Advanced features and MCP access unlock on paid plans.

| Plan | What's included |
|---|---|
| **Free** | Unlimited text-based submissions via API. Full headless access. Core logic and conditions. No credit card required. |
| **Pro** | Everything in Free, plus MCP access, media submissions, AI features, white-labelling, and priority support. Usage-based on media storage. |
| **API & usage-based** | Pay per submission, per API call, or per GB stored. No monthly commitment. Built for pipelines that burst. |

---

## Get API access

API access is live. [Sign up and start building today](#).

---

*© 2026 CraftyForms. All rights reserved.*  
[Privacy](https://craftyforms.in/privacy.html) · [Terms](https://craftyforms.in/terms.html)
