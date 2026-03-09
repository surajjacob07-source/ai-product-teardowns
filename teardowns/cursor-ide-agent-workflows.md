# Cursor IDE Agent Workflows Teardown

## 1. Summary
- Product: Cursor
- Feature: IDE-native AI agent workflows
- Target user: Developers, technical PMs, indie builders, and startup teams shipping code fast
- Core JTBD: Help me move from idea to implementation faster without constantly switching tools or manually wiring boilerplate
- One-line PM take: Cursor turns AI from a chat companion into an in-flow coding operator, but trust, reviewability, and cost awareness still decide whether it becomes habit or hype

## 2. Problem Being Solved
Building software involves repetitive translation work: reading code, locating files, planning edits, writing boilerplate, and validating changes. Traditional chat interfaces help with answers, but they break flow. Cursor collapses asking, editing, and applying changes into the same working surface.

## 3. Primary User
The core user is a developer or builder who values speed but still wants enough control to review what changed. A secondary user is a product-minded operator prototyping ideas without a full engineering team.

## 4. Current Experience
The strongest part of the experience is context continuity inside the IDE. The user can reference files, request edits, and iterate without copy-pasting code into a separate assistant. This reduces friction and makes the AI feel operational instead of advisory.

## 5. What Works
- Keeps users in the coding environment
- Makes multi-file edits faster than plain chat tools
- Lowers prototype-to-code friction for early product exploration
- Helps non-expert coders ship proof-of-concept features faster

## 6. Friction / Gaps
- Users may not know when to trust apply-ready changes vs when to slow down and review
- Large edits can feel opaque if rationale is not surfaced well
- Agent-like behavior is helpful, but can still produce shallow fixes that look correct at first glance

## 7. AI Product Risks
- False confidence from plausible-looking code
- Hidden context causing surprising edits
- Token/cost creep for large codebases
- Security risk if users over-delegate sensitive changes

## 8. Metrics That Matter
- Activation: % of weekly active users making at least one applied AI edit
- Depth: average accepted AI edits per active user
- Trust: revert rate after AI-generated edits
- Retention: 4-week retention for users who adopt agent workflows
- Outcome: time saved on common coding tasks

## 9. Improvement Opportunities
| Priority | Opportunity | Why it matters |
|---|---|---|
| P0 | Add clearer change rationale before apply | Users trust edits more when intent is visible |
| P1 | Add lightweight eval checks for common tasks | Better reliability on repeat workflows |
| P1 | Add task-mode memory for ongoing implementation threads | Helps users move from one-shot edits to end-to-end build flow |

## 10. PM Recommendation
Cursor’s moat is not just code generation. It is workflow compression. The best roadmap bets should deepen trust, reviewability, and task continuity so AI-assisted building feels like a repeatable system rather than a clever shortcut.
