# raise-manifesto

The RAISE Community Proposal
Drafted: November 2025
Objective: RAISE is a community framework built on Transparency, Intent, and Empathy. We believe that if you commit code, you, not the AI—are the author, and you 
bear full responsibility for its effects on the system and your teammates.

Premise: The current landscape of software development in late 2025 is defined by a polarization between "AI bans" (projects rejecting all AI contributions due 
to quality concerns) and "Vibe Coding" (uncritical acceptance of AI outputs). Research from mid-to-late 2025 highlights a phenomenon known as 
"The Quality Floor Collapse." 

While AI tools have lowered the barrier to creating code, they have raised the cost of reviewing it. "PR Slop" refers to verbose, subtly buggy, 
or hallucinatory code that looks correct at a glance but fails under edge cases, overwhelming maintainers.

The following document outlines a framework for RAISE (Responsible AI-assisted Software Development). 
It draws on lessons from the "AI backlash" of 2025 and adapts the structure of the Agile Manifesto to provide a balanced, community-driven path forward.

## The RAISE Manifesto

| We Value... | Over... |
| :--- | :--- |
| Human Understanding & Intent | Machine Generation & Speed |
| Verified Correctness | Plausible-Looking Output |
| Reviewer Empathy | Contributor Convenience |
| Transparent Provenance | Hidden Automation |

### The Principles of RAISE
1. The Human is the Architect: AI is a tool for implementation, not the "contributor".
2. Review is Mandatory: No AI-generated code enters the codebase without human review. "LGTM" (Looks Good To Me) is insufficient; "I understand this" is the standard.
3. Own the Code: If you commit AI-generated code, you own it. "The AI wrote it" is never a valid excuse for a bug, security flaw, or logic error.
3. Transparency is Professionalism: We openly disclose which tools were used to generate code. Hiding the use of AI is a breach of trust.
4. Testing is the Truth: AI is prone to "confident incompetence." Therefore, AI-generated code requires higher test coverage, not lower. Ideally, tests should be written by the human before generation (TDD) to prevent the AI from "marking its own homework" by generating both the buggy code and the passing test that ignores the bug.
5. Combat Bloat: We use AI to refactor and simplify, not to add unnecessary verbosity just because it is easy to generate. We respect our teammates' time by aggressively pruning AI output, verifying logic before the PR, and adding comments explaining our, (human concieved), intent, not just the AI's logic.
6. Security by Design: We actively probe AI suggestions for known vulnerabilities (e.g., injection flaws, hallucinated dependencies) before implementation.
7. Skill Preservation and growth: We use AI to explain complex concepts, not to bypass learning them. If you cannot explain the code you submitted during a live review, you did not write it—you merely pasted it.
8. Sustainable Pace: We do not use AI to create impossible deadlines. We use efficiency gains to improve code quality and work-life balance.
9. Ethical Sourcing: We prefer and advocate for AI tools trained on ethically sourced data and respect the licenses of open-source code. We acknowledge that policies which ban or restrict AI code exist to protect legal clarity. We do not submit AI code to projects with incompatible licenses.
11. Continuous Adaptation: We continuously update our practices as AI models evolve, remaining skeptical of hype and focused on engineering fundamentals.
