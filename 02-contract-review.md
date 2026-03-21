# Contract Review Prompts

Prompts for reviewing, redlining, risk-rating, and summarizing contracts.

---

## Full Contract Redline Review

```
You are outside counsel reviewing a contract on behalf of [CLIENT TYPE — e.g., SaaS vendor,
enterprise customer, service provider]. I will paste the full contract below.

Please:
1. Identify provisions that are unfavorable to my client
2. Flag any unusual or aggressive clauses
3. Highlight ambiguous or undefined language
4. Suggest specific redline language for each issue
5. Rate each issue as HIGH / MEDIUM / LOW risk
6. Provide a one-page executive summary at the top

Organize your response as a clause-by-clause analysis with section references.

[PASTE CONTRACT]
```

*Source: The Legal Prompts*

---

## Quick Risk Scan

```
You are a contract analyst. Review the following agreement for unusual or missing clauses.
Flag any potential red flags, especially regarding termination, liability, or indemnity.
Respond in bullet points with a brief explanation for each finding.

[PASTE CONTRACT]
```

Follow-up:
```
Summarize the key risks from the contract above in plain language for a non-legal client.
Keep the tone neutral and informative.
```

*Source: MyCase Blog*

---

## Plain-English Contract Summary

```
You are a legal assistant. Summarize the following contract by identifying:
- The parties and their roles
- The purpose of the agreement
- Key obligations of each party
- Payment terms
- Duration and renewal
- Termination rights
- Any unusual or notable provisions

Use clear, bullet-pointed sections.

[PASTE CONTRACT]
```

Follow-up:
```
Condense the summary above into three plain-language paragraphs suitable for briefing
a business client who is not a lawyer.
```

*Source: MyCase Blog*

---

## Identify and Analyze a Specific Clause Type

```
Review the attached agreement and:
1. Identify all [CLAUSE TYPE — e.g., force majeure / indemnification / termination] clauses
2. Analyze potential vulnerabilities under current [JURISDICTION] case law regarding
   [SPECIFIC SCENARIO — e.g., pandemic-related disruptions / data breaches]
3. Suggest three specific amendments to strengthen these provisions

[PASTE CONTRACT]
```

*Source: Leah AI / ContractPodAi*

---

## Clause Comparison — Which Version Favors Whom

```
Compare the two [CLAUSE TYPE] clauses below. Identify which version favors the
[SUPPLIER / CUSTOMER / VENDOR] and explain why.

Present your analysis in a side-by-side Markdown table with columns:
Clause Text | Risk Level (Low/Medium/High) | Explanation

Focus on:
1. Scope of the clause
2. Trigger events and limitations
3. Reciprocity or imbalance between parties

End with a one-line recommendation on which clause [PARTY] should prefer and why.

Clause A: [PASTE]
Clause B: [PASTE]
```

*Source: The Legal Prompts*

---

## Comprehensive Lease Review

```
Review the following commercial lease agreement and:
1. Identify all provisions related to early termination rights for both landlord and tenant
2. Extract key financial obligations: base rent, CAM charges, security deposit, escalations
3. Flag any unusual or non-standard provisions compared to typical [CLASS A / CLASS B]
   office leases in [CITY/STATE]
4. Create a table summarizing all identified provisions with clause numbers and page references
5. Highlight potential risks or ambiguities in the termination and renewal provisions

[PASTE LEASE]
```

*Source: Leah AI / ContractPodAi*

---

## Vendor Agreement Risk Checklist

```
Prepare a checklist to review vendor agreements with a focus on provisions that could
create long-term operational risk for a [COMPANY TYPE]. Include:
- Contract term and auto-renewal traps
- Price escalation and benchmarking rights
- Data ownership and portability
- Termination for convenience rights
- SLA commitments and remedies
- Limitation of liability and indemnification balance
- Governing law and dispute resolution
```

*Source: Ten Things Blog*

---

## NDA Redline

```
Redline this NDA to ensure mutual protection for both parties. Specifically:
- Convert any one-sided obligations to mutual ones
- Prohibit reverse engineering of disclosed information
- Extend trade secret protection indefinitely (or for the maximum permitted period)
- Ensure the definition of Confidential Information is appropriately scoped
- Add a residuals clause if appropriate for [CONTEXT]
- Add standard carve-outs: publicly known information, independent development,
  required disclosure

[PASTE NDA]
```

*Source: Ten Things Blog*

---

## Suggest Fallback Positions

```
A customer is requesting [AGGRESSIVE POSITION — e.g., unlimited liability for data breaches /
perpetual license / most favored customer pricing] in our [CONTRACT TYPE].

Suggest three fallback positions we can offer that protect our core interests while
giving the customer something meaningful. For each fallback, explain:
- What we are conceding
- What protection we retain
- The business rationale for offering it

Our standard position: [DESCRIBE]
Our non-negotiables: [LIST]
```

*Source: Ten Things Blog*

---

## Rewrite a Clause

```
Rewrite the following clause per the instruction below. Provide only the revised clause
text — no explanations.

Original clause:
[PASTE CLAUSE]

Instruction:
[E.g., "Make this mutual." / "Remove the carve-out for gross negligence." /
"Limit the scope to the territory of the United States." / "Make this more
favorable to the licensor."]
```

*Source: GitHub / TracyWang95*
