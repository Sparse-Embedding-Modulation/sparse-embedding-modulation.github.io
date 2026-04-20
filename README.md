# SEM: Sparse Embedding Modulation for Post-Hoc Debiasing of Vision-Language Models

> **CVPR Findings 2026**

**[Quentin Guimard](https://mardgui.github.io/)<sup>1,\*</sup> · [Federico Bartsch](https://www.linkedin.com/in/federico-bartsch/)<sup>1,\*</sup> · [Simone Caldarella](https://simonecaldarella.github.io/)<sup>1</sup> · [Rahaf Aljundi](https://www.linkedin.com/in/rahaf-aljundi/)<sup>2</sup> · [Elisa Ricci](https://eliricci.eu/)<sup>1,3</sup> · [Massimiliano Mancini](https://mancinimassimiliano.github.io/)<sup>1</sup>**

<sup>**1**</sup>University of Trento · <sup>**2**</sup>Toyota Motor Europe · <sup>**3**</sup>Fondazione Bruno Kessler

_<sup>\*</sup>Equal contribution_

---

[![Project Page](https://img.shields.io/badge/Project%20Page-sparse--embedding--modulation.github.io-blue?style=flat-square)](https://sparse-embedding-modulation.github.io/)
[![Paper](https://img.shields.io/badge/arXiv-2603.19028-b31b1b?style=flat-square)](https://arxiv.org/abs/2603.19028)
[![Code](https://img.shields.io/badge/Code-GitHub-green?style=flat-square)](https://github.com/mardgui/SEM)
[![License](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by-sa/4.0/)

---

## About This Repository

> **This is the repository for the [project page](https://sparse-embedding-modulation.github.io/) only.**
> The SEM code is available at **[github.com/mardgui/SEM](https://github.com/mardgui/SEM)**.

---

## Abstract

Models that bridge vision and language, such as CLIP, are key components of multimodal AI. Yet, their large-scale, uncurated training data introduces severe **social and spurious biases**. Existing post-hoc debiasing methods often operate directly in the dense CLIP embedding space, where bias and task-relevant information are highly _entangled_—making it difficult to remove bias without degrading semantic fidelity.

In this work, we propose **Sparse Embedding Modulation (SEM)** — a post-hoc, zero-shot debiasing framework that operates in a Sparse Autoencoder (SAE) latent space. By decomposing CLIP text embeddings into _disentangled_ features, SEM can pinpoint and modulate bias-relevant neurons while safely preserving query-relevant ones.

This approach enables more precise, non-linear interventions. Across four benchmark datasets and two CLIP backbones, SEM achieves **substantial fairness gains** in retrieval and zero-shot classification, demonstrating that sparse latent representations provide a highly effective foundation for debiasing vision-language models.

---

## BibTeX

```bibtex
@inproceedings{guimardbartsch2026sem,
  title={{SEM: Sparse Embedding Modulation for Post-Hoc Debiasing of Vision-Language Models}},
  author={Guimard, Quentin and Bartsch, Federico and Caldarella, Simone and Aljundi, Rahaf and Ricci, Elisa and Mancini, Massimiliano},
  booktitle={Findings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2026}
}
```

---

## Website

This site is built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template) and licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
