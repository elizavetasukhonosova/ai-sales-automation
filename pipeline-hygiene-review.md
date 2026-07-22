# Workflow: Pipeline Hygiene Review

A weekly AI audit of your pipeline that tells you the truth you'd rather not see: which deals are stalled, which are fantasy, and what to do about each. Run it every Monday.

## What it does

You give it your current deals (a pasted list or an export). It:

1. Flags every deal with no recent customer activity
2. Flags deals stuck too long in one stage
3. Spots hygiene problems (missing next steps, stale close dates, single-threaded deals)
4. Gives you a short, ranked action list for the week

## The instruction set

```
You are my pipeline auditor. I'll paste my open deals. Be blunt — I'd rather hear
"this deal is dead" than feel good about a full pipeline.

WHAT I'LL GIVE YOU (a row per deal):
Company | Stage | Value | Last customer action | Date of that action | Next step + date | Decision-maker engaged? (y/n)

AUDIT AND REPORT:
1. STALLED — every deal with no customer action in 14+ days. For each: likely cause
   and the one message to send this week.
2. STUCK — deals sitting in the same stage too long (flag anything "verbal" for 3+ weeks —
   that's not verbal, something's blocking it).
3. HYGIENE — deals missing a scheduled next step, deals with a close date already in the past,
   and deals where I've only spoken to one person (single-threaded = fragile).
4. FANTASY CHECK — deals I'm probably keeping alive to feel good. Name them.
5. THIS WEEK — a ranked list of the 5 actions that most improve my pipeline,
   most important first.

End with one honest sentence on the overall health of this pipeline.
```

## Connected version

```
CONNECTED ACTIONS:
- Pull my open deals directly from the CRM instead of me pasting them.
- For each stalled deal, draft the re-engagement message (don't send).
- Flag any deal where the CRM data itself looks wrong (no owner, no amount, no next step).
```

## Why "customer action" is the only honest metric

Most pipelines lie because they advance on *your* activity ("I sent the proposal") instead of the *customer's* ("they brought their boss to the next call"). This audit forces the honest view: a deal only moved if the customer did something. Everything else is you doing homework, which is necessary but isn't progress.

## Field notes

- **Run it before you start selling on Monday,** so the week's actions are set before the inbox hijacks you.
- **The "fantasy check" is the point.** Founders hoard dead deals because a fat pipeline feels safe. A pipeline you can't trust is worse than a small one you can.
- **Act on the breakup recommendations.** Giving a silent prospect permission to say no revives more deals than any follow-up, and clears the ones that were never real.
- **If the same deals get flagged three weeks running,** stop nurturing and close them out. Your attention is the scarce resource, not your pipeline count.
