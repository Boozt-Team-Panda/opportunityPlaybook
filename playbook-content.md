## 1. Why This Playbook Exists

**Goal:** Align on the purpose and value of this playbook.

We're moving from a **feature-led, stakeholder-driven model** to an **outcome-driven, opportunity-led model**. This playbook aligns our teams around solving **real user problems** with strategic impact — not shipping someone's favorite idea.

The "Parking Lot → Delivery" model is broken because it often leads to a backlog of unvalidated ideas, built without a clear understanding of customer needs or business outcomes. This results in wasted effort, slower time-to-value, and a lack of strategic alignment. This playbook is a crucial step in Boozt's ambition to mature product practices by empowering teams to focus on customer-centric outcomes.

## 2. Guiding Principles

**Goal:** Set the cultural and philosophical foundation.

These principles will guide how we operate, collaborate, and make decisions within the product organization at Boozt:

- **Start with problems, not solutions:** Our primary focus is understanding and defining the user or business problem before jumping to any specific solution.
- **Discovery is continuous, not a phase:** Product discovery is an ongoing activity, not a one-off project phase. We continuously learn, test, and iterate.
- **Empower teams to own the how:** Teams are best positioned to determine the most effective ways to solve validated problems.
- **Measure success by outcomes, not outputs:** We define and track success based on measurable impacts (outcomes) rather than just features shipped (outputs).
- **Strategy → Opportunity → Discovery → Delivery:** This sequential yet iterative flow ensures our work is always rooted in strategic intent.

## 3. Core Process Overview

**Goal:** Agree on high-level flow and language.

Our product development process at Boozt, which we can call "The Boozt Opportunity Flow," follows this high-level structure:

```
[ Strategic Inputs ]
      ↓
[ Opportunity Backlog ]
      ↓
[ Continuous Discovery ] ←→ [ Continuous Delivery ]
      ↑
[ Feedback & Learning ]
```

This model emphasizes a continuous flow of validated opportunities moving from strategic alignment through discovery and delivery, with constant feedback loops. This granularity allows for clear understanding without getting bogged down in minutiae.

## 4. Opportunity Backlog

**Goal:** Define what it is, how it works, and who owns it.

The **Opportunity Backlog** is a prioritized, transparent list of well-defined user or business problems that, if solved, would contribute significantly to our strategic goals. It is fundamentally different from a traditional "Parking Lot" which often collects unrefined ideas or feature requests.

**What qualifies as an Opportunity?** An Opportunity is a clearly articulated problem statement, validated by evidence, with a clear link to our strategic objectives. It focuses on *what* problem to solve, not *how* to solve it.

**How is it different from the Parking Lot?** The Parking Lot is often a dumping ground for ideas. The Opportunity Backlog is curated, evidence-backed, strategically aligned, and actively managed. Entries are refined, researched, and regularly reviewed.

**How do we keep it prioritized and visible?** The Head of Product Management, in collaboration with Product Managers and Product Leadership, owns the prioritization and visibility of the Opportunity Backlog. It should be maintained in a shared tool (e.g., Jira, Confluence, Productboard) and regularly reviewed during Opportunity Review sessions.

### Template Fields:

- **Opportunity Name:** A concise, descriptive title for the problem.
- **Problem Statement:** A clear, user-centric description of the problem to be solved, including who is affected and the impact. (e.g., "As a [user type], I want to [goal], but I can't because [pain point], which results in [negative outcome].")
- **Strategic Link:** Which Boozt strategic pillar or OKR does this opportunity directly support?
- **Source / Evidence:** What data, research, or feedback supports the existence and importance of this problem? (e.g., "User interviews," "Analytics data," "Customer support tickets," "Competitor analysis").
- **Status:** (e.g., "Identified," "Validated," "In Discovery," "Completed," "Archived").
- **Next Step:** A clear indication of what needs to happen next for this opportunity.

## 5. Pulling Work into Discovery

**Goal:** Empower teams to pull problems, not receive tasks.

Teams are empowered to **pull opportunities** from the Opportunity Backlog into their continuous discovery process. This ensures ownership, motivation, and a deep understanding of the problem space. Teams should choose opportunities that align with their specific domain and expertise, and that they believe they can realistically impact.

**How do teams choose opportunities?** Product Managers, in collaboration with their design and engineering counterparts, review the prioritized Opportunity Backlog. They select the next opportunity that best fits their team's capacity, expertise, and strategic alignment, ensuring they have sufficient evidence to begin discovery.

**What's the lightweight Discovery template?** The Discovery template provides a structured approach to exploring an opportunity without being overly prescriptive. It focuses on documenting learning and validating assumptions.

### Boozt Discovery Log Template

- **Opportunity:** [Link to Opportunity in Backlog]
- **Team:** [Squad Name]
- **Discovery Question(s):** What are we trying to learn or validate?
- **Hypothesis:** What do we believe to be true about the problem/solution?
- **Discovery Method(s):** How will we test our hypothesis? (e.g., User Interviews, Surveys, A/B Testing, Prototyping, Data Analysis)
- **Key Learnings/Insights:** What did we discover?
- **Evidence:** What data or feedback supports our learnings?
- **Decision:** What's the next step? (e.g., "Proceed to delivery," "Iterate on solution," "Invalidate opportunity," "Pivot")
- **Date:**
- **Owner:**

**How do we avoid stage gates?** Discovery is continuous. Instead of formal stage gates, we encourage frequent, lightweight sharing of insights within the team and with relevant stakeholders. The "Decision" field in the Discovery Log acts as a checkpoint, driving towards clarity on the next steps rather than a formal hand-off.

### Example Discovery Log:

- **Opportunity:** Improve conversion rate for first-time mobile app users.
- **Team:** Account Squad
- **Discovery Question:** What are the main friction points for new users completing their first purchase on mobile app?
- **Hypothesis:** New users abandon the app due to a confusing checkout flow and lack of trust signals.
- **Discovery Method(s):** Usability testing with 5 first-time users, Hotjar recordings analysis, A/B test of simplified checkout form.
- **Key Learnings/Insights:** Users struggle with creating an account before checkout. Trust signals (e.g., payment badges) are not prominent enough.
- **Evidence:** User interview transcripts, heatmaps showing drop-offs, A/B test results showing 3% higher conversion with guest checkout.
- **Decision:** Proceed to delivery for an improved guest checkout flow and more prominent trust badges.
- **Date:** 2025-08-22
- **Owner:** Jane Doe (PM)

## 6. From Discovery to Delivery

**Goal:** Define when a solution is ready for build.

Transitioning from Discovery to Delivery signifies that a solution has been sufficiently validated and is ready for implementation. This is not a strict gate but a checkpoint to ensure alignment and reduce risk.

### Delivery Readiness Checklist:

- **Clear validated problem statement:** The core problem being solved is well-understood and supported by discovery evidence.
- **Evidence supports solution:** There's enough confidence from discovery activities (e.g., prototypes, user tests, data analysis) that the proposed solution addresses the problem effectively.
- **Technical feasibility understood:** The engineering team has assessed the technical implications, effort, and potential risks of the solution.
- **Stakeholders aligned:** Key stakeholders (e.g., business, legal, marketing) are aware of the proposed solution and its expected impact, and their feedback has been incorporated where appropriate.
- **Success metrics defined:** Clear, measurable outcomes and key performance indicators (KPIs) have been established to track the impact of the delivered solution.

## 7. Feedback & Learning

**Goal:** Close the loop.

Closing the loop on product development is crucial for continuous improvement and informed strategic adjustments. Learning is a shared responsibility.

### How do we capture and share learnings?

- **Demo Rituals:** Regular product demos (e.g., bi-weekly or monthly) to relevant stakeholders and other teams to showcase delivered features and share key learnings from both discovery and delivery.
- **Opportunity Log:** Updates to the original Opportunity Backlog entry with actual outcomes, lessons learned, and the ultimate impact (or lack thereof).
- **Centralized Knowledge Base:** Utilizing tools like Confluence for documenting discovery insights, research findings, and post-launch analyses.
- **Product Share-Outs:** Regular sessions (e.g., monthly) where PMs share their team's key learnings, successes, and challenges with the wider product organization.

**What happens to invalidated ideas?** Invalidated ideas are not failures, but valuable learning opportunities. They are moved to an "Archived" or "Invalidated" status within the Opportunity Backlog, with a clear note explaining *why* they were invalidated and what was learned. This prevents revisiting the same problems without new evidence and informs future strategic thinking.

## 8. Roles & Collaboration

**Goal:** Clarify who does what.

Effective collaboration across roles is vital for the Opportunity Flow.

| Stage | Product Manager | Designer | Engineer | Analyst |
|-------|----------------|----------|----------|---------|
| Strategic Inputs | Defines strategy, OKRs, links to business goals. | Understands user needs & strategic vision. | Understands technical constraints & opportunities. | Provides data to inform strategy & OKRs. |
| Opportunity Backlog | Owns prioritization, problem definition, evidence. | Provides user insights to enrich opportunities. | Assesses technical feasibility & complexity (high-level). | Quantifies problem impact, gathers relevant data. |
| Continuous Discovery | Leads discovery, defines hypotheses, synthesizes insights. | Designs tests, prototypes, conducts user research. | Advises on technical feasibility, rapid prototyping. | Sets up tracking, analyzes experiment data, validates hypotheses. |
| Continuous Delivery | Defines success metrics, manages backlog, stakeholder comms. | Ensures UX quality, conducts design reviews. | Builds, tests, deploys solutions, ensures quality. | Monitors post-launch performance, reports on outcomes. |
| Feedback & Learning | Communicates outcomes, updates backlog, shares learnings. | Gathers user feedback, identifies new opportunities. | Provides technical insights, identifies tech debt. | Analyzes impact, identifies trends, informs next steps. |

## 9. Product Leadership & Governance

**Goal:** Define how leaders support without controlling.

Product leadership's role is to enable, coach, and provide strategic guidance, rather than micro-managing or dictating solutions.

### How do leaders review and refine the backlog?

Product leaders facilitate a **Monthly/Quarterly Opportunity Review**. This session focuses on:

- **Strategic Alignment:** Ensuring opportunities still align with overarching company strategy and OKRs.
- **Prioritization:** Reviewing the health and prioritization of the overall Opportunity Backlog, identifying any significant gaps or shifts.
- **Guidance:** Providing feedback and guidance on problem definitions, evidence, and potential strategic implications.
- **Resource Allocation:** Ensuring teams have the necessary resources for discovery and delivery.

### Leadership as coaches, not gatekeepers:

Product leadership acts as **coaches**, offering expertise, challenging assumptions, and guiding teams towards better outcomes. They foster a culture of learning and experimentation, intervening only when strategic misalignment or significant risks are identified, always encouraging team autonomy in *how* they solve problems.

## 10. Templates & Toolkits

**Goal:** Collect all tools in one place.

- **Opportunity Template:** (As defined in Section 4)
- **Discovery Template:** (Boozt Discovery Log, as defined in Section 5)
- **Delivery Checklist:** (As defined in Section 6)
- **Decision Tracker:** A simple log to record key product decisions, their rationale, and the date.
- **Jira/Confluence Links:**
  - [Link to Boozt Jira Board for Opportunity Backlog]
  - [Link to Boozt Confluence Space for Discovery Logs and Research]
  - [Link to Boozt Product Strategy Document]

## 11. FAQ & Edge Cases

**Goal:** Prepare for common "what ifs."

- **What if a team doesn't want to pull anything?**
  - **Response:** This suggests a potential issue with understanding the process, team motivation, or clarity of the Opportunity Backlog. Leadership should engage the team to understand the root cause, provide coaching, or refine opportunities. It might also indicate a need for more strategic guidance or team-specific opportunities.

- **What if all ideas are invalidated?**
  - **Response:** While rare, this signifies strong learning! It means the hypotheses were incorrect, or the problems weren't as impactful as initially thought. This feedback is invaluable. Leaders should commend the team for their rigorous discovery and use these learnings to inform new strategic inputs or pivot to different opportunities. It avoids building the wrong thing.

- **What if a stakeholder pushes a pet feature?**
  - **Response:** This is where the playbook's principles are crucial. Politically redirect the stakeholder to the Opportunity Backlog and the problem-first approach. Ask them: "What problem is this feature solving, and what evidence supports its importance?" Offer to help them articulate the problem as an opportunity, which can then be prioritized and enter the discovery flow. Emphasize that we ship outcomes, not just features.

## 12. Getting Started

**Goal:** Plan rollout & pilot.

Implementing "The Boozt Opportunity Flow" will be a phased approach to ensure smooth adoption and continuous improvement.

### Which squad(s) will pilot?

We will identify 1-2 volunteer squads initially to pilot this playbook. These squads should be keen on adopting new ways of working and provide constructive feedback.

### How do we onboard teams?

Onboarding will involve a combination of structured sessions and ongoing support:

1. **Walkthrough Session:** A comprehensive session for pilot squads and relevant stakeholders to introduce the playbook, its principles, and core processes.
2. **First Opportunity Review:** Facilitate the pilot squad's first "pull" from the Opportunity Backlog and guide them through defining their initial discovery questions.
3. **Retro after 4 weeks:** A dedicated retrospective session with pilot squads to gather feedback on what's working, what's challenging, and how to improve the playbook.
4. **Gather adoption feedback:** Continuously collect feedback from pilot teams and leadership to iterate on the playbook before a wider rollout.
