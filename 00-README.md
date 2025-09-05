# LLM Assessment — Nagarik WadaPatra (Citizen Charter)
**Organization:** Ninja Infosys Pvt. Ltd.  
**Last updated:** 2025-09-03

Welcome to the LLM assessment. This pack contains everything required to build a **small bilingual (EN/NP) domain LLM** for Nepal’s *Nagarik WadaPatra* within one week on commodity hardware.

## Quick Start
1. Read **01-Brief/Candidate-Brief.md** to understand objectives and constraints.  
2. Review **Timeline-and-Checkins.md** to see the daily gates (G0 → G6).  
3. Follow **05-Setup/Environment-Setup.md** to prepare your environment (CPU or single 8–16GB GPU).  
4. Use **04-Context-and-Data/Dataset-Guidelines.md** to curate/clean your corpus and instructions.  
5. Track quality with **03-Standards/Evaluation-Metrics.md** and **09-Checklists**.  
6. Submit artifacts per **02-Rubric-and-Checklist/Submission-Checklist.md**.

> Goal: A tiny decoder-only Transformer (≤50M params) trained from scratch with your tokenizer (SentencePiece/BPE) + optional lightweight RAG. Provide a minimal CLI/Web UI and **clear citations** when RAG is enabled.
