## Dylan Jayabahu

Interpretability and efficient reasoning in language models. Previously an ML Engineering Intern at Shopify, building and evaluating support-triage models.
<br><sub>Computer Science, University of Waterloo · [website](https://www.dylanjayabahu.com/) · [linkedin](https://www.linkedin.com/in/dylan-jayabahu/)</sub>

---

### Papers

| | |
|---|---|
| **The Truth Was Never Gone: Perfect Aliasing in Compliant-Context Truth Probes** <br><sub>Sole author</sub> | In the studied binary tasks, compliant truth and action labels coincide, leaving the probes **unidentified**. Complementary evaluation labels give `AUROC(action) = 1 − AUROC(truth)`. Mixed-context fitting reaches **1.000** versus **0.006** conventional AUROC on Gemma-9B, averaged over three seeds. <br>[code](https://github.com/dylanjayabahu/perfect-aliasing) · [arXiv](https://arxiv.org/abs/2609.10739) |
| **The Halt Vector: Internalizing a Causal Steering Intervention for Efficient Reasoning** <br><sub>First author · COLM 2026, *Efficient Reasoning* workshop · **Spotlight**</sub> | A causal halt direction at layer 18, moved into the weights. Hook-free per-problem self-halt: **−24% thinking at held accuracy**, five unseen benchmarks, 24 problems, no RL. <br>[code](https://github.com/dylanjayabahu/halt-vector) · [arXiv](https://arxiv.org/abs/2608.28859) |
| **Deep Learning Model for Invasive Ductal Carcinoma Detection** <br><sub>Sole author · IEEE CCECE 2025</sub> | Deep model for invasive ductal carcinoma detection. <br>[repo](https://github.com/dylanjayabahu/idc-detection) · [IEEE Xplore](https://ieeexplore.ieee.org/document/11364431) |
| **Human Action Detection using FMCW mmWave Radar** <br><sub>First author · CVIS 2024</sub> | Action recognition off raw radar returns. <br>[JCVIS](https://openjournals.uwaterloo.ca/index.php/vsl/article/view/6364) |

### Ongoing research

| | |
|---|---|
| **Off-Axis Drift: Internalizing a Halt Direction Needs More Than Its Scalar Projection** | Evaluated activation-target training for hook-free early stopping across **1.5B–14B reasoning models**, measuring compression, accuracy costs, and cross-domain transfer. Completed a **376-job development comparison of 46 candidate recipes**, selecting full-vector and on-axis reconstruction pairs at three shortening targets; held-out validation is pending. |
| **RL training dynamics** | Dense-checkpoint probing across **three historical GRPO seeds** shows a gold-free confidence monitor failing to flag a length-penalty reward hack: it holds at **0.71–0.85** while held-out accuracy halves to **0.38–0.48**. A four-arm factorial testing sensitivity to GRPO normalization is implemented and pre-registered, **not yet run**. |

### Projects

| | |
|---|---|
| **[LOB-Engine](https://github.com/dylanjayabahu/LOB-engine)** | A small C++20 matching-engine prototype exploring price-time priority, SPSC queues, and pooled order storage. |
| **[RAG Tradeoffs](https://github.com/dylanjayabahu/rag-tradeoffs)** | Benchmarks retrieval accuracy and latency across context lengths, chunk sizes, and 10+ LLMs. |
| **[Firefighter Robot](https://github.com/dylanjayabahu/firefighter-robot)** | Autonomous maze-solving flame extinguisher. Set course records on two mazes, with recorded demonstrations. |
| **Mr. Nutz** | Poker robotics combining card perception, poker logic, and integrated hardware. |
