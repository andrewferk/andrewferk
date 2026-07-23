# Andrew Ferk

**Staff Software Engineer / Staff Product Engineer**.

I build revenue-critical, regulated, and high-trust software across
e-commerce, healthcare, fintech, and cloud infrastructure.

Over 17 years, I have worked across product strategy, architecture,
frontend, backend, data, infrastructure, security, reliability, and
technical leadership. I am particularly effective in small,
cross-functional teams where product quality, business impact,
privacy, payments, compliance, and engineering execution intersect.

## Areas of focus

- Full-stack product and platform architecture
- Payments, subscriptions, e-commerce, and financial workflows
- Healthcare, privacy, compliance, and high-trust systems
- Multi-tenant and event-driven systems
- Reliability, observability, CI/CD, testing, and developer experience
- AI-assisted software engineering
- Technical leadership

## Current interests

I am exploring practical uses of AI agents in software delivery,
particularly where correctness, security, privacy, observability,
and human review remain essential.

I am currently exploring Staff+ product engineering opportunities,
either remote or in the Los Angeles area.

## Current project

I'm building a personalized speech-recognition and communication assistant for
people with speech impairments — initially motivated by my son, who has Down
syndrome and whose speech can be hard for others to understand. The system adapts a
general speech model to atypical speech, then personalizes it to an individual's
words, phrases, and intended meaning. It supports both known-phrase recognition and
open-ended transcription, surfaces uncertainty instead of guessing, and improves
through caregiver corrections. The architecture is local-first — on-device inference
where practical, with cloud training and fallback when needed — starting on iPad.

I'm building it as a sequence of connected demos, each a reusable component of the
eventual product.

| # | Demo | Description | Primary skills | AI workflow |
|---|------|-------------|----------------|-------------|
| 1 | [Speech Dataset Workbench](https://github.com/andrewferk/speech-dataset-workbench) *(in progress)* | Local-first CLI that turns prompted recordings into validated, reproducible speech datasets — normalizing audio, measuring quality, splitting into train/validation/test by session, and emitting NeMo- and Hugging Face-compatible manifests. | Python, audio processing, dataset preparation, ASR evaluation | ChatGPT (5.6 Sol) for research & brainstorming; Claude (Opus 4.8, medium thinking) with [mattpocock/skills](https://github.com/mattpocock/skills) to plan & implement; Cursor (Grok 4.5 High) to review |
| 2 | Personal Phrase Recognizer | Recognize an individual's fixed set of known phrases from audio using learned embeddings. | PyTorch, embeddings, classification | |
| 3 | Personalized Whisper Adapter | Fine-tune Whisper for atypical speech and personalize it to one speaker. | Hugging Face, LoRA, ASR fine-tuning | |
| 4 | Offline iPad Transcriber | On-device transcription running locally on iPad. | SwiftUI, AVFoundation, whisper.cpp | |
| 5 | Confidence-First Recognition UI | Streaming recognition that exposes uncertainty rather than guessing. | VAD, streaming, confidence calibration | |
| 6 | Training and Model Registry Service | Backend for training jobs and model lifecycle, packaging, and delivery. | MLflow, FastAPI, GPU jobs, model packaging | |
| 7 | Local-First Communication Assistant | End-to-end integration of the prior components into a working assistant. | End-to-end product integration | |
| 8 | Advanced Streaming Model Comparison | Compare streaming ASR models and approaches for latency and accuracy. | NeMo, Parakeet, ONNX, distillation | |

**Currently reading:** *Speech and Language Processing* (Jurafsky & Martin) — a
foundational textbook that builds up how machines process human language and speech,
progressing from text normalization and n-gram models through embeddings, neural
networks, and sequence models, and weaving classic rule-based linguistics together
with the statistical and deep-learning methods behind today's systems.

## Contact

- [LinkedIn](https://www.linkedin.com/in/andrewferk/)
