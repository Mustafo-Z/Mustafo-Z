# Mustafo Ziyamukhamedov

AI engineer building speech recognition, LLM tooling and full-stack ML systems. Final-year Computer Science & AI student at the University of Birmingham Dubai.

[Portfolio](https://mziyo.com) | [LinkedIn](https://www.linkedin.com/in/mziyo) | i@mziyo.com

I work on the layer where ML meets operations: fine-tuning pipelines, data collection and annotation, human-in-the-loop dashboards, and the APIs that put model output in front of real users. From January 2025 to September 2026 I did this at [Mediapark.uz](https://mediapark.uz), where the work ran in production. That also means most of it lives in private repos, so the write-ups are below and I'm happy to walk through any of it.

**Public work to look at first:** [Warmline](https://github.com/Mustafo-Z/warmline), a safety layer for an AI voice agent. It runs pre-call policy checks and post-call transcript audits, was built spec-first, and has 275 tests in CI.

**Open to AI engineering roles** (Dubai or remote), and to collaborations on Uzbek or other low-resource speech recognition. You can request a demo of my Uzbek transcription work at [mziyo.com](https://mziyo.com).

## How I work

- A model is only done when people can use it: every pipeline I build ships with a dashboard, an API, or a feedback loop attached.
- Corrections are training data: human-in-the-loop edits should flow back into the next fine-tune, not die in a spreadsheet.
- Spec first, tests first: I build with AI coding agents (Claude Code, Cursor), write the requirements down before any code, and review what comes back.
- Low-resource languages deserve production-grade speech tooling, and Uzbek is where I started.

## What I've built

| Area | What | Evidence |
|---|---|---|
| Speech recognition | Whisper fine-tuning for Uzbek call-centre transcription: data collection, cleaning, annotation | Ran in production at Mediapark (private code) |
| Structured generation | SmartQuery, an NL-to-SQL tool that lets non-technical staff query the operational database in plain language; automated a weekly stock report that was compiled by hand | Python, FastAPI |
| Human-in-the-loop ML | Full-stack monitoring dashboard where operator transcript corrections feed back into retraining | FastAPI + React |
| LLM pipelines at scale | Automated price monitoring across 100,000+ products with custom scraping and LLM classification, replacing manual price comparison | Python, LLM APIs |
| AI agent safety | Warmline: a policy engine and transcript checks around an ElevenLabs + Claude voice agent | [Repo](https://github.com/Mustafo-Z/warmline), 275 tests in CI |
| Model test tooling | A random-weight MiniCPM-o-2.6 (about 6 MB, INT4 OpenVINO) to replace the 160 MB test model in Optimum Intel's OpenVINO test suite; a take-home task in Intel's interview process | Generator and validation scripts; [on Hugging Face](https://huggingface.co/M-Ziyo/tiny-random-MiniCPM-o-2_6-6mb) |
| Mobile + backend | SpeakVolumes iOS app (solo, shipped to the App Store); a social platform with a Java backend, Swift iOS client and a custom mood classifier | App Store release; Alembic migrations introduced to production |

## Stack

- **Languages:** Python, TypeScript, C, Java, Swift, SQL
- **ML:** PyTorch, Hugging Face Transformers, Whisper fine-tuning, LLM APIs (OpenAI, Anthropic), ElevenLabs
- **Applications:** FastAPI, React, Next.js, NL-to-SQL, human-in-the-loop dashboards, iOS (Swift)
- **Infrastructure:** Linux server admin, Docker, Git, GitHub Actions, PostgreSQL, Alembic, Modal, Google Cloud, Vercel
- **Research:** CNN/ANN stem-cell classification, co-presented at the NYU Abu Dhabi CGSB Symposium; IET Honourable Mention for Best Concept Robotics Project (2024)
- **Spoken languages:** English (fluent), Uzbek (native), Russian (conversational)

## Contact

[mziyo.com](https://mziyo.com) | i@mziyo.com | [LinkedIn](https://www.linkedin.com/in/mziyo)
