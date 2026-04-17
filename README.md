# AgentLift Crew

Working title for an [AI quickstart](https://github.com/rh-ai-quickstart) aligned with [ai-quickstart-contrib#44 — Agentic Software and System Modernization (e.g. RHEL 10)](https://github.com/rh-ai-quickstart/ai-quickstart-contrib/issues/44).

**AgentLift** — agents accelerating modernization work. **Crew** — human-in-the-loop: reviewers, operators, and SMEs stay in control alongside automation.

**North star (context):** Patterns discussed in [Refactoring at the speed of mission: An "agent mesh" approach to legacy system modernization with Red Hat AI](https://www.redhat.com/en/blog/refactoring-speed-mission-agent-mesh-approach-legacy-system-modernization-red-hat-ai) — modular agent harnesses, validation, disconnected-sensitive deployments, brownfield correctness over raw velocity.

Deliverable target: **`ai-quickstart-contrib`** ([contributor guide](https://github.com/rh-ai-quickstart/ai-quickstart-contrib/blob/main/CONTRIBUTING.md), [catalog](https://docs.redhat.com/en/learn/ai-quickstarts)) — a portable, reproducible walkthrough on Red Hat AI / OpenShift AI, not a claim of full portfolio migration automation.

## What this is for (goal)

**Problem:** Brownfield estates (legacy monoliths, old runtimes, weak tests, implicit dependencies) are expensive and risky to move—especially when workloads must stay **disconnected**, **auditable**, and **correct**, not just “fast.”

**Direction (from the blog and architecture narrative):** Treat modernization as an **agent mesh** pattern: many **small, specialized roles** (coding vs planning, tests vs tracking) coordinated by a **harness** with **deterministic steps**—ingest a repo, build **understanding** (reports, graphs, migration catalogs), then run an **analyze → plan → implement → validate** loop where **merge requests and CI** decide what advances, and **humans interrupt** when tests, specs, or policy require it. **OpenShift AI** (model serving, observability, disconnected operation) is the realistic place that pattern runs.

**What AgentLift Crew is meant to prove in a quickstart:** That teams can **see the pattern end-to-end in a lab**: agents and tools produce **structured findings and bounded change proposals**, **automated checks** catch bad suggestions, and **people** keep governance—so modernization gains **speed without trading away** functional correctness or ownership. The goal is **mission-aligned refactoring**: reclaim engineer time from repetitive migration work while the **crew** retains architecture, approvals, and exception handling.

**What this repo is *not* claiming yet:** A full production “modernization engine” that silently upgrades fleets or replaces official RHEL migration guidance; those stay **product, services, and docs**—this work is the **credible first slice** aligned with [Issue #44](https://github.com/rh-ai-quickstart/ai-quickstart-contrib/issues/44).

## GitHub repository

**[`rh-ai-quickstart/agentLift-crew`](https://github.com/rh-ai-quickstart/agentLift-crew)**

```bash
git remote set-url origin https://github.com/rh-ai-quickstart/agentLift-crew.git
```
