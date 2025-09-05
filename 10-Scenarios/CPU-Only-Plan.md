# CPU‑Only Plan

- Reduce to 25–35M params; vocab 16–24k.  
- Use smaller batch size, gradient accumulation.  
- Prefer int8/fp16 inference; constrain output length (≤128 tokens).
