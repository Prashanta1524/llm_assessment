# Candidate Brief — LLM for Nagarik WadaPatra (Citizen Charter)

## Objective
Build a **tiny bilingual (Nepali/English) domain LLM** that answers questions about citizen services (required documents, fees, processing time, responsible office/ward, escalation).

## Scope & Modes
- **Closed-book**: next-token LM answers using model knowledge only.  
- **RAG (optional, recommended)**: add a simple BM25 retriever over your curated charter corpus; show top-3 snippets and **citations**.

## Hard Constraints
- **Model**: Decoder-only Transformer ≤ **50M** params, context ≥ **512**.  
- **Tokenizer**: Train from scratch (SentencePiece Unigram/BPE); handle **Devanagari** + Nepali numerals.  
- **Data**: ~**2–5 MB** cleaned corpus + **≥600** instruction–answer pairs (≥40% Nepali).  
- **Compute**: CPU or a single ≤16GB consumer GPU. **Training ≤10 hours**.  
- **Reproducibility**: fixed seed, deterministic flags, Dockerfile, `README` to run end-to-end.

## Deliverables (High Level)
- Trained tokenizer + model checkpoints (≤200MB total).  
- Minimal **CLI** and **FastAPI** UI (`closed` / `rag` modes) with streaming.  
- Metrics: val perplexity, EM/F1 on held-out test, latency on CPU.  
- Docs: `MODEL_CARD.md`, `DATA_SOURCES.md`, `DATA_PREP.md`.
