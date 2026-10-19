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
| **Internalizing the Halt Vector: What a Halt Target Changes in a Reasoning Model** <br><sub>First author · with Tinuade Adeleke</sub> | On Qwen-7B, the halt target shortened thinking more than random, reversed and covariance controls, and about as much as a nearby progress-tracking direction. On-axis training cut held-out thinking by **14.0% overall** (shorter on MATH at lower Math-Verify accuracy, longer on GSM8K, relative to the untrained model); full-vector training shortened about as much, with more boxed answers and higher Math-Verify accuracy. Math-Verify credits answers anywhere in the output. Removing text loss shortened GSM8K thinking by **37.4 percentage points**. A no-text-loss variant, chosen after that result, cut thinking by **34.3–45.6%** on MATH500, AIME and GPQA-Diamond; correct boxed answers fell on MATH500 and GPQA-Diamond, largely through output format on GPQA-Diamond, while AIME accuracy remains unresolved. Projection-out tests leave halt-specific reliance unresolved; transfer beyond Qwen-7B is not established. |
| **RL training dynamics** | Dense-checkpoint probing across **three historical GRPO seeds** under a length penalty: in two of three seeds a first-answer-token concentration readout ended at **0.81–0.85** while held-out accuracy fell **43–45%**. A pre-registered four-arm factorial testing how GRPO's std and length normalizations jointly change the penalty's accuracy cost has its baseline arm **bit-identical to TRL across 168 cases** and is **not yet run**; the pipeline is calibrated on cloud H200s with a 50-step baseline run. |

### Projects

| | |
|---|---|
| **[LOB-Engine](https://github.com/dylanjayabahu/LOB-engine)** | A small C++20 matching-engine prototype exploring price-time priority, SPSC queues, and pooled order storage. |
| **[RAG Tradeoffs](https://github.com/dylanjayabahu/rag-tradeoffs)** | Benchmarks retrieval accuracy and latency across context lengths, chunk sizes, and 10+ LLMs. |
| **[Firefighter Robot](https://github.com/dylanjayabahu/firefighter-robot)** | Autonomous maze-solving flame extinguisher. Set course records on two mazes, with recorded demonstrations. |
| **Mr. Nutz** | Poker robotics combining card perception, poker logic, and integrated hardware. |
