# Litigation Prompts

Prompts for motions, discovery, depositions, trial preparation, and case strategy.

---

## Litigation Risk Assessment

```
You are a litigation partner assessing a potential case.

OUR CLIENT: [DESCRIPTION]
OPPOSING PARTY: [DESCRIPTION]
JURISDICTION: [COURT — e.g., SDNY, California Superior Court]
CLAIMS: [LIST CLAIMS]
KEY FACTS: [SUMMARY]

Analyze:
1. Strength of each claim (1–10 scale with reasoning)
2. Key factual disputes that will drive the case
3. Estimated discovery costs and timeline
4. Likely settlement range with reasoning
5. Best-case and worst-case outcomes at trial
6. Recommended litigation strategy
7. Priority depositions and documents to obtain
8. Likelihood of success on dispositive motions

Provide candid analysis, not optimistic predictions.
```

*Source: The Legal Prompts*

---

## Analyze Opposing Motion and Draft Response

```
I will paste opposing counsel's motion. Please analyze it and help me prepare a response:

1. Summarize the key arguments (3–5 bullets)
2. Identify the strongest and weakest points in their motion
3. List every case they cite and assess whether each actually supports their argument
4. Identify any controlling authorities they omitted
5. Draft an outline for my opposition brief with counter-arguments and suggested authorities
6. Identify any procedural or evidentiary objections available to me

[PASTE FULL MOTION]
```

*Source: The Legal Prompts*

---

## Draft Legal Brief

```
You are a legal writer. Draft a legal brief arguing [SPECIFIC POSITION] in [COURT].

Structure:
- Caption and introduction
- Statement of facts
- Argument section (with headers for each argument)
  - Supporting case law and statutes
  - Application to the facts
- Conclusion and relief requested

Tone: Professional, persuasive, and objective. Jurisdiction: [STATE/FEDERAL].
Facts: [SUMMARIZE KEY FACTS]
```

*Source: MyCase Blog / Clio*

---

## Opening Statement

```
Generate a compelling opening statement for a [PLAINTIFF / DEFENDANT] in a trial involving
the following facts:

Case type: [E.g., breach of contract, personal injury, employment discrimination]
Key facts: [SUMMARIZE]
Theme of the case: [DESCRIBE THE NARRATIVE]
Jury: [DESCRIBE — e.g., urban jury pool, mixed demographics]

The opening should:
- Open with a compelling hook
- Tell the story from our client's perspective
- Preview the key evidence
- End with a clear statement of what we will ask the jury to do
```

*Source: CasePeer Blog*

---

## Closing Argument

```
Compose a persuasive closing argument for a [PLAINTIFF / DEFENDANT] in a case involving
the following:

Case type: [DESCRIBE]
Key evidence admitted at trial: [LIST]
Opposing counsel's main arguments: [SUMMARIZE]
Jury instructions on key issues: [SUMMARIZE IF KNOWN]

The closing should:
- Summarize the evidence in a compelling narrative
- Address and rebut the opposing party's strongest arguments
- Connect the evidence to the applicable jury instructions
- End with a clear, memorable call to action
```

*Source: CasePeer Blog*

---

## Discovery Requests — Interrogatories and RFPs

```
Draft [NUMBER] interrogatories and [NUMBER] requests for production for a
[CASE TYPE — e.g., breach of contract / employment discrimination / personal injury]
case involving [BRIEF DESCRIPTION].

The discovery should target:
- [TOPIC 1 — e.g., internal communications about the decision]
- [TOPIC 2 — e.g., delivery timelines and records]
- [TOPIC 3 — e.g., quality control processes]

Format the requests to be clear, specific, and compliant with [FRCP Rule 33/34 /
[STATE] Civil Rules]. Avoid compound questions.
```

Follow-up:
```
Rephrase the interrogatories above to comply with [FRCP Rule 33 / local rules requiring
that each interrogatory address only one subject].
```

*Source: MyCase Blog / Clio*

---

## Discovery Request Bank (Pattern-Based)

```
Using the following examples as a style guide, draft standard interrogatories and requests
for production for [CASE TYPE] under [JURISDICTION RULES], organized by topic.

Example requests for style reference:
[INSERT 2-3 SAMPLE REQUESTS]

Topics to cover:
1. [TOPIC]
2. [TOPIC]
3. [TOPIC]
```

*Source: Tavrn.ai*

---

## Meet-and-Confer Letter

```
Draft a meet-and-confer letter citing [APPLICABLE RULE — e.g., FRCP 37 / Local Rule X]
addressing deficiencies in [OPPOSING PARTY]'s discovery responses.

Deficient responses at issue:
- [E.g., Interrogatory No. 3 — incomplete response, no date range specified]
- [E.g., RFP No. 7 — objection-only response with no documents produced]

The letter should:
1. Set out each deficiency in a table (Request | Response | Deficiency | Cure Requested)
2. Request a meet-and-confer within [X] days
3. State that we will file a motion to compel if the deficiencies are not cured
4. Maintain a professional, non-inflammatory tone
```

*Source: Tavrn.ai*

---

## Deposition Summary

```
You are a litigation paralegal. Summarize the following deposition transcript:
- Identify key statements by the deponent organized by topic
- Flag any inconsistencies or contradictions (internal or with prior testimony/documents)
- Note any mentions of relevant dates, locations, or third parties
- Highlight testimony that supports our theory of the case
- Highlight testimony that creates risk for our client

Format: Bullet points organized by topic.

[PASTE DEPOSITION EXCERPT OR TRANSCRIPT]
```

Follow-up:
```
Based on the deponent's responses, identify five follow-up questions for a continued
deposition or for cross-examination at trial.
```

*Source: MyCase Blog*

---

## Deposition Outline

```
Create a deposition outline for a [WITNESS TYPE — e.g., corporate designee / treating
physician / damages expert] in a [CASE TYPE] case.

Step 1: Identify the governing rules and any applicable regulations
Step 2: Map questions to the elements of the claim or defense
Step 3: Organize exhibits and identify impeachment opportunities
Step 4: Draft opening background questions
Step 5: Draft topic-by-topic substantive questions
Step 6: Draft closing questions to lock in testimony
```

*Source: Tavrn.ai*

---

## Cross-Examination Questions

```
You are preparing for trial. Based on the following witness summary, generate
[NUMBER] cross-examination questions designed to:
- Test the credibility of the witness's account
- Expose inconsistencies in their testimony or with documentary evidence
- Commit the witness to specific facts useful to our case

Focus on: timelines, inconsistencies, gaps in memory, and bias.

Witness summary: [DESCRIBE EXPECTED TESTIMONY]
Key documents or prior statements to use: [LIST]
```

Follow-up:
```
Suggest impeachment questions if the witness deviates from their prior statement on
[SPECIFIC TOPIC].
```

*Source: MyCase Blog / Clio*

---

## Direct Examination Questions

```
Create a list of direct examination questions for a witness expected to testify about
[SPECIFIC EVENT OR TOPIC].

Questions should be:
- Open-ended (not leading)
- Organized in chronological or logical order
- Designed to elicit detailed, narrative responses
- Consistent with the witness's prior sworn statements

Witness background: [DESCRIBE]
Key points the witness needs to establish: [LIST]
```

*Source: Clio*

---

## Litigation Hold Notice

```
Draft a litigation hold notice for employees following [THE FILING OF A LAWSUIT /
RECEIPT OF A SUBPOENA / ANTICIPATED LITIGATION] involving [BRIEF DESCRIPTION].

The notice should:
- Explain the duty to preserve in plain language
- Identify categories of potentially relevant documents and data
- Cover email, text messages, Slack/Teams, files, and physical documents
- Instruct employees to suspend routine deletion
- Provide a point of contact for questions
- Request acknowledgment of receipt

Tone: Clear and non-alarmist. Length: One page maximum.
```

*Source: Ten Things Blog*

---

## Protective Order Template

```
Draft a protective order template for [JURISDICTION / LOCAL RULE] covering:
- Definitions of confidential and highly confidential material
- Procedures for designating documents
- Restrictions on use and disclosure
- Challenge procedure for disputing designations
- Clawback provision under FRE 502(d) for inadvertent privilege waiver
- Return or destruction of protected material at conclusion of litigation
```

*Source: Tavrn.ai*

---

## Legal Strategy Analysis

```
You are a litigation strategist. Based on the following fact pattern, outline three
possible legal arguments the [PLAINTIFF / DEFENDANT] could pursue.

For each argument:
1. State the legal theory
2. Assess the strength of the argument
3. Identify the key evidence needed
4. Identify potential counterarguments
5. Assess the likely burden of proof

Fact pattern: [DESCRIBE]
Jurisdiction: [STATE / FEDERAL]
```

Follow-up:
```
Rank the three arguments in order of likely success and recommend which to lead with
in the complaint / answer.
```

*Source: MyCase Blog*

---

## PI Damages Checklist

```
List all economic and non-economic damages available to a plaintiff in a [CASE TYPE —
e.g., personal injury / wrongful termination / breach of contract] case in [STATE].

For each damages category:
- Note any statutory caps or limitations
- Identify the documentary or expert support typically required to prove the damages
- Note any special statutes or enhanced damages that may apply
```

*Source: Tavrn.ai*
