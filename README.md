## Dylan Jayabahu

Interpretability and efficient reasoning in language models.
<br><sub>Computer Science, University of Waterloo · [website](https://www.dylanjayabahu.com/) · [linkedin](https://www.linkedin.com/in/dylan-jayabahu/)</sub>

---

### Papers

| | |
|---|---|
| **Perfect Aliasing in Compliant-Context Truth Probes** <br><sub>Sole author</sub> | Truth probes fit on compliant data are **unidentified** — truth, intent, and emitted token are one label, forcing `AUROC(action) = 1 − AUROC(truth)` exactly. An identified probe reads **1.000** where the conventional one reads **0.006**. <br>[code](https://github.com/dylanjayabahu/perfect-aliasing) |
| **The Halt Vector** <br><sub>First author · COLM 2026, *Efficient Reasoning* workshop · **Spotlight**</sub> | A causal halt direction at layer 18, moved into the weights. Hook-free per-problem self-halt: **−24% thinking at held accuracy**, five unseen benchmarks, 24 problems, no RL. <br>[code](https://github.com/dylanjayabahu/halt-vector) · [arXiv](https://arxiv.org/abs/2608.28859) |
| **IDC Detection in Histopathology** <br><sub>Sole author · IEEE CCECE 2025</sub> | Deep model for invasive ductal carcinoma detection. <br>[repo](https://github.com/dylanjayabahu/idc-detection) · [IEEE Xplore](https://ieeexplore.ieee.org/document/11364431) |
| **Human Action Detection, FMCW mmWave Radar** <br><sub>First author · CVIS 2024</sub> | Action recognition off raw radar returns. <br>[JCVIS](https://openjournals.uwaterloo.ca/index.php/vsl/article/view/6364) |

### In preparation

| | |
|---|---|
| **Off-Axis Drift** | Matching a steering direction's scalar projection doesn't install it. No scalar arm compresses at held accuracy across three model scales; full-vector reconstruction cuts **22.6–33.1%**. Mechanism: drift in the off-axis dimensions a frozen reader depends on. |
| **RL training dynamics** | Dense-checkpoint probing of one GRPO run surfaces a reproducible reward-hacking phase transition — length compression leads the accuracy collapse by **15–30 steps**. |

### Built

| | |
|---|---|
| **[LOB-Engine](https://github.com/dylanjayabahu/LOB-engine)** | C++20 price-time-priority matching engine — **5.8M orders/sec at 86 ns** median. Lock-free SPSC queues, O(1) cancellation. |
| **[RAG Tradeoffs](https://github.com/dylanjayabahu/rag-tradeoffs)** | Where long-context retrieval falls off a cliff versus chunking, across 10+ LLMs. |
| **[Firefighter Robot](https://github.com/dylanjayabahu/firefighter-robot)** | Autonomous maze-solving flame extinguisher. All-time course record holder. |
| **Mr. Nutz** | A robot that plays live Texas Hold'em against humans — Jetson Orin vision at **99.8%**, Monte-Carlo GTO with opponent modeling, real-time Teensy firmware. |
