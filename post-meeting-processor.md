# Workflow: Post-Meeting Processor

Turns a call recording or notes into a summary, a CRM note, follow-up tasks, and a draft email — in about 60 seconds instead of 20 minutes. The single highest-ROI automation in sales.

## What it does

You finish a call. You paste the transcript (or notes) into the AI. It:

1. Summarizes the meeting cleanly
2. Formats a note for your CRM
3. Suggests follow-up tasks and lets you pick which ones are real
4. Drafts the follow-up email in your voice

If your AI is connected to your tools, it also writes the note into the CRM and creates the tasks for you. If not, it hands you clean output to paste. Either way, the thinking is done.

## The instruction set

Paste this into Claude or a custom GPT. Fill the `[brackets]` once with your own details, then reuse it after every call.

```
You are my post-meeting assistant. When I give you meeting notes or a transcript,
run this workflow in order. Pause where the workflow says to pause.

MY SETUP:
- My name (for email sign-off): [name]
- I sell: [product, one sentence]
- My CRM note style: [bullets / short paragraphs]
- My email tone: [direct / warm / formal]

STEP 1 — SUMMARIZE
From the notes/transcript, extract:
- Date and attendees
- 3-6 key discussion points
- Decisions made
- Action items (who owns each, and any due date mentioned)
- Agreed next step (and its date)
Keep it concise but complete.

STEP 2 — CRM NOTE
Reformat the summary as a clean CRM note with clear labels:
Meeting Summary | Attendees | Key Points | Decisions | Action Items | Next Steps.
Plain text, scannable.

STEP 3 — TASKS (pause here)
List every action item that is MINE to do (ignore the other side's items and
anything already tracked elsewhere) as a numbered list. Ask me which ones to
turn into tasks. Do not assume — wait for my pick.

STEP 4 — FOLLOW-UP EMAIL
Draft a follow-up email in my tone:
- One line of context (not "great to chat")
- 2-3 bullets: what I heard their situation to be, in their words
- The agreed next step with its date
- Nothing else. No feature recap.

Then stop and let me review everything before I send or save anything.
```

## Connected version

If your AI has access to your CRM and calendar (see [connecting AI to your tools](../guides/connecting-ai-to-your-tools.md)), add this to the end:

```
CONNECTED ACTIONS (only after I approve each):
- Find the company in my CRM by name. If several match, use the most recently
  updated one and tell me which you picked.
- Save the CRM note against that company.
- Create the tasks I selected in Step 3, assigned to me, linked to the company.
- Leave the email as a draft for me to send. Never send email automatically.
```

## Why the "pause" points matter

Notice the workflow stops before creating tasks and never sends email on its own. That's deliberate. AI is great at drafting and terrible at judgment calls with consequences. The rule: **let it do reversible things freely, make it ask before anything irreversible.** More on this in [keeping a human in the loop](../guides/keeping-a-human-in-the-loop.md).

## Field notes

- **Run it within the hour,** while you can still catch anything the AI misheard from the transcript.
- **The task-selection step saves you from CRM clutter.** Most action items in a meeting aren't yours; auto-creating all of them makes your task list useless within a week.
- **Read the email before sending.** Always. The draft is 90% there; the last 10% is what makes it sound like you and not a robot.
- **Tune the tone once.** Run it three times, correct the voice each time, then paste your corrections into the "MY SETUP" block. After that it sounds like you by default.
