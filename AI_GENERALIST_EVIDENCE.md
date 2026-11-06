# AI Generalist — Evidence Map

**Esoham Abalo | Applied AI, QA, and Operations**

AI Generalist is not a single job description. Some roles focus on **reviewing model responses against rubrics**, others on **building and testing AI workflows**, and others on **helping teams apply AI to business processes**. This page maps my public project evidence to those different responsibilities without claiming production deployments or training experience that has not been demonstrated.

## Short work sample for AI evaluation roles

[**Read the annotated AI evaluation exercise**](AI_EVALUATION_WORK_SAMPLE.md) — three fictional tasks, a weighted scoring rubric, candidate-response labels, and accept/block reasoning. This is an independently written portfolio sample, **not** a paid model-rating benchmark.

## 1. Building and testing AI-assisted workflows

**Project:** [ChangeGuard MFG](https://github.com/Esoham/ChangeGuard_MFG_SUBMIT_READY_FLAT-)

**Scenario:** Before releasing a manufacturing engineering change, evidence from BOMs, inventory, purchase orders, work orders, and quality documents must agree.

**Solution approach:** Combine read-only tool access, configurable model-assisted evidence-source selection, deterministic business rules, an independent verifier, and a human approval gate.

**Inspectable evidence:**
- [Five-minute walkthrough](https://github.com/Esoham/ChangeGuard_MFG_SUBMIT_READY_FLAT-/blob/main/docs/JUDGE_WALKTHROUGH.md)
- [Agent contracts, tool permissions, and stopping rules](https://github.com/Esoham/ChangeGuard_MFG_SUBMIT_READY_FLAT-/blob/main/docs/AGENT_CONTRACTS.md)
- [Evaluation plan](https://github.com/Esoham/ChangeGuard_MFG_SUBMIT_READY_FLAT-/blob/main/docs/EVALUATION_PLAN.md)
- [Reproduction instructions](https://github.com/Esoham/ChangeGuard_MFG_SUBMIT_READY_FLAT-/blob/main/docs/REPRODUCTION.md)

**Scope:** Included evaluations use synthetic data and should not be read as real-world accuracy or deployment metrics.

## 2. Integrating AI into an application

**Project:** [Vanessa Voice AI](https://github.com/Esoham/vanessa-voice-ai)

**Scenario:** A voice-based workflow needs conversational interaction, qualification logic, a dashboard, and escalation to a human.

**Evidence:** The repository includes frontend and backend source, configuration documentation, and screenshots. The prototype uses React, Express, and Vapi/GPT-4 integration. Real outbound use requires separately configured services, authorization, and safeguards.

## 3. Reliability, investigation, and operational QA

- [SentinelWatch](https://github.com/Esoham/SentinelWatch-SOC-Lab): deterministic detection and evidence-based analyst review of synthetic authentication events. [Interactive demo](https://esoham.github.io/projects/sentinelwatch-console.html).
- [MerchantFlow](https://github.com/Esoham/merchantflow): transparent risk rules, a review workflow, a PRD, a QA report, and synthetic order data. [Try the prototype](https://esoham.github.io/projects/merchantflow/).
- [FluxPilot](https://github.com/Esoham/fluxpilot-automation): rule-driven validation, structured exception outputs, and unit tests.
- [VerityFlow](https://github.com/Esoham/verityflow-sql): SQL data-quality checks, reporting definitions, and documented caveats.

## How I approach evaluating an AI workflow

1. **Define the intended behavior:** task, stakeholders, policy, and success criteria.
2. **Create a test set:** valid cases, edge cases, conflicts, and known negative controls.
3. **Assess outcomes:** correctness, source/evidence support, failure severity, and escalation behavior.
4. **Document limitations:** where tests are synthetic, where human review is mandatory, and what has not yet been validated.
5. **Make the result reproducible:** publish test inputs, commands, expected outputs, and the limits of any measured score.

**Important distinction:** I can point to software QA and project evaluation artifacts above. I am **not claiming** a paid AI model-rater role, RLHF experience, inter-rater calibration work, or production AI deployment unless separately documented.

[Back to GitHub profile](https://github.com/Esoham) · [Interactive portfolio](https://esoham.github.io/)
