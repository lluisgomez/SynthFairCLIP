# FairCLIP
Synthetic data for CLIP debiasing

## About

**SynthFairCLIP** is a research initiative focused on fair vision–language models.

We study how to reduce bias in CLIP-style models by combining:

- **Real data** from large-scale datasets such as DataComp/CommonPool.
- **Synthetic data** generated with state-of-the-art diffusion models.
- **Curation and balancing** of demographic attributes across professions, activities and contexts.

---

### What we release

- **CLIP models** trained on hybrid real–synthetic data.
- **Large-scale WebDataset shards** of synthetic / hybrid image–text data.
- **Eval tools and benchmarks** for analysing bias and fairness in CLIP-like models.

[![Hugging Face - Models and Datasets](https://img.shields.io/badge/🤗%20HuggingFace-SynthFairCLIP-purple)](https://huggingface.co/SynthFairCLIP)
[![GitHub – evaluation tools](https://img.shields.io/badge/GitHub-Evaluation%20Tools-black?logo=github)](https://github.com/lluisgomez/SynthFairCLIP/tree/main/evals)


If you use our resources, please consider citing the SynthFairCLIP project.

---

### Acknowledgement

We acknowledge EuroHPC JU for awarding the project ID EHPC-AI-2024A02-040 access to MareNostrum 5 hosted at BSC-CNS.
