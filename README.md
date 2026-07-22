# AI Sales Automation for Founders

**Stop doing the admin. Wire AI into the boring, repeatable parts of sales so you can spend your hours on the parts that actually need a human.**

Every founder-led sales motion drowns in the same busywork: logging meetings, chasing follow-ups, updating the CRM, prepping for calls. None of it needs your brain. All of it eats your week.

This repo shows you how to hand that work to AI, without building software. You'll use tools you already have (Claude, ChatGPT, and whatever CRM/calendar/docs you run) and a set of reusable "workflows" written in plain language that the AI follows step by step.

Written from real experience automating sales and revenue operations, translated into tool-agnostic patterns you can adapt to any stack.

## What's inside

### 🧩 [Workflows](./workflows/)
Copy-paste AI workflows for the repetitive parts of the job. Each one is written as an instruction set you hand to Claude or a custom GPT.

| Workflow | What it automates |
|---|---|
| [Post-meeting processor](./workflows/post-meeting-processor.md) | Turn a call recording into a summary, CRM note, tasks, and a follow-up draft |
| [Pre-call research brief](./workflows/pre-call-research-brief.md) | Auto-build a briefing on any prospect before you talk to them |
| [Pipeline hygiene review](./workflows/pipeline-hygiene-review.md) | Weekly audit that flags stalled and at-risk deals |

### 📐 [Guides](./guides/)
The thinking behind the workflows, so you can build your own.

| Guide | What it teaches |
|---|---|
| [How to design an AI workflow](./guides/how-to-design-an-ai-workflow.md) | The anatomy of a reliable, repeatable AI instruction set |
| [Connecting AI to your tools](./guides/connecting-ai-to-your-tools.md) | Plain-English intro to giving AI access to your CRM, calendar, and docs |
| [Keeping a human in the loop](./guides/keeping-a-human-in-the-loop.md) | Where to let AI run and where to make it stop and ask |

## The core idea

An "AI workflow" is just a **very clear set of written instructions** that an AI follows the same way every time. Think of it like a recipe, or an SOP for a new hire, except the new hire is Claude and it works instantly, 24/7, and never forgets a step.

A good workflow has four parts:

1. **A trigger** — what makes you run it ("process the meeting with Acme")
2. **Inputs** — what the AI needs (the transcript, the company name)
3. **Steps** — the exact sequence, in order, with rules for edge cases
4. **Stops** — the points where it must pause and get your approval before doing something irreversible

Master those four and you can automate almost any recurring sales task. The [design guide](./guides/how-to-design-an-ai-workflow.md) goes deep; the [workflows](./workflows/) are working examples to copy.

## How to use these

- **No tools connected?** The workflows still work as smart prompts — you paste in the transcript, the AI produces the summary and drafts, you copy the output where it needs to go.
- **Tools connected?** (Claude with connectors, or a custom GPT with actions.) The AI does the copying too. See [connecting AI to your tools](./guides/connecting-ai-to-your-tools.md).

Start with the [post-meeting processor](./workflows/post-meeting-processor.md). It saves the most time on day one.

## Who made this

I'm Eli. 12 years in B2C and B2B sales, as a rep and a manager, now consulting founders on building sales from zero and using AI to do it without hiring a big team.

Pairs with my [sales-for-founders](https://github.com/elizavetasukhonosova/sales-for-founders) repo (the prompts and playbooks for the human parts). I also write on selling into industrial and enterprise buyers at **[elizavetaas.substack.com](https://elizavetaas.substack.com/)**.

If this saved you an afternoon, ⭐ star it.

📧 elizaveta.sukhonosova@gmail.com

## License

MIT. Use it, adapt it, sell more.
