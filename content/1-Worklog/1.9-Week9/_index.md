---
title: "Week 9 Worklog"
date: 2026-07-22
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---


### Week 9 Objectives:

* Build CV evaluation prompts using Amazon Bedrock / Nova Lite
* Extract and standardize skills, projects, experience, certificates, suggested roles, and score
* Ensure AI response stability for backend and Dashboard consumption

### Tasks to be carried out this week:
| Day | Task Description | Start Date | Completion Date | Reference Links |
| --- | --- | --- | --- | --- |
| Friday | - Design CV analysis prompt and evaluation criteria for candidate readiness scoring | 2026-06-12 | 2026-06-12 | |
| Saturday | Day off | 2026-06-13 | 2026-06-13 | |
| Sunday | Day off | 2026-06-14 | 2026-06-14 | |
| Monday | - Build prompt template for Bedrock/Nova Lite to extract CV summary, skills, projects, experience, and certificates | 2026-06-15 | 2026-06-15 | |
| Tuesday | - Standardize JSON output schema for score, suggested roles, strengths, weaknesses, and recommendations | 2026-06-16 | 2026-06-16 | |
| Wednesday | - Test prompt across various sample CVs and fix field inconsistencies or non-JSON responses | 2026-06-17 | 2026-06-17 | |
| Thursday | - Fine-tune CV analysis prompt and document fallback structure for AI response failures | 2026-06-18 | 2026-06-18 | |

### Week 9 Achievements:

* JSON Output Schema Standardization:
  * Unified the returning JSON data structure containing all core fields: score, suggested roles, strengths, weaknesses, and recommendations.
* Hands-on Testing & AI Response Stabilization:
  * Tested prompts against diverse CV templates to eliminate field mismatches and invalid JSON responses.
  * Fine-tuned prompts to optimize cost and latency, and successfully built a Fallback Structure to prevent Backend interruption during AI response failures.