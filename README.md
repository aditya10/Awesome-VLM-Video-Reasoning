# Awesome-VLM-Video-Reasoning  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Most Video-LLMs can understand video scenes and caption them with some accuracy. However, can your video model go beyond that, and perform _complex reasoning tasks on surprising events_, _understand spatial relationships_, and _comprehend humor_? This repository contains benchmarks that challenge Multi-frame and Video-LLMs in terms of accurate perception 👁️, comprehension 💡, and reasoning 🧐 on the scene.

**Our paper:**

### 🔥 [Black Swan: Abductive and Defeasible Video Reasoning in Unpredictable Events](https://blackswan.cs.ubc.ca)


*[Aditya Chinchure](https://www.adityachinchure.com/)<sup>1,2\*</sup>,  [Sahithya Ravi](https://sahithyaravi.github.io/)<sup>1,2\*</sup>,  [Raymond Ng](https://www.cs.ubc.ca/people/raymond-ng)<sup>1</sup>,  [Vered Shwartz](https://www.cs.ubc.ca/~vshwartz/)<sup>1,2</sup>,  [Boyang Li](http://www.boyangli.org/index.html)<sup>3</sup>,  [Leonid Sigal](https://www.cs.ubc.ca/~lsigal/index.html)<sup>1,2</sup>* (<sup>\*</sup>Indicates Equal Contribution)

*<sup>1</sup>University of British Columbia, <sup>2</sup>Vector Institute for AI, <sup>3</sup>Nanyang Technological University*

<h5>  
  
 **[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Chinchure_Black_Swan_Abductive_and_Defeasible_Video_Reasoning_in_Unpredictable_Events_CVPR_2025_paper.html)** | **[arXiv](https://arxiv.org/abs/2412.05725)** | **[Project Page](https://blackswan.cs.ubc.ca)**

</h5>

## Table of Contents

- [Benchmarking Video Models](#benchmarking-video-models)
- [Contributing](#contributing)

## Benchmarking Video Models

| Paper | Venue (Year) | Link |
| :----- | :------------: | :----: |
| [**Black Swan: Abductive and Defeasible Video Reasoning in Unpredictable Events**](https://arxiv.org/abs/2412.05725) | CVPR 2025 | [Website](https://blackswan.cs.ubc.ca), [Code](https://github.com/sahithyaravi/BlackSwan) |
| [**FunQA: Towards Surprising Video Comprehension**](https://funqa-benchmark.github.io) | ECCV 2024 | [Website](https://funqa-benchmark.github.io) |
| [**UrbanVideo-Bench: Benchmarking Vision-Language Models on Embodied Intelligence with Video Data in Urban Spaces**](https://embodiedcity.github.io/UrbanVideo-Bench/) | arXiv 2025 | [Website](https://embodiedcity.github.io/UrbanVideo-Bench/) |
| [**OpenEQA: Embodied Question Answering in the Era of Foundation Models**](https://open-eqa.github.io) | CVPR 2024 | [Website](https://open-eqa.github.io) |
| [**MMBench-Video: A Long-Form Multi-Shot Benchmark for Holistic Video Understanding**](https://mmbench-video.github.io) | NeurIPS D&B 2024 | [Website](https://mmbench-video.github.io) |
| [**AGQA: A Benchmark for Compositional Spatio-Temporal Reasoning**](https://openaccess.thecvf.com/content/CVPR2021/papers/Grunde-McLaughlin_AGQA_A_Benchmark_for_Compositional_Spatio-Temporal_Reasoning_CVPR_2021_paper.pdf) | CVPR 2021 | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Grunde-McLaughlin_AGQA_A_Benchmark_for_Compositional_Spatio-Temporal_Reasoning_CVPR_2021_paper.pdf) |
| [**VCR-Bench: A Comprehensive Evaluation Framework for Video Chain-of-Thought Reasoning**](https://vlm-reasoning.github.io/VCR-Bench/) | arXiv 2025 | [Website](https://vlm-reasoning.github.io/VCR-Bench/) |
| [**V-STaR: Benchmarking Video-LLMs on Video Spatio-Temporal Reasoning**](https://v-star-bench.github.io) | arXiv 2025 | [Website](https://v-star-bench.github.io) |
| [**VRBench: A Benchmark for Multi-Step Reasoning in Long Narrative Videos**](https://vrbench.github.io) | ICCV 2025 | [Website](https://vrbench.github.io) |
| [**ANetQA: A Large-scale Benchmark for Fine-grained Compositional Reasoning over Untrimmed Videos**](https://milvlg.github.io/anetqa/) | CVPR 2023 | [Website](https://milvlg.github.io/anetqa/) |
| [**CausalStep: A Benchmark for Explicit Stepwise Causal Reasoning in Videos**](https://www.arxiv.org/abs/2507.16878) | arXiv 2025 | [Website](https://www.arxiv.org/abs/2507.16878) |
| [**CG-Bench: Clue-grounded Question Answering Benchmark for Long Video Understanding**](https://cg-bench.github.io/leaderboard/) | ICLR 2025 | [Website](https://cg-bench.github.io/leaderboard/) |
| [**MINERVA: Evaluating Complex Video Reasoning**](https://github.com/google-deepmind/neptune?tab=readme-ov-file#minerva) | arXiv 2025 | [Code](https://github.com/google-deepmind/neptune?tab=readme-ov-file#minerva) |
| [**Reasoning is All You Need for Video Generalization: A Counterfactual Benchmark with Sub-question Evaluation**](https://arxiv.org/abs/2503.10691) | ACL 2025 Findings | [Paper](https://arxiv.org/abs/2503.10691) |
| [**VideoEval-Pro: Robust and Realistic Long Video Understanding Evaluation**](https://tiger-ai-lab.github.io/VideoEval-Pro/home_page.html) | arXiv 2025 | [Website](https://tiger-ai-lab.github.io/VideoEval-Pro/home_page.html) |
| [**H2VU-Benchmark: A Comprehensive Benchmark for Hierarchical Holistic Video Understanding**](https://github.com/siriusrecco/H2VU-BenchMark) | arXiv 2025 | [Code](https://github.com/siriusrecco/H2VU-BenchMark) |
| [**Sports-QA: A Large-Scale Video Question Answering Benchmark for Complex and Professional Sports**](https://github.com/HopLee6/Sports-QA) | arXiv 2025 | [Code](https://github.com/HopLee6/Sports-QA) |
| [**ImplicitQA: Going beyond frames towards Implicit Video Reasoning**](https://huggingface.co/datasets/ucf-crcv/ImplicitQA) | arXiv 2025 | [Data](https://huggingface.co/datasets/ucf-crcv/ImplicitQA) |
| [**VRU-Accident: A Vision-Language Benchmark for Video Question Answering and Dense Captioning for Accident Scene Understanding**](https://vru-accident.github.io) | arXiv 2025 | [Data](https://huggingface.co/datasets/kyh9191/VRU-Accident) |
| [**VideoVista: A Versatile Benchmark for Video Understanding and Reasoning**](https://videovista.github.io) | arXiv 2025 | [Website](https://videovista.github.io) |
| [**STAR: A Benchmark for Situated Reasoning in Real-World Videos**](https://bobbywu.com/STAR/) | NeurIPS 2021 | [Website](https://bobbywu.com/STAR/) |
| [**Oops! Predicting Unintentional Action in Video**](https://oops.cs.columbia.edu) | CVPR 2020 | [Website](https://oops.cs.columbia.edu)) |
| [**Where Does It Exist: Spatio-Temporal Video Grounding for Multi-Form Sentences**](https://arxiv.org/abs/2001.06891) | CVPR 2020 | [Code](https://github.com/Guaranteer/VidSTG-Dataset) |
 [**MVBench: A Comprehensive Multi-modal Video Understanding Benchmark**](https://arxiv.org/abs/2311.17005) | arXiv 2023 | [Code](https://github.com/OpenGVLab/Ask-Anything) |
 | [**TVQA: Localized, Compositional Video Question Answering**](https://arxiv.org/abs/1809.01696) | EMNLP 2018 | [Website](https://tvqa.cs.unc.edu/) |
| [**Perception Test: A Diagnostic Benchmark for Multimodal Video Models**](https://arxiv.org/abs/2305.13786) | NeurIPS 2023 | [Code](https://github.com/google-deepmind/perception_test) |
| [**TempCompass: Do Video LLMs Really Understand Videos?**](https://arxiv.org/abs/2403.00476) | ACL 2024 | [Code](https://github.com/llyx97/TempCompass) |
| [**Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis**](https://arxiv.org/abs/2405.21075) | arXiv 2024 | [Code](https://github.com/BradyFU/Video-MME) |
| [**VideoHallucer: Evaluating Intrinsic and Extrinsic Hallucinations in Large Video-Language Models**](https://arxiv.org/abs/2406.16338) | arXiv 2024 | [Code](https://github.com/patrick-tssn/VideoHallucer) |
| [**TGIF-QA: Toward Spatio-Temporal Reasoning in Visual Question Answering**](https://arxiv.org/abs/1704.04497) | CVPR 2017 | [Code](https://github.com/YunseokJANG/tgif-qa) |



## Contributing

We greatly appreciate your contributions! Please create a PR with your paper added to the list, in the same format as above. 

## Cite Our Work

```
@inproceedings{chinchure2025black,
    title={Black Swan: Abductive and Defeasible Video Reasoning in Unpredictable Events},
    author={Chinchure, Aditya and Ravi, Sahithya and Ng, Raymond and Shwartz, Vered and Li, Boyang and Sigal, Leonid},
    booktitle={Proceedings of the Computer Vision and Pattern Recognition Conference},
    pages={24201--24210},
    year={2025}
  }
```

