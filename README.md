# Mustafo Ziyamukhamedov

AI engineer building production speech recognition, NL-to-SQL tooling, and full-stack ML systems.

[Portfolio](https://mziyo.com) | [LinkedIn](https://linkedin.com/in/mziyo)

I work on the layer where ML meets operations: fine-tuning pipelines, data collection and annotation, human-in-the-loop dashboards, and the APIs that put model output in front of real users. Most of my work runs in production at [Mediapark.uz](https://mediapark.uz), where it handles 100k+ products and daily call-centre traffic, which also means most of it lives in private repos. Numbers and write-ups below; happy to walk through any of it in detail.

**Open to collaborations on Uzbek ASR** — if you're working on Uzbek or other low-resource speech recognition, I'd like to hear from you. You can also request a demo of my Uzbek transcription work at [mziyo.com](https://mziyo.com).

## How I work

- A model is only done when operators can use it: every pipeline I build ships with a dashboard, an API, or a feedback loop attached.
- Corrections are training data: human-in-the-loop edits should flow back into the next fine-tune, not die in a spreadsheet.
- Low-resource languages deserve production-grade ASR: Uzbek speech tooling is underserved and that gap is where I work.
- Measure before and after: accuracy from 80% to 95%, manual data pulls cut 70%, 50 marketing hours saved per week. If I can't put a number on it, it isn't shipped.

## System Map

| Surface | What I build | Evidence |
|---|---|---|
| Speech recognition | Whisper fine-tuning for Uzbek call-centre transcription: data collection, cleaning, annotation, evaluation | Production at Mediapark, 80% → 95% accuracy on retail vocabulary |
| Structured generation | SmartQuery, an NL-to-SQL tool over a 100k+ record operational database | Python/FastAPI, cut manual data retrieval 70%, automated a multi-hour weekly stock report |
| Human-in-the-loop ML | Full-stack monitoring dashboard where operator transcript corrections feed back into retraining | FastAPI + React, in daily use |
| LLM pipelines at scale | Automated price monitoring across 100,000+ products with custom scraping and LLM classification | Saves Marketing ~50 hrs/week |
| Model compression | Compact variant of MiniCPM-o-2.6 for Intel inference workflows | ~160 MB → ~6 MB, validated against Optimum-Intel test suite |
| Mobile + backend | SpeakVolumes iOS app (solo, shipped to App Store); social platform with Java backend, Swift iOS client, custom mood classifier | App Store release; Alembic migrations introduced to production |

## Technical Vector

- **Core languages:** Python, C, Java, Swift, SQL
- **ML systems:** PyTorch, Hugging Face Transformers, Whisper fine-tuning, LLM classification pipelines
- **Applications:** FastAPI, React, NL-to-SQL, human-in-the-loop dashboards, iOS (Swift)
- **Infrastructure:** Linux server admin, Docker, Git, PostgreSQL, Alembic, Modal, Google Cloud, DigitalOcean
- **Research:** CNN/ANN medical imaging (stem cell classification, presented internationally)
- **Spoken languages:** English (fluent), Uzbek (native), Russian (conversational)

## Contact

[mziyo.com](https://mziyo.com) | i@mziyo.com | [LinkedIn](https://linkedin.com/in/mziyo)
