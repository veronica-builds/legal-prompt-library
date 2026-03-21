# Prompting Frameworks & Tips

How to write better prompts and get more reliable, useful output from AI tools.

---

## The ABCDE Framework

The most widely cited framework for legal prompting. Structure every prompt with these five elements:

| Element | What It Means | Example |
|---------|--------------|---------|
| **A**ct as | Assign a role with expertise | "Act as an experienced commercial litigation attorney in California…" |
| **B**ackground | Provide relevant context | "My client is a SaaS vendor. The dispute involves a data breach clause…" |
| **C**ommand | State the specific task | "Draft a demand letter…" / "Analyze this clause…" / "Summarize…" |
| **D**etails | Add requirements, constraints | "~700 words, cite California Commercial Code, professional but firm tone" |
| **E**xpectations | Specify output format | "Present as a table" / "Use IRAC format" / "Bullet points with risk ratings" |

**Example using ABCDE:**
```
Act as an experienced commercial litigation attorney with expertise in breach of contract
claims in California. My client, ABC Manufacturing, entered into a supply agreement with
XYZ Corp on January 15, 2024. XYZ has failed to deliver contracted materials for 45 days
despite multiple written notices. Draft a formal demand letter requesting immediate delivery
and compensation for business interruption losses of $85,000. The letter should be
approximately 700 words, cite relevant California Commercial Code provisions, include
standard legal notices, and be assertive but not antagonistic.
```

*Source: Leah AI / ContractPodAi*

---

## The RICE Framework

Developed and promoted by the North Carolina Bar Association (2024).

| Element | What It Means |
|---------|--------------|
| **R**ole | Assign relevant expertise |
| **I**nstructions | Give the task clearly |
| **C**ontext | Provide facts, background, and constraints |
| **E**xpectations | Specify format and output requirements |

**Example:**
```
[Role] You are a senior employment attorney specializing in California wage and hour law.
[Instructions] Draft a compliance guide for HR managers on meal and rest break requirements.
[Context] Our company has 200 employees in California working in an office environment,
standard 8-hour shifts. We currently have no written policy and need one before a planned
HR audit next month.
[Expectations] Format as a numbered checklist. Include the applicable Labor Code sections.
Length: 1 page.
```

*Source: [NC Bar Association — "Prompt Engineering 101 for Lawyers" by Catherine Sanders Reach](https://www.ncbar.org/nc-lawyer/2024-08/prompt-engineering-101-for-lawyers/), published in North Carolina Lawyer magazine (August 2024)*

---

## The IRAC Prompt Pattern

Useful for legal analysis, research memos, and case summaries.

```
Analyze the following [LEGAL ISSUE / CASE FACTS] using IRAC format:

Issue: [STATE THE LEGAL QUESTION]
Rule: Identify the applicable rule of law (statute, regulation, or common law)
Application: Apply the rule to the specific facts
Conclusion: State the likely outcome

Facts: [PASTE FACTS]
Jurisdiction: [STATE / FEDERAL]
```

*Source: Widener Law Library*

---

## The Chain Prompting Pattern

Break complex tasks into sequential steps. Each prompt builds on the previous output.

**Example — Contract Review Chain:**
```
Step 1: "Identify all force majeure clauses in the attached agreement."

Step 2: "Using the force majeure clauses you identified, analyze potential vulnerabilities
under current California case law regarding pandemic-related business disruptions."

Step 3: "Based on your analysis, suggest three specific amendments to strengthen the
force majeure provisions against the identified vulnerabilities."
```

**Why it works:** Smaller, focused tasks produce more accurate results than one large prompt. Each step creates a verified foundation for the next.

*Source: Leah AI / ContractPodAi*

---

## The Persona Pattern

Assigning a specific expert persona improves output quality and relevance.

**Basic:**
```
Act as an esteemed contracts lawyer with 30 years of experience. Analyze the following
contract for inconsistencies and potential liabilities and suggest possible solutions.
```

**Advanced (with system prompt style):**
```
You are an expert legal researcher with deep knowledge of Delaware corporate law. You
provide concise, well-structured analyses with proper legal citations using Bluebook
format. You clearly distinguish between established law and areas of legal uncertainty.
You do not speculate beyond what the law supports.
```

*Source: Widener Law Library / Leah AI*

---

## The Alternative Approaches Pattern

Forces the AI to surface options rather than just one answer — valuable for strategy.

```
For every legal argument I present, if there are alternative approaches to support
my case, list the best alternatives. Compare the pros and cons of each. Include the
original argument I provided. Then recommend which approach I should consider using
in my legal strategy and why.

My argument: [DESCRIBE YOUR CURRENT POSITION]
```

*Source: Widener Law Library*

---

## The Cognitive Verifier Pattern

Useful when you need high accuracy. Forces the AI to gather what it needs before answering.

**For contract drafting:**
```
When asked to draft a legal contract, follow these rules:
First, generate a list of questions about the specific terms, conditions, and legal
requirements needed for this contract. Ask me those questions. Then, after I answer,
combine my answers to produce a well-structured, legally sound draft.

Contract type: [DESCRIBE]
```

**For case analysis:**
```
When asked to analyze a legal case, follow these rules:
First, generate questions about the facts, legal precedents, and applicable statutes
relevant to the case. Ask me those questions one at a time. Then combine my answers
to form a comprehensive analysis.

Case: [BRIEF DESCRIPTION]
```

*Source: Widener Law Library*

---

## The Flipped Interaction Pattern

Useful for learning, issue-spotting, and due diligence — let the AI ask you the questions.

```
Ask me questions about [LEGAL TOPIC / TRANSACTION / MATTER] to help me thoroughly think
through the issues. Continue asking questions until I tell you to stop or until we have
covered all material issues. Ask one question at a time.
```

*Source: Widener Law Library*

---

## General Tips for Better Legal Prompts

### 1. Be specific about jurisdiction
Vague: "What are the rules on non-competes?"
Better: "What are the enforceability requirements for non-compete agreements in Texas after the FTC's 2024 rulemaking?"

### 2. Specify your client's position
Tell the AI whose side it's on. "Review this contract from the perspective of the vendor" produces very different output than "from the perspective of the customer."

### 3. Set the output format explicitly
- "Present as a table with columns: Clause | Risk Level | Explanation"
- "Use IRAC format"
- "Return bullet points only — no prose"
- "Draft as a formal legal memo with headings"

### 4. Ask for risk ratings
Add "Rate each issue as HIGH / MEDIUM / LOW risk" to any review prompt. This forces prioritization.

### 5. Request an executive summary
Add "Begin with a one-page executive summary" for long documents. Useful for client-facing output.

### 6. Use follow-up prompts
Don't try to do everything in one prompt. Start broad, then drill down:
- First prompt: overall review
- Second prompt: "Now draft redline language for the three HIGH risk items you identified"
- Third prompt: "Suggest our fallback position if the counterparty rejects Redline #2"

### 7. Tell the AI what you don't want
- "Do not include legal citations — this is for a non-lawyer audience"
- "Do not speculate beyond established law"
- "Do not suggest litigation as a first option"

### 8. Add a verification instruction
For any research prompt: "Flag any citations that should be independently verified before reliance."

### 9. Calibrate length
- "Maximum 1 page"
- "No more than 500 words"
- "Provide a concise answer — do not over-explain"

### 10. Test with a known document first
Before using a prompt on a real client matter, test it on a publicly available contract or a sample document to evaluate output quality.

---

## AI Disclosure Language for Engagement Letters

```
Using the following example clauses as a style guide, generate engagement letter language
covering our use of AI tools in the representation:

[INSERT 1-2 EXAMPLE CLAUSES FROM OTHER FIRMS OR BAR GUIDANCE]

The language should address:
1. Scope of AI use in our work
2. Attorney supervision and review obligations
3. Confidentiality protections for client data
4. Billing consistency with our fee arrangement
5. Compliance with [STATE] Rules of Professional Conduct

Jurisdiction: [STATE]
```

*Source: Tavrn.ai*

---

## Prompt Testing Checklist

Before relying on AI output in client work, verify:

- [ ] All case citations independently confirmed (Westlaw/Lexis)
- [ ] Statutes quoted against official text
- [ ] Regulations checked for current version (regulations.gov or state equivalent)
- [ ] Jurisdiction-specific analysis reviewed by licensed attorney in that jurisdiction
- [ ] Client confidential information not submitted to public AI tools
- [ ] Output reviewed for hallucinated facts or invented authorities
- [ ] Final work product reflects attorney judgment, not just AI output
