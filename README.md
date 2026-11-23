# LLM VRAM Calculator: feedback

Reports for the [StudioTV LLM VRAM Calculator](https://studiotvai.com/llm-vram-calculator): a measurement that differs from
the estimate, a wrong number, a missing GPU or model.

This repository only holds issues. The site's code is not here.

## Report a measurement

Open a new issue with the "Measurement" form, or use the "Report it" link under the speed estimate in the calculator: it
fills the form with your setup and the calculator's estimate.

What makes a report usable:

- the model and its file (for example `Qwen3.6-35B-A3B-Q4_K_M.gguf`),
- the machine: GPU or Mac, how many, system RAM if part of the model is in RAM,
- the engine and its version (llama.cpp build, Ollama, LM Studio, vLLM, SGLang, mlx-lm),
- how it was measured: command or settings, context length, requests at once,
- the number: tokens/s, GB of memory, or time to first token,
- a proof: log lines or a screenshot.

## What happens next

Nothing is published automatically. Each report is read and checked against its proof. A measurement that holds is added to
the [accuracy table](https://studiotvai.com/llm-vram-accuracy) with its source and its gap, whether it flatters the
calculator or not. A report without a proof cannot be added.

For anything else, send a message to [@ytstudiotv on X](https://x.com/ytstudiotv).
