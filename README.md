## Dylan Jayabahu

Interpretability and efficient reasoning in language models. Previously an ML Engineering Intern at Shopify, building and evaluating support-triage models.
<br><sub>Computer Science, University of Waterloo · [website](https://www.dylanjayabahu.com/) · [linkedin](https://www.linkedin.com/in/dylan-jayabahu/)</sub>

---

### Papers

| | |
|---|---|
| **The Truth Was Never Gone: Perfect Aliasing in Compliant-Context Truth Probes** <br><sub>Sole author</sub> | In the studied binary tasks, compliant truth and action labels coincide, leaving the probes **unidentified**. Complementary evaluation labels give `AUROC(action) = 1 − AUROC(truth)`. Mixed-context fitting reaches **1.000** versus **0.006** conventional AUROC on Gemma-9B, averaged over three seeds. <br>[code](https://github.com/dylanjayabahu/perfect-aliasing) |
| **The Halt Vector: Internalizing a Causal Steering Intervention for Efficient Reasoning** <br><sub>First author · COLM 2026, *Efficient Reasoning* workshop · **Spotlight**</sub> | A causal halt direction at layer 18, moved into the weights. Hook-free per-problem self-halt: **−24% thinking at held accuracy**, five unseen benchmarks, 24 problems, no RL. <br>[code](https://github.com/dylanjayabahu/halt-vector) · [arXiv](https://arxiv.org/abs/2608.28859) |
| **Deep Learning Model for Invasive Ductal Carcinoma Detection** <br><sub>Sole author · IEEE CCECE 2025</sub> | Deep model for invasive ductal carcinoma detection. <br>[repo](https://github.com/dylanjayabahu/idc-detection) · [IEEE Xplore](https://ieeexplore.ieee.org/document/11364431) |
| **Human Action Detection using FMCW mmWave Radar** <br><sub>First author · CVIS 2024</sub> | Action recognition off raw radar returns. <br>[JCVIS](https://openjournals.uwaterloo.ca/index.php/vsl/article/view/6364) |

### Ongoing research

| | |
|---|---|
| **Off-Axis Drift: Internalizing a Steering Direction Needs More Than Its Scalar Projection** | For the halt direction, six scalar-projection objectives fail to compress at held accuracy across three model scales; full-vector reconstruction cuts **22.6–33.1%**. Off-axis drift explains the failure. A separate refusal-direction test succeeds under both objectives, bounding the claim. |
| **RL training dynamics** | Dense-checkpoint probing across **three GRPO seeds** surfaces a reward-hacking phase transition — length compression leads the accuracy collapse by **15–30 steps**. |

### Projects

| | |
|---|---|
| **[LOB-Engine](https://github.com/dylanjayabahu/LOB-engine)** | A small C++20 matching-engine prototype exploring price-time priority, SPSC queues, and pooled order storage. |
| **[RAG Tradeoffs](https://github.com/dylanjayabahu/rag-tradeoffs)** | Benchmarks retrieval accuracy and latency across context lengths, chunk sizes, and 10+ LLMs. |
| **[Firefighter Robot](https://github.com/dylanjayabahu/firefighter-robot)** | Autonomous maze-solving flame extinguisher. Set course records on two mazes, with recorded demonstrations. |
| **Mr. Nutz** | Early-stage poker-robot prototype exploring card perception, poker decision-making, and embedded control. |
