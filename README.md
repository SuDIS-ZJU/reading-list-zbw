# LLM Serving Papers
**Last Update: 2024-09-11**
- [LLM Serving Papers](#llm-serving-papers)
  - [Survey](#survey)
  - [Offloading](#offloading)

## Survey
|Paper|Code|Category|Abstract
|--|--|--|--|
[[2407.12391] LLM Inference Serving: Survey of Recent Advances and Opportunities (arxiv.org)](https://arxiv.org/abs/2407.12391)|||Focus on system-level enhancements without altering LLM decoding algorithms, including memory (KV cache management), compute (scheduling), scalability (cloud-LLM) and emerging fields|
[[2407.14645] Performance Modeling and Workload Analysis of Distributed Large Language Model Training and Inference (arxiv.org)](https://arxiv.org/abs/2407.14645)||||
[[2404.14294] A Survey on Efficient Inference for Large Language Models (arxiv.org)](https://arxiv.org/abs/2404.14294)||||
[[2402.16363] LLM Inference Unveiled: Survey and Roofline Model Insights (arxiv.org)](https://arxiv.org/abs/2402.16363)|https://github.com/hahnyuan/LLM-Viewer||Framework based on Roofline model, profiling different hardware and inference configs. Cover model compression, algorithm, system and hardware optimizations|
[The CAP Principle for LLM Serving: A Survey of Long-Context Large Language Model Serving](https://arxiv.org/pdf/2405.11299)||Long Context||

## Offloading
|Paper|Code|Category|Abstract
|--|--|--|--|
[[2303.06865] FlexGen: High-Throughput Generative Inference of Large Language Models with a Single GPU (arxiv.org)](https://arxiv.org/abs/2303.06865)|https://github.com/FMInference/FlexiGen||latency-insensitive tasks with batch processing. overcome inefficiency in offloading with GPU,CPU,Disk. consider what to offload, where to offload in memory hierarchy, when to offload during inference|