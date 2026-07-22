---
title: "Week 11 Worklog"
date: 2026-07-22
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---


### Week 11 Objectives:

* Connect voice capabilities to AI Interview using Amazon Polly and Amazon Transcribe
* Prepare fallback options in case AWS voice services encounter errors during demo
* Ensure answer transcripts can be seamlessly fed into the AI scoring logic

### Tasks to be carried out this week:
| Day | Task Description | Start Date | Completion Date | Reference Links |
| --- | --- | --- | --- | --- |
| Friday | - Analyze voice workflow: question text -> Polly audio -> answer recording -> Transcribe text -> AI evaluation | 2026-06-26 | 2026-06-26 | |
| Saturday | Day off | 2026-06-27 | 2026-06-27 | |
| Sunday | Day off | 2026-06-28 | 2026-06-28 | |
| Monday | - Prepare integration plan for Polly to convert interview questions into audio | 2026-06-29 | 2026-06-29 | |
| Tuesday | - Prepare integration plan for Transcribe to convert answer audio into text | 2026-06-30 | 2026-06-30 | |
| Wednesday | - Design fallback mechanism using Web Speech API when AWS voice services are unavailable | 2026-07-01 | 2026-07-01 | |
| Thursday | - Test voice-to-evaluation pipeline and document fallback steps for live demo | 2026-07-02 | 2026-07-02 | |


### Week 11 Achievements:

* End-to-End Voice Workflow Mapping & Architecture:
  * Successfully mapped the complete voice interaction pipeline: Question Text -> Polly Audio -> Candidate Response Recording -> Transcribe Text -> AI Evaluation.
* AWS Voice Services Integration Planning:
  * Formulated the technical strategy for Amazon Polly integration to convert text questions into candidate-facing audio.
  * Designed the Amazon Transcribe integration strategy to convert recorded answer audio into clean text for AI analysis.
* Exception Handling & Demo Preparedness:
  * Developed a resilient Fallback Strategy that automatically switches to the browser's native Web Speech API during AWS voice service latency or outages.
  * Successfully tested the complete voice-to-evaluation workflow and compiled clear operational guides for seamless demo execution.