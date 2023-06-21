# Awesome-KGLLM
A collection of papers and resources about knowledge graph enhanced large language models (KGLLM)

Recently, ChatGPT, a representative large language model (LLM), has gained considerable attention due to its powerful emergent abilities. Some researchers suggest that LLMs could potentially replace structured knowledge bases like knowledge graphs (KGs) and function as parameterized knowledge bases. However, while LLMs are proficient at learning probabilistic language patterns based on large corpus and engaging in conversations with humans, they, like previous smaller pre-trained language models (PLMs), still have difficulty in recalling facts while generating knowledge-grounded contents. To overcome these limitations, researchers have proposed enhancing data-driven PLMs with knowledge-based KGs to incorporate explicit factual knowledge into PLMs, thus improving their performance to generate texts requiring factual knowledge and providing more informed responses to user queries. Therefore, we review the studies on enhancing PLMs with KGs, detailing existing knowledge graph enhanced pre-trained language models (KGPLMs) as well as their applications. Inspired by existing studies on KGPLM, we propose to enhance LLMs with KGs by developing knowledge graph-enhanced large language models (KGLLMs). KGLLM provides a solution to enhance LLMs' factual reasoning ability, opening up new avenues for LLM research.

The organization of these papers refers to our survey: [ChatGPT is not Enough: Enhancing Large Language Models with Knowledge Graphs for Fact-aware Language Modeling](https://arxiv.org/abs/2306.11489 "悬停显示")

Please let us know if you find any mistakes or have any suggestions by email: yangly@zhejianglab.com

If you find our survey useful for your research, please cite the following paper:
```bash
@article{KGLLM,
title={ChatGPT is not Enough: Enhancing Large Language Models with Knowledge Graphs for Fact-aware Language Modeling},
author={Yang, Linyao and Chen, Hongyang and Li, Zhao and Ding, Xiao and Wu, Xindong},
journal={arXiv preprint arXiv:2306.11489},
year={2023}
}
```

## Overview
In this repository, we collect recent advances in knowledge graph enhanced large language models. According to the stage at which KGs participate in pre-training, existing methods can be categorized into before-training enhancement, during-training enhancement, and post-training enhancement methods.

<img src="figs/KGPLM-framework.png" width = "800" />

