# Safety / harm benchmarks (downloaded 2026-10-01)

| Dir | Source | Contents |
|---|---|---|
| AdvBench | github: llm-attacks/llm-attacks (data/advbench) | harmful_behaviors 520, harmful_strings 574 |
| HarmBench | github: centerforaisafety/HarmBench (data/) | text test 320 / val 80 (all 400), multimodal 110, optimizer targets |
| StrongREJECT | github: alexandrasouly/strongreject | full 313, small 60 |
| SimpleSafetyTests | hf: Bertievidgen/SimpleSafetyTests | 100 |
| SafetyBench | hf: thu-coai/SafetyBench | test_en / test_zh 11435, test_zh_subset 2100, dev 5-shot per category |
| Aegis/v1.0 | hf: nvidia/Aegis-AI-Content-Safety-Dataset-1.0 | test 1199, train 10798 |
| Aegis/v2.0 | hf: nvidia/Aegis-AI-Content-Safety-Dataset-2.0 | test 1964, val 1245, train 25007 (+ refusals) |
| OpenAI-Moderation | github: openai/moderation-api-release | samples-1680.jsonl.gz, 1680 |
| BeaverTails | hf: PKU-Alignment/BeaverTails | 30k: test 3021 / train 27186; 330k: test 33396 / train 300567 |
| BeaverTails-Evaluation | hf: PKU-Alignment/BeaverTails-Evaluation | 700 prompts |
| PKU-SafeRLHF | hf: PKU-Alignment/PKU-SafeRLHF (current version) | per generator Alpaca-7B / Alpaca2-7B / Alpaca3-8B, test 8211 total |
| SafeRLHF-30K | hf: PKU-Alignment/PKU-SafeRLHF-30K (original Safe RLHF paper version) | test 2989, train 26874 |

Note: walledai/{AdvBench,HarmBench,StrongREJECT} on HF are gated, so the official GitHub sources were used instead.
