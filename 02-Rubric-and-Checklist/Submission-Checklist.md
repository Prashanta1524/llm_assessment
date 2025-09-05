# Submission Checklist

- [ ] `docker/` image builds from clean machine.  
- [ ] `tokenizer_train.py` produces `sp.model` (≈32k).  
- [ ] `train.py` prints best val perplexity ≤ 35.  
- [ ] `eval.py --split test` reports EM/F1 targets.  
- [ ] `chat.py --mode closed|rag` runs; rag shows citations.  
- [ ] `MODEL_CARD.md`, `DATA_SOURCES.md`, `DATA_PREP.md` complete.  
- [ ] All code, configs, seeds committed; final checkpoint saved.
