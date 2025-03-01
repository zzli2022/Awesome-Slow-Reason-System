# Awesome-System2-Reasoning-LLM

[![arXiv](https://img.shields.io/badge/arXiv-Slow_Reason_System-b31b1b.svg)](http://arxiv.org/abs/2502.17419) 
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/zzli2022/System2-Reasoning-LLM)
[![Last Commit](https://img.shields.io/github/last-commit/zzli2022/Awesome-System2-Reasoning-LLM)](https://github.com/zzli2022/System2-Reasoning-LLM)
[![Contribution Welcome](https://img.shields.io/badge/Contributions-welcome-blue)]()

<!-- omit in toc -->
## 📢 Updates

- **2025.02**: We released a survey paper "[From System 1 to System 2: A Survey of Reasoning Large Language Models](http://arxiv.org/abs/2502.17419)". Feel free to cite or open pull requests.

<!-- omit in toc -->
## 👀 Introduction

Welcome to the repository for our survey paper, "From System 1 to System 2: A Survey of Reasoning Large Language Models". This repository provides resources and updates related to our research. For a detailed introduction, please refer to [our survey paper](http://arxiv.org/abs/2502.17419).

Achieving human-level intelligence requires enhancing the transition from System 1 (fast, intuitive) to System 2 (slow, deliberate) reasoning. While foundational Large Language Models (LLMs) have made significant strides, they still fall short of human-like reasoning in complex tasks. Recent reasoning LLMs, like OpenAI’s o1, have demonstrated expert-level performance in domains such as mathematics and coding, resembling System 2 thinking. This survey explores the development of reasoning LLMs, their foundational technologies, benchmarks, and future directions. We maintain an up-to-date GitHub repository to track the latest developments in this rapidly evolving field.


![image](./assets/develope.jpg)

This image highlights the progression of AI systems, emphasizing the shift from rapid, intuitive approaches to deliberate, reasoning-driven models. It shows how AI has evolved to handle a broader range of real-world challenges.

![image](./assets/timeline.png)
The recent timeline of reasoning LLMs, covering core methods and the release of open-source and closed-source reproduction projects.

<!-- omit in toc -->
## 📒 Table of Contents

- [Awesome-System-2-AI](#awesome-system-2-ai)
  - [Part 1: O1 Replication](#part-1-o1-replication)
  - [Part 2: Process Reward Models](#part-2-process-reward-models)
  - [Part 3: Reinforcement Learning](#part-3-reinforcement-learning)
  - [Part 4: MCTS/Tree Search](#part-4-mctstree-search)
  - [Part 5: Self-Training / Self-Improve](#part-5-self-training--self-improve)
  - [Part 6: Reflection](#part-6-reflection)
  - [Part 7: Efficient System2](#part-7-efficient-system2)
  - [Part 8: Explainability](#part-8-explainability)
  - [Part 9: Multimodal Agent related Slow-Fast System](#part-9-multimodal-agent-related-slow-fast-system)
  - [Part 10: Benchmark and Datasets](#part-10-benchmark-and-datasets)
  - [Part 11: Reasoning and Safety](#part-11-reasoning-and-safety)

## Part 1: O1 Replication
* Open-Reasoner-Zero [[Paper]](https://github.com/Open-Reasoner-Zero/Open-Reasoner-Zero/blob/main/ORZ_paper.pdf) ![](https://img.shields.io/badge/pdf-2025.02-red)
* X-R1 [[github]](https://github.com/dhcode-cpp/X-R1) ![](https://img.shields.io/badge/github-2025.02-red)
* Unlock-Deepseek [[Blog]](https://mp.weixin.qq.com/s/Z7P61IV3n4XYeC0Et_fvwg) ![](https://img.shields.io/badge/blog-2025.02-red)
* Logic-RL: Unleashing LLM Reasoning with Rule-Based Reinforcement Learning [[Paper]](https://arxiv.org/abs/2502.14768) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* LLM-R1 [[github]](https://github.com/TideDra/lmm-r1) ![](https://img.shields.io/badge/github-2025.02-red)
* mini-deepseek-r1 [[Blog]](https://www.philschmid.de/mini-deepseek-r1) ![](https://img.shields.io/badge/blog-2025.01-red)
* Run DeepSeek R1 Dynamic 1.58-bit [[Blog]](https://unsloth.ai/blog/deepseekr1-dynamic) ![](https://img.shields.io/badge/blog-2025.01-red)
* Simple Reinforcement Learning for Reasoning [[Notion]](https://hkust-nlp.notion.site/simplerl-reason) ![](https://img.shields.io/badge/Notion-2025.01-red)
* TinyZero [[github]](https://github.com/Jiayi-Pan/TinyZero) ![](https://img.shields.io/badge/github-2025.01-red)
* Open R1 [[github]](https://github.com/huggingface/open-r1) ![](https://img.shields.io/badge/github-2025.01-red)
* Search-o1: Agentic Search-Enhanced Large Reasoning Models [[Paper]](https://arxiv.org/abs/2501.05366) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* Virgo: A Preliminary Exploration on Reproducing o1-like MLLM [[Paper]](https://arxiv.org/abs/2501.01904) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* Imitate, Explore, and Self-Improve: A Reproduction Report on Slow-thinking Reasoning Systems [[Paper]](https://arxiv.org/abs/2412.09413) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* o1-Coder: an o1 Replication for Coding [[Paper]](https://arxiv.org/abs/2412.00154) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs [[Paper]](https://arxiv.org/abs/2412.18925) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* DRT: Deep Reasoning Translation via Long Chain-of-Thought [[Paper]](https://arxiv.org/abs/2412.17498) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Enhancing LLM Reasoning with Reward-guided Tree Search [[Paper]](https://arxiv.org/abs/2411.11694) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* Marco-o1: Towards Open Reasoning Models for Open-Ended Solutions [[Paper]](https://arxiv.org/abs/2411.14405) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* O1 Replication Journey--Part 2: Surpassing O1-preview through Simple Distillation, Big Progress or Bitter Lesson? [[Paper]](https://arxiv.org/abs/2411.16489) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* O1 Replication Journey: A Strategic Progress Report -- Part 1 [[Paper]](https://arxiv.org/abs/2410.18982) ![](https://img.shields.io/badge/arXiv-2024.10-red)
## Part 2: Process Reward Models
* PRMBench: A Fine-grained and Challenging Benchmark for Process-Level Reward Models. [[Paper]](https://arxiv.org/abs/2501.03124) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* ReARTeR: Retrieval-Augmented Reasoning with Trustworthy Process Rewarding [[Paper]](https://arxiv.org/abs/2501.07861) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* The Lessons of Developing Process Reward Models in Mathematical Reasoning. [[Paper]](https://arxiv.org/abs/2501.07301) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* ToolComp: A Multi-Tool Reasoning & Process Supervision Benchmark. [[Paper]](https://arxiv.org/abs/2501.01290) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* AutoPSV: Automated Process-Supervised Verifier [[Paper]](https://openreview.net/forum?id=eOAPWWOGs9) ![](https://img.shields.io/badge/NeurIPS-2024-blue)
* ReST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search [[Paper]](https://openreview.net/forum?id=8rcFOqEud5) ![](https://img.shields.io/badge/NeurIPS-2024-blue)
* Free Process Rewards without Process Labels. [[Paper]](https://arxiv.org/abs/2412.01981) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Outcome-Refining Process Supervision for Code Generation [[Paper]](https://arxiv.org/abs/2412.15118) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations [[Paper]](https://aclanthology.org/2024.acl-long.510/) ![](https://img.shields.io/badge/ACL-2024-blue)
* OVM: Outcome-supervised Value Models for Planning in Mathematical Reasoning [[Paper]](https://aclanthology.org/2024.findings-naacl.55/) ![](https://img.shields.io/badge/ACL_Findings-2024-blue)
* Step-DPO: Step-wise Preference Optimization for Long-chain Reasoning of LLMs [[Paper]](https://arxiv.org/abs/2406.18629) ![](https://img.shields.io/badge/arXiv-2024.06-red)
* Let's Verify Step by Step. [[Paper]](https://arxiv.org/abs/2305.20050) ![](https://img.shields.io/badge/arXiv-2024.05-red)
* Improve Mathematical Reasoning in Language Models by Automated Process Supervision [[Paper]](https://arxiv.org/abs/2306.05372) ![](https://img.shields.io/badge/arXiv-2023.06-red)
* Making Large Language Models Better Reasoners with Step-Aware Verifier [[Paper]](https://arxiv.org/abs/2206.02336) ![](https://img.shields.io/badge/arXiv-2023.06-red)
* Solving Math Word Problems with Process and Outcome-Based Feedback [[Paper]](https://arxiv.org/abs/2211.14275) ![](https://img.shields.io/badge/arXiv-2022.11-red)
* Uncertainty-Aware Step-wise Verification with Generative Reward Models [[Paper]](https://arxiv.org/abs/2502.11250) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* AdaptiveStep: Automatically Dividing Reasoning Step through Model Confidence [[Paper]](https://www.arxiv.org/abs/2502.13943) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Self-Consistency of the Internal Reward Models Improves Self-Rewarding Language Models [[Paper]](https://www.arxiv.org/abs/2502.08922) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Can 1B LLM Surpass 405B LLM? Rethinking Compute-Optimal Test-Time Scaling [[Paper]](https://arxiv.org/abs/2502.06703) ![](https://img.shields.io/badge/arXiv-2025.02-red)
## Part 3: Reinforcement Learning
* Satori: Reinforcement Learning with Chain-of-Action-Thought Enhances LLM Reasoning via Autoregressive Search [[Paper]](https://arxiv.org/abs/2502.02508) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* DeepScaleR: Surpassing O1-Preview with a 1.5B Model by Scaling RL [[Paper]](https://pretty-radio-b75.notion.site/DeepScaleR-Surpassing-O1-Preview-with-a-1-5B-Model-by-Scaling-RL-19681902c1468005bed8ca303013a4e2) ![](https://img.shields.io/badge/Notion-2025.02-red)
* QLASS: Boosting Language Agent Inference via Q-Guided Stepwise Search [[Paper]](https://arxiv.org/abs/2502.02584) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Process Reinforcement through Implicit Rewards [[Paper]](https://arxiv.org/abs/2502.01456) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Advancing Language Model Reasoning through Reinforcement Learning and Inference Scaling [[Paper]](https://arxiv.org/abs/2501.11651) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* Challenges in Ensuring AI Safety in DeepSeek-R1 Models: The Shortcomings of Reinforcement Learning Strategies [[Paper]](https://arxiv.org/abs/2501.17030) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning [[Paper]](https://arxiv.org/abs/2501.12948) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* Kimi k1.5: Scaling Reinforcement Learning with LLMs [[Paper]](https://arxiv.org/abs/2501.12599) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* Does RLHF Scale? Exploring the Impacts From Data, Model, and Method [[Paper]](https://arxiv.org/abs/2412.06000) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Offline Reinforcement Learning for LLM Multi-Step Reasoning [[Paper]](https://arxiv.org/abs/2412.16145) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* ReFT: Representation Finetuning for Language Models [[Paper]](https://aclanthology.org/2024.acl-long.410.pdf) ![](https://img.shields.io/badge/ACL-2024-blue)
* Deepseekmath: Pushing the limits of mathematical reasoning in open language models [[Paper]](https://arxiv.org/abs/2402.03300) ![](https://img.shields.io/badge/arXiv-2024.02-red)
* Reasoning with Reinforced Functional Token Tuning [[Paper]](https://arxiv.org/abs/2502.13389) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Value-Based Deep RL Scales Predictably [[Paper]](https://arxiv.org/abs/2502.04327) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* InfAlign: Inference-aware language model alignment [[Paper]](https://arxiv.org/abs/2412.19792) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* LIMR: Less is More for RL Scaling [[Paper]](https://arxiv.org/abs/2502.11886) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* A Survey on Feedback-based Multi-step Reasoning for Large Language Models on Mathematics [[Paper]](https://arxiv.org/abs/2502.143) ![](https://img.shields.io/badge/arXiv-2025.02-red)
## Part 4: MCTS/Tree Search
* On the Convergence Rate of MCTS for the Optimal Value Estimation in Markov Decision Processes [[Paper]](https://ieeexplore.ieee.org/abstract/document/10870057/) ![](https://img.shields.io/badge/IEEE_TAC-2025-blue)
* Search-o1: Agentic Search-Enhanced Large Reasoning Models [[Paper]](https://arxiv.org/abs/2501.05366) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep Thinking [[Paper]](https://arxiv.org/abs/2501.04519) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* ReST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search [[Paper]](https://arxiv.org/abs/2406.03816) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Forest-of-Thought: Scaling Test-Time Compute for Enhancing LLM Reasoning [[Paper]](https://arxiv.org/abs/2412.09078) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs [[Paper]](https://arxiv.org/abs/2412.18925) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search [[Paper]](https://arxiv.org/abs/2412.18319) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Proposing and solving olympiad geometry with guided tree search [[Paper]](https://arxiv.org/abs/2412.10673) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* SPaR: Self-Play with Tree-Search Refinement to Improve Instruction-Following in Large Language Models [[Paper]](https://arxiv.org/abs/2412.11605) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Towards Intrinsic Self-Correction Enhancement in Monte Carlo Tree Search Boosted Reasoning via Iterative Preference Learning [[Paper]](https://arxiv.org/abs/2412.17397) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* CodeTree: Agent-guided Tree Search for Code Generation with Large Language Models [[Paper]](https://arxiv.org/abs/2411.04329) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* GPT-Guided Monte Carlo Tree Search for Symbolic Regression in Financial Fraud Detection [[Paper]](https://arxiv.org/abs/2411.04459) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* MC-NEST -- Enhancing Mathematical Reasoning in Large Language Models with a Monte Carlo Nash Equilibrium Self-Refine Tree [[Paper]](https://arxiv.org/abs/2411.15645) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* Marco-o1: Towards Open Reasoning Models for Open-Ended Solutions [[Paper]](https://arxiv.org/abs/2411.14405) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* SRA-MCTS: Self-driven Reasoning Augmentation with Monte Carlo Tree Search for Code Generation [[Paper]](https://arxiv.org/abs/2411.11053) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* Don’t throw away your value model! Generating more preferable text with Value-Guided Monte-Carlo Tree Search decoding [[Paper]](https://openreview.net/forum?id=kh9Zt2Ldmn#discussion) ![](https://img.shields.io/badge/CoLM-2024-blue)
* AFlow: Automating Agentic Workflow Generation [[Paper]](https://arxiv.org/abs/2410.10762) ![](https://img.shields.io/badge/arXiv-2024.10-red)
* Interpretable Contrastive Monte Carlo Tree Search Reasoning [[Paper]](https://arxiv.org/abs/2410.01707) ![](https://img.shields.io/badge/arXiv-2024.10-red)
* LLaMA-Berry: Pairwise Optimization for O1-like Olympiad-Level Mathematical Reasoning [[Paper]](https://arxiv.org/abs/2410.02884) ![](https://img.shields.io/badge/arXiv-2024.10-red)
* Towards Self-Improvement of LLMs via MCTS: Leveraging Stepwise Knowledge with Curriculum Preference Learning [[Paper]](https://arxiv.org/abs/2410.06508) ![](https://img.shields.io/badge/arXiv-2024.10-red)
* TreeBoN: Enhancing Inference-Time Alignment with Speculative Tree-Search and Best-of-N Sampling [[Paper]](https://arxiv.org/abs/2410.16033) ![](https://img.shields.io/badge/arXiv-2024.10-red)
* Understanding When Tree of Thoughts Succeeds: Larger Models Excel in Generation, Not Discrimination [[Paper]](https://arxiv.org/abs/2410.17820) ![](https://img.shields.io/badge/arXiv-2024.10-red)
* RethinkMCTS: Refining Erroneous Thoughts in Monte Carlo Tree Search for Code Generation [[Paper]](https://arxiv.org/abs/2409.09584) ![](https://img.shields.io/badge/arXiv-2024.09-red)
* Strategist: Learning Strategic Skills by LLMs via Bi-Level Tree Search [[Paper]](https://arxiv.org/abs/2408.10635) ![](https://img.shields.io/badge/arXiv-2024.08-red)
* LiteSearch: Efficacious Tree Search for LLM [[Paper]](https://arxiv.org/abs/2407.00320) ![](https://img.shields.io/badge/arXiv-2024.07-red)
* Tree Search for Language Model Agents [[Paper]](https://arxiv.org/abs/2407.01476) ![](https://img.shields.io/badge/arXiv-2024.07-red)
* Uncertainty-Guided Optimization on Large Language Model Search Trees [[Paper]](https://arxiv.org/abs/2407.03951) ![](https://img.shields.io/badge/arXiv-2024.07-red)
* Accessing GPT-4 level Mathematical Olympiad Solutions via Monte Carlo Tree Self-refine with LLaMa-3 8B [[Paper]](https://arxiv.org/abs/2406.07394) ![](https://img.shields.io/badge/arXiv-2024.06-red)
* Beyond A*: Better Planning with Transformers via Search Dynamics Bootstrapping [[Paper]](https://openreview.net/forum?id=rviGTsl0oy) ![](https://img.shields.io/badge/ICLR_WorkShop-2024-blue)
* LLM Reasoners: New Evaluation, Library, and Analysis of Step-by-Step Reasoning with Large Language Models [[Paper]](https://openreview.net/forum?id=h1mvwbQiXR) ![](https://img.shields.io/badge/ICLR_WorkShop-2024-blue)
* AlphaMath Almost Zero: process Supervision without process [[Paper]](https://arxiv.org/abs/2405.03553) ![](https://img.shields.io/badge/arXiv-2024.05-red)
* Generating Code World Models with Large Language Models Guided by Monte Carlo Tree Search [[Paper]](https://arxiv.org/abs/2405.15383) ![](https://img.shields.io/badge/arXiv-2024.05-red)
* MindStar: Enhancing Math Reasoning in Pre-trained LLMs at Inference Time [[Paper]](https://arxiv.org/abs/2405.16265) ![](https://img.shields.io/badge/arXiv-2024.05-red)
* Monte Carlo Tree Search Boosts Reasoning via Iterative Preference Learning [[Paper]](https://arxiv.org/abs/2405.00451) ![](https://img.shields.io/badge/arXiv-2024.05-red)
* Stream of Search (SoS): Learning to Search in Language [[Paper]](https://arxiv.org/abs/2404.03683) ![](https://img.shields.io/badge/arXiv-2024.04-red)
* Toward Self-Improvement of LLMs via Imagination, Searching, and Criticizing [[Paper]](https://arxiv.org/abs/2404.12253) ![](https://img.shields.io/badge/arXiv-2024.04-red)
* Uncertainty of Thoughts: Uncertainty-Aware Planning Enhances Information Seeking in Large Language Models [[Paper]](https://openreview.net/forum?id=CVpuVe1N22&noteId=aTI8PGpO47) ![](https://img.shields.io/badge/NeurIPS-2024-blue)
* Reasoning with Language Model is Planning with World Model [[Paper]](https://aclanthology.org/2023.emnlp-main.507/) ![](https://img.shields.io/badge/EMNLP-2023-blue)
* Large Language Models as Commonsense Knowledge for Large-Scale Task Planning [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/65a39213d7d0e1eb5d192aa77e77eeb7-Abstract-Conference.html) ![](https://img.shields.io/badge/NeurIPS-2023-blue)
* ALPHAZERO-LIKE TREE-SEARCH CAN GUIDE LARGE LANGUAGE MODEL DECODING AND TRAINING [[Paper]](https://openreview.net/forum?id=PJfc4x2jXY) ![](https://img.shields.io/badge/NeurIPS_WorkShop-2023-blue)
* Alphazero-like Tree-Search can Guide Large Language Model Decoding and Training [[Paper]](https://openreview.net/forum?id=PJfc4x2jXY) ![](https://img.shields.io/badge/NeurIPS_WorkShop-2023-blue)
* MAKING PPO EVEN BETTER: VALUE-GUIDED MONTE-CARLO TREE SEARCH DECODING [[Paper]](https://arxiv.org/abs/2309.15028) ![](https://img.shields.io/badge/arXiv-2023.09-red)
* Leveraging Constrained Monte Carlo Tree Search to Generate Reliable Long Chain-of-Thought for Mathematical Reasoning [[Paper]](https://arxiv.org/abs/2502.11169) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Hypothesis-Driven Theory-of-Mind Reasoning for Large Language Models [[Paper]](https://arxiv.org/abs/2502.11881) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Fine-grained Conversational Decoding via Isotropic and Proximal Search [[Paper]](https://aclanthology.org/2023.emnlp-main.5/) ![](https://img.shields.io/badge/EMNLP-2023-blue)
* Control-DAG: Constrained Decoding for Non-Autoregressive Directed Acyclic T5 using Weighted Finite State Automata [[Paper]](https://aclanthology.org/2024.naacl-short.42/) ![](https://img.shields.io/badge/NAACL-2024-blue)
* Look-back Decoding for Open-Ended Text Generation [[Paper]](https://aclanthology.org/2023.emnlp-main.66/) ![](https://img.shields.io/badge/EMNLP-2023-blue)
* PairJudge RM: Perform Best-of-N Sampling with Knockout Tournament [[Paper]](https://arxiv.org/abs/2501.13007) ![](https://img.shields.io/badge/arXiv-2025.01-red)
## Part 5: Self-Training / Self-Improve
* Small LLMs Can Master Reasoning with Self-Evolved Deep Thinking (Rstar-Math) [[Paper]](https://arxiv.org/abs/2501.04519) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* ReST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search [[Paper]](https://arxiv.org/abs/2406.03816) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Recursive Introspection: Teaching Language Model Agents How to Self-Improve [[Paper]](https://openreview.net/forum?id=DRC9pZwBwR) ![](https://img.shields.io/badge/NeurIPS-2024-blue)
* B-STaR: Monitoring and Balancing Exploration and Exploitation in Self-Taught Reasoner [[Paper]](https://arxiv.org/abs/2412.17256) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* ReST-EM: Beyond Human Data: Scaling Self-Training for Problem-Solving with Language Models [[Paper]](https://openreview.net/forum?id=lNAyUngGFK) ![](https://img.shields.io/badge/TMLR-2024-blue)
* ReFT: Representation Finetuning for Language Models [[Paper]](https://aclanthology.org/2024.acl-long.410.pdf) ![](https://img.shields.io/badge/ACL-2024-blue)
* Interactive Evolution: A Neural-Symbolic Self-Training Framework for Large Language Models [[Paper]](https://arxiv.org/abs/2406.11736) ![](https://img.shields.io/badge/arXiv-2024.06-red)
* CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing [[Paper]](https://openreview.net/forum?id=Sx038qxjek) ![](https://img.shields.io/badge/ICLR-2024-blue)
* Enhancing Large Vision Language Models with Self-Training on Image Comprehension [[Paper]](https://arxiv.org/abs/2405.19716) ![](https://img.shields.io/badge/arXiv-2024.05-red)
* Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking [[Paper]](https://arxiv.org/abs/2403.09629) ![](https://img.shields.io/badge/arXiv-2024.03-red)
* V-star: Training Verifiers for Self-Taught Reasoners [[Paper]](https://arxiv.org/abs/2402.06457) ![](https://img.shields.io/badge/arXiv-2024.02-red)
* Self-Refine: Iterative Refinement with Self-Feedback [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/91edff07232fb1b55a505a9e9f6c0ff3-Abstract-Conference.html) ![](https://img.shields.io/badge/NeurIPS-2023-blue)
* ReST: Reinforced Self-Training for Language Modeling [[Paper]](https://arxiv.org/abs/2308.08998) ![](https://img.shields.io/badge/arXiv-2023.08-red)
* STaR: Bootstrapping Reasoning With Reasoning [[Paper]](https://arxiv.org/abs/2203.14465) ![](https://img.shields.io/badge/arXiv-2022.05-red)
* Expert Iteration: Thinking Fast and Slow with Deep Learning and Tree Search [[Paper]](https://proceedings.neurips.cc/paper/2017/hash/d8e1344e27a5b08cdfd5d027d9b8d6de-Abstract.html) ![](https://img.shields.io/badge/NeurIPS-2017-blue)
* Self-Improvement in Language Models: The Sharpening Mechanism [[Paper]](https://arxiv.org/abs/2412.01951) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Enabling Scalable Oversight via Self-Evolving Critic [[Paper]](https://arxiv.org/abs/2501.05727) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* S<sup>2</sup>R: Teaching LLMs to Self-verify and Self-correct via Reinforcement Learning [[Paper]](https://www.arxiv.org/abs/2502.12853) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* ProgCo: Program Helps Self-Correction of Large Language Models [[Paper]](https://arxiv.org/abs/2501.01264) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* Self-Refine: Iterative Refinement with Self-Feedback [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/91edff07232fb1b55a505a9e9f6c0ff3-Abstract-Conference.html) ![](https://img.shields.io/badge/NeurIPS-2023-blue)
* SelfCheck: Using LLMs to Zero-Shot Check Their Own Step-by-Step Reasoning [[Paper]](https://openreview.net/forum?id=pTHfApDakA) ![](https://img.shields.io/badge/ICLR_WorkShop-2024-blue)
* CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing [[Paper]](https://openreview.net/forum?id=Sx038qxjek) ![](https://img.shields.io/badge/ICLR_WorkShop-2024-blue)
* Large Language Models are Better Reasoners with Self-Verification [[Paper]](/aclanthology.org/2023.findings-emnlp.167/) ![](https://img.shields.io/badge/ACL_Findings-2023-blue)
* Self-Evaluation Guided Beam Search for Reasoning [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/81fde95c4dc79188a69ce5b24d63010b-Abstract-Conference.html) ![](https://img.shields.io/badge/NeurIPS-2023-blue)
* Learning From Correctness Without Prompting Makes LLM Efficient Reasoner [[Paper]](https://openreview.net/forum?id=dcbNzhVVQj#discussion) ![](https://img.shields.io/badge/CoLM-2024-blue)
## Part 6: Reflection
* rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep Thinking [[Paper]](https://arxiv.org/abs/2501.04519) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* RedStar: Does Scaling Long-CoT Data Unlock Better Slow-Reasoning Systems? [[Paper]](https://arxiv.org/abs/2501.11284) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs [[Paper]](https://arxiv.org/abs/2412.18925) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search [[Paper]](https://arxiv.org/abs/2412.18319) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* AtomThink: A Slow Thinking Framework for Multimodal Mathematical Reasoning [[Paper]](https://arxiv.org/abs/2411.18478) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* Beyond Examples: High-level Automated Reasoning Paradigm in In-Context Learning via MCTS [[Paper]](https://arxiv.org/abs/2411.11930) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* Marco-o1: Towards Open Reasoning Models for Open-Ended Solutions [[Paper]](https://arxiv.org/abs/2411.14405) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* LLaVA-o1: Let Vision Language Models Reason Step-by-Step [[Paper]](https://arxiv.org/abs/2411.10440) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* Vision-Language Models Can Self-Improve Reasoning via Reflection [[Paper]](https://arxiv.org/abs/2411.00855) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* LLaMA-Berry: Pairwise Optimization for O1-like Olympiad-Level Mathematical Reasoning [[Paper]](https://arxiv.org/abs/2410.02884) ![](https://img.shields.io/badge/arXiv-2024.10-red)
* Mutual Reasoning Makes Smaller LLMs Stronger Problem-Solvers [[Paper]](https://arxiv.org/abs/2408.06195) ![](https://img.shields.io/badge/arXiv-2024.08-red)
* Refiner: Restructure Retrieved Content Efficiently to Advance Question-Answering Capabilities [[Paper]](https://aclanthology.org/2024.findings-emnlp.500/) ![](https://img.shields.io/badge/EMNLP-2024-blue)
* Reflection-Tuning: An Approach for Data Recycling [[Paper]](https://arxiv.org/abs/2310.11716) ![](https://img.shields.io/badge/arXiv-2023.10-red)
* Learning From Mistakes Makes LLM Better Reasoner [[Paper]](https://arxiv.org/abs/2310.20689) ![](https://img.shields.io/badge/arXiv-2023.10-red)
* SelfCheck: Using LLMs to Zero-Shot Check Their Own Step-by-Step Reasoning [[Paper]](https://arxiv.org/abs/2308.00436) ![](https://img.shields.io/badge/arXiv-2023.08-red)
## Part 7: Efficient System2
* O1-Pruner: Length-Harmonizing Fine-Tuning for O1-Like Reasoning Pruning [[Paper]](https://arxiv.org/abs/2501.12570) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* Think More, Hallucinate Less: Mitigating Hallucinations via Dual Process of Fast and Slow Thinking [[Paper]](https://arxiv.org/abs/2501.01306) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* DynaThink: Fast or Slow? A Dynamic Decision-Making Framework for Large Language Models [[Paper]](https://arxiv.org/abs/2407.01009) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* B-STaR: Monitoring and Balancing Exploration and Exploitation in Self-Taught Reasoner [[Paper]](https://arxiv.org/abs/2412.17256) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Token-Budget-Aware LLM Reasoning [[Paper]](https://arxiv.org/abs/2412.18547) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Training Large Language Models to Reason in a Continuous Latent Space [[Paper]](https://arxiv.org/abs/2412.06769) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Guiding Language Model Reasoning with Planning Tokens [[Paper]](https://arxiv.org/abs/2310.05707) ![](https://img.shields.io/badge/arXiv-2024.10-red)
* One Example Shown, Many Concepts Known! Counterexample-Driven Conceptual Reasoning in Mathematical LLMs [[Paper]](https://arxiv.org/abs/2502.10454) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Small Models Struggle to Learn from Strong Reasoners [[Paper]](https://arxiv.org/abs/2502.12143) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* TokenSkip: Controllable Chain-of-Thought Compression in LLMs [[Paper]](https://arxiv.org/abs/2502.12067) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* SoftCoT: Soft Chain-of-Thought for Efficient Reasoning with LLMs [[Paper]](https://arxiv.org/abs/2502.12134) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Dynamic Chain-of-Thought: Towards Adaptive Deep Reasoning [[Paper]](https://arxiv.org/abs/2502.10428) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Thinking Preference Optimization [[Paper]](https://arxiv.org/abs/2502.13173) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Revisiting the Test-Time Scaling of o1-like Models: Do they Truly Possess Test-Time Scaling Capabilities? [[Paper]](https://arxiv.org/abs/2502.12215) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Flow-of-Options: Diversified and Improved LLM Reasoning by Thinking Through Options [[Paper]](https://arxiv.org/abs/2502.12929) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* CodeI/O: Condensing Reasoning Patterns via Code Input-Output Prediction [[Paper]](https://arxiv.org/abs/2502.07316) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* OctoTools: An Agentic Framework with Extensible Tools for Complex Reasoning [[Paper]](https://arxiv.org/abs/2502.11271) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* LogiDynamics: Unraveling the Dynamics of Logical Inference in Large Language Model Reasoning [[Paper]](https://arxiv.org/abs/2502.11176) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Atom of Thoughts for Markov LLM Test-Time Scaling [[Paper]](https://arxiv.org/abs/2502.12018) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Efficient Long-Decoding Inference with Reasoning-Aware Attention Sparsity [[Paper]](https://arxiv.org/abs/2502.11147) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Integrating Arithmetic Learning Improves Mathematical Reasoning in Smaller Models [[Paper]](https://arxiv.org/abs/2502.12855) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Stepwise Perplexity-Guided Refinement for Efficient Chain-of-Thought Reasoning in Large Language Models [[Paper]](https://www.arxiv.org/abs/2502.13260) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Titans: Learning to Memorize at Test Time [[Paper]](https://arxiv.org/abs/2501.00663) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* MoBA: Mixture of Block Attention for Long-Context LLMs [[Paper]](https://arxiv.org/abs/2502.13189) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* AutoReason: Automatic Few-Shot Reasoning Decomposition [[Paper]](https://arxiv.org/abs/2412.06975) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Enhancing Auto-regressive Chain-of-Thought through Loop-Aligned Reasoning [[Paper]](https://arxiv.org/abs/2502.08482) ![](https://img.shields.io/badge/arXiv-2025.02-red)
## Part 8: Explainability
* Agents Thinking Fast and Slow: A Talker-Reasoner Architecture [[Paper]](https://openreview.net/forum?id=xPhcP6rbI4) ![](https://img.shields.io/badge/NeurIPS_WorkShop-2024-blue)
* What Happened in LLMs Layers when Trained for Fast vs. Slow Thinking: A Gradient Perspective [[Paper]](https://arxiv.org/abs/2410.23743) ![](https://img.shields.io/badge/arXiv-2024.10-red)
* When a Language Model is Optimized for Reasoning, Does It Still Show Embers of Autoregression? An Analysis of OpenAI o1 [[Paper]](https://arxiv.org/abs/2410.01792) ![](https://img.shields.io/badge/arXiv-2024.10-red)
* The Impact of Reasoning Step Length on Large Language Models [[Paper]](https://arxiv.org/abs/2401.04925) ![](https://img.shields.io/badge/arXiv-2024.08-red)
* Distilling System 2 into System 1 [[Paper]](https://arxiv.org/abs/2407.06023) ![](https://img.shields.io/badge/arXiv-2024.07-red)
* System 2 Attention (is something you might need too) [[Paper]](https://arxiv.org/abs/2311.11829) ![](https://img.shields.io/badge/arXiv-2023.11-red)
* SafeChain: Safety of Language Models with Long Chain-of-Thought Reasoning Capabilities [[Paper]](https://arxiv.org/abs/2502.12025) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* ThinkGuard: Deliberative Slow Thinking Leads to Cautious Guardrails [[Paper]](https://arxiv.org/abs/2502.13458) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* SafeChain: Safety of Language Models with Long Chain-of-Thought Reasoning Capabilities [[Paper]](https://arxiv.org/abs/2502.12025) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* H-CoT: Hijacking the Chain-of-Thought Safety Reasoning Mechanism to Jailbreak Large Reasoning Models, Including OpenAI o1/o3, DeepSeek-R1, and Gemini 2.0 Flash Thinking [[Paper]](https://arxiv.org/abs/2502.12893) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* BoT: Breaking Long Thought Processes of o1-like Large Language Models through Backdoor Attack [[Paper]](https://arxiv.org/abs/2502.12202) ![](https://img.shields.io/badge/arXiv-2025.02-red)
## Part 9: Multimodal Agent related Slow-Fast System
* Diving into Self-Evolving Training for Multimodal Reasoning [[Paper]](https://arxiv.org/abs/2412.17451) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* Visual Agents as Fast and Slow Thinkers [[Paper]](https://openreview.net/forum?id=ncCuiD3KJQ) ![](https://img.shields.io/badge/ICLR-2025-blue)
* Virgo: A Preliminary Exploration on Reproducing o1-like MLLM [[Paper]](https://arxiv.org/abs/2501.01904) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* Scaling Inference-Time Search With Vision Value Model for Improved Visual Comprehension [[Paper]](https://arxiv.org/pdf/2412.03704) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* Slow Perception: Let's Perceive Geometric Figures Step-by-Step [[Paper]](https://arxiv.org/abs/2412.20631) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* AtomThink: A Slow Thinking Framework for Multimodal Mathematical Reasoning [[Paper]](https://arxiv.org/abs/2411.11930) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* LLaVA-o1: Let Vision Language Models Reason Step-by-Step [[Paper]](https://arxiv.org/abs/2411.10440) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* Vision-Language Models Can Self-Improve Reasoning via Reflection [[Paper]](https://arxiv.org/abs/2411.00855) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* I Think, Therefore I Diffuse: Enabling Multimodal In-Context Reasoning in Diffusion Models [[Paper]](https://arxiv.org/abs/2502.10458) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* RAG-Gym: Optimizing Reasoning and Search Agents with Process Supervision [[Paper]](https://arxiv.org/abs/2502.13957) ![](https://img.shields.io/badge/arXiv-2025.02-red)
## Part 10: Benchmark and Datasets
* Big-Math: A Large-Scale, High-Quality Math Dataset for Reinforcement Learning in Language Models [[Paper]](https://arxiv.org/abs/2502.17387) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* PRMBench: A Fine-grained and Challenging Benchmark for Process-Level Reward Models [[Paper]](https://arxiv.org/abs/2501.03124) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* MR-Ben: A Meta-Reasoning Benchmark for Evaluating System-2 Thinking in LLMs [[Paper]](https://openreview.net/forum?id=GN2qbxZlni) ![](https://img.shields.io/badge/NeurIPS-2024-blue)
* Do NOT Think That Much for 2+3=? On the Overthinking of o1-like LLMs [[Paper]](https://arxiv.org/abs/2412.21187) ![](https://img.shields.io/badge/arXiv-2024.12-red)
* A Preliminary Study of o1 in Medicine: Are We Closer to an AI Doctor? [[Paper]](https://arxiv.org/abs/2409.15277) ![](https://img.shields.io/badge/arXiv-2024.09-red)
* EquiBench: Benchmarking Code Reasoning Capabilities of Large Language Models via Equivalence Checking [[Paper]](https://arxiv.org/abs/2502.12466) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* SuperGPQA: Scaling LLM Evaluation across 285 Graduate Disciplines [[Paper]](https://arxiv.org/abs/2502.14739) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* Multimodal RewardBench: Holistic Evaluation of Reward Models for Vision Language Models [[Paper]](https://arxiv.org/abs/2502.14191) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* FrontierMath: A Benchmark for Evaluating Advanced Mathematical Reasoning in AI [[Paper]](https://arxiv.org/abs/2411.04872) ![](https://img.shields.io/badge/arXiv-2024.11-red)
* Evaluation of OpenAI o1: Opportunities and Challenges of AGI [[Paper]](https://arxiv.org/abs/2409.18486) ![](https://img.shields.io/badge/arXiv-2024.09-red)
* MATH-Perturb: Benchmarking LLMs' Math Reasoning Abilities against Hard Perturbations [[Paper]](https://arxiv.org/abs/2502.06453) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* LongReason: A Synthetic Long-Context Reasoning Benchmark via Context Expansion [[Paper]](https://arxiv.org/abs/2501.15089) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* Humanity's Last Exam [[Paper]](https://arxiv.org/abs/2501.14249) ![](https://img.shields.io/badge/arXiv-2025.01-red)
* RM-Bench: Benchmarking Reward Models of Language Models with Subtlety and Style [[Paper]](https://openreview.net/forum?id=QEHrmQPBdd)![](https://img.shields.io/badge/ICLR(Oral)-2025.01-blue)

## Part 11: Reasoning and Safety
* OverThink: Slowdown Attacks on Reasoning LLMs [[Paper]](https://arxiv.org/abs/2502.02542) ![](https://img.shields.io/badge/arXiv-2025.02-red)
* GuardReasoner: Towards Reasoning-based LLM Safeguards [[Paper]](https://arxiv.org/abs/2501.18492) ![](https://img.shields.io/badge/arXiv-2025.01-red)

## Citation
If you find this work useful, welcome to cite us.
```bib
@misc{li202512surveyreasoning,
      title={From System 1 to System 2: A Survey of Reasoning Large Language Models}, 
      author={Zhong-Zhi Li and Duzhen Zhang and Ming-Liang Zhang and Jiaxin Zhang and Zengyan Liu and Yuxuan Yao and Haotian Xu and Junhao Zheng and Pei-Jie Wang and Xiuyi Chen and Yingying Zhang and Fei Yin and Jiahua Dong and Zhijiang Guo and Le Song and Cheng-Lin Liu},
      year={2025},
      eprint={2502.17419},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2502.17419}, 
}
```

<!-- omit in toc -->
## ⭐ Star History

<a href="https://star-history.com/#zzli2022/Awesome-System2-Reasoning-LLM&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=zzli2022/Awesome-System2-Reasoning-LLM&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=zzli2022/Awesome-System2-Reasoning-LLM&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=zzli2022/Awesome-System2-Reasoning-LLM&type=Date" />
 </picture>
</a>
