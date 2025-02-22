# Judging the Judges: A Collection of LLM-Generated Relevance Judgements

<div align="center">

  [![arxiv-link](https://img.shields.io/badge/Paper-PDF-red?style=flat&logo=arXiv&logoColor=red)](https://arxiv.org/abs/2502.13908)
  [![made-with-pytorch](https://img.shields.io/badge/Made%20with-Python-brightgreen)](https://www.python.org/)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
</div>

## Abstract
Using Large Language Models (LLMs) for relevance assessments offers promising opportunities to improve Information Retrieval (IR), Natural Language Processing (NLP), and related fields. Indeed, LLMs hold the promise of allowing IR experimenters to build evaluation collections with a fraction of the manual human labor currently required. This could help with fresh topics on which there is still limited knowledge and could mitigate the challenges of evaluating ranking systems in low-resource scenarios, where it is challenging to find human annotators. Given the fast-paced recent developments in the domain, many questions concerning LLMs as assessors are yet to be answered. Among the aspects that require further investigation, we can list the impact of various components in a relevance judgment generation pipeline, such as the prompt used or the LLM chosen.
This paper benchmarks and reports on the results of a large-scale automatic relevance judgment evaluation, the LLMJudge challenge at SIGIR 2024, where different relevance assessment approaches were proposed. In detail, we release and benchmark 42 LLM-generated labels of the TREC 2023 Deep Learning track relevance judgments produced by eight international teams who participated in the challenge. Given their diverse nature, these automatically generated relevance judgments can help the community not only investigate systematic biases caused by LLMs but also explore the effectiveness of ensemble models, analyze the trade-offs between different models and human assessors, and advance methodologies for improving automated evaluation techniques. The released resource is available at the following link: [LLMJudge-benchmark](https://llm4eval.github.io/LLMJudge-benchmark/)

## Details
This is the repository that contains source codes, prompts, and LLM-generated relevance judgments for the [LLMJudge Challenge](https://github.com/llm4eval/LLMJudge). This website is based on [Nerfies website](https://github.com/nerfies/nerfies.github.io)

## Cite
If you find LLMJudge-benchmark useful for your work please cite:
```
@misc{rahmani2025judgingjudgescollectionllmgenerated,
        title={Judging the Judges: A Collection of LLM-Generated Relevance Judgements}, 
        author={Hossein A. Rahmani and Clemencia Siro and Mohammad Aliannejadi and Nick Craswell and Charles L. A. Clarke and Guglielmo Faggioli and Bhaskar Mitra and Paul Thomas and Emine Yilmaz},
        year={2025},
        eprint={2502.13908},
        archivePrefix={arXiv},
        primaryClass={cs.IR},
        url={https://arxiv.org/abs/2502.13908}, 
  }
```
