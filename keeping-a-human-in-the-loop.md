# Keeping a Human in the Loop

The single most important design decision in any AI workflow: where does the machine stop and ask you? Get this right and AI is pure leverage. Get it wrong and it quietly does damage in your name.

## Why "fully automated" is a trap in sales

The dream sold online is a hands-off machine that runs your whole sales motion. In sales specifically, that dream backfires, because the currency of sales is trust, and trust breaks in exactly the places AI is weakest: judgment, tone, and knowing when the rules don't apply.

An AI will confidently send a follow-up to a prospect whose spouse just died (it was in an email it didn't fully read). It will log a "next step" that misrepresents what the customer actually agreed to. It will apply your standard cadence to the one VIP who needed a personal touch. None of these are bugs you can prompt away. They're the reason a human stays in the loop.

## The reversibility test

For every action in a workflow, ask one question: **if this goes wrong, can I undo it?**

- **Reversible** (a draft, a CRM note, an internal summary): let the AI do it freely. Worst case, you edit or delete it. Low stakes, high convenience.
- **Irreversible** (sending an email, messaging a customer, deleting a record, booking over someone's calendar): the AI prepares it, **you approve it.** The cost of a mistake is real and can't be taken back.

This one test decides where every "stop and ask" goes. It's simple enough to apply on the fly and it almost never steers you wrong.

## The three levels of autonomy

Match the level to the stakes:

**Level 1 — Draft only.** The AI produces; you do everything else. Use for anything customer-facing that carries your reputation. All outbound email lives here.

**Level 2 — Act and report.** The AI does reversible things automatically and tells you what it did afterward. Use for internal, low-stakes actions: logging notes, creating your own tasks, updating a status.

**Level 3 — Act freely.** The AI does it and you don't check. Reserve this for zero-stakes, purely internal work: formatting, summarizing, drafting things only you will read.

When unsure, drop a level. The cost of over-checking is a few seconds; the cost of under-checking is a customer.

## Where to put stops in a sales workflow

Concrete defaults, drawn from what actually goes wrong:

- **Before any outbound message** → always stop. No exceptions. AI drafts, human sends.
- **Before creating tasks or records** → stop once to let you select which ones are real (auto-creating everything buries you in noise).
- **Before anything touching a customer's calendar** → stop.
- **When the AI is uncertain or data is ambiguous** → instruct it to stop and ask rather than guess. "If several companies match, ask me" prevents the confident-but-wrong failure that erodes trust in the whole system.
- **After it takes reversible actions** → not a stop, but require a report ("here's what I logged"), so nothing happens invisibly.

## The paradox worth internalizing

More human checkpoints, placed well, make you *more* willing to automate, not less. When you trust that the AI can't send something embarrassing or delete something important, you happily hand it the whole tedious middle of your workflow. The stops aren't friction slowing the machine down. They're the guardrails that let you drive fast.

Design them in from the first draft, never bolt them on after something breaks.
