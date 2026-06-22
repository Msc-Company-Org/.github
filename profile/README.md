<div align="center">

# MSC Labs

### Stop renting intelligence. Own a model that beats GPT-4 on your task.

**Done-for-you custom model training** — we turn your data into a production-ready,
fine-tuned open-source model that beats a generic frontier API *on your specific task*,
at a fraction of the inference cost. You own the weights.

[🌐 Website](https://labs.msccompany.com.br) · [📅 Book a free model audit](https://labs.msccompany.com.br/assessment) · [🤗 Hugging Face](https://huggingface.co/MSC-Company)

</div>

---

## What we ship

Data engineering → **QLoRA/LoRA fine-tuning** → eval harness vs. your baseline → deployment
(API · Docker · vLLM · on-prem). One team, end to end. Eval-first, no vibes.

| | **Pilot** | **Production** |
|---|---|---|
| **Price** | $5,000 | $10,000 |
| **Timeline** | 2–3 weeks | 4–6 weeks |
| **You get** | Model + eval report + hosted endpoint | Full repo, weights, runbook, on-prem/VPC deploy |

> Every model below is built on the same pipeline we run for clients.

## 🧠 Reference models

Open, reproducible demos of small fine-tuned models out-performing frontier APIs on a focused task.
*Benchmark numbers are illustrative reference results from our standard eval harness.*

| Model | Task | Base | Result vs. frontier baseline |
|---|---|---|---|
| [**Atlas**](https://github.com/Msc-Company-Org/atlas) | Knowledge-grounded QA (RAG + tuned) | Qwen2.5-7B | **+12 pts** answer accuracy · 18× cheaper |
| [**Prometheus**](https://github.com/Msc-Company-Org/prometheus) | Customer-support reply generation | Llama-3.1-8B | **94%** human-pref · 22× cheaper |
| [**Artemis**](https://github.com/Msc-Company-Org/artemis) | Sales / lead-qualification agent | Mistral-7B | **+19%** qualified-lead rate (offline) |
| [**Hermes**](https://github.com/Msc-Company-Org/hermes) | Code assistant / dev automation | Qwen2.5-Coder-7B | **+15 pts** pass@1 on internal suite |
| [**Zeus**](https://github.com/Msc-Company-Org/zeus) | Intent routing / classification | Gemma-2-2B | **99.1%** routing accuracy · 40× cheaper |
| [**Arquimedes**](https://github.com/Msc-Company-Org/arquimedes) | Structured extraction & reasoning | Qwen2.5-7B | **0.97** field-level F1 on extraction |

## 🛠️ How we work
- **Eval-first** — benchmark against your real GPT-4/Claude baseline; report numbers before/after.
- **Open weights, you own them** — Llama · Qwen · Mistral · Gemma. No vendor lock.
- **2-stage training protocol** — smoke test → full run. Predictable cost, predictable timeline.
- **Privacy by design** — on-prem / in-VPC option; your data never trains anyone else's model.

---

<div align="center">

**Is fine-tuning worth it for your task?** → [Book a free 30-min model audit](https://labs.msccompany.com.br/assessment)

<sub>MSC Labs · custom LLM fine-tuning · made by the MSC Company team</sub>

</div>
