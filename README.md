# Terminal Agent – on-device model

`terminal-brain.litertlm` is the optional offline AI model used by the **Terminal Agent** Android app
(the app downloads it from this repository's Releases when you tap *Download* in **CONNECT AI**).

- Base model: **FunctionGemma 270M** by Google.
- **Modified:** fine-tuned to map short phone requests (English, Arabic, Arabizi) to Terminal Agent
  commands, then converted to LiteRT-LM int8 (~284 MB).

## License and use restrictions

Gemma is provided under and subject to the **Gemma Terms of Use** found at
[gemma.ai/resources/terms](https://gemma.ai/resources/terms/) – a copy is in
[GEMMA_TERMS_OF_USE.md](GEMMA_TERMS_OF_USE.md). See also [NOTICE](NOTICE).

By downloading or using this model you agree to the Gemma Terms of Use. The use restrictions of
**Section 3.2** apply to you, including the **Gemma Prohibited Use Policy**
([gemma.ai/resources/prohibited-use](https://gemma.ai/resources/prohibited-use/), copy in
[GEMMA_PROHIBITED_USE_POLICY.md](GEMMA_PROHIBITED_USE_POLICY.md)): you may not use the model, or let
others use it, for any of the uses that policy forbids.
