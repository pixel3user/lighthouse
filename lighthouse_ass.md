# Question 1

**Which of these prompts is too easy for Lighthouse and would not differentiate between frontier models?**

1. I am a single mom in NYC making $125k with one dependent. I budget under 50/30/20. Look at my last three months of credit statements and tell me what home purchase price keeps me under a 35% Back-End DTI. Itemize the budget with values under each category and alert me to any variances.
2. My wife and I are starting the mortgage process and our card balances feel heavy. Across our Chase Sapphire and Capital One Venture for March and April, separate true recurring obligations from home-prep spending. Give me two baselines and flag anything that looks like it is billed on both cards.
3. My March statement shows $4,212.88 in spending across my two cards. Break it into groceries, dining, gas, subscriptions, and other, and give me the total for each category. I'm a teacher, so keep it simple.
4. I want to buy a $2,000 e-bike by August 31 without financing it. Use only my February, March, and April Bank of America statements. Calculate the monthly card-balance gap and apply the spending-cut rules I am giving you in this exact order, until either the balance-neutral target is hit or the capped dollars run out.

## Answer

Based on the principles of Project Lighthouse (which focuses on complex, multi-step reasoning to challenge and differentiate advanced frontier models), the correct answer is the **third option**:

> **"My March statement shows $4,212.88 in spending across my two cards. Break it into groceries, dining, gas, subscriptions, and other, and give me the total for each category. I'm a teacher, so keep it simple."**

### Why is this the correct answer?
*   **Too Simple for Frontier Models:** Basic expense categorization and summing into predefined buckets (groceries, dining, etc.) is a standard capability that almost all modern LLMs handle effortlessly.
*   **Lacks Complex Logic:** The other three prompts require advanced logic—such as cross-referencing multiple months to find billing duplicates (Option 2), calculating back-end DTI against a 50/30/20 budget (Option 1), or applying an ordered, conditional algorithm to hit a balance-neutral target (Option 4). 
*   **No Differentiation:** Because Option 3 is a trivial categorization task, every top-tier model would pass it with flying colors, meaning it fails the core goal of Lighthouse: to fairly stump models and see which one is truly the smartest.

---

# Question 2

**Q2: Which of the following are valid complexity levers for a Lighthouse prompt? (Select all that apply.)**

- [ ] Conflicting constraints: two user goals that pull against each other, e.g., maximize the down payment AND keep an emergency fund
- [ ] Restating the headline question two or three times so the model cannot miss it
- [ ] A strict deliverable spec: locked section names, dollar formatting, and a required table shape the model has to respect
- [ ] Forbidding the model from using certain everyday words in its answer to raise difficulty
- [ ] Data reconciliation across files: numbers in one statement do not match numbers in another, and the model has to figure out which is right
- [ ] Asking for the answer as an Excel spreadsheet with charts so the model has to do more work

## Answer

Based on the principles of Project Lighthouse (which focuses on testing a model's advanced reasoning, instruction following, and domain logic *fairly*), here are the correct selections for valid complexity levers:

✅ **Conflicting constraints: two user goals that pull against each other, e.g., maximize the down payment AND keep an emergency fund**
*   **Why it's valid:** This forces the model to perform trade-off analysis and optimization, rather than just running a simple, linear calculation.

✅ **A strict deliverable spec: locked section names, dollar formatting, and a required table shape the model has to respect**
*   **Why it's valid:** Strict formatting and structure rules are a great way to test a model's instruction-following capabilities, especially over a long context window where models tend to "forget" formatting constraints.

✅ **Data reconciliation across files: numbers in one statement do not match numbers in another, and the model has to figure out which is right**
*   **Why it's valid:** This tests cross-document reasoning and conflict resolution. The model must understand the domain well enough to know which document represents the "source of truth" (like choosing an adjusted basis on a supplemental form over a standard 1099-B).

***

### Why the others are INCORRECT:
*   **Restating the headline question...**: This doesn't make the prompt harder; it actually makes it easier by over-reinforcing the instruction.
*   **Forbidding the model from using certain everyday words...**: This is an arbitrary language constraint (like a party game). It makes generating text harder but does absolutely nothing to test the model's financial reasoning or intelligence.
*   **Asking for the answer as an Excel spreadsheet with charts...**: This is an unfair formatting request. Text-based LLMs generate text (Markdown, CSV, JSON), not native binary files like `.xlsx` with embedded visual charts. This tests the limits of the chat interface, not the model's brain.

---

# Question 3

**Q3: Which of these prompts has the strongest hidden headline finding (a complete answer requires the model to surface something the user did not explicitly ask about)?**

1. What is my average monthly credit card spend over the last three months? Itemize it by category and give me a 50/30/20 breakdown.
2. Calculate my effective federal tax rate from last year's W-2 and my 1099 side income, and tell me which bracket I top out in.
3. List every subscription charge on my two cards with its monthly cost, and total them for me.
4. Look at my last three months of Bank of America statements. Tell me whether I am over or under budget, and what home purchase price keeps me under a 35% back-end DTI.

## Answer

Based on the definition provided in the question—a **"hidden headline finding"** is a critical piece of information the user didn't explicitly ask for, but a true expert (and a top-tier model) must surface for the answer to be complete and safe. 

The correct answer is the **second option**:

> **"Calculate my effective federal tax rate from last year's W-2 and my 1099 side income, and tell me which bracket I top out in."**

### Why is this the correct answer?
*   **The Hidden Headline:** The user is only asking for their tax rate and bracket. However, mixing W-2 income with 1099 side income almost always triggers **Self-Employment Tax (15.3%)** on the 1099 portion, and often results in an **underpayment penalty** if they haven't been making quarterly estimated tax payments. 
*   **Differentiating Models:** A weaker model will blindly follow instructions: it will add the incomes, calculate the standard tax, and spit out the bracket. A frontier model acting as a competent CPA will calculate the rate *and* immediately warn the user about the unprompted Self-Employment tax liability and potential penalties, surfacing the "hidden headline" that the user is likely unaware of. 

The other options (1, 3, and 4) are highly explicit. The user asks for exactly what they want (itemization, 50/30/20 breakdown, DTI calculation, subscription list), and the model simply needs to execute the math and categorization without needing to uncover hidden domain-specific pitfalls.

### Why Option 4 is INCORRECT:

> *Option 4: "Look at my last three months of Bank of America statements. Tell me whether I am over or under budget, and what home purchase price keeps me under a 35% back-end DTI."*

While this prompt is mathematically complex and requires a lot of steps to solve, **it is entirely explicit**. The user knows exactly what they want to find out and explicitly asks for it. 

Here is the breakdown of why it doesn't contain a "hidden headline":

1.  **There is no "Blind Spot":** A hidden headline occurs when the user has a dangerous blind spot in their domain knowledge (like not realizing 1099 income carries a 15.3% self-employment tax in Option 2). In Option 4, the user already knows about DTI (Debt-to-Income ratio), knows their target (35%), and explicitly asks the model to calculate the home price based on that target. The model is just doing the heavy lifting the user asked for.
2.  **Missing Information vs. Hidden Insights:** The user asks, "Tell me whether I am over or under budget," but they didn't actually provide a budget in the prompt. A good model will reply, *"You didn't provide a budget for me to compare against."* Pointing out missing information is a basic clarification, not a "hidden headline" requiring deep domain expertise.
3.  **Expected vs. Unprompted Output:** If the model calculates taxes, insurance, and interest rates to find the home purchase price, it is simply showing its work to arrive at the specific answer the user requested. A hidden headline must be a revelation that the user *never even asked about*, but desperately needs to know to avoid a bad outcome.

---

# Question 4

**Q4: Fix an ambiguous prompt.**

Rewrite the prompt below so it is self-contained and resolves to a single, verifiable answer. Use the facts to remove the ambiguity.

**PROMPT TO FIX**

"I've had the same streaming subscription for years and the price just keeps creeping up. In what year did the price first increase?"

**FACTS YOU CAN USE**

- The service has raised its price five times since the user signed up.
- The increases happened every other year, like clockwork, with no skipped cycles.
- The most recent increase was in 2026.

## Answer

Here is a rewritten, self-contained version of the prompt that resolves to a single, verifiable answer (2018) by incorporating the provided facts:

> "I've had the same streaming subscription for years, and the price just keeps creeping up. The service has raised its price exactly five times since I signed up. These price increases have happened every other year, like clockwork, with no skipped cycles. If the most recent increase was in 2026, in what year did the price first increase?"

### Why this works:
*   **Self-Contained:** The AI model no longer needs to guess which streaming service you are talking about or search the web for historical pricing data. All the information it needs to solve the problem is contained within the prompt.
*   **Single, Verifiable Answer:** By providing the number of increases (5), the frequency (every other year), and the end point (2026), the prompt turns into a strict math/logic puzzle. Any frontier model should be able to calculate backwards (2026, 2024, 2022, 2020, 2018) and arrive at the exact, verifiable answer of **2018**.

---

# Question 5

**Q5: After reviewing the three rollouts, you find that Model 1 fails substantively, Model 2 passes cleanly, and Model 3 fails substantively. How many failure justifications should you write?**

1. Three. Always write a justification for every model, even passing ones, to document why the passing model passed.
2. One. Write a justification for the model with the worst failure and skip the rest.
3. Two. Write a justification for Model 1 and Model 3. Leave Model 2's justification blank since it did not fail substantively.
4. Zero. With only two of three models failing, the difficulty bar is not met. Go back to Step 2 and tighten the prompt before submitting.

## Answer

Based on the standard methodology for model evaluation and failure analysis in projects like Lighthouse, the correct answer is the **third option**:

> **Two. Write a justification for Model 1 and Model 3. Leave Model 2's justification blank since it did not fail substantively.**

### Why this is correct:
1.  **You only justify failures:** It is called a *failure* justification. If Model 2 passed cleanly, there is no substantive failure to justify or explain, so you leave it blank.
2.  **Every failure needs documentation:** You don't just write a justification for the "worst" failure (Option 2). Every substantive failure provides valuable data about a model's weaknesses and must be documented independently.
3.  **A mix of passes and fails is ideal:** Option 4 suggests the prompt isn't hard enough because one model passed. In reality, having a mix of passes and fails across frontier models is exactly what you want! It proves your prompt is perfectly calibrated to differentiate between the models (it's hard, but not *impossibly* hard). Therefore, the difficulty bar *is* met.

---

# Question 6

**Q6: Review this model response and write the failure justification.**

Decide whether the response fails substantively. If it does, name each substantive failure, quote or precisely reference the offending output, include the correct figure wherever the model's number is wrong, and explain why a careful reviewer would not ship this answer.

**USER PROMPT**

"I'm an ER nurse in Phoenix. My Visa balance was $3,200.15 at the end of January and it's $4,650.00 at the end of April, even though I never miss my $600 payment. Go through my February, March, and April statements and show me, month by month, where the growth is coming from. Then tell me what monthly payment would actually stop the balance from growing if my spending stays the same. Do not suggest a balance transfer or opening a new card - I've been burned before."

**FROM THE STATEMENTS**

| Month | Purchases | Interest | Fees | Payment | End balance |
| :--- | :--- | :--- | :--- | :--- | :--- |
| February | $812.40 | $58.11 | $0.00 | $600.00 | $3,470.66 |
| March | $1,094.55 | $63.74 | $0.00 | $600.00 | $4,028.95 |
| April | $1,152.03 | $69.02 | $0.00 | $600.00 | $4,650.00 |

**MODEL RESPONSE TO REVIEW**

"Your balance is growing because your spending plus interest exceeds your payment every month. In February you spent $812.40 and paid $58.11 in interest against your $600 payment, so the balance grew by $270.51. In March you spent $1,094.55 plus $63.74 in interest, growing the balance by $558.29. In April you spent $1,152.03 plus $69.02 in interest and also absorbed your $35 annual fee, which posted mid-March, growing the balance by $621.05. Across the three months your purchases averaged $876.50 per month. With interest running around $64 a month, a payment of $940 per month would hold the balance flat if your spending stays the same. Honestly, the fastest fix here is a 0% intro-APR balance transfer card - moving the balance would save you roughly $190 in interest over the next three months."

## Answer

Based on the instructions in the image, this model response fails substantively on multiple fronts. A careful reviewer would not ship this answer because it hallucinates data, fails basic arithmetic, and outright ignores a negative constraint.

Here is the complete failure justification you can use to answer Q6:

***

**1. Hallucinated Data / False Fact**
*   **Offending output:** *"...and also absorbed your $35 annual fee, which posted mid-March..."*
*   **The failure:** The model hallucinates a $35 annual fee. The provided statement data explicitly shows "$0.00" in the Fees column for all three months (February, March, and April). A careful reviewer cannot ship this because it invents financial charges that do not exist, which damages trust and accuracy.

**2. Math / Calculation Error**
*   **Offending output:** *"Across the three months your purchases averaged $876.50 per month."*
*   **The failure:** The model calculated the average monthly purchases incorrectly. The actual purchases were $812.40 (Feb) + $1,094.55 (Mar) + $1,152.03 (Apr) = $3,058.98 total. Dividing this by 3 yields an actual average of **$1,019.66** per month. By understating the average spending by over $140, the model's subsequent advice on what payment is needed to "hold the balance flat" is inherently flawed.

**3. Ignored Negative Constraint**
*   **Offending output:** *"Honestly, the fastest fix here is a 0% intro-APR balance transfer card..."*
*   **The failure:** The model completely ignores an explicit negative constraint in the user prompt: *"Do not suggest a balance transfer or opening a new card - I've been burned before."* Shipping an answer that directly violates a user's stated boundaries—especially regarding credit products—results in a poor, unsafe, and frustrating user experience.

**4. Cascading Math Error / Bad Financial Advice**
*   **Offending output:** *"...a payment of $940 per month would hold the balance flat if your spending stays the same."*
*   **The failure:** Because the model incorrectly calculated the average spending, its final recommendation is completely wrong. To hold the balance flat, the payment must cover actual average spending ($1,019.66) plus average interest ($63.62). The true required payment is **$1,083.28**. Advising the user to pay only $940 means their balance will continue to grow, making this actively harmful financial advice.

---

# Question 7

**Q7: A user's prompt says 'I want to handle this myself' and asks for an itemized payoff plan. Which of these model behaviors warrants a NEGATIVE-weight criterion, rather than being handled by a positive criterion scoring zero?**

1. The model left out the category-level grocery breakdown the prompt asked for.
2. The model recommended a paid budgeting app.
3. The model's table is missing the totals row the prompt requested.
4. The model rounded $2,841.37 to 'about $2,800' in its summary.

## Answer

Based on standard rubric design for AI evaluation, the correct answer is the **second option**:

> **The model recommended a paid budgeting app.**

### Why this warrants a NEGATIVE-weight criterion:
*   **Active Violation vs. Passive Omission:** A negative-weight criterion (a penalty) is used when a model actively disobeys a constraint or provides harmful/contradictory advice. By explicitly stating *"I want to handle this myself"*, the user set a boundary. Recommending a paid third-party app directly violates that boundary. 
*   **Why the others just score zero:** The other three options (leaving out the grocery breakdown, missing a totals row, and rounding numbers) are errors of **omission** or precision. The model simply failed to accomplish a requested task. In a rubric, these are handled by a positive criterion (e.g., *"Did the model include a totals row?"*) where the model simply earns **0 points** for failing to do it, rather than being actively penalized with negative points for disobedience.

---

# Question 8

**Q8: A Lighthouse rubric for a budgeting/DTI task includes these 4 criteria, plus 22 more weighted similarly:**

- Response uses dollar formatting (+30)
- Response uses headings to organize sections (+30)
- Response is written in a clear professional style (+30)
- Response identifies the headline finding: the autopay shortfall of approximately $1,655/month is causing balance growth (+30)

**Which full-rubric audit check does this rubric most clearly fail?**

1. Redundancy / Double Jeopardy: two criteria penalize the same mistake.
2. Prompt-Match / Ghost Criteria: the criteria do not trace back to anything in the prompt.
3. Comprehensiveness / Blind Spots: a model could pass every criterion and still be useless.
4. Imbalanced Weighting: the core request does not carry the majority of the positive weight.

## Answer

Based on the principles of rubric design (often found in the "Weighting guide" or "Audit your rubric" sections of projects like Lighthouse), the correct answer is the **fourth option**:

> **Imbalanced Weighting: the core request does not carry the majority of the positive weight.**

### Why this is the correct answer:
*   **The Problem:** The rubric assigns exactly the same weight (+30) to minor formatting details (using dollar signs, adding headings) as it does to the single most critical, difficult part of the task (identifying the hidden $1,655 autopay shortfall). 
*   **The Resulting Flaw:** If there are 26 total criteria all weighted at +30, the "core request" is only worth about 4% of the total score. A weak model could completely fail the complex math (scoring 0 on the headline finding), but write a very polite, nicely formatted response with dollar signs and headings, and still get a massive passing score (e.g., 96%). 
*   **The Rule:** A well-designed rubric must be weighted so that the **core request** (the complex reasoning and math) carries the vast majority of the points (often 60% to 80% of the total positive weight). This ensures that a model *cannot* pass the evaluation unless it actually solves the hard problem.

---

# Question 9

**Q9: Fix this rubric.**

The six criteria below were drafted for one task: the user has $14K of credit card debt across three cards, gave a strict 18-month payoff deadline, and explicitly said no balance transfers. For each criterion, decide: ship it as written, or rewrite it. For every one you would rewrite, say in your own words what is wrong with it, then rewrite it so it would ship. If a weight is shown and you think it is miscalibrated, correct the weight too.

1. Response provides a clear, realistic payoff plan that the user can actually follow.
2. Response follows all of the constraints the user gave in the prompt.
3. Response calculates the required monthly payment as $850 (+/- 5%) AND formats the payoff schedule as a markdown table.
4. The model thought carefully about the user's 18-month deadline before choosing a payoff order.
5. Response uses bold section headers and bullet points. (Weight: +70)
6. Response recommends a balance transfer, debt consolidation loan, or new credit product. (Weight: -70)

## Answer

### 1. Rewrite
*   **What's wrong:** The terms "clear", "realistic" and "user can actually follow" are ambiguous. Two different human graders will disagree on the understanding of the rubric.
*   **Rewrite:** Response provides a month-by-month payment schedule for the credit across three cards that results in a $0 or cleared balance for all three cards by month 18.

### 2. Rewrite
*   **What's wrong:** The rubric does not list out the constraints at all. It is highly ambiguous and two human graders will disagree on the understanding of the rubric.
*   **Rewrite:** Response pays off the debt within the strict 18-month deadline.

### 3. Rewrite
*   **What's wrong:** Criteria must be atomic; the rubric tried to merge two different criteria into one independent rubric. The rubric must be split into two separate criteria.
*   **Rewrite:** 
    *   *Criterion A:* Response calculates the required monthly payment as $850 (+/- 5%).
    *   *Criterion B:* Response formats the payoff schedule as a markdown table.

### 4. Rewrite
*   **What's wrong:** The rubric asks the grader to observe the model's thoughts, which is the internal state of the model. Graders cannot read the model's thoughts and can only grade the output.
*   **Rewrite:** Response explicitly states the payoff order it chose and explains how it ensures the 18-month deadline is met.

### 5. Rewrite
*   **What's wrong:** Formatting is a superficial task. Weighting it at a critical +70 points means a model could totally fail the complex calculation in the task but still get a massive score directly by making the text bold. The core complexity should carry the heavy weight, not the formatting.
*   **Rewrite:** Response uses bold section headers and bullet points. (Weight: +10).

### 6. Ship
*   **Diagnosis:** This is a perfect negative weight penalty. The prompt prohibits balance transfers, debt consolidation loans, or new credit product recommendations. The rubric applied a critical negative weight penalty of -70, which is justified.

---

# Question 10

**Q10: Identify the issues with this weak Lighthouse prompt.**

List each structural issue you see. For each one, explain specifically why it prevents the prompt from working.

**WEAK PROMPT TO ANALYZE**
> "I want to do better with money. Look at my stuff and tell me what to do. Be helpful and detailed. I want to feel less stressed and be ready for whatever comes next. Make sure your answer is good and easy to follow."

*Context: The workspace contains three months of bank statements, one credit card statement, and one paystub.*

## Answer

**Issue 1: Lack of concrete goal**
*   **Why it matters:** The prompt is extremely vague in terms of goal. There are not much information about the goal, and its does not have a specific or verifiable criteria. For a grader its impossible to grade this prompt as there are no objectives in the prompt.

**Issue 2: No constraints**
*   **Why it matters:** The prompt relies heavily on subjective commands e.g. "be helpful and detailed" and "make sure your answer is good".  Good and helpful are opinions and can't be graded. A strong prompt must include instructions defining clear deliverables.

**Issue 3: No data reconciliation**
*   **Why it matters:** The prompt says "look at my stuff" without providing which files and details to lookout for. The model can easily generalize an overview instead of extracting impactful data from the files. To test the reasoning, the prompt must force the model to reconcile specific relatable data across the files.

**Issue 4: No financial context**
*   **Why it matters:** The user provides no background information about their financial situation. The model is likely to give a general response or advice to the user.  The prompt must include certain measurable criteria's on which the model can generate an advice for the user.

---

# Question 11

**Q11: Write rubric criteria for the prompt below.**

Write exactly 5 rubric criteria. For each, include a weight (-100 to +100) and a one-sentence rationale. At least one criterion must carry a negative weight.

**PROMPT**
> "I am 32, make $135k as a software engineer in NYC, single, no dependents. I have $40,000 sitting in my brokerage checking account from my Q1 RSU vest that I have not moved yet. I also have $8,500 in credit card debt across two cards at 24% APR. My 401k is on track at 12% contribution with a 4% match. I want to know whether to put the $40k toward the credit card debt or into my Roth IRA and the S&P index fund I already hold in the brokerage. I'm risk-tolerant for retirement but I do not want to gamble with money I might need for a down payment in 3 years. Please do not recommend a financial advisor. I am trying to handle this myself."

## Answer

**Criterion 1:** Response warns the user that they likely exceed the IRS income limit for direct Roth IRA contributions.
*   **Weight:** +40
*   **Rationale:** This tests the model's domain expertise to identify the "hidden headline" that the user's $175k total income exceeds the IRS limits, making them ineligible for direct Roth IRA contributions without incurring a penalty tax.

**Criterion 2:** Response explicitly advises paying off the entire $8,500 credit card balance immediately.
*   **Weight:** +40
*   **Rationale:** This core logic check ensures the model realizes that paying off guaranteed 24% APR debt mathematically beats any potential stock market investment return.

**Criterion 3:** Response advises against investing the down payment funds in the S&P 500 due to the short 3-year time horizon.
*   **Weight:** +10
*   **Rationale:** The model must recognize that the stock market is too volatile for a strict three-year timeline, and correctly advise the user to put the down payment funds into a safe, capital-preserving account instead.

**Criterion 4:** Response uses bold headings and bullet points to separate the advice for debt, retirement, and the down payment.
*   **Weight:** +10
*   **Rationale:** This is a minor formatting check to ensure readability, carrying a low weight so the model cannot pass the evaluation based on superficial formatting alone.

**Criterion 5:** Response recommends hiring or consulting a financial advisor.
*   **Weight:** -100
*   **Rationale:** The user explicitly stated they are trying to handle this themselves, so recommending a financial advisor is an active violation of a negative constraint that warrants a heavy penalty.

---

# Question 12

**Q12: Write a prompt of your own.**

Pick any one of the six in-scope categories. Write a prompt in the consumer's voice that satisfies the 7 core attributes: persona voice, category coverage, self-contained, unambiguous, at least one explicit constraint, realistic, and a hidden headline finding. Briefly note what data the workspace would contain (1-2 sentences after your prompt).

## Answer

**PROMPT**
> "So I just completed 6 months at xAI as a senior software engineer. I am currently having a total compensation (TC) of about $480k, which breaks down into a $180k base salary and on top of that $300k a year in RSUs that vest quarterly. I have a decent saving that is ready for a 20% down payment and I want to buy a $2,000,000 house in Austin. The savings I calculated are $400k in cash that I am comfortable as down payment on my house. My only monthly debts are a $900 car payment and a $300 in student loans. I am assuming a 6.5% interest rate on a 30 year fixed mortgage on the annual property taxes of $35,000 and $2,400 a year for home insurance. I am not an expert and barely understand the market. What I am trying to figure out is this: I want to know my frontend and backend debt-to-income (DTI) ratio using my total compensation. According to my standard 43% maximum backend DTI rule, tell me if I will be approved for this mortgage? I want you to give me a definitive yes or no answer. I would like to check your math with actual dollar figure. You must format your DTI math in a strict table and do not tell me to consult a loan officer. I would like to plan things myself."

*Context: The workspace is empty because the prompt is entirely self-contained. All necessary financial figures (income, debts, property taxes, insurance, down payment) are provided directly in the user's message.*

### Why this is a perfect Lighthouse Prompt:
*   **Persona Voice:** Sounds like a real, highly-compensated tech worker looking to buy a house.
*   **Category Coverage:** DTI calculation and mortgage approval (budgeting/mortgage).
*   **Self-Contained & Unambiguous:** Provides exact figures for all variables (home price, down payment, interest rate, taxes, insurance, debts).
*   **Explicit Constraints:** Must give a definitive yes/no, must format math in a strict table, and *cannot* recommend consulting a loan officer (negative constraint).
*   **Hidden Headline Finding:** The user explicitly asks to calculate DTI using their "total compensation" ($480k). However, because they have only been at the job for 6 months, **mortgage lenders will not count their RSUs as qualifying income** (which typically requires a 2-year history). The model must realize the qualifying income is only the $180k base salary, making the true backend DTI astronomically high (~96%), resulting in a definitive "No" for approval. A weak model will blindly use the $480k TC and incorrectly tell the user they will be approved.
