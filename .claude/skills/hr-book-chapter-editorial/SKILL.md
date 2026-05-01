---
name: hr-book-chapter-editorial
description: Use this skill whenever Katherine wants to write, draft, edit, revise, or build a chapter of "HR Is Not Your Friend." Triggers include any mention of chapter writing, chapter editing, chapter drafting, starting a new chapter, or continuing work on the book. Also triggers when Katherine says "let's work on Chapter [X]," "start Chapter [X]," "new chapter," "chapter session," or references any chapter by number or title. Always use this skill for any chapter-related work on the book. This skill runs automatically and does not require Katherine to ask for it.
---

# HR Is Not Your Friend: Chapter Editorial Skill

## When This Skill Triggers

Any time Katherine wants to write, edit, revise, or build a chapter of the book. This includes new chapters, revisions to existing chapters, and continuation of in-progress chapters.

## Before You Begin

Read the playbook at `/mnt/user-data/outputs/HR_Is_Not_Your_Friend_Chapter_Editorial_Playbook.md` before starting any chapter work. It contains every editorial standard, checklist, and audit question. The playbook is the authority.

## Session Startup Protocol

When Katherine starts a chapter session, run this sequence:

### Step 1: Identify the Chapter

Ask which chapter Katherine wants to work on. Check the project knowledge and past chats for any prior work on that chapter.

### Step 2: Determine Stage

The chapter is in one of four stages:

**Stage A: Pre-Drafting (no draft exists)**

- Run context-gathering questions before any writing
- Gather: client stories, personal experiences, legal frameworks, case law, research, emotional beats, hypocrisy moments, tactical tools
- Do not draft until Katherine has provided the raw material

**Stage B: First Draft (context gathered, no draft yet)**

- Write the full chapter from scratch following the Chapter Structure Template in the playbook
- Apply all voice rules from the start
- Include all required screenshottable elements

**Stage C: Revision (draft exists)**

- Read the existing draft
- Run the 13-pass editorial sequence (see below)
- Present findings and ask Katherine which fixes to execute

**Stage D: Final Polish (chapter is near complete)**

- Run passes 11-14 only (voice, voice rules, trim, final read)
- Present the chapter for send

### Step 3: Load Voice Rules

These are non-negotiable. Check on every output:

```
grep -n -i -w "matter\|matters\|trap\|traps\|trapped\|real\|really" chapter.md
grep -n "—" chapter.md
```

- No em dashes
- No "matter/matters"
- No "trap/traps/trapped"
- No "real/really"
- No "not X but Y" constructions
- No random bolding
- No AI-generic phrases
- Short declarative sentences
- Prosecutorial first person
- Direct address to readers

## 14-Pass Editorial Sequence

Run these in order. Present findings after each pass. Ask Katherine which fixes to execute before moving to the next pass.

### Pass 1: Story Compression

- Do stories match Chapter 1 Marcus register (~300 words)?
- Setup → betrayal → outcome, no detours?
- Gavel line at the end?
- Interior beat present but short (2-3 sentences)?

### Pass 2: Consultation Structure

- Does "If [Name] Had Come to Me" flow directly from the story with no section break?
- Does it include one concrete tool (email template, script)?
- Does it sound like Katherine in her office?

### Pass 3: Structure and Flow

- Five to six sections maximum
- Each section does one job
- No double endings
- Transitions explicit between every section
- Chapter reads as one piece, not a patchwork

### Pass 4: Logic and Cause-Effect

- Does the timeline track? Are events in the right order?
- Does each story beat cause the next one?
- Are there orphaned references (mentioning something that was cut or never introduced)?
- Does the reader understand WHY the company made each decision, not just WHAT it did?
- Does each paragraph's claim follow from the prior paragraph?
- Are there logical leaps from observation to conclusion without showing the connection?
- Does the chapter contradict itself anywhere?
- Do the legal hedges match the story's assertions?
- Does the tactical advice match the legal framing?
- If the chapter qualifies a claim in one place, does it maintain that qualification throughout?
- Can the reader answer "why did that happen?" after every major event?
- Can the reader answer "so what?" after every analytical paragraph?

### Pass 5: Hypocrisy / Power Dynamics

- Gap between what company says and does explicitly named?
- Contradiction shown in at least two places per story?
- Active deception shown, not just passive neglect?
- Reader feels unfairness without being told "this is unfair"?

### Pass 6: Emotional Punch

- Private human moment present (car scene, 2 a.m., etc.)?
- Identity cost named?
- Self-doubt caught and reframed?
- Katherine's anger present in at least one moment?
- Every 2-3 paragraphs: would someone underline this?

### Pass 7: Research and Psychology

- Two to three research anchors (Staw, Rousseau, Bidwell, or chapter-specific)?
- Human experience first, academic name second?
- Endnotes complete in Bluebook format?

### Pass 8: Accessibility

- Would a nurse/teacher/retail manager understand every sentence?
- All jargon translated on first use?
- Cross-profession examples specific with duties named?
- Conversion ladder universal, not startup-coded?

### Pass 9: Legal Accuracy

- All citations verified, Bluebook format?
- Every legal conclusion hedged or attributed?
- Unfair vs. unlawful stated clearly?
- At-will employment defined?
- Filing deadlines included with correct numbers?
- Temporal proximity explained where relevant?
- Protected status list complete?
- Chapter honest about when there may be no claim?

### Pass 10: Actionability

- Reader knows what to do after each section?
- Steps have timing ("today," "this week," "within 24 hours")?
- Five to seven screenshottable tools included?
- Reader knows how to find an attorney and what to say?
- Prioritization on checklists?
- Immediate first step identified?

### Pass 11: Voice

- Sounds like Katherine, not generic advice?
- No podcast phrases, self-help cadences, keynote triplets?
- No motivational-speaker lines?
- Company named as actor, not passive constructions?
- "Here is what I would tell you" not "this is what you do next"?

### Pass 12: Voice Rules (automated)

Run the grep checks. Zero tolerance.

### Pass 13: Trim and Precision

- Any paragraph restate what a prior one said?
- Any sentence use ten words where five would work?
- Post-style standalone lines that should be book prose?
- Same concept in two tables that should be one?
- Legal framing duplicated between consultation and law section?
- Alignment thesis stated more than twice?

### Pass 14: Final Read

Read start to finish without editing. Answer:

1. Did I want to keep reading at every section break?
2. Did I feel the unfairness without being told?
3. Do I know what to do this week?
4. Does every line sound like Katherine?
5. Would I send this to someone going through this?

## Chapter Structure Template

Every chapter follows this architecture:

1. **Story One** (~300 words, flows into consultation)
2. **If [Name] Had Come to Me** (consultation with tool)
3. **The Pattern / Concept** (research, cross-profession examples, Red Flags)
4. **Story Two** (~250-400 words, flows into consultation)
5. **If [Name] Had Come to Me** (different tactical focus)
6. **Your Tactical Move** (Katherine's bridge, chart, They Say / You Say, What to Save, action plan)
7. **What the Law Can and Cannot Do** (3-4 paragraphs, plain language first)
8. **The Reframe** (emotional acknowledgment, thesis, conversion, closing)
9. **Endnotes** (Bluebook format)

Target: 5,500-6,500 words before endnotes.

## Required Screenshottable Elements (5-7 per chapter)

- [ ] Email template reader can copy
- [ ] Red Flags / recognition checklist
- [ ] Tactical chart (Move / What to Do / Why)
- [ ] They Say / You Say table (two columns)
- [ ] Vocabulary decoder (if applicable)
- [ ] What to Save checklist
- [ ] Numbered action plan with timing

## Required Uncomfortable Truths (3-5 per chapter)

- [ ] One counterintuitive insight
- [ ] One "they already decided" moment
- [ ] One "feedback as translation" observation
- [ ] One "silence is information" line
- [ ] One "you are being watched too" inversion
- [ ] One "timing is leverage" statement
- [ ] One "optimizing, not evaluating" reframe

## Output Protocol

- All chapter files go to `/mnt/user-data/outputs/`
- Backup before major rewrites: `Chapter_X_BACKUP.md`
- Always run voice rule grep checks before presenting
- Always present files with `present_files`
- End every completed pass with word count and section structure

## Katherine's Voice Examples

**Sounds like Katherine:**

- "It is not disloyalty. It is due diligence."
- "The company is building its file. You need to be building yours."
- "You were operating on a promise the company never made in any way that required it to follow through."
- "The arrangement was designed to benefit the company. It was working exactly as intended."
- "A title the company withheld is a business decision. It is not an assessment of your capability."

**Does NOT sound like Katherine:**

- "Make the math work" (podcast)
- "It is the first thing you do for yourself after spending years doing everything for them" (self-help)
- "It gives you leverage. It gives you choice. It gives you clarity." (keynote)
- "Never confuse a title they withheld with a verdict on your worth" (motivational speaker)
- "The system" when you mean "the company" (vague)

## Data and Sourcing Standards

- Bureau of Labor Statistics: employment data
- AFL-CIO Executive Paywatch: CEO compensation
- PayScale, Glassdoor, Levels.fyi: market rates (caveat: self-reported)
- News outlets (NPR, Reuters, Bloomberg, WSJ): company incidents
- SEC filings, court documents, public lawsuits: company cases
- Academic studies: peer-reviewed only
- Avoid: blog posts, unverified claims, unsourced statistics
