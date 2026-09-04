# AI Product Studio

A portfolio of practical AI products focused on agentic workflows, retrieval-augmented generation, LLM applications, and reliable product engineering.

## Featured Projects

| Project | Problem solved | Core AI pattern | Stack | Status |
| --- | --- | --- | --- | --- |
| [ResearchForge](./featured/researchforge/) | Turns a research question into a structured, source-aware brief. | Multi-agent planning, research, verification, and synthesis. | Python, Gemini, Tavily, Pydantic, Streamlit | Featured |
| [PRReview AI](./featured/prreview-ai/) | Produces structured reviews for GitHub pull requests. | Per-file review with map-reduce synthesis and validation. | Python, Gemini, PyGitHub, Pydantic, Streamlit | Featured |
| [QueryMind](./featured/querymind/) | Lets users query a SQLite database in plain English. | NL-to-SQL with guarded execution and error-driven self-correction. | Python, Gemini, SQLite, Pydantic, Streamlit | Featured |
| [SymptomSense](./featured/symptomsense/) | Demonstrates safety-oriented symptom triage. | Deterministic red-flag checks with constrained LLM triage. | Python, Gemini, Pydantic, Streamlit | Featured |

## Labs

### Agents

- [CompeteAI](./labs/agents/competeai/) plans competitive-intelligence searches, gathers web evidence, and synthesizes a structured brief.

### RAG Systems

- [ClauseGuard](./labs/rag-systems/clauseguard/) retrieves contract clauses to support structured risk analysis.
- [BrainBase](./labs/rag-systems/brainbase/) indexes multiple document formats for cited, grounded answers.
- [SupportSense](./labs/rag-systems/supportsense/) combines knowledge-base retrieval with confidence-aware human escalation.
- [MentorAI](./labs/rag-systems/mentorai/) retrieves curriculum material tailored to an individual learning profile.

### LLM Applications

- [ResumeLens AI](./labs/llm-applications/resumelens-ai/) produces schema-validated resume-to-job fit analysis.
- [MeetingMind](./labs/llm-applications/meetingmind/) transforms local audio transcription into decisions, actions, and follow-ups.
- [PitchBot](./labs/llm-applications/pitchbot/) uses a staged prompt chain to generate personalized outreach.
- [JobPulse](./labs/llm-applications/jobpulse/) combines application-funnel analytics with LLM-generated career insights.

### Voice & Document AI

- [FieldReport AI](./labs/voice-and-document-ai/fieldreport-ai/) converts spoken field notes into domain-specific structured reports.

## Selected Standalone Work

These are related projects that remain independent repositories; their code is not duplicated here.

- [Mentor Insight Extractor](https://github.com/vedp9/mentor-insight-extractor) — Bayesian triage agent for extracting actionable technical advice.
- [Career Ops](https://github.com/vedp9/career-ops) — AI-powered job evaluation and resume-tailoring application.
- [Skin App](https://github.com/vedp9/skin-app) — AI-enabled skincare guidance product.

## Shared Assets

[Shared Assets](./shared/) is reserved for reusable prompts, utilities, evaluation assets, and starter templates.

## Local Setup

Clone this repository, then follow the README in the project you want to run. Projects have their own dependencies and configuration requirements; do not assume a single environment or dependency file works for every project.

```bash
git clone https://github.com/vedp9/AI-Product-Studio.git
cd AI-Product-Studio
```

## Repository Structure

```text
AI-Product-Studio/
├── README.md
├── featured/
│   ├── researchforge/
│   ├── prreview-ai/
│   ├── querymind/
│   └── symptomsense/
├── labs/
│   ├── agents/
│   │   └── competeai/
│   ├── rag-systems/
│   │   ├── clauseguard/
│   │   ├── brainbase/
│   │   ├── supportsense/
│   │   └── mentorai/
│   ├── llm-applications/
│   │   ├── resumelens-ai/
│   │   ├── meetingmind/
│   │   ├── pitchbot/
│   │   └── jobpulse/
│   └── voice-and-document-ai/
│       └── fieldreport-ai/
└── shared/
    └── README.md
```
