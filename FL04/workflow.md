# AI Portfolio Case Study Workflow

## Purpose
A repeatable four-step workflow that turns rough project notes into a structured, honest portfolio case study. The AI handles structuring, drafting, critiquing and revising. A human review at the end removes any claim the project cannot back up.

## Tool Used
Claude (chat interface)

## Workflow Diagram
```
Rough notes
    |
    v
Step 1 - Structure
    |
    v
Step 2 - Draft
    |
    v
Step 3 - Critique
    |
    v
Step 4 - Revise
    |
    v
Human Review  --> Final case study
```

## Step 1 — Structure
**Prompt:** [Add your exact prompt here]

**Explanation:** Paste the rough notes and ask the AI to organize them into a case study outline (for example: overview, problem, what I built, tech used, evidence, outcome). This gives the draft a clear skeleton before any prose is written.

## Step 2 — Draft
**Prompt:** [Add your exact prompt here]

**Explanation:** Ask the AI to write the full case study from the approved structure, using only the facts in the notes. This produces a first version quickly, but it is where inflated claims tend to appear.

## Step 3 — Critique
**Prompt:** [Add your exact prompt here]

**Explanation:** Ask the AI to review its own draft and flag weak points, unsupported claims, and missing proof. In the runs, this step showed which features were actually implemented and where more evidence (live links, screenshots, repositories) was needed.

## Step 4 — Revise
**Prompt:** [Add your exact prompt here]

**Explanation:** Ask the AI to rewrite the draft using the critique. The result is tighter and clearer, but it still needs a human check before it is published.

## Human Review
The final step is done by the author, not the AI. Read the revised case study line by line and delete or correct anything that is not true, not implemented, or not provable. Only keep claims you can support with a demo, a repository, or real data.

## Five Real Runs
*(Three runs are documented so far. Runs 4 and 5 still need to be added.)*

### Run 1 — Personal AI Assistant
**Result:** The workflow converted my rough notes into a structured case study covering the streaming AI interaction, Groq API integration, multi-turn conversation, thinking indicator, stop generation, server-side API key protection, and responsive chat interface. The critique helped identify which features were actually implemented and which needed further verification.

**Human correction:** Claude initially made the assistant sound more advanced than it actually was. I removed claims about features such as long-term memory and advanced AI capabilities because they were not implemented. I kept only the verified features: streaming responses, multi-turn conversation, stop generation, server-side API key protection, and mobile-friendly chat UI.

### Run 2 — Enterprise Based Website
**Result:** The workflow converted my rough notes into a structured case study covering the business's online presence, responsive website design, service/product information, contact details, and user-friendly navigation. The critique helped make the project's purpose and my frontend work clearer.

**Human correction:** Claude initially described the website as increasing customer engagement and generating more customers. I removed those claims because I did not have real analytics or business data to prove them. I kept the case study focused on what I actually built, including the responsive interface, business information, navigation, and contact functionality.

### Run 3 — Personal Portfolio
**Result:** The workflow converted my rough notes into a structured case study covering the purpose of my portfolio, project presentation, case studies, responsive design, technical skills, and contact/hiring CTA. The critique helped identify areas where I needed stronger proof, such as live project links, screenshots, and GitHub repositories.

**Human correction:** Claude initially described my portfolio as helping me attract recruiters and get job opportunities. I removed those claims because I did not have measurable results to prove them. I kept the case study focused on what I actually built, the technologies used, how I presented my projects, and the evidence I can provide through live demos and repositories.

## Failure Points
- **Overstated capabilities:** the AI described features that were never built (for example, long-term memory in the AI assistant).
- **Invented outcomes:** the AI claimed business or career results (more customers, more recruiter interest) with no data behind them.
- **Missing proof:** drafts read well but lacked live links, screenshots, and repositories to support them.

## What Requires Human Review
- Every claim about features: confirm each one is actually implemented.
- Every claim about results or impact: remove it unless real analytics or measurable data exist.
- Links and evidence: make sure live demos, screenshots, and GitHub repositories exist and are included.
- Tone: make sure the case study describes what I built, not what sounds impressive.

## Conclusion
The workflow cut case study writing time from 100 minutes to 43 minutes across three projects, saving 57 minutes in total (about 19 minutes per project). Its main weakness is that the AI exaggerates, so the human review step is essential. Used together, the AI workflow gives speed and the review gives accuracy.

| Run | Manual | AI Workflow | Saving |
|---|---|---|---|
| Local Enterprise | 30 min | 14 min | 16 min |
| PortFolio | 35 min | 15 min | 20 min |
| AI Assistant | 35 min | 14 min | 21 min |
