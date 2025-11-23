# SPARTA: Spectral Prompt Agnostic Adversarial Attack on Medical Vision-Language Models (MICCAI'25 - UNSURE)

> [**SPARTA: Spectral Prompt Agnostic Adversarial Attack on Medical Vision-Language Models**]()<br><br>
> [Asif Hanif](https://scholar.google.com/citations?hl=en&user=6SO2wqUAAAAJ), [Zaigham Zaheer](https://scholar.google.com/citations?user=nFxWrXEAAAAJ), [Salman Khan](https://scholar.google.com/citations?hl=en&user=M59O9lkAAAAJ),
[Fahad Shahbaz Khan](https://scholar.google.com/citations?hl=en&user=zvaeYnUAAAAJ) and [Rao Anwer](https://scholar.google.com/citations?user=_KlvMVoAAAAJ)


[comment]: [![page](https://img.shields.io/badge/Project-Page-F9D371)](https://asif-hanif.github.io/sparta/)
[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://openreview.net/forum?id=AZQrFsNe7m&referrer=%5Bthe%20profile%20of%20Salman%20Khan%5D(%2Fprofile%3Fid%3D~Salman_Khan4))




<hr />

| <img src="/media/sparta_miccai2025_unsure.png" width="800">|
|:--| 
| <p align="justify">**Overview of SPARTA** SPARTA transforms the input image into the frequency domain, where it applies learnable multiplicative noise to perturb the spectrum before reconstructing the image via inverse-transform. On the text side, it introduces learnable context within the token embedding space and prepends it to the actual text prompt. Learnable parameters are optimized within a competitive optimization framework to enhance cross-prompt transferability. </p> |

</br>
<hr />
</br>

> **Abstract** <p align="justify"><i>
Medical Vision-Language Models (Med-VLMs) are gaining popularity in different medical tasks, such as visual question-answering (VQA), captioning, and diagnosis support. However, despite their impressive performance, Med-VLMs remain vulnerable to adversarial attacks, much like their general-purpose counterparts. In this work, we investigate the cross-prompt transferability of adversarial attacks on Med-VLMs in the context of VQA. To this end, we propose a novel adversarial attack algorithm that operates in the frequency domain of images and employs a learnable text context within a max-min competitive optimization framework, enabling the generation of adversarial perturbations that are transferable across diverse prompts. Evaluation on three Med-VLMs and four Med-VQA datasets shows that our approach outperforms the baseline, achieving an average attack success rate of 67% (compared to baseline's 62%).
<br><br>
</i></p>

<!-- > <b>TLDR:</b> .. -->

</br>
<hr />
</br>

<img src="/media/sparta_alg.png" width="600">

</br>
<hr />
</br>

## Updates :rocket:
- **July 17, 2025** : Accepted in [MICCAI 2025 - UNSURE](https://unsuremiccai.github.io/) &nbsp;&nbsp; :confetti_ball: :tada:


</br>
</br>

<a name="results"/>

## Results :microscope:

<img src="/media/results_1.png" width="600">

<img src="/media/results_2.png" width="600">


</br>
</br>

<a name="citation"/>

## Citation :star:
If you find our work or this repository helpful, please consider giving a star :star: and citation.
```bibtex
@inproceedings{hanif2025sparta,
  title={SPARTA: Spectral Prompt Agnostic Adversarial Attack on Medical Vision-Language Models},
  author={Hanif, Asif and Zaheer, Zaigham and Khan, Salman and Khan, Fahad Shahbaz and Anwer, Rao},
  booktitle={International Workshop on Uncertainty for Safe Utilization of Machine Learning in Medical Imaging},
  pages={69--80},
  year={2025},
  organization={Springer}
}
```

</br>
</br>

<a name="contact"/>

## Contact :mailbox:
Should you have any questions, please create an issue on this repository or contact us at **asif.hanif@mbzuai.ac.ae**

</br>
</br>

