# sample-claude-analysis-prompt.md
# Working example of claude-analysis-prompt.md in use.
# This is an actual analysis session prompt from the Lab-in-a-Box
# product development cycle.

---

## Analysis Session Prompt

You are the analysis agent for my AI team. Your job is to read 
the latest research report, analyze it against my standing brief 
and memory files, and produce actionable findings.

Please start by reading my standing brief:
https://raw.githubusercontent.com/WolfNinja32/multi-ai-team-playbook/main/sample-CONTEXT.md

Then read my memory files for current context:
https://raw.githubusercontent.com/WolfNinja32/multi-ai-team-playbook/main/memory/sample-opportunities.md
https://raw.githubusercontent.com/WolfNinja32/multi-ai-team-playbook/main/memory/sample-decisions.md
https://raw.githubusercontent.com/WolfNinja32/multi-ai-team-playbook/main/memory/sample-products-watched.md

Then read the latest research report:
https://raw.githubusercontent.com/WolfNinja32/multi-ai-team-playbook/main/reports/sample-research-report.md

When you have read everything, please:

1. Summarize the key findings from the research report
2. Identify anything that conflicts with or updates the memory files
3. Flag new opportunities worth adding to opportunities.md
4. Flag any products worth adding to products-watched.md
5. Note any decisions that should be logged in decisions.md
6. Write follow-up research tasks for the next ChatGPT session
7. Produce a draft analysis saved as analysis/2026-03-13-analysis.md

Be specific. Lead with findings, then explain them. Flag uncertainty 
explicitly — if the research doesn't support a conclusion, say so.
Do not re-surface anything already resolved in the memory files 
unless new evidence changes the picture.

---

## What Claude Found

**Key findings from the research report:**
- No competing product teaches multi-model coordination without coding
- Competing technical solutions require 3+ services and real setup time
- Target buyer frustration confirmed across Reddit and YouTube comments
- Gumroad prompt libraries saturated under $10 — wrong category to enter
- Sweet spot identified: $24-$34 for practical AI workflow guides

**Opportunities flagged:**
- Multi-AI team playbook — gap confirmed, pursuing
- Local model integration — deferred, revisit post-launch

**Products flagged for watching:**
- OpenBrain video — evaluated, used for competitive positioning
- AI Productivity Bundle at $34.99 — watching sales velocity

**Decisions logged:**
- GitHub as coordination layer — final
- Tier 1 manual workflow first, automation deferred — final
- Price at $29.99 — revisable after 30 days

**Follow-up tasks written for ChatGPT:**
- Search Gumroad for AI workflow bundles over $25 — need more
  pricing data at the upper end of the range
- Search for buyer reviews of AI productivity products —
  what do buyers say they wished was included?

---

## After the Session

1. Copied full Claude output
2. Created analysis/2026-03-13-analysis.md
3. Updated memory/opportunities.md with two new entries
4. Updated memory/decisions.md with three new decisions
5. Added two follow-up tasks to inbox/tasks.md
6. Queued next ChatGPT research session
