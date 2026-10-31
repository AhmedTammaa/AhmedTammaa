# Ahmed Tammaa — AI Engineer (LLM systems, agents, evals, voice AI)

**Founding AI Engineer at [SUN](https://sunapp.ai) (a16z-backed)** · M.Sc. Computer Science at TU Graz · ICPC World Finalist · LangChain contributor

San Francisco, CA · [LinkedIn](https://www.linkedin.com/in/ahmedtammaa101/) · [Email](mailto:ahmed.tammaa.ai@icloud.com) · [Google Scholar](https://scholar.google.com/citations?user=1fgHgYQAAAAJ) · [ORCID](https://orcid.org/0009-0005-9655-3770) · [ResearchGate](https://www.researchgate.net/profile/Ahmed-Tammaa) · [Medium](https://medium.com/@ahmedtammaa101_24052)

I build production LLM systems end to end: multi-agent orchestration, real-time voice AI, LLM evaluation infrastructure, and fine-tuning. At SUN I built the generation engine that turns a single prompt into a finished, podcast-style audio course

## Experience

**Founding AI Engineer — SUN** *(a16z portfolio, current)*
- Built the multi-agent engine that turns one topic prompt into a complete audio course: course planning, script generation, and prosody-aware text-to-speech (TTS).
- Built a two-track evaluation system: text-level factuality grading plus audio-level pairwise judging with a large audio-language model (LALM-as-a-judge), aggregated with Bradley–Terry / Elo. Ranked #1 against NotebookLM in a 600-comparison blind evaluation.
- Built a factual-accuracy benchmark (100 topics × 10 domains) and a LoRA SFT pipeline on Qwen2.5-7B-Instruct with a prosody-tag vocabulary and WhisperX forced alignment.
- Benchmarked commercial and open-weight TTS models, including ElevenLabs v3, Fish Audio S2 and Gemini Flash TTS.

**Previously**
- Generative AI Engineer — Graph8
- AI Engineer — Wassel AI
- ML & NLP Engineer — Corporatica
- Teaching & Research Assistant — British University in Egypt

## Research

**PAN 2026 at CLEF, Multi-Author Writing Style Analysis — 1st place on the medium and hard test sets** (11 teams)
- Top F1 on both: 0.768 (medium) and 0.780 (hard)
- Contrastive windowed boundary classification: DeBERTa encoder, domain- and task-adaptive pretraining (DAPT + TAPT), threshold calibration
- [Task overview](https://ceur-ws.org/Vol-4283/paper388.pdf)

**Publications**
- A. Voznyuk, **A. Tammaa** — *Contrastive Windowed Boundary Classification for Multi-Author Writing Style Analysis*, CLEF 2026 Working Notes · [PDF](https://ceur-ws.org/Vol-4283/paper429.pdf)
- A. Pester, **A. Tammaa**, C. Gütl, A. Steinmaurer, S. Abou El-Seoud — *Conversational Agents, Virtual Worlds, and Beyond: A Review of Large Language Models Enabling Immersive Learning*, IEEE EDUCON 2024 · [DOI](https://doi.org/10.1109/EDUCON60312.2024.10578895)
- Full list on [Google Scholar](https://scholar.google.com/citations?user=1fgHgYQAAAAJ)

Interests: LLM evaluation, authorship analysis and computational stylistics, LLMs for learning.

## Open source

**[LangChain](https://github.com/langchain-ai/langchain)** — 7+ merged PRs across text splitters, output parsers, and the Anthropic and DeepSeek integrations
- [#27678](https://github.com/langchain-ai/langchain/pull/27678), [#29397](https://github.com/langchain-ai/langchain/pull/29397) — Moved `HTMLHeaderTextSplitter` from lxml/XSLT to BeautifulSoup so it handles large HTML documents, then refactored it for maintainability
- [#30936](https://github.com/langchain-ai/langchain/pull/30936) — Output parsers raise a specific error when generation is truncated by `max_tokens`
- [#30935](https://github.com/langchain-ai/langchain/pull/30935) — Anthropic integration: optional tool descriptions
- [#29758](https://github.com/langchain-ai/langchain/pull/29758) — DeepSeek integration: JSON decoding error handling

**[python-pptx-text-replacer](https://github.com/fschaeck/python-pptx-text-replacer)** — [#14](https://github.com/fschaeck/python-pptx-text-replacer/pull/14): text replacement in master slides

## Selected projects

- **LLM data-analyst agent** — LangGraph agent that analyzes enterprise data and generates visualizations, with role-based access control (RBAC) for permissioned database queries.
- **Legal document summarizer** — LangChain agent that turns long legal PDFs into structured JSON summaries, with automated correctness and safety evaluations.

## Honors

- **ICPC World Finalist (2023)** — top 2% of collegiate programmers worldwide
- **ACPC Regional Finalist (2021, 2022)** — Arab and African Collegiate Programming Contest
- **First Class Honors, Valedictorian** — B.Sc. Artificial Intelligence, British University in Egypt (ranked 1st in cohort)
- **Best Research and Design Award** — undergraduate project on text-to-image synthesis with GANs

## Skills

- **LLMs & agents:** LangChain, LangGraph, multi-agent orchestration, tool calling, structured outputs
- **Evaluation:** LLM-as-a-judge, pairwise preference ranking (Bradley–Terry / Elo), factuality scoring, benchmark design
- **Training:** PyTorch, Hugging Face Transformers, LoRA / SFT, domain-adaptive pretraining, contrastive learning
- **Speech:** text-to-speech (TTS), prosody control, WhisperX forced alignment
- **Machine learning & NLP:** TensorFlow, scikit-learn, authorship analysis
- **Languages:** Python, C++, SQL, Java
- **Infrastructure:** FastAPI, Docker, AWS SageMaker, MongoDB, Git
