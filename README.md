# MARS: Multimodal Adaptation Rank Selection

**Status:** 🚧 In Preparation



## 1. Overview

MARS addresses **Modality Convergence Imbalance** in MLLM fine-tuning. By leveraging **Dual Scaling Laws** that capture the relationship between dataset size, convergence dynamics, and model capacity, MARS analytically derives the optimal rank ratio between the visual encoder and the LLM backbone.

* Paper: https://minkyoungcho.github.io/mars/
* Webpage: https://minkyoungcho.github.io/mars/


## 2. Release Roadmap

We are currently finalizing the codebase and documentation to ensure reproducibility.

**Current Status:**  
- Code cleanup and refactoring

**To Do:**  
- Documentation  
- Scripts for simple tests and reproducibility


## 3. Acknowledgements

This codebase is built upon **[Cornstarch](https://github.com/cornstarch-org/Cornstarch)**. We thank the authors for providing a robust foundation for multimodal research.


## 4. Contact & Citation

If you have questions about the paper or the upcoming release, please feel free to reach out: **Minkyoung Cho** (minkycho@umich.edu)

### Citation

If you find our theoretical framework useful, please cite our preprint:

```bibtex
@article{cho2026mars,
    title={MARS: Harmonizing Multimodal Convergence via Adaptive Rank Search},
    author={Cho, Minkyoung and Jang, Insu and Jin, Shuowei and Zhao, Zesen and Jothi, Adityan and Can, Ethem F. and Chen, Min-Hung and Mao, Z. Morley},
    journal={arXiv preprint},
    year={2026}
}
