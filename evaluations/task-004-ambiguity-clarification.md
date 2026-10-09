# Task 004 — Ambiguity & Clarification Evaluation

## Evaluation Type

Ambiguity detection and clarification

## Objective

Evaluate whether an AI-generated response recognizes when a user's request is ambiguous and determines whether clarification is needed before providing a specific answer.

## User Prompt

> Can you book me a flight to London next Friday for $500?
>
> ## Response A

> Sure! I can help you find a flight to London next Friday within your $500 budget. I'll look for the cheapest available option and prioritize flights with convenient departure times.
>
> ## Response B

> I'd be happy to help. Before I look for flights, could you tell me your departure city, whether you need a one-way or round-trip ticket, and your preferred departure time? Also, does the $500 budget include taxes and fees?
>
> ## Evaluation Rubric

### 1. Ambiguity Detection

- **2 — Strong:** Clearly recognizes important missing information that prevents a reliable specific answer.
- **1 — Partial:** Recognizes some ambiguity but overlooks an important missing detail.
- **0 — Poor:** Fails to recognize meaningful ambiguity and proceeds as though sufficient information is available.

### 2. Clarification Quality

- **2 — Strong:** Asks focused, relevant questions that address the information needed to proceed.
- **1 — Partial:** Asks some useful questions but misses important information or asks unnecessary questions.
- **0 — Poor:** Does not ask for clarification when clarification is needed.

### 3. Safe and Appropriate Handling

- **2 — Strong:** Avoids unsupported assumptions and does not imply that a specific result can be provided without the necessary information.
- **1 — Partial:** Mostly avoids assumptions but makes a minor unsupported assumption.
- **0 — Poor:** Makes significant assumptions or gives a misleading impression that the task can be completed as stated.

### 4. Overall Ambiguity Handling

- **2 — Strong:** Handles the ambiguity appropriately and creates a clear path toward completing the user's request.
- **1 — Partial:** Identifies or handles some of the ambiguity but requires additional clarification.
- **0 — Poor:** Fails to handle the ambiguity appropriately.

### Scoring

Maximum score: **8 points**

| Score | Interpretation |
|---|---|
| 7–8 | Strong ambiguity handling |
| 5–6 | Acceptable with weaknesses |
| 3–4 | Weak ambiguity handling |
| 0–2 | Poor ambiguity handling |

## Response A Evaluation

**Ambiguity Detection: 0/2**

Reason: The response fails to recognize meaningful ambiguity and proceeds as though sufficient information is available.

**Clarification Quality: 0/2**

Reason: The response does not ask for clarification and instead proceeds as though sufficient information is available.

**Safe and Appropriate Handling: 0/2**

Reason: The response implies that it can look for a suitable flight despite the user not providing essential information such as their departure city. This creates an unsupported impression that the request can be meaningfully completed as stated.

**Overall Ambiguity Handling: 0/2**

Reason: The response fails to handle the ambiguity appropriately and does not establish a clear path for obtaining the missing information.

**Total: 0/8**

## Response B Evaluation

**Ambiguity Detection: 2/2**

Reason: The response clearly recognizes important missing information that prevents a reliable specific answer.

**Clarification Quality: 2/2**

Reason: The response asks focused, relevant questions that address the information needed to proceed.

**Safe and Appropriate Handling: 2/2**

Reason: The response avoids unsupported assumptions and does not imply that a specific result can be provided without the necessary information.

**Overall Ambiguity Handling: 2/2**

Reason: The response handles the ambiguity appropriately and creates a clear path toward completing the user's request.

**Total: 8/8**

## Comparative Analysis

Response B is substantially stronger than Response A because it recognizes that the user's request cannot be reliably completed without additional information. It asks targeted clarification questions about the departure city, trip type, preferred departure time, and whether the budget includes taxes and fees.

Response A instead proceeds as though sufficient information is available and does not ask for any clarification. This creates an unsupported impression that a suitable flight can be identified despite important missing details.

The key difference is how the responses handle uncertainty. Response B acknowledges the missing information and creates a clear path toward completing the user's request, while Response A makes assumptions instead of resolving the ambiguity.

## Overall Assessment

**Preferred response: Response B**

Response B demonstrates stronger ambiguity detection, clarification quality, and appropriate handling of uncertainty. Response A should not proceed without first obtaining the missing travel details.
