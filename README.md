# Multimodal-Conditioned Latent Diffusion Models for Fashion Image Editing
[**Alberto Baldrati**](https://scholar.google.com/citations?hl=en&user=I1jaZecAAAAJ)**\***,
[**Davide Morelli**](https://scholar.google.com/citations?user=UJ4D3rYAAAAJ&hl=en)**\***,
[**Marcella Cornia**](https://scholar.google.com/citations?hl=en&user=DzgmSJEAAAAJ),
[**Marco Bertini**](https://scholar.google.com/citations?user=SBm9ZpYAAAAJ&hl=en),
[**Rita Cucchiara**](https://scholar.google.com/citations?hl=en&user=OM3sZEoAAAAJ)

**\*** Equal contribution.

<!-- [![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)]() -->
[![GitHub Stars](https://img.shields.io/github/stars/aimagelab/Ti-MGD?style=social)](https://github.com/aimagelab/Ti-MGD)

This is the **official repository** for the [**paper**]() "*Multimodal-Conditioned Latent Diffusion Models for Fashion Image Editing*".

**Code coming soon**

## Overview

>**Abstract**: <br>
> Fashion illustration is a crucial medium for designers to convey their creative vision and transform design concepts into tangible representations that showcase the interplay between clothing and the human body. In the context of fashion design, computer vision techniques have the potential to enhance and streamline the design process. Departing from prior research primarily focused on virtual try-on, this paper tackles the task of multimodal-conditioned fashion image editing. Our approach aims to generate human-centric fashion images guided by multimodal prompts, including text, human body poses, garment sketches, and fabric textures. To address this problem, we propose extending latent diffusion models to incorporate these multiple modalities and modifying the structure of the denoising network, taking multimodal prompts as input. To condition the proposed architecture on fabric textures, we employ textual inversion techniques and let diverse cross-attention layers of the denoising network attend to textual and texture information, thus incorporating different granularity conditioning details. Given the lack of datasets for the task, we extend two existing fashion datasets, Dress Code and VITON-HD, with multimodal annotations.
Experimental evaluations demonstrate the effectiveness of our proposed approach in terms of realism and coherence concerning the provided multimodal inputs.

## Citation
If you make use of our work, please cite our paper:

<!-- ```bibtex
@inproceedings{baldrati2023multimodal,
  title={Multimodal Garment Designer: Human-Centric Latent Diffusion Models for Fashion Image Editing},
  author={Baldrati, Alberto and Morelli, Davide and Cartella, Giuseppe and Cornia, Marcella and Bertini, Marco and Cucchiara, Rita},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  year={2023}
}
``` -->

## Acknowledgements
This work has been supported by the European Commission under the PNRR-M4C2 project ``FAIR - Future Artificial Intelligence Research'' and the European Horizon 2020 Programme (grant number 951911 - AI4Media), and by the PRIN project ``CREATIVE: CRoss-modal understanding and gEnerATIon of Visual and tExtual content'' (CUP B87G22000460001), co-funded by the Italian Ministry of University.

## LICENSE
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />All material is available under [Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). You can **use, redistribute, and adapt** the material for **non-commercial purposes**, as long as you give appropriate credit by **citing our paper** and **indicate any changes** you've made.