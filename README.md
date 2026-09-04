# AI Product Studio

A portfolio of practical AI products focused on agentic workflows, retrieval-augmented generation, LLM applications, and reliable product engineering.

## Featured Projects

| Project | Problem solved | Core AI pattern | Stack |
| --- | --- | --- | --- |
| [ResearchForge](./featured/researchforge/) | Turns a research question into a structured, source-aware brief. | Multi-agent planning, research, verification, and synthesis. | Python, Gemini, Tavily, Pydantic, Streamlit |
| [PRReview AI](./featured/prreview-ai/) | Produces structured reviews for GitHub pull requests. | Per-file review with map-reduce synthesis and validation. | Python, Gemini, PyGitHub, Pydantic, Streamlit |
| [QueryMind](./featured/querymind/) | Lets users query a SQLite database in plain English. | NL-to-SQL with guarded execution and error-driven self-correction. | Python, Gemini, SQLite, Pydantic, Streamlit |
| [SymptomSense](./featured/symptomsense/) | Demonstrates safety-oriented symptom triage. | Deterministic red-flag checks with constrained LLM triage. | Python, Gemini, Pydantic, Streamlit |

## Labs

### Agents
| Project | Problem solved |
| --- | --- |
| [CompeteAI](./labs/agents/competeai/) | Plans competitive-intelligence searches, gathers web evidence, and synthesizes a structured brief. |

### RAG Systems

| Project | Problem solved |
| --- | --- |
| [ClauseGuard](./labs/rag-systems/clauseguard/) | Retrieves contract clauses to support structured risk analysis. |
| [BrainBase](./labs/rag-systems/brainbase/) | Indexes multiple document formats for cited, grounded answers. |
| [SupportSense](./labs/rag-systems/supportsense/) | Combines knowledge-base retrieval with confidence-aware human escalation. |
| [MentorAI](./labs/rag-systems/mentorai/) | Retrieves curriculum material tailored to an individual learning profile. |

### LLM Applications

| Project | Problem solved |
| --- | --- |
| [ResumeLens AI](./labs/llm-applications/resumelens-ai/) | Produces schema-validated resume-to-job fit analysis. |
| [MeetingMind](./labs/llm-applications/meetingmind/) | Transforms local audio transcription into decisions, actions, and follow-ups. |
| [PitchBot](./labs/llm-applications/pitchbot/) | Uses a staged prompt chain to generate personalized outreach. |
| [JobPulse](./labs/llm-applications/jobpulse/) | Combines application-funnel analytics with LLM-generated career insights. |

### Voice & Document AI

| Project | Problem solved |
| --- | --- |
| [FieldReport AI](./labs/voice-and-document-ai/fieldreport-ai/) | Converts spoken field notes into domain-specific structured reports. |

## Standalone Work

These are AI related projects that remain independent repositories.

| Project | Problem solved |
| --- | --- |
| [Mentor Insight Extractor](https://github.com/vedp9/mentor-insight-extractor) | Bayesian triage agent for extracting actionable technical advice. |
| [Career Ops](https://github.com/vedp9/career-ops) | AI-powered job evaluation and resume-tailoring application. |
| [Skin App](https://github.com/vedp9/skin-app) | AI-enabled skincare guidance product. |

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
