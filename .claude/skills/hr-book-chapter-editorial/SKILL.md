---
name: hr-book-chapter-editorial
description: "Use this skill whenever Katherine wants to write, draft, edit, revise, audit, polish, or build a chapter of HR Is Not Your Friend. Triggers include any mention of chapter writing, chapter editing, chapter drafting, chapter structure, chapter voice, chapter pass, book section, survival guide framing, or continuing work on the book. Also triggers when Katherine says 'let's work on Chapter [X],' 'start Chapter [X],' 'new chapter,' 'chapter session,' 'voice audit,' 'pass this chapter,' or references any chapter by number or title. Always use this skill for chapter-related book work. This skill runs automatically and does not require Katherine to ask for it."
---

# HR Is Not Your Friend: Chapter Editorial Skill

## Core Book Identity

This book is not a career advice book. It is a workplace survival guide.

The editorial goal is to help workers stay employed, stay sane, preserve leverage, protect themselves, and understand what the company is doing before the company finishes writing the record.

The book's core thesis:

The company has a playbook. It has HR templates, performance language, severance deadlines, investigation protocols, calendar records, payroll systems, and lawyers. Most employees have memory, shock, fear, and a folder of emails they saved too late. This book is the missing playbook.

Every chapter must leave the reader with three feelings:

1. I know you.
2. This was not your fault, but it was not safe.
3. Here is the move you can make today.

## When This Skill Triggers

Any time Katherine wants to write, edit, revise, audit, polish, or build a chapter of the book. This includes new chapters, revisions to existing chapters, continuation of in-progress chapters, chapter strategy, voice audits, pass audits, chapter comparison, and final polish.

## Before You Begin

Read the playbook at:

`/mnt/user-data/outputs/HR_Is_Not_Your_Friend_Chapter_Editorial_Playbook.md`

The playbook is the authority unless Katherine gives newer chapter-specific instructions in the conversation.

If newer instructions conflict with the playbook, follow Katherine's latest instruction and flag the conflict briefly.

## Session Startup Protocol

When Katherine starts a chapter session, run this sequence.

### Step 1: Identify the Chapter

Identify the chapter number and title if provided.

Check project knowledge, prior chats, and any current draft for:

- Existing chapter draft
- Prior rulings
- Voice flags
- Structural decisions
- Research anchors
- Legal framework
- Chapter-specific banned phrases or deliberate exceptions

Do not ask Katherine which chapter if she already named it.

### Step 2: Determine Stage

The chapter is in one of five stages:

**Stage A: Pre-Drafting** — No draft exists.

- Gather client stories, personal observations, legal framework, hypocrisy moments, power dynamics, research anchors, psychology, tactical tools, emotional beats, and survival move.
- Do not draft a full chapter until Katherine has provided enough raw material or asks you to make a best-effort draft.

**Stage B: First Draft** — Context exists, but no full draft exists.

- Draft a full chapter using the flexible chapter architecture below.
- Apply voice rules from the start.
- Include practical tools, legal framing, emotional reframe, and endnotes.

**Stage C: Revision** — A draft exists.

- Read the draft.
- Identify what the chapter is trying to do.
- Run the editorial passes.
- Present findings with rulings and proposed fixes.

**Stage D: Final Polish** — Chapter is near complete.

- Run voice, logic, trim, survival-guide, bestseller, and final-read passes.
- Do not restructure unless necessary.
- Prioritize clarity, punch, and reader momentum.

**Stage E: Voice / Line Audit Only** — Katherine asks for specific line-level or voice feedback.

- Do only the requested audit.
- Do not relitigate the full chapter unless a major issue appears.

## Core Voice Rules

Check every chapter output against these rules:

- No em dashes except inside official citation titles or quoted source material.
- Avoid "matter/matters."
- Avoid "trap/traps/trapped" unless Katherine intentionally approves the framing.
- Avoid "real/really" except in dialogue, citation titles, or deliberate emphasis.
- Avoid repetitive "not X but Y" constructions.
- No random bolding.
- No AI-generic phrases.
- No motivational-speaker cadence.
- No keynote triplets unless rhythm demands it and it sounds like Katherine.
- Use short declarative sentences.
- Use prosecutorial first person.
- Use direct address to readers.
- Name the company as the actor.
- Prefer "the company did X" over passive constructions.
- Use anger with precision.
- Validate the reader before correcting the reader.
- Do not shame the survival strategy. Replace it.

## Automated Voice Checks

When working in a file, run:

```bash
grep -n -i -w "matter\|matters\|trap\|traps\|trapped\|real\|really" chapter.md
grep -n "—" chapter.md
```

These are flags, not automatic failures.

Allowed exceptions:

- Official case, article, or book titles.
- Direct quotations.
- Dialogue.
- Katherine-approved deliberate phrasing.
- Necessary legal terms.
- Previously ruled exceptions.

Report exceptions clearly.

## Flexible Chapter Architecture

Not every chapter needs the same structure. Use the architecture that best serves the chapter.

A chapter may use:

### One-Story Structure

Best when one composite carries the whole concept.

1. Author's note / chapter frame
2. Primary story
3. Thesis / reader validation
4. Psychology / bias / power mechanism
5. Consultation section: If [Name] Had Come to Me
6. Pattern recognition
7. They Say / You Say or tactical tool
8. Your Tactical Move
9. Law section
10. Reframe
11. Endnotes

### Two-Story Structure

Best when the chapter compares two related patterns.

1. Author's note / chapter frame
2. Story One
3. If [Name] Had Come to Me
4. Pattern / concept / research
5. Story Two
6. If [Name] Had Come to Me
7. Tactical move
8. Law section
9. Reframe
10. Endnotes

### Hybrid Structure

Best when the chapter needs one primary story and several cross-profession miniatures.

1. Author's note / chapter frame
2. Primary story
3. Thesis and validation
4. Pattern miniatures
5. Psychology / research
6. Consultation and tool
7. Tactical move
8. Law section
9. Reframe
10. Endnotes

Do not force a chapter into two stories if one story is stronger.

Do not force "If [Name] Had Come to Me" to appear immediately after the story if the chapter flows better through psychology, bias, or pattern first.

The structure must serve reader momentum.

## Target Length

General target: 5,000 to 6,500 words before endnotes.

Shorter is acceptable if the chapter is sharp, complete, and useful.

Longer is acceptable only if every section does a new job.

Do not preserve length for its own sake. Cut echoes.

## Required Chapter Functions

Every chapter must include:

- A human story with betrayal, consequence, and a gavel line.
- A clear workplace pattern.
- The company's incentive.
- The reader's survival strategy and why it made sense.
- The moment the strategy stopped protecting them.
- The legal or leverage consequence.
- At least one concrete tool the reader can use.
- A recognition checklist or pattern language.
- A "what to do this week" action plan.
- A plain-language law section.
- A reframe that gives agency without pretending the workplace is fair.
- Endnotes with verified sources.

## Required Survival-Guide Elements

Each chapter must answer:

1. What is the danger?
2. Why does the employee not see it sooner?
3. How does the company benefit?
4. What is the smallest protective move the reader can make while still scared?
5. What should the reader save?
6. What should the reader put in writing?
7. What should the reader not do too quickly?
8. When should the reader call an attorney?
9. What clock or deadline may be running?
10. What does the company get to deny if the reader does nothing?

Survival-guide tone:

- Do not tell the reader to simply be brave.
- Do not assume the reader can quit.
- Do not assume the reader can safely confront.
- Do not shame fear, appeasement, loyalty, silence, or delay.
- Treat those as survival strategies that need another layer of protection.
- Give moves that can be done quietly, from inside the job.

Useful survival lines:

- "The goal is not to win every conversation. The goal is to stop being the only person with no proof of what happened."
- "You may not be able to change the company today. You can change what the company gets to deny tomorrow."
- "The company's version gets written whether you participate or not."
- "This book is about documenting back."

## Required Moral Anger / Power Pass

Every chapter must identify the company's benefit.

Ask:

- What did the company get?
- What did the employee give?
- What did the company call it?
- What did it actually function as?
- What did the company avoid paying, naming, documenting, investigating, or admitting?
- How did the company use warmth, loyalty, fear, ambition, silence, or confusion?
- Where is the hypocrisy between what the company said and what it did?
- Did the company create the rule, punish the violation, and call the punishment feedback?
- Does the chapter blame the employee too much?
- Does the chapter make clear that the employee adapted to a broken incentive system?

The anger should be tactical, not theatrical.

Good anger:

- "HR can cry and still attach the release."
- "The absence of a record is not neutral. It is useful."
- "The company reserves precision for itself and calls your precision an attitude."
- "The company accepted every benefit of that work. Then, when it no longer needed her, it treated the absence of a paper trail like the absence of a problem."

Bad anger:

- Cartoon villains.
- Overclaiming illegality.
- Insults.
- Rage that replaces analysis.
- Blaming all individual managers when the chapter is about institutional incentive.

## Required Validation Pass

Every chapter must validate before it instructs.

Ask:

- What did the reader do that made sense at the time?
- What did the survival strategy protect them from?
- Why would a smart person make this choice?
- What fear was rational?
- What did the company reward before punishing or exploiting it?
- Where might the reader be blaming herself?
- Does the chapter say clearly: "You were not stupid. You were adapting. Now you are adapting again"?

Validation must not remove accountability. It should remove shame.

Useful validation forms:

- "If you recognize yourself here, you are not foolish."
- "That fear is rational. It is also useful to the company."
- "You learned how to survive a workplace by becoming easy to keep close."
- "This worked until it became dangerous."
- "The strategy got you here. It should not negotiate your severance package."

## Required Psychology Pass

Each chapter should include two to four psychology or research anchors, depending on the topic.

Rules:

- Human experience first.
- Academic name second.
- No literature-review feel.
- Research should explain the reader's lived experience, not interrupt it.
- Use psychology to deepen the "why," not decorate the chapter.

Psychology categories to consider:

- Escalation of commitment
- Psychological contract
- Intermittent reinforcement
- Fawn response / appeasement
- Conformity
- Agreeableness income penalty
- Warmth / competence bias
- Backlash effect
- Tightrope bias
- Role congruity
- Moral injury / betrayal
- Learned helplessness
- Ambiguity aversion
- Loss aversion
- Status quo bias
- Impression management
- Identity threat
- Sunk cost fallacy
- Retaliation fear
- Institutional betrayal

For each psychology point, ask:

- Does this help the reader feel seen?
- Does it explain why the employee stayed, softened, waited, signed, or doubted herself?
- Does it clarify the company's leverage?
- Can it be said in one plain paragraph?
- Is the citation in the endnotes?

## Required Bestseller Pass

Every chapter should contain:

- A reader identity. Example: "If you built your career on being the easy one, this chapter is for you."
- A sticky thesis line. Example: "The company had a file. Elena had a reputation. Only one of those is evidence."
- A moral indictment. Example: "The company accepted every benefit of that work. Then, when it no longer needed her, it treated the absence of a paper trail like the absence of a problem."
- One concrete survival move. Example: "After any conversation about your pay, your role, or your performance, send the calm follow-up email."
- One emotional release. Example: "You were not stupid. You were adapting. Now you are adapting again."
- One final line that lands. Example: "Elena was easy to work with. That is what made her easy to remove."

Ask:

1. Would a reader underline this?
2. Would a reader send this chapter to a friend?
3. Does the chapter name something people feel but have not been able to explain?
4. Does the chapter make the invisible mechanism visible?
5. Does the chapter give the reader one move they can do today?
6. Does the ending leave force, not fog?

## Required Screenshottable Elements

Each chapter should include five to seven, but use judgment. Do not overload the chapter with tables.

Possible elements:

- Email template reader can copy
- Red flags / recognition checklist
- Tactical chart
- They Say / You Say table
- Vocabulary decoder
- What to Save checklist
- Numbered action plan with timing
- "If this is happening, start here" box
- One-sentence survival rule
- Attorney call script

Only use two tables if both do different jobs. Otherwise prefer one table and one numbered list.

## Required Uncomfortable Truths

Each chapter should include three to five of these:

- One counterintuitive insight
- One "they already decided" moment
- One "feedback as translation" observation
- One "silence is information" line
- One "you are being watched too" inversion
- One "timing is leverage" statement
- One "the company is optimizing, not evaluating" reframe
- One "the company benefits from your survival strategy" moment
- One "the law may not save you if the record does not exist" moment
- One "the deadline does not wait for you to process what happened" moment

## 17-Pass Editorial Sequence

Run passes in order unless Katherine asks for a specific pass.

Do not ask Katherine before every pass unless she requested a step-by-step process. For long audits, present grouped findings and recommended fixes.

### Pass 1: Story Compression

- Does the story move?
- Is there setup, company benefit, betrayal, consequence?
- Is the story too long for the point it serves?
- Does the gavel line land?
- Is there one private human moment?
- Does the story avoid unnecessary detours?
- Does the reader understand what the employee believed and what the company knew?

### Pass 2: Consultation Structure

- Does "If [Name] Had Come to Me" appear where the chapter needs it?
- Does it sound like Katherine in her office?
- Does it include one concrete tool?
- Does it show what Katherine would have changed?
- Does it name missed doors, timing, and leverage?
- Does it avoid blaming the client while still being honest?

### Pass 3: Structure and Flow

- Does each section do one job?
- Are section titles active and non-boring?
- Are transitions explicit?
- Does the chapter read as one piece, not a patchwork?
- Is there any double ending?
- Does the chapter escalate instead of circle?

### Pass 4: Logic and Cause-Effect

- Does the timeline track?
- Does each story beat cause the next?
- Are there orphaned references?
- Does the reader understand why the company acted?
- Does each paragraph follow from the prior paragraph?
- Are there logical contradictions?
- Do hedges remain consistent?
- Does the tactical advice match the legal framing?
- Can the reader answer "why did that happen?" after every major event?
- Can the reader answer "so what?" after every analytical paragraph?

### Pass 5: Hypocrisy / Power Dynamics

- Is the gap between what the company says and does explicit?
- Is the contradiction shown in at least two places?
- Is active company benefit shown, not passive neglect?
- Does the reader feel the unfairness without being told?
- Does the chapter name the company's incentive?

### Pass 6: Emotional Punch

- Is there a private human moment?
- Is the identity cost named?
- Is self-doubt caught and reframed?
- Is Katherine's anger present?
- Would someone underline something every two to three paragraphs?
- Does the chapter create recognition without shame?

### Pass 7: Survival Guide

- Does the chapter identify the danger?
- Does it explain why the employee did not see it sooner?
- Does it name the smallest protective move?
- Does it avoid assuming the reader can quit or confront?
- Does it tell the reader what to save, write, and delay?
- Does it give time-based actions?
- Does it tell the reader when to call an attorney?
- Does the chapter feel like a field guide, not a lecture?

### Pass 8: Research and Psychology

- Are there two to four research anchors?
- Does research follow lived experience?
- Does psychology explain behavior without excusing the company?
- Does the section avoid sounding academic?
- Are endnotes complete and accurate?

### Pass 9: Accessibility

- Would a nurse, teacher, retail manager, paralegal, salesperson, or office manager understand every sentence?
- Is jargon translated?
- Are cross-profession examples specific?
- Are tools universal?
- Is the chapter too startup-coded, law-firm-coded, or executive-coded?

### Pass 10: Legal Accuracy

- Are legal citations verified?
- Are legal conclusions hedged?
- Is unfair versus unlawful stated clearly?
- Is at-will employment defined if relevant?
- Are filing deadlines correct?
- Is temporal proximity explained where relevant?
- Is protected status/activity complete enough?
- Is the chapter honest about when there may be no claim?
- Are release/revocation rules accurate if discussed?
- Does the chapter avoid giving jurisdiction-specific advice as universal?

### Pass 11: Actionability

- Does the reader know what to do after each major section?
- Are steps timed: today, tonight, within seven days, within thirty days?
- Is there a first step?
- Does the reader know what to save?
- Does the reader know what to say?
- Does the reader know how to find an attorney and what to ask?
- Are tools clear enough to copy?

### Pass 12: Voice

- Does it sound like Katherine?
- Is the company the actor?
- Is anger precise?
- Are sentences clean and declarative?
- Is the prose human, not generic?
- Are there podcast phrases, self-help cadences, or motivational lines?
- Are there too many slogans?
- Does the chapter avoid random bolding?

### Pass 13: Voice Rules / Automated Flags

Run the grep checks.

- Review every flagged word.
- Mark deliberate exceptions.
- Fix accidental violations.
- Check for em dashes.
- Check for repeated "not X but Y."
- Check for overused chapter-specific phrases.

### Pass 14: Trim and Precision

- Does any paragraph repeat an earlier point?
- Can any sentence be cut by one-third?
- Are there too many standalone post-style lines?
- Are there two tables doing the work of one?
- Is legal framing duplicated?
- Is the thesis repeated too many times?
- Are the best lines buried in cushion?

### Pass 15: Clarification Pass

Ask:

- What might a reader misparse?
- What pronoun has a weak antecedent?
- What sentence has a grammar ambiguity?
- What concept needs one more sentence?
- What legal rule needs one plain-language explanation?
- What chapter distinction needs clarification?
- What section title does not tell the reader why they are there?

### Pass 16: Bestseller Pass

Ask:

- What is the chapter's sticky identity?
- What line will readers repeat?
- What line will make readers feel exposed?
- What line will make readers feel forgiven?
- What is the one move they will remember?
- Is there enough scene?
- Is there enough anger?
- Is there enough relief?
- Is there a final line that lands?

### Pass 17: Final Read

Read start to finish without editing. Answer:

1. Did I want to keep reading at every section break?
2. Did I feel the unfairness without being told?
3. Did the chapter validate before instructing?
4. Did the company's incentive become visible?
5. Do I know what to do this week?
6. Does every line sound like Katherine?
7. Would I send this to someone going through this?
8. Does the ending leave force?

## Output Protocol

When working with files:

- All chapter files go to `/mnt/user-data/outputs/`
- Backup before major rewrites: `Chapter_X_BACKUP.md`
- Run voice-rule grep checks before presenting final version
- Present files with `present_files`
- End completed file passes with word count and section structure

When working in chat only:

- Do not pretend a file was created.
- Provide rulings, replacement text, or revised sections directly.
- Use concise editorial reasoning.
- Do not over-explain obvious fixes.
- Prioritize execution-ready language.

## Katherine's Voice Examples

### Sounds like Katherine

- "It is not disloyalty. It is due diligence."
- "The company is building its file. You need to be building yours."
- "You were operating on a promise the company never made in any way that required it to follow through."
- "The arrangement was designed to benefit the company. It was working exactly as intended."
- "A title the company withheld is a business decision. It is not an assessment of your capability."
- "HR can cry and still attach the release."
- "The absence of a record is not neutral. It is useful."
- "The company reserves precision for itself and calls your precision an attitude."
- "You may not be able to change the company today. You can change what the company gets to deny tomorrow."
- "The company's version gets written whether you participate or not."

### Does Not Sound Like Katherine

- "Make the math work."
- "It is the first thing you do for yourself after spending years doing everything for them."
- "It gives you leverage. It gives you choice. It gives you clarity."
- "Never confuse a title they withheld with a verdict on your worth."
- "The system" when you mean "the company."
- "Unlock your power."
- "Step into your worth."
- "Own your story."
- "Your truth is your superpower."
- Generic HR-consultant language.
- Generic self-help language.

## Data and Sourcing Standards

Use reliable sources only.

Preferred sources:

- Bureau of Labor Statistics for employment data
- EEOC for charge and enforcement data
- NLRB for protected concerted activity
- Department of Labor for wage/hour and leave rules
- SEC filings, court documents, public lawsuits
- Peer-reviewed academic studies
- Major news outlets such as Reuters, Bloomberg, NPR, WSJ, NYT, AP
- State agencies for state-specific legal rules
- Official statutes and cases for legal authority

Use with caution:

- PayScale, Glassdoor, Levels.fyi, LinkedIn salary data; caveat as self-reported or estimate-based
- Surveys by advocacy groups; verify methodology
- Popular psychology articles; use only as support, not authority

Avoid:

- Unsourced statistics
- Blog posts as authority
- Viral LinkedIn claims
- Unverified legal summaries
- Overgeneralized employment-law claims
- Treating one jurisdiction's rule as universal

## Legal Safety Standards

- Do not say something is illegal unless the facts and law support that.
- Use "may," "can," "could," or "depending on the facts" where needed.
- Distinguish unfair from unlawful.
- Distinguish protected status from protected activity.
- Do not universalize state-specific rules.
- Include deadlines where delay is dangerous.
- Encourage attorney consultation before reporting, resigning, or signing when legal rights may be affected.
- Make clear the record cannot manufacture a claim that does not exist.
- Make clear the record can create options even when there is no claim.
