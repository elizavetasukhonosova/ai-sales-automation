# Connecting AI to Your Tools

The workflows in this repo work two ways. As **prompts**, you paste information in and copy output out. As **connected workflows**, the AI reaches into your CRM, calendar, and docs and does the copying itself. This guide explains the connected version in plain English, no engineering required.

## What "connected" actually means

By default, an AI like Claude or ChatGPT is a brain in a jar: brilliant, but it can only see what you paste in and can only give you text back. **Connecting** it means giving it hands — the ability to read from and write to the apps you already use.

Once connected, "summarize this meeting and log it in the CRM" stops being two steps (AI drafts, you paste) and becomes one (AI drafts and logs it). That's the whole payoff: fewer copy-paste steps, less context-switching, more of the busywork gone.

## The two common ways to connect

You don't build anything. You turn on connections through settings.

**1. Built-in connectors (the easy path).**
Modern AI assistants offer official connectors to popular apps — calendar, email, common CRMs, document tools. You authorize the connection once (log in, click allow), and the AI can then use that app on your behalf. This is the same permission flow as "Sign in with Google" on any website. No code, a few minutes of setup.

**2. Custom actions / automation tools (the flexible path).**
If your specific tool isn't offered as a built-in connector, you have two routes:
- A **custom GPT or assistant** where you add "actions" that call your tool. This needs a bit of technical setup (or a technical friend for an hour).
- An **automation platform** (the Zapier-style tools) that sits between the AI and your app and passes information back and forth. More approachable than custom actions, and enough for most sales workflows.

Start with built-in connectors. Only reach for the flexible path when you hit a tool they don't cover.

## What to connect first (for sales)

In order of payoff:

1. **Calendar** — so the AI can see your schedule and draft invites. Low risk, high convenience.
2. **Notes / docs** — so it can read meeting transcripts and write summaries where you keep them.
3. **CRM** — so it can log notes and create tasks. The biggest time-saver and the one that needs the most care (see below).
4. **Email** — so it can draft replies in context. Connect this for *drafting only*; never let it send.

## The golden rule: read freely, write carefully

Reading your data is safe and instantly useful — let the AI see your calendar, your notes, your deal history. **Writing** is where you stay cautious. The safe default for any connected workflow:

- **Reading** anything: fine, automatic.
- **Writing** reversible things (a CRM note, a draft): fine, but have it tell you what it did.
- **Writing** irreversible things (sending an email, deleting a record, messaging a customer): **never automatic.** The AI drafts or proposes; you press the button.

Every workflow in this repo is built this way on purpose. It's the difference between a helpful assistant and a liability. The reasoning is in [keeping a human in the loop](./keeping-a-human-in-the-loop.md).

## Security basics (don't skip)

- **Only connect tools you trust the AI provider with.** Read what data access you're granting when you authorize.
- **Use least access.** If a connector lets you limit it to specific data, do. The AI doesn't need your whole inbox to draft one follow-up.
- **Never paste secrets** — passwords, API keys, customer financial data — into a chat as plain text.
- **Review permissions periodically** and revoke connections you've stopped using.

## Honest expectations

Connecting tools removes copy-paste friction; it does not remove your judgment from the loop, and you don't want it to. The realistic win is turning a 20-minute post-call ritual into a 2-minute review-and-approve. That compounds fast across a week of calls, and it's a genuine edge — but the human still decides. Anyone selling you "fully autonomous AI sales" is selling you a future churn problem.
