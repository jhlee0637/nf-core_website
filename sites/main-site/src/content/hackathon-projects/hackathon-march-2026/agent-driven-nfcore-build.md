---
title: Optimizing Nextflow Development with LLM Agents & Custom Skills
category: Tooling
slack: https://nfcore.slack.com/archives/C0ACF0TPF5E
location: Seoul 
image: ""
image_alt: ""
leaders:
  Minyoung Park:
    name: Minyoung Park
    slack: https://nfcore.slack.com/team/U04UPG02SBY
---

*본 프로젝트는 3월 13일 서울로컬허브에서 오프라인으로만 진행됩니다.

Injecting structural knowledge and troubleshooting methods as explicit "Skills" significantly improves the LLM's code quality and generation efficiency.    

This project implements a "Pipeline Dev Agent" architecture designed to strictly control the LLM, ensuring it builds pipelines without deviating from the provided skill instructions.

## Goal

1. **Skillset Documentation**: Structure essential reference data, such as Nextflow patterns and error-handling guidelines, into LLM-parsable markdown files.
2. **Agent Prompt Design**: Develop system prompts that make the model to prioritize the custom skillset throughout the code writing and revision processes.
3. **Pipeline Validation**: Compare the outputs of a baseline LLM against the agent-based model, verifying the actual executability of the generated pipelines using test datasets.

## Tasks
- Build the Knowledge Base: Draft the skills.md documents for the agent.
- Write Agent Directives: Create prompts that govern the agent's behavior and enforce the application of skills.
- Test and Optimize: Deploy the agent to build a specific target pipeline.

---
