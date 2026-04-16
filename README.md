# Awesome Agent Benchmarks

A curated list of benchmarks for evaluating AI agents. Scoped to three domains: games, robotics, and computer use.

## Contents

- [Games](#games)
- [Robotics](#robotics)
- [Computer Use](#computer-use)
- [Contributing](#contributing)

---

## Games

Interactive environments — primarily 2D — for training and evaluating decision-making agents on exploration, planning, and generalization.

| Name | Year | Type | Paper | Description |
| --- | --- | --- | --- | --- |
| Atari (ALE) | 2012 | 2D / pixel | [arXiv:1207.4708](https://arxiv.org/abs/1207.4708) | 57 Atari 2600 games; the canonical pixel-based RL benchmark. |
| Procgen | 2019 | 2D / pixel | [arXiv:1912.01588](https://arxiv.org/abs/1912.01588) | 16 procedurally-generated games for measuring generalization. |
| NetHack Learning Environment | 2020 | 2D / symbolic | [arXiv:2006.13760](https://arxiv.org/abs/2006.13760) | The full game of NetHack as a long-horizon, open-ended RL challenge. |
| Alchemy | 2021 | 3D | [arXiv:2102.02926](https://arxiv.org/abs/2102.02926) | Structured meta-learning task probing latent-variable inference. |
| MiniHack | 2021 | 2D / symbolic | [arXiv:2109.13202](https://arxiv.org/abs/2109.13202) | Custom NetHack-based environments for targeted RL skill tests. |
| DiscoveryWorld | 2024 | 2D | [arXiv:2406.06769](https://arxiv.org/abs/2406.06769) | Scientific-discovery tasks requiring hypothesis generation and experimentation. |
| PUZZLES | 2024 | 2D | [arXiv:2407.00401](https://arxiv.org/abs/2407.00401) | Suite of Simon Tatham puzzle games for reasoning-focused RL. |
| Craftax | 2024 | 2D | [arXiv:2402.16801](https://arxiv.org/abs/2402.16801) | JAX-based open-world Crafter/NetHack hybrid for fast RL research. |
| ARC-AGI-3 | 2025 | 2D | [arcprize.org](https://arcprize.org/arc-agi/3) | Interactive reasoning games designed to resist memorization. |
| AutumnBench | 2025 | 2D / grid | [arXiv:2510.19788](https://arxiv.org/abs/2510.19788) | 43 grid-world environments and 129 tasks for evaluating world-model learning. |
| Terra Nova | 2025 | 2D / symbolic | [arXiv:2511.15378](https://arxiv.org/abs/2511.15378) | Civilization-V-inspired CCE with large action spaces and partial observability. |

---

## Robotics

Physics-based simulation (and real-robot) benchmarks covering manipulation, locomotion, and physical reasoning.

| Name | Year | Type | Paper | Description |
| --- | --- | --- | --- | --- |
| AI2-THOR | 2017 | 3D | [arXiv:1712.05474](https://arxiv.org/abs/1712.05474) | Photorealistic interactive 3D household environments. |
| DM Control | 2018 | 3D | [arXiv:1801.00690](https://arxiv.org/abs/1801.00690) | MuJoCo-based continuous-control tasks; de facto RL standard. |
| PHYRE | 2019 | 2D | [arXiv:1908.05656](https://arxiv.org/abs/1908.05656) | Classical-mechanics puzzles for physical reasoning. |
| Habitat | 2019 | 3D | [arXiv:1904.01201](https://arxiv.org/abs/1904.01201) | High-performance simulator for embodied navigation and rearrangement. |
| ALFRED | 2020 | 3D | [arXiv:1912.01734](https://arxiv.org/abs/1912.01734) | Language-conditioned household tasks from demonstrations. |
| Virtual Tools | 2020 | 2D | [PNAS](https://www.pnas.org/doi/10.1073/pnas.1912341117) | Tool-use puzzle game probing flexible physical reasoning. |
| CALVIN | 2021 | 3D | [arXiv:2112.03227](https://arxiv.org/abs/2112.03227) | Long-horizon language-conditioned manipulation. |
| ProcTHOR | 2022 | 3D | [arXiv:2206.06994](https://arxiv.org/abs/2206.06994) | Procedurally generated embodied-AI houses at scale. |
| FurnitureBench | 2023 | 3D | [arXiv:2305.12821](https://arxiv.org/abs/2305.12821) | Real-world furniture assembly for long-horizon manipulation. |
| LIBERO | 2023 | 3D | [NeurIPS 2023](https://arxiv.org/abs/2306.03310) | Lifelong robot learning across distribution shifts. |
| BEHAVIOR-1k | 2024 | 3D | [arXiv:2403.09227](https://arxiv.org/abs/2403.09227) | 1,000 everyday household activities in realistic simulation. |
| DittoGym | 2024 | 2D | [arXiv:2401.13231](https://arxiv.org/abs/2401.13231) | Learning to control soft shape-shifting robots via differentiable simulation. |
| Embodied Agent Interface | 2024 | 3D | [arXiv:2410.07166](https://arxiv.org/abs/2410.07166) | LLM decision-making evaluation over embodied tasks. |
| I-PHYRE | 2024 | 2D | [ICLR 2024](https://arxiv.org/abs/2312.03009) | Interactive physical reasoning requiring multi-step intervention. |
| Kinetix | 2024 | 2D | [arXiv:2410.23208](https://arxiv.org/abs/2410.23208) | Open-ended physics-based control tasks for general agents. |
| RoboCasa | 2024 | 3D | [RSS 2024](https://arxiv.org/abs/2406.02523) | Large-scale household simulation for generalist robots. |
| EmbodiedBench | 2025 | 3D | [ICML 2025](https://arxiv.org/abs/2502.09560) | Multi-modal LLM evaluation for vision-driven embodied agents. |
| ManiSkill-HAB | 2025 | 3D | [ICLR 2025](https://arxiv.org/abs/2412.13211) | Low-level manipulation in home-rearrangement tasks. |
| OGBench | 2025 | Both | [ICLR 2025](https://arxiv.org/abs/2410.20092) | Offline goal-conditioned RL benchmark. |
| VLABench | 2025 | 3D | [ICCV 2025](https://arxiv.org/abs/2412.18194) | Language-conditioned manipulation with long-horizon reasoning. |
| VLMgineer | 2025 | 3D | [arXiv:2507.12644](https://arxiv.org/abs/2507.12644) | Vision–language models as robotic toolsmiths. |
| KinDER | 2026 | Both | RSS 2026 (under review) | Physical-reasoning benchmark covering kinematic/dynamic 2D and 3D tasks. |

---

## Computer Use

Benchmarks for agents that interact with software — browsers, desktop GUIs, terminals, and codebases.

| Name | Year | Type | Paper | Description |
| --- | --- | --- | --- | --- |
| MiniWoB++ | 2017 | Web | [ICML 2017](https://proceedings.mlr.press/v70/shi17a.html) | Small web-interaction tasks; foundational GUI-agent benchmark. |
| WebShop | 2022 | Web | [arXiv:2207.01206](https://arxiv.org/abs/2207.01206) | Simulated shopping site for instruction-following web agents. |
| Mind2Web | 2023 | Web | [arXiv:2306.06070](https://arxiv.org/abs/2306.06070) | Generalist web-agent tasks across 137 real sites. |
| WebArena | 2023 | Web | [arXiv:2307.13854](https://arxiv.org/abs/2307.13854) | Self-hostable realistic web environments for agent evaluation. |
| AgentBench | 2023 | Multi | [arXiv:2308.03688](https://arxiv.org/abs/2308.03688) | LLM-as-agent evaluation across 8 environments. |
| SWE-bench | 2023 | Code | [arXiv:2310.06770](https://arxiv.org/abs/2310.06770) | Real GitHub issues requiring repo-level code changes. |
| GAIA | 2023 | Multi | [arXiv:2311.12983](https://arxiv.org/abs/2311.12983) | General-assistant questions requiring tool use and reasoning. |
| VisualWebArena | 2024 | Web | [arXiv:2401.13649](https://arxiv.org/abs/2401.13649) | Visually-grounded multimodal web tasks. |
| WorkArena | 2024 | Web | [arXiv:2403.07718](https://arxiv.org/abs/2403.07718) | Enterprise (ServiceNow) workflows for knowledge-worker agents. |
| OSWorld | 2024 | GUI | [arXiv:2404.07972](https://arxiv.org/abs/2404.07972) | Real OS environments across Ubuntu, Windows, and macOS. |
| AndroidWorld | 2024 | GUI | [arXiv:2405.14573](https://arxiv.org/abs/2405.14573) | Dynamic Android tasks across 20 real apps. |
| τ-bench | 2024 | Multi | [arXiv:2406.12045](https://arxiv.org/abs/2406.12045) | Tool-agent–user interaction in realistic domains (retail, airline). |
| TheAgentCompany | 2024 | Multi | [arXiv:2412.14161](https://arxiv.org/abs/2412.14161) | Simulated software company measuring end-to-end job performance. |
| BrowseComp | 2025 | Web | [OpenAI](https://openai.com/index/browsecomp/) | Hard-to-find information-seeking tasks for browsing agents. |

---

## Contributing

PRs welcome. Please:
- Keep entries within one of the three domains above.
- Include a paper or primary reference link in the **Paper** column.
- Keep the description to one sentence (~15 words).
- Preserve chronological order within each table.
