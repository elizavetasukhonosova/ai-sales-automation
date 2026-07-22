# How to Design an AI Workflow

Once you can write your own workflows, you stop depending on other people's prompts and start automating anything repetitive in your business. This is the whole method, and it's simpler than it sounds.

## An AI workflow is a recipe, not magic

Think of onboarding a smart new assistant who is fast, tireless, and slightly too literal. They'll do exactly what you write, every time, without initiative or common sense about consequences. Your job is to write instructions so clear that a literal-minded genius can't get them wrong.

That's all a workflow is: **a written procedure the AI follows the same way every time.** The skill is in the writing, and it's a skill you already have if you've ever documented a process for a colleague.

## The four parts of every reliable workflow

### 1. The trigger

How you'll invoke it and how the AI knows what you're asking for.

> "When I say 'process the meeting with [company]', run this workflow."

Give it a few phrasings, because you won't remember the exact one. Clear triggers stop the AI from running the wrong procedure.

### 2. The inputs

Everything the AI needs before it can start. List them explicitly, and tell it to **ask** if something's missing rather than guess. Guessing is where AI workflows go wrong.

> "Before starting, confirm you have: the transcript, the company name, and the customer's main goal. If any is missing, ask me."

### 3. The steps

The procedure itself, numbered, in order. Two rules make steps reliable:

- **One action per step.** "Summarize the meeting AND update the CRM AND draft an email" is three steps, not one. Split them so the AI can't skip the middle.
- **Handle the edge cases inline.** Don't just say "find the company." Say "find the company; if several match, use the most recent one and tell me which." The edge cases are where vague workflows fall apart.

### 4. The stops

The points where the AI must pause and get your approval before continuing. This is the part beginners forget and it's the most important one. Anything with consequences — sending a message, deleting data, creating records — gets a stop in front of it. Full treatment in [keeping a human in the loop](./keeping-a-human-in-the-loop.md).

## Write it like an SOP, test it like software

**Draft:** write the four parts in plain language. No technical syntax needed. If a competent human could follow it, the AI can.

**Test:** run it on a real example and watch where it goes wrong. It will go wrong, the first time, in a specific spot.

**Patch:** wherever it made a bad call, add a rule. "It picked the wrong company" becomes "if several match, use the most recently updated one." Each patch makes it more reliable.

**Freeze:** after a few rounds it runs clean. Save it. Now you have an asset you use forever.

This loop — draft, test, patch — is the entire craft. Three iterations usually gets a workflow from "flaky" to "trustworthy."

## Make it sound like you

For anything customer-facing, the AI's default voice is generic. Fix it once: run the workflow, correct the tone, and paste your corrections into the instructions as examples ("write like this, not like that"). After that it defaults to your voice. Giving it two or three real examples of your writing beats any amount of describing your style in the abstract.

## What to automate first

Rank your recurring tasks by two questions: how often do you do it, and how little judgment does it need? The top-right quadrant — frequent and low-judgment — is where you start. Meeting notes, follow-up drafts, research briefs, and CRM updates all live there. Save the high-judgment work (deciding whether to walk from a deal, how to price) for yourself; that's not automation, that's your job.

## The mindset that makes this click

You are not "using AI." You are **writing procedures and hiring an instant, tireless worker to run them.** The leverage isn't in any single clever prompt; it's in building a small library of reliable workflows that quietly handle the parts of your week that were never worth your time. Build five good ones and you've effectively hired an operations person who works for pennies and never sleeps.
