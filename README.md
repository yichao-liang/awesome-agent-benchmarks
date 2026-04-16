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

| Name | Year | Type | Description |
| --- | --- | --- | --- |
| [Atari (ALE)](https://arxiv.org/abs/1207.4708) | 2012 | 2D / pixel | 57 Atari 2600 games; the canonical pixel-based RL benchmark. |
| [Procgen](https://arxiv.org/abs/1912.01588) | 2019 | 2D / pixel | 16 procedurally-generated games for measuring generalization. |
| [NetHack Learning Environment](https://arxiv.org/abs/2006.13760) | 2020 | 2D / symbolic | The full game of NetHack as a long-horizon, open-ended RL challenge. |
| [Alchemy](https://arxiv.org/abs/2102.02926) | 2021 | 3D | Structured meta-learning task probing latent-variable inference. |
| [MiniHack](https://arxiv.org/abs/2109.13202) | 2021 | 2D / symbolic | Custom NetHack-based environments for targeted RL skill tests. |
| [DiscoveryWorld](https://arxiv.org/abs/2406.06769) | 2024 | 2D | Scientific-discovery tasks requiring hypothesis generation and experimentation. |
| [PUZZLES](https://arxiv.org/abs/2407.00401) | 2024 | 2D | Suite of Simon Tatham puzzle games for reasoning-focused RL. |
| [Craftax](https://arxiv.org/abs/2402.16801) | 2024 | 2D | JAX-based open-world Crafter/NetHack hybrid for fast RL research. |
| [ARC-AGI-3](https://arcprize.org/arc-agi/3) | 2025 | 2D | Interactive reasoning games designed to resist memorization. |
| [AutumnBench](https://arxiv.org/abs/2510.19788) | 2025 | 2D / grid | 43 grid-world environments and 129 tasks for evaluating world-model learning. |
| [Terra Nova](https://arxiv.org/abs/2511.15378) | 2025 | 2D / symbolic | Civilization-V-inspired CCE with large action spaces and partial observability. |

---

## Robotics

Physics-based simulation (and real-robot) benchmarks covering manipulation, locomotion, and physical reasoning.

| Name | Year | Type | Description |
| --- | --- | --- | --- |
| [AI2-THOR](https://arxiv.org/abs/1712.05474) | 2017 | 3D | Photorealistic interactive 3D household environments. |
| [DM Control](https://arxiv.org/abs/1801.00690) | 2018 | 3D | MuJoCo-based continuous-control tasks; de facto RL standard. |
| [PHYRE](https://arxiv.org/abs/1908.05656) | 2019 | 2D | Classical-mechanics puzzles for physical reasoning. |
| [Habitat](https://arxiv.org/abs/1904.01201) | 2019 | 3D | High-performance simulator for embodied navigation and rearrangement. |
| [ALFRED](https://arxiv.org/abs/1912.01734) | 2020 | 3D | Language-conditioned household tasks from demonstrations. |
| [Virtual Tools](https://www.pnas.org/doi/10.1073/pnas.1912341117) | 2020 | 2D | Tool-use puzzle game probing flexible physical reasoning. |
| [CALVIN](https://arxiv.org/abs/2112.03227) | 2021 | 3D | Long-horizon language-conditioned manipulation. |
| [ProcTHOR](https://arxiv.org/abs/2206.06994) | 2022 | 3D | Procedurally generated embodied-AI houses at scale. |
| [FurnitureBench](https://arxiv.org/abs/2305.12821) | 2023 | 3D | Real-world furniture assembly for long-horizon manipulation. |
| [LIBERO](https://arxiv.org/abs/2306.03310) | 2023 | 3D | Lifelong robot learning across distribution shifts. |
| [BEHAVIOR-1k](https://arxiv.org/abs/2403.09227) | 2024 | 3D | 1,000 everyday household activities in realistic simulation. |
| [DittoGym](https://arxiv.org/abs/2401.13231) | 2024 | 2D | Learning to control soft shape-shifting robots via differentiable simulation. |
| [Embodied Agent Interface](https://arxiv.org/abs/2410.07166) | 2024 | 3D | LLM decision-making evaluation over embodied tasks. |
| [I-PHYRE](https://arxiv.org/abs/2312.03009) | 2024 | 2D | Interactive physical reasoning requiring multi-step intervention. |
| [Kinetix](https://arxiv.org/abs/2410.23208) | 2024 | 2D | Open-ended physics-based control tasks for general agents. |
| [RoboCasa](https://arxiv.org/abs/2406.02523) | 2024 | 3D | Large-scale household simulation for generalist robots. |
| [EmbodiedBench](https://arxiv.org/abs/2502.09560) | 2025 | 3D | Multi-modal LLM evaluation for vision-driven embodied agents. |
| [ManiSkill-HAB](https://arxiv.org/abs/2412.13211) | 2025 | 3D | Low-level manipulation in home-rearrangement tasks. |
| [OGBench](https://arxiv.org/abs/2410.20092) | 2025 | Both | Offline goal-conditioned RL benchmark. |
| [VLABench](https://arxiv.org/abs/2412.18194) | 2025 | 3D | Language-conditioned manipulation with long-horizon reasoning. |
| [VLMgineer](https://arxiv.org/abs/2507.12644) | 2025 | 3D | Vision–language models as robotic toolsmiths. |
| [KinDER](https://prpl-group.com/kinder-site/) | 2026 | Both | Physical-reasoning benchmark covering kinematic/dynamic 2D and 3D tasks (RSS 2026, under review). |

---

## Computer Use

Benchmarks for agents that interact with software — browsers, desktop GUIs, terminals, and codebases.

| Name | Year | Type | Description |
| --- | --- | --- | --- |
| [MiniWoB++](https://proceedings.mlr.press/v70/shi17a.html) | 2017 | Web | Small web-interaction tasks; foundational GUI-agent benchmark. |
| [WebShop](https://arxiv.org/abs/2207.01206) | 2022 | Web | Simulated shopping site for instruction-following web agents. |
| [Mind2Web](https://arxiv.org/abs/2306.06070) | 2023 | Web | Generalist web-agent tasks across 137 real sites. |
| [WebArena](https://arxiv.org/abs/2307.13854) | 2023 | Web | Self-hostable realistic web environments for agent evaluation. |
| [AgentBench](https://arxiv.org/abs/2308.03688) | 2023 | Multi | LLM-as-agent evaluation across 8 environments. |
| [SWE-bench](https://arxiv.org/abs/2310.06770) | 2023 | Code | Real GitHub issues requiring repo-level code changes. |
| [GAIA](https://arxiv.org/abs/2311.12983) | 2023 | Multi | General-assistant questions requiring tool use and reasoning. |
| [VisualWebArena](https://arxiv.org/abs/2401.13649) | 2024 | Web | Visually-grounded multimodal web tasks. |
| [WorkArena](https://arxiv.org/abs/2403.07718) | 2024 | Web | Enterprise (ServiceNow) workflows for knowledge-worker agents. |
| [OSWorld](https://arxiv.org/abs/2404.07972) | 2024 | GUI | Real OS environments across Ubuntu, Windows, and macOS. |
| [AndroidWorld](https://arxiv.org/abs/2405.14573) | 2024 | GUI | Dynamic Android tasks across 20 real apps. |
| [τ-bench](https://arxiv.org/abs/2406.12045) | 2024 | Multi | Tool-agent–user interaction in realistic domains (retail, airline). |
| [TheAgentCompany](https://arxiv.org/abs/2412.14161) | 2024 | Multi | Simulated software company measuring end-to-end job performance. |
| [BrowseComp](https://openai.com/index/browsecomp/) | 2025 | Web | Hard-to-find information-seeking tasks for browsing agents. |

---

## Contributing

PRs welcome. Please:
- Keep entries within one of the three domains above.
- Link the benchmark **Name** to its paper or primary reference.
- Keep the description to one sentence (~15 words).
- Preserve chronological order within each table.
