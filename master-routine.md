# Master Routine

The meta-workflow for running the practice day-to-day. Every slash command,
automation, and client file in this repo should trace back to a phase below.

## Practice

- **Attorney:** Katherine Kleyman (`katherine@kleymanesq.com`)
- **Focus:** NY plaintiff-side employment law
- **Shape:** Sole / small practice

## The 8 phases

Work moves top-to-bottom once per day. Each phase has a narrow job; resist
collapsing them, because the cost of skipping (especially *Audit Gaps* and
*Codify*) shows up days later as a missed deadline or a re-solved problem.

### 1. Scan
Light, fast pass over every input surface so nothing sits unseen.

- Inbox (unread, last 24h)
- Calendar (today + next 3 days)
- NYSCEF / court notifications
- Voicemail and texts
- Task list / tickler

Output: a rough list of what landed. No judgment yet.

### 2. Deepen
Open the items from Scan that looked like they mattered. Read them
properly. Pull the underlying document, not just the notification.

Output: for each item, one line — what it is, what it wants from you.

### 3. Audit Gaps
Look for what *didn't* show up. The dangerous items are the ones no
system surfaces.

- Matters with no activity in N days (pick a threshold per matter type)
- Outbound items awaiting response past their expected turn
- Clients who've gone quiet mid-matter
- Court deadlines approaching that aren't yet on the calendar
- Names showing up in filings but not in the client roster

Output: a short "what's missing" list.

### 4. Prioritize
Rank the combined Deepen + Audit lists. Anchor on:

- Hard deadlines (statute, court order, stipulated extension)
- Client-facing silence aging past comfort
- Highest-leverage draft or call that moves a matter forward

Output: today's top 3–5, this week's next 5–10.

### 5. Draft
Sit down and write — pleadings, letters, emails, memos. One matter at a
time; don't fragment the attention.

### 6. Execute
Send, file, call. Turn drafts into outbound action. File stipulations on
NYSCEF, send demand letters, return client calls.

### 7. Codify
Capture what was learned today so you don't solve it again:

- New matter → add to roster
- New opposing-counsel pattern → note on matter file
- New template-worthy paragraph → save to form bank
- Procedural gotcha → add to a checklist

### 8. Automate
For anything that showed up in Codify more than twice, build the rule:

- Slash command for repeated prompts (`/triage`, `/eod`, `/weekly`)
- Hook or script for repeated mechanical steps
- Calendar template for recurring review cadences

## Active client roster

Source of truth. If a name shows up in a filing, email, or voicemail and
isn't on this list, it's an *Audit Gaps* item — add the matter or
investigate.

| Client | Last activity | Created |
|---|---|---|
| Allyson Stinchfield | 14 days ago | 09/22/25 |
| Britney Galbreath | ~1 month ago | 03/28/25 |
| Christina Johnson | ~1 month ago | 07/24/25 |
| Christine Consolino | 4 days ago | 03/28/25 |
| Cristal Rodriguez | 17 days ago | 01/21/26 |
| Denise Garcia | 5 days ago | 04/17/25 |
| Erin L. Vail | ~1 month ago | 07/08/25 |
| Farzad Ghasemzadeh | 15 days ago | 04/06/26 |
| Fiona Hillery | 11 hours ago | 03/04/26 |
| Jasmina Jahic | 12 days ago | 03/27/25 |
| Manish | ~1 month ago | 03/28/25 |
| Marina Bowlin | 19 days ago | 06/04/25 |
| Mehyar | ~1 month ago | 04/16/25 |
| Michelle Garcia | 11 days ago | 07/10/25 |

_Snapshot date: 2026-04-21. "Last activity" is relative to that date._

## How to run this workflow fresh

If someone else is picking this up cold:

1. Read this file top to bottom.
2. Do one pass of Scan → Deepen → Audit Gaps by hand, without any
   automation. Feel where the friction is.
3. Then, and only then, look at the slash commands and automation in the
   repo. They're accelerators for a workflow you should already understand.
4. When you change the workflow, change this file first. The slash
   commands and automation should follow, not lead.
