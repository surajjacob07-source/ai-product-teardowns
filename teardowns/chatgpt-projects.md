# ChatGPT Projects Teardown

## 1. Summary
- Product: ChatGPT
- Feature: Projects
- Target user: Knowledge workers, students, operators, and builders managing ongoing AI work
- Core JTBD: Help me organize repeated AI interactions around a persistent goal or body of work
- One-line PM take: Strong move from one-off prompting to workflow continuity, but the collaboration and visibility layer still feels early

## 2. Problem Being Solved
Users often run repeated conversations around the same theme: job search, coding, research, planning, content, or study. Without structure, context gets fragmented and retrieval becomes annoying. Projects aim to reduce context switching and preserve continuity.

## 3. Primary User
The most obvious user is a repeat ChatGPT user with multi-step work. These users value persistence, file context, and a sense of workspace memory.

## 4. Current Experience
The experience improves organization by grouping related chats and assets. This lowers retrieval effort and makes the tool feel more like a workspace than a chatbot.

## 5. What Works
- Gives conversations a durable home
- Supports multi-session work better than standalone chats
- Nudges behavior toward repeated usage and stickiness

## 6. Friction / Gaps
- Limited visibility into what context is actively influencing outputs
- Collaboration is not central to the experience
- Users may still struggle to turn project context into repeatable workflows

## 7. AI Product Risks
- Users may overtrust project memory
- Hidden context can make outputs feel unpredictable
- Large context may increase latency and cost

## 8. Metrics That Matter
- Activation: % of active users creating a project
- Engagement: chats per project per week
- Retention: 4-week retention of project creators vs non-creators
- Quality: % of users reporting improved organization / usefulness
- Business: conversion lift among project users

## 9. Improvement Opportunities
| Priority | Opportunity | Why it matters |
|---|---|---|
| P0 | Add clearer context visibility | Trust improves when users understand why the model answered the way it did |
| P1 | Add lightweight workflow templates | Helps users go from storage to repeatable value |
| P1 | Add collaboration / sharing controls | Expands the use case from solo productivity to team workflows |

## 10. PM Recommendation
Position Projects as the bridge between conversational AI and real work management. Prioritize trust, visibility, and reusable workflows over pure storage.
