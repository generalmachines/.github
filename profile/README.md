<a href="https://generalmachines.ai/?utm_source=github&utm_medium=org_readme">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/gm-banner-dark-v3.png">
    <img alt="General Machines. Fig. 1: how AI agents buy, from search to checkout" src="./assets/gm-banner-light-v3.png" width="100%">
  </picture>
</a>

# General Machines

General Machines is an applied AI research lab building open datasets, evals and small models for the agentic web and physical AI.

Our first focus is commerce. [Machine Commerce](https://machinecommerce.co/?utm_source=github&utm_medium=org_readme), the agentic commerce arm of General Machines, studies how AI agents search, compare and pay in online stores, and which store details decide whether they can buy.

## Releases

| Release | Type | Status | Links |
|---|---|---|---|
| **CartTrace-100k** | Dataset | Released | [Dataset](https://huggingface.co/datasets/generalmachines/CartTrace-100k) · [Replay kit](https://github.com/generalmachines/cartTrace-100k) · [Explorer](https://machinecommerce.co/carttrace) · [Announcement](https://generalmachines.ai/datasets/carttrace-100k) · Paper: coming to arXiv |
| **CartBench** | Benchmark | Planned | |
| **Commerce&#8209;1** | Small evaluator model | Planned | |

### CartTrace-100k

101,416 shopping journeys by one agent (Qwen3.8-27B) in 1,044 stand-in stores built from open catalogs, across 25 product categories. Each journey runs from search through checkout and payment over five commerce protocols: UCP, ACP, AP2, MPP and WebMCP. Payments use test tokens only; nothing was bought on a real store. On journeys with full store data, the agent succeeds 68.8% of the time.

- Dataset: CC BY 4.0
- Replay kit: Apache-2.0

```bibtex
@misc{bhatnagar2026carttrace,
  title     = {CartTrace-100k: Shopping-Agent Journeys Through Checkout and Payment, and Where They Fail},
  author    = {Bhatnagar, Pratham and Pal, Deepanshu},
  year      = {2026},
  publisher = {General Machines},
  url       = {https://generalmachines.ai/datasets/carttrace-100k}
}
```

## Contact

Working on shopping agents, agent evaluations or an online store? Write to [founders@generalmachines.ai](mailto:founders@generalmachines.ai).

<p>
  <a href="https://generalmachines.ai/?utm_source=github&utm_medium=org_readme">generalmachines.ai</a> ·
  <a href="https://machinecommerce.co/?utm_source=github&utm_medium=org_readme">machinecommerce.co</a> ·
  <a href="https://huggingface.co/generalmachines">Hugging Face</a> ·
  <a href="https://x.com/machinecommerce">X</a> ·
  <a href="https://www.linkedin.com/company/generalmachinesai">LinkedIn</a> ·
  <a href="https://generalmachines.ai/careers/?utm_source=github&utm_medium=org_readme">Careers</a>
</p>

<sub>General Machines Pte. Ltd., Singapore.</sub>
