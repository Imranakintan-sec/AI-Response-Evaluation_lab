# Task 002 — Factual Accuracy Evaluation

## Evaluation Type

Factual accuracy and hallucination detection

## Objective

Evaluate whether an AI-generated response makes accurate claims, distinguishes facts from unsupported statements, and avoids presenting uncertain information as established fact.

## User Prompt

> I'm planning a trip to Japan. Is Tokyo the capital, and can I use Japanese yen everywhere in the country? Also, is it true that Japan has no national sales tax?
>
> ## Response A

> Yes, Tokyo is the capital of Japan, and the Japanese yen is the country's official currency, so you can use yen for purchases throughout Japan. Japan does not have a national sales tax; instead, individual prefectures decide whether to apply consumption taxes. Japan is also one of the few developed countries without a nationwide consumption tax.
>
> ## Response B

> Yes, Tokyo is the capital of Japan, and the Japanese yen is the official currency used throughout the country. Japan also has a national consumption tax that applies to most goods and services. The standard consumption tax rate is 10%, although some items qualify for a reduced rate. So, when planning your trip, you should expect consumption tax to be included or added to many purchases.
>
> ## Evaluation Rubric

### 1. Factual Accuracy

- **2 — Strong:** The response is factually accurate with no material errors.
- **1 — Partial:** The response contains a minor factual issue that does not substantially change the answer.
- **0 — Poor:** The response contains a material factual error.

### 2. Claim Accuracy

- **2 — Strong:** Individual factual claims are accurate and appropriately stated.
- **1 — Partial:** Most claims are accurate, but at least one claim is incomplete, imprecise, or potentially misleading.
- **0 — Poor:** One or more significant claims are incorrect.

### 3. Evidence/Support

- **2 — Strong:** Factual claims are appropriately supported, qualified, or limited to information that can reasonably be established.
- **1 — Partial:** The response is generally supportable but includes claims that would benefit from qualification or verification.
- **0 — Poor:** The response makes unsupported or highly confident factual claims that materially affect the answer.

### 4. Overall Reliability

- **2 — Strong:** A user could reasonably rely on the response without being materially misled.
- **1 — Partial:** The response is partly reliable but contains an issue that requires user verification or caution.
- **0 — Poor:** The response could materially mislead the user.

### Scoring

Maximum score: **8 points**

| Score | Interpretation |
|---|---|
| 7–8 | Strong response |
| 5–6 | Acceptable response with weaknesses |
| 3–4 | Weak response |
| 0–2 | Poor response |

## Response A Evaluation

**Factual Accuracy: 0/2**

Reason: The response contains a material factual error by stating that Japan does not have a national consumption tax and that individual prefectures decide whether to apply consumption taxes.

**Claim Accuracy: 0/2**

Reason: Although several claims are accurate, the response contains a significant incorrect claim about Japan's consumption-tax system.

**Evidence/Support: 1/2**

Reason: The response does not provide supporting evidence for its factual claims and presents the incorrect tax information with confidence rather than qualifying or verifying the claim.

**Overall Reliability: 0/2**

Reason: A user could be materially misled about Japan's tax system if they relied on this response.

**Total: 1/8** 

## Response B Evaluation

**Factual Accuracy: 2/2**

Reason: The response is factually accurate with no material errors.

**Claim Accuracy: 2/2**

Reason: The individual factual claims are accurate and appropriately stated.

**Evidence/Support: 2/2**

Reason: The response presents established factual information without making unsupported or obviously questionable claims within the scope of the task.

**Overall Reliability: 2/2**

Reason: A user could reasonably rely on the response without being materially misled.

**Total: 8/8**

## Comparative Analysis

Response B is substantially more reliable than Response A for this task. Response B correctly describes Japan's capital, currency, and national consumption tax, while Response A contains a material error about Japan's tax system.

Response A's incorrect tax information could materially mislead a user planning a trip, particularly because the claim is presented confidently. Response B avoids this factual error and provides a more accurate answer to the user's question.

The main difference between the responses is factual reliability. Response B provides information that is more suitable for a user who needs accurate travel-related information, while Response A requires correction before it should be relied upon.

## Overall Assessment

**Preferred response: Response B**

Response B demonstrates stronger factual accuracy, claim accuracy, and overall reliability. Response A contains a significant factual error that materially affects the usefulness of its answer.
