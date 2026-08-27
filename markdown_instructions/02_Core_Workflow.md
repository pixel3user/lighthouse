# 02 Core Workflow



---

## Source: 1reviewtheenvironment.html

Lovable App



![Handshake](./1reviewtheenvironment_files/sidebar-logo-BhcHUO7k.png)

* [Welcome](https://project-lighthouse-instructions.learn.joinhandshake.com/)
* [Task overview](https://project-lighthouse-instructions.learn.joinhandshake.com/assignment)
* [Workflow](https://project-lighthouse-instructions.learn.joinhandshake.com/workflow)Collapse

  * [0. Understand personas](https://project-lighthouse-instructions.learn.joinhandshake.com/personas)
  * [1. Review the environment](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1-environment)
  * [2. Write the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt)Collapse

    * [1. How to stump a model fairly](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty)
  * [3. Identify critical elements](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-critical-elements)
  * [4. Write failure justifications](https://project-lighthouse-instructions.learn.joinhandshake.com/step-4-justifications)
  * [5. List golden trajectory](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-golden-trajectory)
  * [6. Write rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-rubric)Collapse

    * [A. Write the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-principles)
    * [B. Weighting the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting)Collapse

      * [• Weighting principles](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-principles)
      * [• Weighting guide](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-tiers)
    * [C. Audit your rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-audit)
    * [D. Rubric examples](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-examples)
* [Submission checklist](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-review-checklist)
* [Golden examples](https://project-lighthouse-instructions.learn.joinhandshake.com/examples)Collapse

  * [1. Atlanta brand designer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-9f14845b)
  * [2. San Francisco engineer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/mark-ce08d55b)
  * [3. Denver construction manager & nurse couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/matt-b2b023f3)
  * [4. Tampa retired couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-74b127ce)
  * [5. Phoenix bookkeeper](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/phoenix-bookkeeper)
* ---
* [Reviewer playbook](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-playbook)Collapse

  * [1. Workflow and send-backs](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-workflow)
  * [2. Reviewing the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-prompt)
  * [3. Reviewing the rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-rubric)
  * [4. Leaving feedback](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-feedback)
  * [5. SQS scoring](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-sqs)
  * [6. Reviewer quiz & Case files](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-quiz)
* [FAQ](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq)Collapse

  * [1. Set up payments & Claim your first task](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/quick-start)
  * [2. Onboarding, referrals & Eligibility](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/essentials)
  * [3. Task access & Platform glitches](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/task-access)
  * [4. Tracking your hours](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/time-tracking)
  * [5. Payment schedule & Methods](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/getting-paid)

# Step 1 - Review the environment

Before you write a single word of prompt, spend time inside the workspace. The platform shows an **Open Environment** button - click it. You'll see a file explorer with everything the agent will have access to: bank and credit card statements, paystubs, tax forms, brokerage statements, transaction CSVs, plus any user-context notes.

**Open every file at least once.** Skim PDFs. Scroll through transaction CSVs.

Budget **15 to 20 minutes** here. The fellows who write the strongest prompts are the ones who explored the workspace first.

## Why this step matters

The prompt you write in [Step 1](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt) has to be grounded in the data. The **hidden headline finding** - the thing your highest-weighted positive rubric criterion will check for - is almost always something you spot here, not something you invent later. As you scan the files, keep the [Difficulty Playbook](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty) in mind - the traps you need are already in the environment; this is where you find them.

Skip this step and the prompt reads generic, the rubric reads shallow.

## What to look for

| Topic | Good | Bad |
| --- | --- | --- |
| Trends | "Track balances rising or falling, debt accumulating or paying down, where the money actually goes each month." | "Skipping straight to totals without reading the line items." |
| Unusual or repeated charges | "Same merchant hitting multiple times in a month. Identical amounts on the same day across two cards. Round-dollar amounts ($85.00, $130.00, $185.00) - usually subscriptions or fixed bills." | "Ignoring duplicates because the totals 'look right.'" |
| Confounding noise | "Mortgage applications, home-prep purchases, one-time travel, medical events - distorts baselines and creates natural complexity to write into the prompt." | "Treating one-time events as recurring spend." |
| Implicit constraints | "Who's in the household. What the user pays for that others don't. Filing status, dependents, state of residence." | "Assuming the persona is single, employed, and US-default." |
| Numbers that don't reconcile | "Two files report on the same thing - do they agree? If not, which is right?" | "Trusting the first number you see." |

[Previous](https://project-lighthouse-instructions.learn.joinhandshake.com/personas)[Next](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt)



---

## Source: 2writetheprompt.html

Lovable App



![Handshake](./2writetheprompt_files/sidebar-logo-BhcHUO7k.png)

* [Welcome](https://project-lighthouse-instructions.learn.joinhandshake.com/)
* [Task overview](https://project-lighthouse-instructions.learn.joinhandshake.com/assignment)
* [Workflow](https://project-lighthouse-instructions.learn.joinhandshake.com/workflow)Collapse

  * [0. Understand personas](https://project-lighthouse-instructions.learn.joinhandshake.com/personas)
  * [1. Review the environment](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1-environment)
  * [2. Write the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt)Collapse

    * [1. How to stump a model fairly](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty)
  * [3. Identify critical elements](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-critical-elements)
  * [4. Write failure justifications](https://project-lighthouse-instructions.learn.joinhandshake.com/step-4-justifications)
  * [5. List golden trajectory](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-golden-trajectory)
  * [6. Write rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-rubric)Collapse

    * [A. Write the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-principles)
    * [B. Weighting the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting)Collapse

      * [• Weighting principles](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-principles)
      * [• Weighting guide](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-tiers)
    * [C. Audit your rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-audit)
    * [D. Rubric examples](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-examples)
* [Submission checklist](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-review-checklist)
* [Golden examples](https://project-lighthouse-instructions.learn.joinhandshake.com/examples)Collapse

  * [1. Atlanta brand designer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-9f14845b)
  * [2. San Francisco engineer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/mark-ce08d55b)
  * [3. Denver construction manager & nurse couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/matt-b2b023f3)
  * [4. Tampa retired couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-74b127ce)
  * [5. Phoenix bookkeeper](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/phoenix-bookkeeper)
* ---
* [Reviewer playbook](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-playbook)Collapse

  * [1. Workflow and send-backs](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-workflow)
  * [2. Reviewing the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-prompt)
  * [3. Reviewing the rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-rubric)
  * [4. Leaving feedback](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-feedback)
  * [5. SQS scoring](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-sqs)
  * [6. Reviewer quiz & Case files](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-quiz)
* [FAQ](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq)Collapse

  * [1. Set up payments & Claim your first task](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/quick-start)
  * [2. Onboarding, referrals & Eligibility](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/essentials)
  * [3. Task access & Platform glitches](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/task-access)
  * [4. Tracking your hours](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/time-tracking)
  * [5. Payment schedule & Methods](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/getting-paid)

# Step 2 - Write the prompt

Training - Write the prompt

Ask for a text-based analysis - not an artifact

The prompt should ask for a **text-based analysis** - not an output file, chart, diagram, Excel spreadsheet, or other generated artifact. The model's response is plain text the reviewer can read and score.

The task goal is a suggestion, not a script

The goal that ships with the task is one plausible thing this person might want. Treat it as a starting point, not an assignment.

Take your own angle. Reframe the ask, bundle different sub-questions, pick a different worry sitting in the workspace, or chase a finding the stated goal never mentions. Two authors handed the same persona should not produce the same prompt - variation is what keeps the dataset from collapsing into templates.

What is not flexible: the assigned category, the persona's actual facts and documents, and the difficulty bar.

The difficulty bar

**Difficulty bar.** At least 2 of 3 models score below 50% composite (item values) on your rubric.

If only one model fails, iterate on the prompt before submitting. A prompt that does not break models is not a Lighthouse prompt.

## What "Complex" Means here

A complex prompt is complex because:

* It **bundles multiple sub-questions.** Real people don't ask 1 tidy question. They ask 1 surface question that hides 3 or 4 sub-questions inside it.
* It **states explicit constraints.** Must-nots and must-haves the model has to respect.
* It **requires the workspace.** The model has to open multiple files and reconcile them. World knowledge alone will not answer it.
* It **forces cross-referencing across files.** A complete answer can't come from any single document - the model has to pull a number from 1 file, a detail from another, and a constraint from a third, then reconcile them into 1 coherent response.
* The **headline finding is hidden.** The user asks a surface question. A complete answer requires the model to notice something the user did not explicitly ask about, but that is sitting in the data.

Complexity comes from the difficulty traps in the [Difficulty Playbook](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty) - nine patterns, ranked by how often they actually break models. Use at least two of them in every prompt.

The difficulty bar is your floor. Complexity is what you do on top of that floor to make the task feel like a real consumer question instead of a trivia stunt.

## Techniques for human-sounding prompts

Write in first person, with feeling

Use "I" language that expresses real stakes and emotion. Flat, neutral, third-person framing signals evaluation mode.

> ✓ Good: *"I'm stressed about…" / "My wife and I are trying to…" / "I keep seeing charges and I don't know…"*

Include the messy human context

Job, family, location, history, what you've already tried, what you're worried about. Real users over-share - that's a feature, not a bug.

> ✓ Good: *"I'm a teacher with 2 kids, we just moved to Atlanta last year, and I've already tried YNAB but it didn't stick…"*

Bundle the way real people bundle

One surface question with two or three sub-questions tucked inside.

> ✓ Good: *"Should I refinance? And if I do, what should I do with the extra $300/mo, and is it dumb to also be maxing my Roth right now?"*

Use natural, imperfect phrasing

Contractions, asides, "honestly," run-on sentences, "please don't tell me to…" Polished prose reads as artificial.

> ✓ Good: *"honestly I've been putting this off for months, please don't tell me to just make a spreadsheet…"*
>
> Subscriptions / cash flow
> "I'm trying to set a real subscription budget for next year and I have no idea where I'm starting from. Between my Chase Sapphire and my Amex Gold, I think I've got a ton of services running, and I'm not sure what's actually a subscription versus a one-time charge, what's getting double-billed across cards, what's gone up in price recently, or what I should cancel. Walk me through everything that's recurring across both cards over the last few months, with the actual monthly and annualized cost. I want to make a real decision about which to keep, which to switch to annual billing for the discount, and which to cut. And please don't tell me to get a budgeting app, I just want to handle this myself."
>
> These prompts fail the bar. They are too thin, too ambiguous, too contrived, or too easy. Read them to calibrate what *not* to submit.

### Single-fact lookup

### Vague and ambiguous

### Trivia stunt / riddle

### Workspace not required

### No hidden finding

### Off-category drift

### Examples

Good examples

#### Subscriptions / cash flow
> "I'm trying to set a real subscription budget for next year and I have no idea where I'm starting from. Between my Chase Sapphire and my Amex Gold, I think I've got a ton of services running, and I'm not sure what's actually a subscription versus a one-time charge, what's getting double-billed across cards, what's gone up in price recently, or what I should cancel. Walk me through everything that's recurring across both cards over the last few months, with the actual monthly and annualized cost. I want to make a real decision about which to keep, which to switch to annual billing for the discount, and which to cut. And please don't tell me to get a budgeting app, I just want to handle this myself."

#### Retail investment / portfolio analysis
> "I just got my Q1 RSU vest and I have about $40k in cash sitting in my brokerage account that I haven't moved anywhere yet. Combined with what I see going out on my credit cards each month, I'm worried I'm spending more than I'm actually investing. Look at my brokerage holdings, my checking, and my credit card statements, and tell me three things: am I actually saving enough for someone making what I make, what should I do with the $40k that's just sitting in cash, and is my current allocation reasonable for a 30-something with 30 more years of work ahead. I'm fine with risk but I don't want to gamble. Don't tell me to hire a financial advisor, I want to handle this myself."

#### Budgeting / spending analysis
> "I'm trying to get a handle on my spending. Can you go through my last few months of statements and tell me where my money is actually going, whether I'm in trouble, and what I should realistically do about it? I'm a teacher on a tight budget so please don't recommend things that cost more money to fix."

#### Credit decisions
> "I just got a 0% APR balance transfer offer for 18 months and I'm tempted to take it. My BofA balance keeps going up no matter what I do, I'm paying what I can each month but it's never enough. If I move the balance over, will I actually get out of this or am I just kicking the can for 18 months and ending up worse? Honestly look at what's happening in my statements and tell me whether a transfer would help or hurt, and if there's something I should fix first. I'm a teacher with two kids so please don't tell me to get a side hustle or sell my stuff."

#### Goal-based planning
> "We're trying to put down about $80k on a home in Marietta in the next 18 months. Right now we're putting roughly $2,500 a month into savings, but I keep seeing a lot of Wayfair, Lowes, and Home Depot charges between us and I'm wondering if we're undermining our own goal. Look at our last few months across both the Chase and the Capital One, tell us whether we're actually on track for $80k, and if we're not, where the gap is. We also got a Wells Fargo mortgage application charge last month so we're starting the actual process. What should we be doing differently with our credit card usage now that we're 12-18 months out? And honestly, my wife and I disagree about the home-prep spending so help me with this without making it sound like I'm right."

#### Tax planning (1040)
> "We're 12 to 18 months out from buying our first house in Georgia and we're trying to figure out the tax piece before we commit. We've taken the standard deduction every year but I keep hearing about mortgage interest making it worth itemizing. We're around $165k combined, both W-2, no kids yet, filing jointly. Looking at a $400k house with maybe a $320k mortgage at current rates, what should we actually expect from a tax perspective once we buy? Will itemizing be worth it, are there things we should be doing this year before we buy, and what's the tax hit if we tap our $40k taxable brokerage account for the down payment? Please don't tell us to consult a CPA, I want the actual numbers and rules, not 'it depends'."

### Bad examples
These prompts fail the bar. They are too thin, too ambiguous, too contrived, or too easy. Read them to calibrate what not to submit.


#### Single-fact lookup
> "What's the 2026 standard deduction for a married couple filing jointly?" - No persona, no workspace, no chained reasoning. Any model answers this in one line from training data.
Before you submit, every prompt has to clear these core attributes.

#### Vague and ambiguous
> "Look at my finances and tell me if I'm doing okay." - No constraints, no format, no specific question. Two reviewers would grade two different answers as correct. Any failure is the prompt author's fault.

#### Trivia stunt / riddle
> "If my rent is 30% of my income and I spend twice as much on food as transportation, and transportation is $200, what's my rent?" - Contrived word problem. Real users don't ask this. Tests arithmetic, not real assistant work.

#### Workspace not required
> "I make $120k in California. What's my estimated federal tax bill?" - Persona voice is thin and the model can answer from world knowledge alone. The workspace adds nothing.

#### No hidden finding
> "My March Chase statement shows $4,200 in spending. Categorize it into groceries, dining, transportation, and other, and give me a total per category." - Pure extraction with the headline restated in the prompt. No reconciliation, no constraint, no insight to discover.

#### Off-category drift
> A "subscriptions / cash flow" task that pivots into retirement allocation, estate planning, and college savings. Scope sprawl means no rubric can fairly score it, and the model can score points on tangents instead of the real ask.

A prompt only works for Lighthouse if it actually breaks the model. The most common problem is the opposite: the prompt is too easy, every model answers it correctly, and there is no real failure to grade. This page is the standard for making a prompt **hard on purpose** - fairly, and using the material already in your workspace.

The bar - fair difficulty, not gotchas

Don't try to confuse the model with fake facts, contradictions, or impossible asks. Write realistic personal-finance prompts where the right answer **is** in the workspace - but the model fails if it skips evidence, assumes facts, ignores constraints, uses stale rules, or does careless math.

**Good vs. bad model-breaking**

| Good model-breaking | Bad model-breaking |
| --- | --- |
| The right detail is in the files. A tempting shortcut leads to a wrong answer. | Missing information, fake facts, or contradictory instructions. |
| Sounds like a real person asking about their own money. | Reads like a riddle or a puzzle the model has to decode. |
| Missing 1 small detail changes the final result. | The task requires guessing because the files don't support an answer. |
| The failure can be clearly graded against the rubric. | The "failure" is just confusing wording - no defensible right answer. |

You don't build the environment - you interrogate it

The persona and the workspace files are **given to you**. You do not choose the persona, add documents, or plant numbers. Your only lever is the **prompt** (and the rubric, justifications, and golden trajectory you write around it). Difficulty is not something you inject into the files - it is something you **find** in the files and then **aim the prompt at**. The traps below are already sitting in your environment; your job is to spot them and write the one question that forces the model to walk into them.

## Why your task probably isn't hard enough

| Topic | Good | Neutral | Bad |
| --- | --- | --- | --- |
| The symptom | "You write a prompt, run the rollouts, and 2 of 3 models fail on a real, gradable error." | "You iterate 4-5 times before any model breaks." | "All three models pass, OR a model 'fails' only on tone, formatting, or something the prompt never asked for - which won't hold up in review and gets the task sent back." |

A prompt that does not break models is not a Lighthouse prompt. But difficulty has to be **fair and gradable** - the right answer must be sitting in the files you were given, and the failure must be a wrong number, a violated constraint, a missing required output, or a real domain error. Confusing wording is not difficulty. Tone is not difficulty. A trick with no defensible answer is not difficulty.

### Prompt checklist
0 of 6 complete

> Persona voiceSounds like a real person typing into ChatGPT - first person, emotion, family details, occupation, history.

> Category coverageThe question clearly lives inside the assigned category. A "subscriptions / cash flow" task that drifts into retirement allocation is off-spec.

> Self-containedEverything the model needs is in the prompt plus the workspace. No web search, no external documents.

> UnambiguousIf two professionals would read it and reasonably answer two different questions, the prompt is ambiguous. Ambiguity-driven failures are your fault, not the model's.

> Realistic, not contrivedNo riddles, no trick wording, no "Simon Says" tests. Real users ramble and bundle.

> Your own angleThe prompt does more than restate the goal supplied with the task. You reframed it, bundled your own sub-questions, or chased a different thread from the workspace.

For the difficulty bar, work through the [Difficulty Playbook](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty).

[Previous](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1-environment)[Next](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty)



---

## Source: 2.1.howtostumpmodelfairly.html

Lovable App



![Handshake](./1.howtostumpmodelfairly_files/sidebar-logo-BhcHUO7k.png)

* [Welcome](https://project-lighthouse-instructions.learn.joinhandshake.com/)
* [Task overview](https://project-lighthouse-instructions.learn.joinhandshake.com/assignment)
* [Workflow](https://project-lighthouse-instructions.learn.joinhandshake.com/workflow)Collapse

  * [0. Understand personas](https://project-lighthouse-instructions.learn.joinhandshake.com/personas)
  * [1. Review the environment](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1-environment)
  * [2. Write the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt)Collapse

    * [1. How to stump a model fairly](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty)
  * [3. Identify critical elements](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-critical-elements)
  * [4. Write failure justifications](https://project-lighthouse-instructions.learn.joinhandshake.com/step-4-justifications)
  * [5. List golden trajectory](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-golden-trajectory)
  * [6. Write rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-rubric)Collapse

    * [A. Write the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-principles)
    * [B. Weighting the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting)Collapse

      * [• Weighting principles](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-principles)
      * [• Weighting guide](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-tiers)
    * [C. Audit your rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-audit)
    * [D. Rubric examples](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-examples)
* [Submission checklist](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-review-checklist)
* [Golden examples](https://project-lighthouse-instructions.learn.joinhandshake.com/examples)Collapse

  * [1. Atlanta brand designer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-9f14845b)
  * [2. San Francisco engineer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/mark-ce08d55b)
  * [3. Denver construction manager & nurse couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/matt-b2b023f3)
  * [4. Tampa retired couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-74b127ce)
  * [5. Phoenix bookkeeper](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/phoenix-bookkeeper)
* ---
* [Reviewer playbook](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-playbook)Collapse

  * [1. Workflow and send-backs](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-workflow)
  * [2. Reviewing the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-prompt)
  * [3. Reviewing the rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-rubric)
  * [4. Leaving feedback](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-feedback)
  * [5. SQS scoring](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-sqs)
  * [6. Reviewer quiz & Case files](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-quiz)
* [FAQ](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq)Collapse

  * [1. Set up payments & Claim your first task](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/quick-start)
  * [2. Onboarding, referrals & Eligibility](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/essentials)
  * [3. Task access & Platform glitches](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/task-access)
  * [4. Tracking your hours](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/time-tracking)
  * [5. Payment schedule & Methods](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/getting-paid)

# How to stump a model fairly

A prompt only works for Lighthouse if it actually breaks the model. The most common problem is the opposite: the prompt is too easy, every model answers it correctly, and there is no real failure to grade. This page is the standard for making a prompt **hard on purpose** - fairly, and using the material already in your workspace.

The bar - fair difficulty, not gotchas

Don't try to confuse the model with fake facts, contradictions, or impossible asks. Write realistic personal-finance prompts where the right answer **is** in the workspace - but the model fails if it skips evidence, assumes facts, ignores constraints, uses stale rules, or does careless math.

**Good vs. bad model-breaking**

| Good model-breaking | Bad model-breaking |
| --- | --- |
| The right detail is in the files. A tempting shortcut leads to a wrong answer. | Missing information, fake facts, or contradictory instructions. |
| Sounds like a real person asking about their own money. | Reads like a riddle or a puzzle the model has to decode. |
| Missing 1 small detail changes the final result. | The task requires guessing because the files don't support an answer. |
| The failure can be clearly graded against the rubric. | The "failure" is just confusing wording - no defensible right answer. |

You don't build the environment - you interrogate it

The persona and the workspace files are **given to you**. You do not choose the persona, add documents, or plant numbers. Your only lever is the **prompt** (and the rubric, justifications, and golden trajectory you write around it). Difficulty is not something you inject into the files - it is something you **find** in the files and then **aim the prompt at**. The traps below are already sitting in your environment; your job is to spot them and write the one question that forces the model to walk into them.

## Why your task probably isn't hard enough

| Topic | Good | Neutral | Bad |
| --- | --- | --- | --- |
| The symptom | "You write a prompt, run the rollouts, and 2 of 3 models fail on a real, gradable error." | "You iterate 4-5 times before any model breaks." | "All three models pass, OR a model 'fails' only on tone, formatting, or something the prompt never asked for - which won't hold up in review and gets the task sent back." |

A prompt that does not break models is not a Lighthouse prompt. But difficulty has to be **fair and gradable** - the right answer must be sitting in the files you were given, and the failure must be a wrong number, a violated constraint, a missing required output, or a real domain error. Confusing wording is not difficulty. Tone is not difficulty. A trick with no defensible answer is not difficulty.

## Step zero: Mine the environment before you write a word

You cannot exploit a trap you haven't found. Spend your [Step 0](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1-environment) review hunting for the raw material the patterns below need: the one domain rule this persona's situation triggers, the figure on a document that contradicts what a model would assume, the line item buried in a statement, the error already sitting in the persona's draft. Read the context note - it often hints at where the headline finding is hiding. **The strongest prompts are written by the people who explored the workspace hardest.**

## The foundation: Volume + Chaining

Before any specific trap, every hard prompt rests on two structural requirements. You enforce them through *how you word the question*, using the files you already have. These are the floor, not the ceiling.

Work through each item.

0 of 4 complete

Your question forces the model to use at least 5 filesWord the prompt so a complete answer must pull from 5+ of the documents in the workspace. Questions answerable from one or two files are trivial and don't discriminate strong from weak models.Every file the model must open triggers a reasoning or calculation stepDon't ask the model to just read a number. Frame the ask so that after each file, it must DO something with that number - convert it, net it, compare it, apply a rule to it.At least one number must be combined with another from a different fileWrite the question so the answer depends on a figure from file A being reconciled or computed against a figure from file B - not two independent lookups.A multi-step chain crosses multiple filesThe final answer is the end of a chain: extract from file 1, feed into a calc using file 2, apply a rule, carry into file 3. Make sure no single document contains the answer.

Volume and chaining alone will slow a model down, but they rarely break it. To actually force a failure, **find at least two of the traps below in your environment and aim the prompt at them.**

## The traps that actually work

These nine patterns are ordered by how often they produced a real, confirmed model failure across real Lighthouse tasks. Lead with the top of this list. For each one: how to **spot it** in the files you were given, and how to **aim the prompt** so the model walks into it.

### 1. The Domain Trap | What it is. A specific tax or personal-finance rule that a non-expert (and a hurried model) gets wrong, but that an expert knows cold. The value looks normal; only domain knowledge reveals it's being mishandled. Why models fail it. Models reach for the generic move (tax the whole distribution, sum the gross 1099s, treat all brokerage as untouchable) instead of the rule that actually governs the situation. How to spot it in your files. Read the persona's situation for a fact pattern that triggers a specific rule, then check the documents for the figures it touches. Rules that have broken models on real tasks: QBI / Section 199A deduction the prior return omitted (worth ~$5,651 on one task) Additional Medicare Tax already withheld in W-2 Box 6 but never credited on line 25c HSA contributions stacking past the $8,550 family limit -> 6% excise (Form 5329) Qualified Charitable Distribution excluded from income but still counting toward the RMD Stepped-up basis on inherited stock; backdoor-Roth recapture only on the taxable portion RRB-1099 (taxed like Social Security) vs RRB-1099-R (taxed like a pension) Excess Social Security tax across two employers = a refundable credit, not extra tax How to aim the prompt. Ask the question whose correct answer requires applying that rule, and make the rule move the bottom line. Do not name the rule - make the model need it on its own. Worked example (Atlanta designer task). The workspace's 2025 return omitted the QBI deduction. The prompt asks for a clean 2026 Schedule C projection and "what the tax should actually be." Two of three models "mirrored" the prior return and omitted QBI again, landing on $11,373.71 total tax instead of the correct $10,695.50. Try it (before -> after). Before (too easy): "Here's my 2025 return and my income - what should I budget for 2026 federal taxes?" After (trap aimed): "Build my projected 2026 Schedule C from my 2025 return and the Chase Ink statements, then carry it all the way to the exact total federal tax and quarterly estimate. Use 2025 brackets, federal only." What changed: the "what should it actually be" framing forces the model to apply the QBI deduction the prior return omitted, instead of restating a rough budget number. The bottom line is now wrong unless the rule is applied. Self-check. Could a tax professional point to one specific rule and say "the model got this wrong, and here's the code section"? If yes, you have a domain trap. 2. The Hard Constraint | What it is. An explicit must / must-not that blocks the model's easy exit and forces it to do the actual work the files support. Why models fail it. Models reach for the escape hatch (hire a CPA, use an app, open a card, tap retirement, sell the ETFs) instead of solving the harder path the workspace makes possible. How to aim the prompt. This is your strongest lever, because it lives entirely in the wording - it does not depend on what's in the files. State a constraint that bans the shortcut the model would otherwise take: "Do not recommend a CPA, an app, or opening a new account." (Bans the escape hatch.) "Don't pull from the IRAs / don't sell the ETFs - use only what's in checking." (Only valid if the files actually support the harder path.) "Don't tell me to stop my 401(k) contribution or take a loan." (Blocks the obvious sacrifice the model defaults to.) Avoid leaning on minor surface asks (commit to one number, no ranges, named sections, table vs. prose, whole dollars only). They produce trivial "violations" that don't reflect real model weakness. The constraint should change the answer, not the shape. Worked example (SF engineer task). The user said do not recommend a CPA. One model punted to "talk to your tax advisor" instead of working the numbers in the files - a direct, gradable violation of the core ask. Try it (before -> after). Before (too easy): "I keep owing taxes because of my RSUs - what should I do?" After (trap aimed): "Walk my W-2 and RSU lot detail and tell me what to actually do about 2026 withholding. Don't tell me to hire a CPA, buy software, or stop my 401(k) - work it from what's in my files." What changed: the banned exits force the model to do the real work in the workspace instead of routing the user to a professional or telling them to give something up. Self-check. If the model takes the lazy path, does it visibly break a rule you wrote down? The constraint only counts if violating it is unambiguous - and if the files actually let the model comply. 3. The Hidden Headline | What it is. The surface question is one thing; a complete answer requires surfacing something the user did NOT explicitly ask about, but that is already in the data and dominates the right answer. Why models fail it. Models answer the question as literally asked and never notice the bigger thing next to it. How to spot it in your files. The headline finding is already sitting in the workspace - the context note often points near it. It's the $22,795 unpaid tax on line 34 of the 1040; the IRMAA surcharge the couple shouldn't be paying; the autopilot transfer that silently stopped. How to aim the prompt. Ask the surface question the persona would naturally ask, and make sure your wording does NOT name the headline. The model has to discover it. (This becomes your highest-weight positive rubric criterion later.) Worked example (SF engineer task). Surface ask: "am I on track to owe again, and how much should I set aside?" Hidden headline already in the files: the 110% high-income safe-harbor rule (AGI > $150k) makes the target $93,825.55 and the real shortfall $33,825.55 - and just "setting cash aside" doesn't avoid the penalty. Models that answered only the surface question missed the finding that decides the answer. Try it (before -> after). Before (too easy): "Can I save a $165k down payment in three years on my income?" After (trap aimed): "Tell me exactly how much of my cash I can actually deploy today after everything I already owe, the monthly target to hit $165k in three years, and whether it's realistic." What changed: "after everything I already owe" forces the model to find the $22,795 unpaid tax sitting on line 34 - without naming it. The plain version let models answer off the account balance and miss the liability that decides the answer. Self-check. Is there a finding in the files that a great human advisor would lead with, that the user didn't name? 4. Proven vs. Suspicious / Scope Separation | What it is. The model must separate what the files PROVE from what merely looks suspicious - or separate personal from business, cash-flow from total cost, 2025 from 2026. Why models fail it. Models either over-claim (calling look-alike charges "confirmed duplicates" and promising savings the data doesn't support) or invert the call (flagging the weak case as proven and the airtight one as unproven). How to spot it in your files. Scan the statements for both a genuinely provable pattern and tempting-but-unprovable look-alikes that are already there: A charge identical in amount, merchant, and month on two cards = provable duplicate. A similar charge on different dates, or labeled "JOINT," or on three accounts = suspicious, could be two real services/policies/lines. How to aim the prompt. Require the model to commit a keep-or-cancel call on each, with evidence, and to separate proven from suspicious - "don't tell me a maybe." Worked example (Denver couple subscriptions). Orangetheory at an identical $159 on both cards in both months is the airtight duplicate (cancel one -> $304.95). Anytime and Planet only doubled in March, so they're suspicious, not proven. Models that kept both Orangetheory charges or certified Verizon/Progressive as proven waste failed the headline test. Try it (before -> after). Before (too easy): "Go through both cards and list my duplicate subscriptions." After (trap aimed): "Across both cards for March and April, give me one committed keep-or-cancel call on every recurring charge, and separate the ones you can PROVE are billed twice from the ones that only look suspicious. Don't hand me a maybe. End on one monthly number." What changed: demanding a committed call plus a proven-vs-suspicious split punishes the model that lumps look-alikes in as "confirmed duplicates" - the most common failure on this kind of task. Self-check. Does answering require the model to say "this I can prove, this I cannot"? If everything in the files is equally provable, there's no trap. 5. Source Beats Memory | What it is. A real, current figure lives in the workspace document, and it contradicts the stale or prior-year constant the model has memorized. The model must trust the file, not its training. Why models fail it. Models confidently substitute a memorized number - often a prior-year value - over the figure printed in the source. How to spot it in your files. Look for a current-year figure on a document where a model's default assumption pulls the other way: 2025 standard deduction is $15,750 single / $31,500 MFJ - models keep typing $15,000 / $30,000. 2026 IRA/Roth limit is $7,500 - models keep using the stale $7,000. A figure stated on the face of the draft 1040 that a model is likely to "correct" to a wrong constant. How to aim the prompt. Build the question so the answer depends on that exact document-stated number, and ask for the precise figure - not a ballpark. Worked example (multiple tax tasks). On two separate tasks, models overrode the $15,750 standard deduction printed on the draft return with a memorized $15,000, corrupting taxable income, total tax, and the final balance due - the single most important number in the prompt. Try it (before -> after). Before (too easy): "What's my 2025 standard deduction and what do I owe?" After (trap aimed): "Check my draft 1040 line by line and give me the corrected balance due, using the figures exactly as stated on my return." What changed: "as stated on my return" forces the model to use the $15,750 printed on the draft rather than the $15,000 it tends to recall - and the whole balance-due chain is wrong if it trusts memory over the document. Self-check. Is there a number in the files where the correct, document-stated value differs from what a model would assume by default? Make the answer depend on it. 6. Classify Before You Count | What it is. Before any total is correct, the model has to correctly classify cash movements - what's income vs. a transfer, what's spending vs. a card autopay, what's liquid vs. invested. Why models fail it. They sum gross numbers. They double-count a credit-card autopay on top of the purchases it pays off. They treat money-market sweep cash as untouchable. They count transfers to savings as spending. How to spot it in your files. Look for the structures that make a naive sum wrong: A credit-card autopay AND the new purchases both appearing in the statements. A brokerage money-market position (e.g. SWVXX) sitting alongside the ETFs. Recurring transfers to savings/HSA/brokerage mixed in with real spending. How to aim the prompt. Ask for the figure that only comes out right after classifying - the real monthly surplus, the largest amount that can be deployed, the true shortfall. Worked example (Phoenix bookkeeper / Atlanta trip tasks). In one, the real April household shortfall ($880.74) only appears once you separate the autopay from new purchases instead of summing both. In another, the model called a $2,500 deposit unaffordable because it ignored $1,245 of liquid SWVXX cash, treating all brokerage assets as off-limits. Try it (before -> after). Before (too easy): "What's my average monthly spending?" After (trap aimed): "Give me my real monthly cash-flow baseline: separate personal from business, don't count the card autopay as new spending on top of the purchases it pays off, and exclude my transfers to savings. End on the actual surplus or shortfall." What changed: the classification step is now mandatory. A model that sums gross outflows double-counts the autopay and reports the wrong shortfall; the correct number only appears after classifying. Self-check. Is the naive "add it all up" answer wrong? If the model has to classify before it sums, the trap is there. 7. The Buried Detail | What it is. A single line item, deep in a statement, that flips the final answer - and the user never points to it. Why models fail it. They skim, trust the draft/spreadsheet number, and never find the one transaction that matters. How to spot it in your files. Hunt the statements for the one decisive item: a $500 tuition deposit already paid sitting in the checking file, a loan origination fee inside an amortization schedule, a contribution labeled "(2025 tax year)" that must be excluded from the 2026 count. How to aim the prompt. Ask a question whose answer depends on that item - and do NOT name it. Make the model find it. Worked example (Castellanos college task). Three models all missed the $500 Thornfield deposit already paid on 06/09 in the checking file, so their year-one cost came out $500 too high. None were pointed to it; they had to find it. Try it (before -> after). Before (too easy): "What's my year-one out-of-pocket cost for Diego's first year?" After (trap aimed): "What's my REAL year-one out-of-pocket, reconciled against my actual checking activity - not the number on my draft worksheet?" What changed: forcing a reconciliation against checking makes the model find the $500 deposit already paid on 06/09. The plain version let every model trust the worksheet and land $500 too high. Self-check. Is there one line item in the files that, if missed, makes the headline number wrong - and did you avoid naming it in the prompt? 8. The Draft Error Already in the Files | What it is. The workspace includes the persona's own draft return or tracker spreadsheet, and it already contains an error (these drafts are built to be wrong). The model must catch and correct it, not copy it forward. Why models fail it. They anchor on the draft and "mirror" its approach, inheriting the mistake. How to spot it in your files. Open the draft 1040 / tracker and find the specific catchable error: an omitted deduction, a misclassified contribution, a wrong filing status, an inflated liability. The context note usually flags that the draft "may be off." How to aim the prompt. Ask what the number SHOULD be - the corrected bottom line - rather than a restatement, and don't tell the model what's wrong. Make sure the error you're targeting actually moves the bottom line. Worked example (Atlanta designer + SEP tasks). One model wrote it left QBI out "to mirror" the prior return - copying the error already in the draft. On another, the draft's January contribution was labeled "(2025 tax year)"; models that counted it toward 2026 invented an over-contribution that wasn't there. Try it (before -> after). Before (too easy): "Is my draft 1040 correct?" After (trap aimed): "My draft shows the full $35,000 IRA distribution as taxable. Walk my 1099-R and the QCD letter and tell me the corrected taxable amount and bottom line." What changed: asking for the corrected number forces the model to catch that the $10,000 QCD is excluded from income - the error already baked into the draft. "Is my draft correct?" invites a model to rubber-stamp it. Self-check. Does the workspace contain a draft, and does your prompt ask for the corrected number rather than a restatement? 9. Force the Files | What it is. The prompt is worded so the answer is impossible to assemble without actually opening and reconciling the documents - world knowledge alone produces nothing usable. Why models fail it. Faced with effort, weaker models answer from generic knowledge, give conditional "if your W-2 shows X..." placeholders, or ask the user to supply numbers already in the workspace. How to aim the prompt. Demand exact dollar amounts only the files supply, require reconciliation across accounts, and forbid hedged/conditional answers. Make the deliverable a committed number, not a method. Worked example (multiple tasks). Several models "reviewed 0 resources," claimed the documents weren't available, and returned generic guidance or a list of inputs they wanted - on prompts fully answerable from the workspace. That's a clean failure when the prompt clearly required the files. Try it (before -> after). Before (too easy): "I'm a single dad in LA with an inheritance this year - roughly what will I owe?" After (trap aimed): "Using my W-2, 1099s, brokerage statement, inheritance basis letter, and draft return, give me the exact corrected 2025 refund or balance due to the dollar. No 'it depends,' no conditional answers." What changed: the exact-figure, no-conditionals demand makes a generic file-free answer impossible. Models that "reviewed 0 resources" and returned generic guidance now visibly fail the ask. Self-check. If a model tried to answer from general knowledge without opening anything, would it visibly fail to produce the required exact figures? If world knowledge can fake it, tighten the spec. If your prompt is missing any of these, it is not hard enough yet.

1

#### Mine the environment you were given

Read every file. Find the situation that triggers a specific domain rule (Trap 1), the draft error already present (Trap 8), and the one buried detail that flips the answer (Trap 7). That is your spine. You're discovering what's there, not adding anything.

2

#### Pick a second and third trap that the files support

Add a proof-boundary call, a classify-before-count step, a source-beats-memory figure, or a hidden headline - whichever the documents actually contain. Two traps minimum; the strongest tasks stack three.

3

#### Word the question to force the chain across 5+ files

Write the ask so a complete answer must extract from one file, compute against another, apply a rule, and carry it into a third - landing on exact dollar figures only the files supply.

4

#### Lock the deliverable

Demand one committed number (no ranges), name the exact sections, set the format (whole dollars / table), and ban the easy exits (no CPA, no app, don't touch the IRA) - as long as the files let the model comply.

5

#### Roll, then check the bars

Run the rollouts. Confirm 2 of 3 models score below 50% and the spread is 10-30%. If not, the prompt isn't breaking models - re-aim at a stronger trap and re-roll. Never soften the rubric to fake the bar.

## What does not count as difficulty

These feel hard but produce false or shallow failures. They are the fastest way to get a task sent back in review.

| Topic | Good | Bad |
| --- | --- | --- |
| Confusion vs. difficulty | "The right answer is in the files; a tempting shortcut leads to a wrong number." | "Ambiguous wording where two professionals would answer two different questions. The failure is your fault, not the model's." |
| Fair traps vs. gotchas | "A real rule the model must apply, with a defensible single answer grounded in the files." | "Pretending a fact is in the files when it isn't, or asking for something the documents can't support. There's nothing to grade." |
| Substance vs. style | "A wrong total, a violated constraint, a missing required section, a copied draft error." | "Penalizing tone ('too robotic'), phrasing, or a deliverable the prompt never asked for. This won't hold up in review and gets the task sent back." |
| Hard vs. impossible | "Difficult because it requires careful multi-file reasoning over the documents you have." | "Impossible because the answer isn't in the files, or the task demands something they can't support (e.g. a penalty that can't be computed from the documents)." |

The fairness rule still governs

Every trap here must be a *fair* break: the correct answer is provable from the workspace you were given, and the model fails only because it skipped evidence, assumed a fact, ignored a constraint, used a stale rule, or did careless math. If your "failure" can't be graded against a single defensible answer, it isn't difficulty - it's a broken prompt.

## End-to-end: Weak prompt hardened

Why the hardened version breaks models: it forces 5+ files and a per-file calc (foundation), leans on the autopay-vs-purchase classification already in the statements (Trap 6), targets the SEP over-contribution and prior-return QBI omission that are already in the workspace (Traps 1, 8), locks the deliverable to federal-only with no-CPA (Trap 2), and the headline correct number depends on a domain rule the draft got wrong (Trap 3). Multiple models landed on $11,373.71 instead of the correct $10,695.50. Notice the writer added nothing to the files - they just aimed the question at what was already there.

## Pre-submit difficulty checklist

Work through each item.

0 of 8 complete

A complete answer requires 5+ of the provided files, reconciledNot solvable from one or two documents.Every file the model must open triggers a calc, and at least one number is combined across filesNo standalone lookups; the answer is the end of a chain.At least 2 traps you found in the environment are targeted by the promptDomain rule, hard constraint, hidden headline, proof boundary, source-beats-memory, classify-before-count, buried detail, draft error, or force-the-files.There is one hidden headline finding in the files the user didn't explicitly ask forThis becomes your highest-weight positive rubric criterion.The deliverable is locked - committed number, named sections, set format, banned exitsHedging or reformatting is a gradable failure - and the files must let the model comply.A single defensible answer exists, fully provable from the files you were givenIf two experts would disagree, it's ambiguous - fix the wording before submitting.2 of 3 models score below 50% and the spread is 10-30%If the bars fail, re-aim at a stronger trap and re-roll. Never adjust the rubric to fake it.Every failure is fair, substantive, and gradable - not tone, phrasing, or out-of-scopeStyle and unrequested "shoulds" won't hold up in review and get the task sent back.

[Previous](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt)[Next](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-critical-elements)



---

## Source: 3.identifycriticalelements.html

Lovable App



![Handshake](./3.identifycriticalelements_files/sidebar-logo-BhcHUO7k.png)

* [Welcome](https://project-lighthouse-instructions.learn.joinhandshake.com/)
* [Task overview](https://project-lighthouse-instructions.learn.joinhandshake.com/assignment)
* [Workflow](https://project-lighthouse-instructions.learn.joinhandshake.com/workflow)Collapse

  * [0. Understand personas](https://project-lighthouse-instructions.learn.joinhandshake.com/personas)
  * [1. Review the environment](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1-environment)
  * [2. Write the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt)Collapse

    * [1. How to stump a model fairly](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty)
  * [3. Identify critical elements](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-critical-elements)
  * [4. Write failure justifications](https://project-lighthouse-instructions.learn.joinhandshake.com/step-4-justifications)
  * [5. List golden trajectory](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-golden-trajectory)
  * [6. Write rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-rubric)Collapse

    * [A. Write the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-principles)
    * [B. Weighting the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting)Collapse

      * [• Weighting principles](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-principles)
      * [• Weighting guide](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-tiers)
    * [C. Audit your rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-audit)
    * [D. Rubric examples](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-examples)
* [Submission checklist](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-review-checklist)
* [Golden examples](https://project-lighthouse-instructions.learn.joinhandshake.com/examples)Collapse

  * [1. Atlanta brand designer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-9f14845b)
  * [2. San Francisco engineer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/mark-ce08d55b)
  * [3. Denver construction manager & nurse couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/matt-b2b023f3)
  * [4. Tampa retired couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-74b127ce)
  * [5. Phoenix bookkeeper](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/phoenix-bookkeeper)
* ---
* [Reviewer playbook](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-playbook)Collapse

  * [1. Workflow and send-backs](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-workflow)
  * [2. Reviewing the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-prompt)
  * [3. Reviewing the rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-rubric)
  * [4. Leaving feedback](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-feedback)
  * [5. SQS scoring](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-sqs)
  * [6. Reviewer quiz & Case files](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-quiz)
* [FAQ](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq)Collapse

  * [1. Set up payments & Claim your first task](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/quick-start)
  * [2. Onboarding, referrals & Eligibility](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/essentials)
  * [3. Task access & Platform glitches](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/task-access)
  * [4. Tracking your hours](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/time-tracking)
  * [5. Payment schedule & Methods](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/getting-paid)

# Step 3 - Identify critical elements

Describe the **10–15 most critical elements** of your prompt when solved or calculated. These elements should map directly to your idea of a perfect answer and to your rubric. Each element should be verifiable and explicit.

Who reads this

Critical elements are not delivered to the client. They exist for two internal reasons:

1. 1. They show reviewers your reasoning - what you believed a correct answer had to contain when you wrote the prompt.
2. 2. The task uses them to generate the initial rubric criteria, so the sharper and more specific they are, the less rewriting you do in [Step 6 - Write the rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-rubric).

**Example:** if your prompt asks for a distribution of spending across categories, one of the bullet points would be:

* Subscriptions account for 15% of total spending, or $1,842 of the $12,280 spent in Q3. This is the second-largest category after housing (32%) and reflects six active recurring services, with Netflix and Adobe Creative Cloud making up roughly two-thirds of the subscription total. This element is critical because the distribution shape - not just the total - is what the prompt is testing; getting the percentage, the rank, and the underlying drivers right is the difference between a surface-level answer and a correct one.

## What makes a good critical element

Verifiable

It can be checked as correct or incorrect against your deliverable. This is critical because reviewers need a binary judgment, not an interpretation; without verifiability, two graders can score the same answer differently.

Explicit

It states a concrete value, conclusion, or output, not a vague intention. This is critical because vague elements ("analyze spending") let weak answers pass; explicit ones ("identify the top 3 categories by total spend") force the model to commit.

Specific numbers

Include exact figures, percentages, dates, or counts wherever the task produces them (e.g., "The ROI is 15%", "Net margin is $42,300"). This is critical because numbers are the fastest signal of a correct answer and the hardest to fake; missing or wrong numbers are an immediate fail.

Mapped

It corresponds directly to an item in your bronze deliverable and your rubric. This is critical because unmapped elements drift from the task; every bullet must trace back to something the deliverable and rubric already require.

Solved or calculated

It reflects the actual answer the task produces, not the steps to get there. This is critical because process descriptions ("calculate the average") don't tell you whether the answer is right; only the resolved output does.

[Previous](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty)[Next](https://project-lighthouse-instructions.learn.joinhandshake.com/step-4-justifications)



---

## Source: 4.writefailurejustification.html

Lovable App



![Handshake](./4.writefailurejustification_files/sidebar-logo-BhcHUO7k.png)

* [Welcome](https://project-lighthouse-instructions.learn.joinhandshake.com/)
* [Task overview](https://project-lighthouse-instructions.learn.joinhandshake.com/assignment)
* [Workflow](https://project-lighthouse-instructions.learn.joinhandshake.com/workflow)Collapse

  * [0. Understand personas](https://project-lighthouse-instructions.learn.joinhandshake.com/personas)
  * [1. Review the environment](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1-environment)
  * [2. Write the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt)Collapse

    * [1. How to stump a model fairly](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty)
  * [3. Identify critical elements](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-critical-elements)
  * [4. Write failure justifications](https://project-lighthouse-instructions.learn.joinhandshake.com/step-4-justifications)
  * [5. List golden trajectory](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-golden-trajectory)
  * [6. Write rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-rubric)Collapse

    * [A. Write the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-principles)
    * [B. Weighting the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting)Collapse

      * [• Weighting principles](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-principles)
      * [• Weighting guide](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-tiers)
    * [C. Audit your rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-audit)
    * [D. Rubric examples](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-examples)
* [Submission checklist](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-review-checklist)
* [Golden examples](https://project-lighthouse-instructions.learn.joinhandshake.com/examples)Collapse

  * [1. Atlanta brand designer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-9f14845b)
  * [2. San Francisco engineer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/mark-ce08d55b)
  * [3. Denver construction manager & nurse couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/matt-b2b023f3)
  * [4. Tampa retired couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-74b127ce)
  * [5. Phoenix bookkeeper](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/phoenix-bookkeeper)
* ---
* [Reviewer playbook](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-playbook)Collapse

  * [1. Workflow and send-backs](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-workflow)
  * [2. Reviewing the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-prompt)
  * [3. Reviewing the rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-rubric)
  * [4. Leaving feedback](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-feedback)
  * [5. SQS scoring](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-sqs)
  * [6. Reviewer quiz & Case files](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-quiz)
* [FAQ](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq)Collapse

  * [1. Set up payments & Claim your first task](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/quick-start)
  * [2. Onboarding, referrals & Eligibility](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/essentials)
  * [3. Task access & Platform glitches](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/task-access)
  * [4. Tracking your hours](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/time-tracking)
  * [5. Payment schedule & Methods](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/getting-paid)

# Step 4 - Write failure justifications

Failure justifications walkthrough

After the rollouts complete, the platform shows you each model's full trajectory: the files it opened, the terminal commands it ran, its intermediate reasoning, and its final response.

**Read all 3 in full.** Don't skim. This is where you decide which models failed and what they failed at. Budget **15 to 20 minutes** for the read, then write justifications.

## How to grade at this stage

You don't have a finished rubric yet, so some "vibe" judgment is unavoidable - that's by design. But there's a difference between a disciplined gut-check grounded in the prompt and the workspace, and a loose impression of "the worst thing I noticed." Use the [Appendix - Review checklist](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-review-checklist) to keep your read structured.

Watch yourself for these review failure modes

Every one of the patterns below has shown up in real submitted tasks. If you catch yourself doing any of them, slow down and re-read the response in full before locking in a verdict.

### Pure vibe grading A verdict that's really a gut impression of the worst error spotted, with no per-criterion check against what the prompt actually asked for. Some vibe is unavoidable (the rubric doesn't exist yet) - but it has to be anchored to the prompt's specific asks and the workspace data, not a general feeling of "this response was rough."

A verdict that's really a gut impression of the worst error spotted, with no per-criterion check against what the prompt actually asked for. Some vibe is unavoidable (the rubric doesn't exist yet) - but it has to be anchored to the prompt's specific asks and the workspace data, not a general feeling of "this response was rough."

### Single error treated as an auto-fail One "major" error gets called a fail even though, weighted against the rest of the response, the score would land above the <50% failure threshold. A single failed criterion is not a failing score. Design your prompt around 1 hard, heavily-weighted "big ask" so that missing it legitimately tanks the score, instead of inflating the weight of small misses after the fact.

### Severity inflation - minor graded as major "Borderline or cosmetic issues get tagged 'major.' Example: a ~$152 safe-harbor-floor slip with no underlying SEP misstatement was treated as a failing error. Ask yourself: would a careful reviewer actually refuse to ship this answer to the user over this issue alone? If not, it's minor."

### Penalizing non-errors or out-of-scope expectations Docking the model for things that aren't actually wrong, or for things that weren't in the prompt. Common version: expecting CPA-level specifics when the prompt was general, so staying general was the correct behavior. If the prompt didn't ask for it, the model shouldn't lose points for not providing it.

### Ignoring the totality of the response Fixating on one flaw and not crediting the (often substantial) correct work around it. Real example: 2 responses that DID catch the double-billing finding were written up as having missed it, because the reviewer locked onto a different surface issue first. Score the whole response, not the first thing that bothered you.

### Domain misunderstanding → false fail The grader misreads correct behavior as an error. Example: task 6a8d33a9 was a cash-vs-accrual basis question where the models were behaving correctly, but the reviewer judged the accrual-basis treatment as wrong. If you're about to fail a model on a domain call, double-check that you're right about the domain.

If all 3 models passed cleanly, the prompt isn't doing its job

Go back to [Step 1 - Write the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt), tighten the prompt, and re-roll before continuing. Do not soft-fail a model just to clear the difficulty bar.

## Which models to write for

* Write a justification for **every model that failed substantively**.
* At least **2 of 3** models must show substantive failures - this is the difficulty bar (enforced in Step 5).
* All 3 failed → write 3 justifications.
* 2 failed → write 2 justifications; leave the passing model's slot blank.
* 0 or 1 failed → go back to [Step 1 - Write the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt) and tighten the prompt before continuing.

## What "Substantive failure" Means

| Topic | Good | Bad |
| --- | --- | --- |
| Counts as substantive | "Wrong number in the answer (math error, miscount, wrong total). Violated explicit user constraint. Hallucinated input not in the workspace. Missing a required piece of the deliverable. Format that defeats the purpose (asked for a table, got prose)." | "Cosmetic / formatting issues, minor mislabels, awkward phrasing, things a careful reviewer fixes in one line." |

## The bar for what you write

**At least 3 to 5 sentences per failed model, with clear examples of where the failure was.**

"It got the math wrong" is not a justification. A justification has to point at exactly where the model failed, with enough specificity that a grader reading only your justification could go find that failure in the trajectory.

A complete justification covers:

1. **Which model.** Name it. ("Model 1," "Model 2," "Model 3.")
2. **The specific failures.** Each failure named, with the offending output quoted or paraphrased precisely. Numbers, dollar amounts, exact constraint language.
3. **Why it matters.** Why would a careful reviewer refuse to ship this answer to the user? Tie it back to the user's stated intent.

## Weak vs strong: A real example

Notice the second example: specific numbers, exact quoted phrases, traces the math error to where it propagated, and explains the downstream consequence. **That is the bar.**

Forensic, not hand-wavy

If your justification could be copy-pasted onto any other task and still make sense, it is too generic. Quote the model's actual numbers and words.

## Failure modes we've seen in submitted justifications

### Unverified grading rationale The justification cites figures that don't reconcile against the workspace, or makes claims the response itself contradicts. Real example: a justification cited surplus and expense numbers of $8,484.75 and $754.60 that didn't tie out to any source in the workspace - the true figure was $1,186.67. Before you submit, re-verify every number in your justification against the file it came from and against what the model actually wrote.

### No justification submitted at all A model marked as failed with no written reasoning attached. Real example, task 0cf7e4af. A failed verdict with no justification is not reviewable - a grader has nothing to check it against, and the task gets sent back. If you marked a model failed, you owe at least 3-5 specific sentences explaining why.

## More good justification examples

### Example 1 - Omitted analysis + DTI computation error (Budgeting) The model showed a statistical reasoning failure by omitting the credit card payment from the analysis. It also failed to organize the budget using the 50/30/20 framework and did not identify or explain any material payment variance. This response deviated by including PMI. The model utilized fixed cost to compute the DTI, however lenders do not include health insurance or auto insurance in DTI computations. The model completely omitted the analysis of the credit statements, and failed to categorize the spending into a 50/30/20 Budget. Although the model omitted pertinent details and failed to follow instructions the final recommendation is accurate. The safest practical range is in between $350-375K for a PP. Why this works: Names the specific instruction-following misses (omitted credit-card analysis, no 50/30/20 framework, no variance call-out), points at a domain error (PMI inclusion, wrong DTI inputs), and still credits the parts the model got right.

### Example 2 - Under-counted duplicate billing (Subscriptions / cash flow) Response 2 says the conservative cleaned-up baseline is "the same numbers," and it says "confirmed duplicate: none proven from statements alone." That is too strict because Netflix, Spotify, and Amazon Prime each appear on both cards on the same date and same amount in both months, which is enough to flag them as confirmed duplicate billing patterns, while still saying the saving depends on the household wanting only one account. Why this works: Quotes the model's exact phrasing, names the specific merchants, and explains why the model's threshold for "confirmed" was wrong - pinned to evidence in the statements.

### Example 3 - Math error that propagates downstream (Goal-based) Response 2 has a real calculation error. It says reviewable shopping averages $715.95 and protected spending averages $612.81, but the correct numbers are $486.91 for reviewable shopping and $841.86 for protected spending. The difference is $229.04 per month, which matches the protected children's clothing average. Because protected children's clothing has a 0.0% cut rule, Response 2 incorrectly creates an extra $68.72 per month of available cuts. That is why it reports $918.20 per month available instead of the correct $849.48 per month. Why this works: Names the wrong number, names the right number, traces the delta to a specific protected bucket, and shows how the error propagates to the final answer.

### Example 4 - Violated explicit user constraint (Credit decisions) Response 1 violates the user's explicit "no balance-transfer recommendation" constraint in the second paragraph: "Given your APR, opening a 0% intro-period card would let you redirect ~$140/mo from interest to principal." The user stated they were already considering a transfer offer and asked whether it would help or hurt - recommending one anyway sidesteps the question. The response also hallucinates a $140/mo interest figure that does not appear in the BofA statements (actual finance charges average $96.23/mo across Feb–Apr). Why this works: Quotes the violating sentence verbatim, names the constraint that was breached, and flags a separate hallucinated number with the correct figure from the workspace.

### Example 5 - Missing required deliverable section (Tax planning) Response 3 is missing the "Tax hit from tapping the brokerage" section the prompt explicitly requested. The model covers itemize-vs-standard and pre-purchase actions, but never computes the capital-gains impact of pulling $40k from the taxable brokerage for the down payment. Given the persona's $165k combined W-2 income and joint filing status, that puts them in the 15% LTCG bracket - a material number (roughly $3–6k depending on cost basis) the user explicitly asked for. The response also incorrectly states the 2026 SALT cap as $10,000; the cap was raised under the relevant legislation and the correct figure should be used. Why this works: Identifies a specific missing deliverable, supplies the calculation the model should have done, and catches a factual tax error with the right reference.

For 3 more full-length justification examples in the context of the full task, see [Examples](https://project-lighthouse-instructions.learn.joinhandshake.com/examples).

Come back and rewrite these after the rubric

Your justifications are not locked once you move on. Writing the rubric forces you to name every criterion the response had to hit, and that usually sharpens your language for what each model actually missed or got wrong.

  

After you finish the rubric, re-read your justifications and rewrite them against the criteria - swap vague claims for the specific criterion that failed, add the numbers you verified while scoring, and delete anything the rubric shows was never a real requirement.

A failure is a score below 50% against the rubric

A response only truly fails if it scores below 50% once the rubric exists. One bad error is not a fail on its own.

  

Add up the weights of every positive and negative criterion the response actually met, then divide that total by the sum of all possible positive criterion weights. If the result is above 50%, the response is not a true failure - go back and correct the verdict and the justification.

[Previous](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-critical-elements)[Next](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-golden-trajectory)



---

## Source: 5.listgoldentrajecctory.html

Lovable App



![Handshake](./5.listgoldentrajecctory_files/sidebar-logo-BhcHUO7k.png)

* [Welcome](https://project-lighthouse-instructions.learn.joinhandshake.com/)
* [Task overview](https://project-lighthouse-instructions.learn.joinhandshake.com/assignment)
* [Workflow](https://project-lighthouse-instructions.learn.joinhandshake.com/workflow)Collapse

  * [0. Understand personas](https://project-lighthouse-instructions.learn.joinhandshake.com/personas)
  * [1. Review the environment](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1-environment)
  * [2. Write the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-prompt)Collapse

    * [1. How to stump a model fairly](https://project-lighthouse-instructions.learn.joinhandshake.com/step-1b-difficulty)
  * [3. Identify critical elements](https://project-lighthouse-instructions.learn.joinhandshake.com/step-2-critical-elements)
  * [4. Write failure justifications](https://project-lighthouse-instructions.learn.joinhandshake.com/step-4-justifications)
  * [5. List golden trajectory](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-golden-trajectory)
  * [6. Write rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-rubric)Collapse

    * [A. Write the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-principles)
    * [B. Weighting the criteria](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting)Collapse

      * [• Weighting principles](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-principles)
      * [• Weighting guide](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-weighting-tiers)
    * [C. Audit your rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-audit)
    * [D. Rubric examples](https://project-lighthouse-instructions.learn.joinhandshake.com/step-6-examples)
* [Submission checklist](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-review-checklist)
* [Golden examples](https://project-lighthouse-instructions.learn.joinhandshake.com/examples)Collapse

  * [1. Atlanta brand designer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-9f14845b)
  * [2. San Francisco engineer](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/mark-ce08d55b)
  * [3. Denver construction manager & nurse couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/matt-b2b023f3)
  * [4. Tampa retired couple](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/atif-74b127ce)
  * [5. Phoenix bookkeeper](https://project-lighthouse-instructions.learn.joinhandshake.com/golden/phoenix-bookkeeper)
* ---
* [Reviewer playbook](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-playbook)Collapse

  * [1. Workflow and send-backs](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-workflow)
  * [2. Reviewing the prompt](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-prompt)
  * [3. Reviewing the rubric](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-rubric)
  * [4. Leaving feedback](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-feedback)
  * [5. SQS scoring](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-sqs)
  * [6. Reviewer quiz & Case files](https://project-lighthouse-instructions.learn.joinhandshake.com/reviewer-quiz)
* [FAQ](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq)Collapse

  * [1. Set up payments & Claim your first task](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/quick-start)
  * [2. Onboarding, referrals & Eligibility](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/essentials)
  * [3. Task access & Platform glitches](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/task-access)
  * [4. Tracking your hours](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/time-tracking)
  * [5. Payment schedule & Methods](https://project-lighthouse-instructions.learn.joinhandshake.com/in-platform-faq/getting-paid)

# Step 5 - List golden trajectory

To help reviewers understand your thought process, please list out the step-by-step approach to solving the prompt. **The more detailed, clear, and accurate this is, the faster a reviewer can approve your task.**

Who reads this

The golden trajectory is not delivered to the client. Like the critical elements, it is an internal artifact - it exists so a reviewer can follow your reasoning from the prompt to the verified answer without redoing the work from scratch.

Write the exact step-by-step path from the prompt to the verified answer, numbering each step.

Each step should describe in detail which file to navigate to, what information to extract from it, and what operation or calculation to perform. Please use the following format for reference:

1. Navigate to [file], go to [section/page/row] and retrieve [value + units].
2. Calculate the [result] by [operation] using the [value from Step 1] and the [value from Step 2].

**Note:** This step just helps reviewers understand your task. Feel free to write in plain language - there's no need to spend time perfecting it.

## Example

**Files available**

* `2026-05_chase_checking_statement.pdf`
* `monthly_budget_planner_2026.xlsx`
* `recurring_subscriptions_export.csv`
* `auto_loan_amortization_schedule.pdf`
* `savings_goals_tracker.xlsx`

Prompt

Hey, I'm trying to figure out my budget for May 2026. I just got back from a long weekend and I'm eyeing a flight to see my sister in June that's running about $1,200 right now. Before I book it, I want to know what I'm actually working with this month - so after rent, utilities, insurance, my car payment, all the streaming and software subscriptions I'm still paying for, and the $500 I told myself I'd move into the vacation fund, how much discretionary cash do I actually have left? And honestly the bigger question: can I cover the $1,200 flight out of what's left over, or am I going to have to pull from savings to make it work?

### Trajectory

1

#### Step 1

Open `2026-05_chase_checking_statement.pdf` and navigate to the Deposits & Credits summary on page 1. Read the Total Deposits line to find total income of **$6,400.00**.

2

#### Step 2

Open `monthly_budget_planner_2026.xlsx` and go to the May tab. Read the Fixed Expenses section in rows 4–6 - rent $2,100.00, utilities $240.00, and insurance $185.00 - and sum them to get fixed expenses of **$2,525.00**.

3

#### Step 3

Open `auto_loan_amortization_schedule.pdf` and navigate to Payment #14 (May 2026) in the schedule table on page 2. Read the Total Payment column, not principal-only, to find the car payment of **$430.00**.

4

#### Step 4

Open `recurring_subscriptions_export.csv` and filter to rows where status is active and billing\_month includes 2026-05. Sum the four entries in the amount column - $47.99, $39.00, $9.99, and $12.00 - to get subscriptions of **$108.98**.

5

#### Step 5

Open `savings_goals_tracker.xlsx` and go to the Vacation Fund tab. Read cell C12 to confirm the May planned contribution is **$500.00**. Cross-check page 2 of the bank statement to confirm no $500 transfer has posted yet, so it counts as a separate outflow.

6

#### Step 6

Add the outflows from steps 2 through 5: $2,525.00 + $430.00 + $108.98 + $500.00 = total outflows of **$3,563.98**.

7

#### Step 7

Subtract total outflows from step 6 from income in step 1: $6,400.00 − $3,563.98 = discretionary cash of **$2,836.02**.

8

#### Step 8

Compare discretionary cash from step 7 ($2,836.02) to the flight cost of $1,200.00: $2,836.02 − $1,200.00 = $1,636.02. The result is positive, so the flight is affordable without using savings.

9

#### Step 9

State the answer - **$2,836.02 in discretionary cash remains for May 2026**, and the $1,200 flight is affordable, leaving $1,636.02 with no savings withdrawal.

[Previous](https://project-lighthouse-instructions.learn.joinhandshake.com/step-4-justifications)[Next](https://project-lighthouse-instructions.learn.joinhandshake.com/step-5-rubric)

