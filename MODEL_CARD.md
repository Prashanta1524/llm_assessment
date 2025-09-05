# Model Card — LLM for Citizen Charter

- **Architecture**: Decoder-only Transformer (≤50M params)  
- **Tokenizer**: SentencePiece (≈32k) on NP/EN corpus  
- **Context length**: ≥512  
- **Training budget**: ≤10 hours on single consumer GPU or CPU  
- **Intended use**: QA on Nepalese citizen charter content  
- **Limitations**: Narrow domain; may abstain when uncertain
