# LENS AI Readiness Map

**Auditor:** Test User | **Role:** Product Manager in SaaS | **Completed:** 2026-07-19T20:16:42.923Z

Kickstart scenario used: During a Q3 planning meeting, the VP mentioned integrating an LLM-powered workflow and asked each team lead to assess feasibility. You nodded but had no idea what implementation would require.

---

## Stage 1: Competence Identity Threat Inventory

### Incident Log

Incident 1: In a team standup, my manager asked if we could use GPT to summarize customer tickets. I froze and said I would look into it, though I had no idea where to start. Trigger: public technical question. Fear: being seen as outdated. Verdict: real gap. Incident 2: During a client call a stakeholder asked whether our roadmap included generative AI features and I deflected with a buzzword answer instead of admitting I had not scoped it. Trigger: being seen as the product expert. Fear: losing credibility. Verdict: manufactured, because I could have simply promised a follow up. Incident 3: A peer casually mentioned they had automated their reporting with a script and I felt a hot flash of inadequacy and changed the subject. Trigger: peer comparison. Fear: falling behind my cohort. Verdict: mostly manufactured, with a small real gap around scripting basics that I can close with a short course.

### Pattern Summary

My recurring mechanism is the Competence Identity Threat: I fear that admitting an AI knowledge gap will make me look obsolete, so I stay vague instead of asking. Most common trigger: public technical questions from leadership. Roughly 70% of my anxiety is manufactured. This pattern shows up whenever I am put on the spot about tools I have not personally used, and the fear is less about capability and more about reputation and identity, which is why naming it as a manufactured threat rather than a real skill gap helps me respond calmly and ask better clarifying questions instead of bluffing my way through the conversation.

---

## Stage 2: Level Principle Stack Map

**AI-affected decision responsibilities:**
Which vendor AI tools to approve for my team, how to prioritize the product roadmap when features touch AI, whether to automate our weekly reporting, and how to evaluate a candidate who claims AI fluency during hiring loops.

**Stack layer relevance assessment:**
Application layer: highly relevant, because I choose and configure the AI tools my team uses day to day and must judge their fit. Prompt and workflow layer: relevant, since I design how we interact with these tools and where they slot into our process. Model and API layer: partially relevant, I need enough fluency to reason about capabilities and cost but not to build. Infrastructure and training layer: not relevant, that is legitimately the platform team's job and sits below my Level Threshold. My threshold sits between the model layer and the infrastructure layer, so I commit to fluency above it and deliberately delegate everything below it.

**Level Threshold justification:**
I drew my Level Threshold between the model or API layer and the infrastructure layer. Two job responsibilities justify this choice clearly. First, I own vendor selection and roadmap prioritization decisions, which require me to reason fluently about model capabilities, their real limits, and the cost tradeoffs involved in each option. Second, I am directly accountable for delivery timelines but not for platform reliability or uptime, so training infrastructure, hosting, and scaling decisions legitimately sit with the platform team below my line and outside my required fluency zone.

**Load-Bearing Myth challenged:**
The Adoption Mirage — I felt everyone else understood all layers, so I should too

---

## Stage 3: Edge Inventory

### Knowledge Asset Catalog
1. Deep knowledge of our customer onboarding funnel and where enterprise accounts stall. 2. Understanding of the regulatory constraints in our fintech vertical. 3. Tacit knowledge of which internal stakeholders block or unblock roadmap decisions. 4. Historical context on why past product bets failed. 5. Domain fluency in payment reconciliation edge cases. 6. Relationships with our three largest customers and their unspoken priorities.

### Amplifier Mapping
Onboarding funnel knowledge: without AI I analyze account drop-off manually over several days by hand; with AI I query the patterns across all accounts almost instantly; the amplifier effect here is raw speed. Regulatory constraints: without AI I rely mostly on memory and scattered notes; with AI I cross-check every relevant policy at scale in seconds; the amplifier is scale and coverage. Stakeholder mapping: without AI I track relationships informally in my head; with AI I surface sentiment and signals from written comms; the amplifier is precision. Failure history: without AI that context lives only in my head; with AI I synthesize past post-mortems and decisions quickly and reliably; the amplifier is speed and recall combined.

### Edge Statement
My real edge is that I understand exactly why our enterprise onboarding stalls and which specific stakeholders quietly move or block decisions, knowledge that no model has access to. AI dramatically amplifies how fast and how thoroughly I can act on that judgment, but the underlying judgment itself is entirely mine. That combination of tacit context plus AI leverage is genuinely hard for anyone to replace quickly.

### Irreplaceability Proof of Concept
Last month I overrode a data-driven recommendation to churn a slow-moving account because I personally knew their internal champion was in the middle of a reorg and simply could not respond; they renewed the following quarter at roughly double the value.

---

## Stage 4: AI Signal Registry

### Signal Evaluation Table
1. Vendor claim that AI automates 80 percent of our reporting, source a sales demo, verdict Low Signal, reasoning it completely ignores our payment reconciliation edge cases that genuinely need human judgment and would break silently. 2. LinkedIn post declaring that prompt engineering is dead, source social media, verdict Low Signal, pure hype with no bearing on my actual daily workflow. 3. Internal claim that we should build our own model, source a colleague, verdict Deferred, reasoning maybe later but absolutely not now given the cost and our team size. 4. Claim that RAG completely solves hallucination, source a vendor blog, verdict Deferred, partially true but needs careful testing in our domain first. 5. Claim that AI copilots meaningfully boost developer speed, source a peer team, verdict High Signal, worth learning because our engineers ship code every single day. 6. Claim that AI can draft first-pass compliance summaries, source an internal pilot, verdict High Signal, directly relevant to my regulatory review work. 7. Claim that autonomous agents will replace analysts this year, source a conference talk, verdict Low Signal, a wildly overstated timeline. 8. Claim that fine-tuning beats prompting for our use case, source a whitepaper, verdict Deferred, entirely unproven for us. 9. Claim that AI note-takers improve meeting recall, source a trial, verdict High Signal, cheap and useful right now. 10. Claim that we must adopt every new model immediately, source leadership chatter, verdict Low Signal, that is textbook Adoption Mirage.

### Domain-Specific Failure Mode Map
Most dangerous hallucination scenario: an AI-drafted compliance summary invents a plausible-looking regulation citation that a busy reviewer trusts and ships to an enterprise client, creating real legal and reputational exposure for the company. Hardest-to-detect error: a subtle misreconciliation inside a payments report where the totals look completely plausible but a rounding rule was silently applied wrong, because the numbers pass a quick glance test and nobody re-derives them. Safe zone: internal brainstorming, exploratory analysis, and first-draft marketing copy where a human always reviews the output before anything at all leaves the building, so any errors are caught cheaply and never reach a paying customer or a regulator.

### Noise Ratio Assessment
High Signal count is four, Low or Deferred is six. The ratio reveals that most of the noise reaching me is hype rather than genuinely useful signal, which validates filtering hard before spending learning time. Jargon Tollbooth term: RAG, which simply means letting the model look things up in your documents before answering; it sits below my Level Threshold as implementation detail.

---

## Stage 5: Sight — Minimum Viable Knowledge Threshold and First Action

### Need to understand well enough to use and evaluate
How large language models actually generate text token by token, how to systematically evaluate a model's output quality for my specific fintech domain, and how to reason clearly about token cost, latency, and accuracy tradeoffs when I am choosing between competing tools.

### Need to understand well enough to ask good questions and spot red flags
Retrieval augmented generation at a solid conceptual level, and the basic prompt design patterns that matter, which is enough for me to ask vendors genuinely sharp questions and reliably spot the obvious red flags in a pitch.

### Releasing the obligation to learn
Model training and fine-tuning internals, GPU infrastructure provisioning and hosting, and the underlying mathematics of transformer architectures, all of which sit deliberately and comfortably below my Level Threshold for now.

### Action Gap Analysis
Current state: I approve AI tools reactively and case by case without any clear, repeatable evaluation framework guiding me. My ninety-day target is to run every single significant AI decision through my LENS Readiness Map and produce a short documented verdict each time. The single most important gap between those two states is simply a consistent, repeatable evaluation habit that I actually apply every time rather than improvising ad hoc under pressure.

### First Action Commitment (next 7 days)
In the next seven days I will evaluate one real, specific AI vendor claim using my Signal Registry format and write a concise one-page verdict on it. Completion criterion: the finished verdict is written down and shared directly with my manager for feedback. Skill it builds: disciplined, evidence-based AI evaluation that I can repeat reliably.

### LENS Audit Reflection
What surprised me most about this audit? I had always assumed my ongoing anxiety about AI was a genuine, concrete skill gap, but working through the stages showed me that most of it was a manufactured Competence Identity Threat tied to how I feared being perceived by leadership rather than any real deficiency. Where is my professional edge strongest? It is clearly in enterprise onboarding, regulatory nuance, and stakeholder judgment, areas where my accumulated tacit context reliably beats any general purpose model. What will I actually change first? I will stop approving AI tools reactively and instead deliberately run each new claim through my Signal Registry format, starting with a single concrete vendor claim this very week and sharing the written verdict.

Generated: 2026-07-19T20:16:42.923Z
