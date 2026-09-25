# ScoreCraft Assets

Public download assets for the ScoreCraft MDCAT app. **No source code lives here** —
the app repository is private. This repo exists only so the app can fetch the two
large binary files anonymously at runtime.

## Releases

| Tag | File | Size | SHA-256 |
| --- | --- | --- | --- |
| `qwen3-v1` | `Qwen3-0.6B-Q4_K_M.gguf` | 396,704,416 B | `15e434d8ddf0af38fe3f7003af6ce6eac4edada6df34324aa45979f9cc79f02e` |
| `rag-v1` | `rag.db` | 17,436,672 B | `2b993946fa8843115f382cebb4bd67d1513c6ffe7fcd1fe21f70d4c31710b5ed` |

Direct download URLs (no auth required):

```
https://github.com/mehrankhan909/ScoreCraft-Assets/releases/download/qwen3-v1/Qwen3-0.6B-Q4_K_M.gguf
https://github.com/mehrankhan909/ScoreCraft-Assets/releases/download/rag-v1/rag.db
```

## Licences

- **Qwen3-0.6B-GGUF** — Apache-2.0, from the official
  [`Qwen/Qwen3-0.6B-GGUF`](https://huggingface.co/Qwen/Qwen3-0.6B-GGUF) repository.
  The `Q4_K_M` quant here was produced from the verified official `Q8_0` with
  `llama-quantize --allow-requantize` (llama.cpp commit `a25c986`).
- **rag.db** — derived from the user's own MDCAT study material.

## Verification

```bash
sha256sum Qwen3-0.6B-Q4_K_M.gguf   # must match the table above
sha256sum rag.db
```
