## SVLTA: Benchmarking Vision-Language Temporal Alignment via Synthetic Video Situations
[SVLTA Homepage](https://svlta-bench.github.io/SVLTA/)  

Vision-language temporal alignment is a crucial capability for human recognition and cognition in real-world scenarios. Although existing works have designed methods to capture vision-language correlations, they are limited by benchmark issues, including biased temporal distributions, imprecise annotations, and inadequate compositionally. To achieve comprehensive evaluation and exploration, our objective is to investigate and evaluate the ability of models to achieve alignment from a temporal perspective, specifically focusing on their capacity to synchronize visual scenarios with linguistic context in a temporally coherent manner. As a preliminary, we first present the statistical analysis of existing benchmarks and reveal the existing challenges from a decomposed perspective. To this end, we introduce **SVLTA**, a synthetic, large-scale, and compositional benchmark for vision-language temporal alignment derived via a well-designed and feasible control generation method within a simulation environment. The approach considers commonsense knowledge, process permutation, and constrained filtering, which generates reasonable, diverse, and balanced data distributions for diagnostic evaluations. Our experiments reveal diagnostic insights through the evaluations in temporal question answering, distributional shift sensitiveness, and temporal alignment adaptation.



<!-- 
Reasoning from visual dynamics scenes has many real-world applications. However, existing video reasoning benchmarks are still inadequate since they were mainly designed for factual or situated reasoning and rarely involve broader knowledge in the real world.
-->

## Benchmark Overview
* 96 Human Activity Actions
* 26.2K Synthetic Video Situations
* 78K High-quality Timestamps with associated Language Sentence
* Commonsense Activity Graph
* Controllable Activity Manuscript

<div align="center">
<img src="./imgs/svlta_overview.png" width="800" >
</div>

## Data Download

To download the dataset, please refer to the [SVLTA Dataset](https://github.com/csbobby/SOK-Bench?tab=readme-ov-file#data-download) 
