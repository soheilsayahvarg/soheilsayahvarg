### Soheil Sayah Varg

Computer Engineering undergraduate at Sharif University of Technology, Tehran.

I work on **inference and approximation under uncertainty**: when the thing you care about
cannot be computed exactly — a posterior, a value function, an expectation over an
intractable distribution — you compute an approximation instead, and the interesting
question is what licenses trusting it.

A pattern runs through most of what is here. I build the method, then build the thing that
could prove it wrong, and report what that says even when it is not the answer I wanted.
A backtest of mine returned several hundred percent and a coin flip reproduced its Sharpe
ratio. An estimator I implemented lost to the baseline it was designed to beat, in all
fifteen cells of the sweep. Those are the results I put in the README, not the ones I
buried.

---

### Research

Work in progress, not public yet. Happy to discuss any of it by email.

| | |
| --- | --- |
| **Exact controlled generation from tilted autoregressive targets** | Digital Media Lab, Sharif. Sampling from a reward-tilted language model *exactly in distribution* rather than approximately, via a particle-Gibbs ladder over a batched proposal chain. Supervised by Dr. Ali Rostami, in Prof. Hamid R. Rabiee's group. Manuscript in preparation. |
| **Model-based RL in confounded POMDPs** | First empirical implementation of a theory-only ICML 2024 result. Dual bridge-function identification from negative-control proxies, oracle-verified to machine precision, extended to continuous state and action with a kernel backend. Private while the course cycle is open. |
| **Strategic endurance under uncertainty** | An RL agent for a multi-stage war of attrition with incomplete information — Bayesian type filtering and potential-based reward shaping. Private for the same reason. |

---

### Public work

Coursework and personal projects, cleaned up and documented properly.

| Repository | What it is |
| --- | --- |
| [**modern-information-retrieval**](https://github.com/soheilsayahvarg/modern-information-retrieval) | Three phases: a search engine built from scratch (VSM/BM25/LM), embeddings and BERT fine-tuning, then a hybrid dense+sparse multimodal system with cross-encoder reranking. |
| [**convex-optimization-algorithms**](https://github.com/soheilsayahvarg/convex-optimization-algorithms) | Chambolle-Pock and ADMM written from their update rules, with a solver used as an oracle to disagree with rather than a black box to defer to. |
| [**market-predictability-study**](https://github.com/soheilsayahvarg/market-predictability-study) | A profitable backtest, and the study of whether any of its stated reasons hold up. They do not. |
| [**segmentation-and-deep-rl**](https://github.com/soheilsayahvarg/segmentation-and-deep-rl) | Attention U-Net variants for segmentation, and Soft Actor-Critic built from scratch. |
| [**neogit**](https://github.com/soheilsayahvarg/neogit) | A version control system in C. Staging, commits, branches, merge, tags, pre-commit hooks. No libraries. |
| [**atomic-bomber**](https://github.com/soheilsayahvarg/atomic-bomber) | A JavaFX arcade game, built solo in a week during first year. |

---

### For other Sharif students

These two are not portfolio pieces. They are the full set of reports, schematics and
simulations for two lab courses, published because I could not find anything to check my
own work against when I took them.

- [**computer-architecture-lab**](https://github.com/soheilsayahvarg/computer-architecture-lab) — nine sessions, ending in a working CPU datapath with assembly programs
- [**logic-design-lab**](https://github.com/soheilsayahvarg/logic-design-lab) — ten sessions, Fritzing layouts and Proteus simulations

Use them to check your work, not to replace it. The lab staff have seen these files.

---

Also: co-founder of [Resonance](https://resonanceoly.ir), an online Physics Olympiad school
for students who have no selective high school near them, and a teaching assistant at Sharif
for nine course-semesters.

📫 soheilsayahvarg@gmail.com
