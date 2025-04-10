## Pico Project

This is a small course project to train a LLM based on `tinystories` dataset.

The basic script to start with:
`python pico.py --tinystories_weight 1 --prompt "0 1 2 3 4" --block_size 32`

Supported models:
- `LSTM`
- `Transformer (Decoder-only)`
- `Transformer with KV cache (Decoder-only)` (To be completed)