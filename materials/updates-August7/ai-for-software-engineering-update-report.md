# AI for Software Engineering Skills — Update Report

**Date:** 7 August 2026
**Status:** Complete and verified

## What was added

The repository now has a dedicated **AI for Software Engineering Skills** track with eight course-aligned topics. The README contains a separate navigation section for the new learning path.

| Topic | Main course / briefing inputs | Image |
| --- | --- | --- |
| AI Coding Foundations & Trust | Course lesson 1 | `img/ai-coding-foundations.png` |
| Context, Model & Prompt | Course lesson 2 | `img/context-model-prompt.png` |
| Specification-Driven Development | Course lesson 3 | `img/specification-driven-development.png` |
| Secure Model Selection, Privacy & AI Skills | Course lesson 4 | `img/secure-model-selection-and-skills.png` |
| Multi-Agent Coding Workflows | Course lesson 5 | `img/multi-agent-coding-workflows.png` |
| Model Context Protocol (MCP) | Course lesson 6 + systems architecture briefing | `img/model-context-protocol.png` |
| AI PR Review Automation & Hooks | Course lesson 7 | `img/ai-pr-review-automation.png` |
| Agentic Systems Architecture & Frameworks | Systems architecture briefing + BMAD/Superpowers briefing | `img/agentic-systems-architecture.png` |

Each new topic page contains:

- an original, matching 1536×1024 pixel-art image;
- a plain-language TL;DR;
- a five-step quickstart;
- a deeper explanation and a Mermaid flow or comparison table where helpful;
- core skills, applicability guidance, pitfalls, next steps, and curated resources or framework summaries.

## Source material incorporated

- The eight August 2026 course decks were read and distilled into practical, repository-ready guidance on tool adoption, context engineering, SDD, model selection, privacy, skills, multi-agent workflows, MCP, and PR automation.
- The AI systems architecture briefing contributed the deterministic-shell approach, explicit run state, bounded autonomy, evidence and evaluation gates, policy-aware MCP gateway, delegated authority, progressive autonomy, and control/runtime/trust/data plane separation.
- The BMAD Method and Superpowers briefing contributed right-sized workflow selection, specialized-agent handoffs, file-based artifacts, skills as focused reusable workflows, and the explicit warning to choose one owner for the implementation phase.

## Content decisions and corrections

- Benchmarks are presented as comparative signals, not a substitute for private evaluations on representative engineering work.
- MCP is described as a tool-interoperability protocol, not as an authorization, tenancy, or safety solution by itself.
- AI PR review is positioned as first-pass assistance with human merge accountability.
- Unattributed slide statistics about review time savings and security-issue detection were deliberately not repeated as repository claims.

## Verification completed

| Check | Result |
| --- | --- |
| New topic pages present | PASS — 8 pages |
| Required page structure | PASS — every page has TL;DR, Quickstart, deeper explanation, Deep Dive, pitfalls, a resources or framework section, and next steps |
| README navigation | PASS — all 8 new pages are linked |
| Referenced topic images | PASS — 8 of 8 local image paths resolve |
| LinkedIn post asset references | PASS — 8 of 8 image paths resolve |
| Image format and dimensions | PASS — every generated image is PNG, 1536×1024 RGB |
| Visual inspection | PASS — images are consistent neon pixel-art, have no unreliable generated text, and represent their corresponding topic |
| Outbound resource links | PASS — 26 of 26 returned HTTP 200 after redirects on 7 August 2026 |

## Broader repository check

A local-link scan covered 75 Markdown files. The new AI for Software Engineering track has **0 broken local links**. The scan found **30 pre-existing broken links** in `materials/SA/SA-structure.md`; each uses the misspelled directory `solution-archtecture` rather than the repository's `solution-architecture` directory. These unrelated course-material links were not changed in this update and should be corrected in a focused maintenance pass.

## Deliverables in this update folder

- `ai-for-software-engineering-update-report.md` — this report.
- `linkedin-ai-for-software-engineering.html` — eight concise, ready-to-copy LinkedIn posts with their matching images. The repository URL is already included in each post.

## Maintenance notes

- `materials/` was globally ignored. `.gitignore` now keeps the existing material contents ignored while explicitly tracking this update folder, so these two deliverables are included in future commits.
- External documentation changes over time. Re-run the outbound-link check before a major publication or course refresh.
