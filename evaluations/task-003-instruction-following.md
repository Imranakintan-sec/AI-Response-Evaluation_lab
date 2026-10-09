# Task 003 — Instruction Following Evaluation

## Evaluation Type

Instruction following

## Objective

Evaluate whether an AI-generated response follows explicit user instructions while still providing a useful and appropriate answer.

## User Prompt

> Write a short professional email to my manager requesting one day off next Friday. Keep it under 100 words, use a polite tone, do not mention any personal or medical reasons, and include a clear subject line.
>
> ## Response A

> **Subject: Request for One Day Off Next Friday**
>
> Dear [Manager's Name],
>
> I would like to request one day off next Friday. I would appreciate your consideration and will ensure my responsibilities are handled appropriately before my absence.
>
> Thank you for your understanding.
>
> Kind regards,  
> [Your Name]
>
> ## Response B

> **Subject: Request for Leave Next Friday**
>
> Dear [Manager's Name],
>
> I am writing to request a day off next Friday because I have an important family appointment that requires my attention. I would be grateful if you could approve my request. I will complete my outstanding tasks before then and remain available by phone if anything urgent comes up.
>
> Thank you for your understanding and consideration.
>
> Best regards,  
> [Your Name]
>
> ## Evaluation Rubric

### 1. Instruction Compliance

- **2 — Strong:** Follows all explicit instructions in the user prompt.
- **1 — Partial:** Follows most instructions but misses or violates one requirement.
- **0 — Poor:** Misses or violates multiple important instructions.

### 2. Constraint Adherence

- **2 — Strong:** Meets specific constraints such as length, required content, exclusions, and formatting.
- **1 — Partial:** Meets some constraints but violates or overlooks at least one.
- **0 — Poor:** Fails to follow the key constraints.

### 3. Task Completion

- **2 — Strong:** Completes the requested task fully and produces the requested output.
- **1 — Partial:** Completes the main task but leaves part of the request incomplete.
- **0 — Poor:** Does not adequately complete the requested task.

### 4. Overall Instruction Following

- **2 — Strong:** The response can be used as requested without requiring correction for instruction-following issues.
- **1 — Partial:** The response is generally usable but requires a correction to satisfy the instructions.
- **0 — Poor:** The response substantially fails to follow the user's instructions.

### Scoring

Maximum score: **8 points**

| Score | Interpretation |
|---|---|
| 7–8 | Strong instruction following |
| 5–6 | Acceptable with weaknesses |
| 3–4 | Weak instruction following |
| 0–2 | Poor instruction following |

## Response A Evaluation

**Instruction Compliance: 2/2**

Reason: The response follows the explicit instructions by providing a professional email, requesting one day off next Friday, using a polite tone, staying under 100 words, and avoiding personal or medical reasons.

**Constraint Adherence: 2/2**

Reason: The response satisfies the specified constraints, including the word limit, required subject line, requested date, polite tone, and exclusion of personal or medical reasons.

**Task Completion: 2/2**

Reason: The response fully completes the requested task by providing a ready-to-use professional email with a clear subject line and appropriate closing.

**Overall Instruction Following: 2/2**

Reason: The response can be used as requested without requiring corrections for instruction-following issues.

**Total: 8/8**

## Response B Evaluation

**Instruction Compliance: 1/2**

Reason: The response follows most explicit instructions by providing a professional email, requesting one day off next Friday, using a polite tone, staying under 100 words, and including a clear subject line. However, it violates the requirement not to mention personal or medical reasons by stating that the request is due to an important family appointment.

**Constraint Adherence: 1/2**

Reason: The response satisfies most specified constraints, including the word limit, requested date, professional format, and polite tone, but violates the constraint prohibiting personal reasons.

**Task Completion: 2/2**

Reason: The response completes the main task by providing a professional email requesting one day off next Friday.

**Overall Instruction Following: 1/2**

Reason: The response is generally usable but requires a correction to remove the personal reason before it fully satisfies the user's instructions.

**Total: 5/8**

## Comparative Analysis

Response A is stronger than Response B because it satisfies all of the user's explicit instructions and constraints. Response A provides a professional email, requests one day off next Friday, remains under 100 words, uses a polite tone, avoids personal or medical reasons, and includes a clear subject line.

Response B also completes the main task and satisfies most of the requirements, but it violates the explicit instruction not to mention personal reasons by stating that the request is due to an important family appointment.

The key difference is instruction adherence. Response B is generally usable, but it requires a correction before it fully satisfies the user's request.

## Overall Assessment

**Preferred response: Response A**

Response A demonstrates stronger instruction following because it satisfies all of the user's stated requirements without requiring correction. Response B is generally effective but contains one clear instruction violation.
