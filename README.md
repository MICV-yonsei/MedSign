<p align="center">
  <h1 align="center">Pathology-Aware Adaptive Watermarking for Text-Driven Medical Image Synthesis</h1>
  <h3 align="center"><b>MICCAI 2025 (Early Accept)</b></h3>
  <p align="center">
    <h3 align="center">
      <a href="https://kochanha.github.io/"><strong>Chanyoung Kim*</strong></a> · 
      <a href="https://jdy77.github.io/"><strong>Dayun Ju*</strong></a> · 
      <a href="https://rubato-yeong.github.io/"><strong>Jinyeong Kim</strong></a> · 
      <a href="https://dnwjddl.github.io/"><strong>Woojung Han</strong></a> · 
      <a href="https://www.amazon.science/author/roberto-alcover-couso"><strong>Roberto Alcover-Couso</strong></a> · 
      <a href="https://micv-yonsei.github.io/#professor"><strong>Seong Jae Hwang</strong></a>
    </h3>
    <h3 align="center">
      Yonsei University ·
      Amazon 
    </h3>
  </p>
  <p align="center">
    <a href="https://arxiv.org/abs/2503.08346"><img alt='arXiv' src="https://img.shields.io/badge/arXiv-2503.08346-b31b1b.svg"></a>
  </p>
  <br>
</p>
 
<be>
<img width="1775" alt="Image" src="https://github.com/user-attachments/assets/025ae3ff-ffb7-4209-a5ca-044fa88add29" />

> #### **Pathology-Aware Adaptive Watermarking for Text-Driven Medical Image Synthesis**<be>  
>International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2025  
>Chanyoung Kim*, Dayun Ju*, Jinyeong Kim, Woojung Han, Roberto Alcover-Couso, Seong Jae Hwang   
>Yonsei University & Amazon (Work done prior to joining Amazon)
### Abstract
As recent text-conditioned diffusion models have enabled the generation of high-quality images, concerns over their potential misuse have also grown. This issue is critical in the medical domain, where text-conditioned generated medical images could enable insurance fraud or falsified records, highlighting the urgent need for reliable safeguards against unethical use. While watermarking techniques have emerged as a promising solution in general image domains, their direct application to medical imaging presents significant challenges. A key challenge is preserving fine-grained disease manifestations, as even minor distortions from a watermark may lead to clinical misinterpretation, which compromises diagnostic integrity. To overcome this gap, we present MedSign, a deep learning-based watermarking framework specifically designed for text-to-medical image synthesis, which preserves pathologically significant regions by adaptively adjusting watermark strength. Specifically, we generate a pathology localization map using cross-attention between medical text tokens and the diffusion denoising network, aggregating token-wise attention across layers, heads, and time steps. Leveraging this map, we optimize the LDM decoder to incorporate watermarking during image synthesis, ensuring cohesive integration while minimizing interference in diagnostically critical regions. Experimental results show that our MedSign preserves diagnostic integrity while ensuring watermark robustness, achieving state-of-the-art performance in image quality and detection accuracy on MIMIC-CXR and OIA-ODIR datasets.

## Citation
If you found this code useful, please cite the following paper:  
```
@InProceedings{kim2025pathology,
  title={Pathology-Aware Adaptive Watermarking for Text-Driven Medical Image Synthesis},
  author={Kim, Chanyoung and Ju, Dayun and Kim, Jinyeong and Han, Woojung and Alcover-Couso, Roberto and Hwang, Seong Jae},
  booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
  year={2025},
  organization={Springer}
}
```
