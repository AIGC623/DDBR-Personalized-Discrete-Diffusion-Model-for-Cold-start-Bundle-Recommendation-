# DDBR: Personalized Discrete Diffusion Model for Cold-start Bundle Recommendation

This repository contains the paper source for **DDBR** (personalized **D**iscrete **D**iffusion Model for cold-start **B**undle **R**ecommendation), accepted by IEEE Transactions on Consumer Electronics.

## Abstract

New bundles that are continuously created for various marketing purposes pose a significant cold-start challenge to bundle recommendation. Existing collaborative filtering-based bundle recommendation models do not work well for this cold-start issue since they often learn bundle representations with the interactions at both the item and bundle levels. To address the cold-start challenge, we focus on recommending strict cold-start bundles for users and propose DDBR, which introduces a "Generate-then-Match" paradigm that shifts bundle recommendation from discriminative interaction modeling to generative bundle synthesis.

## Paper

The LaTeX source of the paper is available in the [`paper/`](paper/) directory.

- **Paper**: `paper/bare_jrnl_new_sample4_r2.tex`
- **Figures**: `paper/figures/`

### Compiling

```bash
cd paper
pdflatex bare_jrnl_new_sample4_r2.tex
bibtex bare_jrnl_new_sample4_r2
pdflatex bare_jrnl_new_sample4_r2.tex
pdflatex bare_jrnl_new_sample4_r2.tex
```

## Citation

If you find this work useful, please cite our paper:

```bibtex
@article{yang2026ddbr,
  title={{DDBR}: Personalized Discrete Diffusion Model for Cold-start Bundle Recommendation},
  author={Yang, Zhijing and Wang, Jin and Qin, Jinghui},
  journal={IEEE Transactions on Consumer Electronics},
  year={2026}
}
```

## Acknowledgment

This work was supported in part by the National Natural Science Foundation of China (NSFC) under Grant No. 62206314, GuangDong Basic and Applied Basic Research Foundation under Grant No. 2025A1515010454 and 2023A1515012561.
