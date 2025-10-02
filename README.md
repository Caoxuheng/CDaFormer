<img align="right" src="https://ars.els-cdn.com/content/image/S00313203.gif" />  


# [CaFormer: Cross-Domain Aware Deep Unfolding Transformer for Hyperspectral and Multispectral Image Fusion](https://doi.org/10.1016/j.patcog.2025.112374)
Fusing low-spatial-resolution hyperspectral images with high-spatial-resolution (HSR) multispectral images is pivotal for generating HSR hyperspectral images (HSR-HSIs). While current deep unrolling-based multi-stage frameworks have shown notable advancements due to their robustness and interpretability, they still exhibit limitations in adequately harnessing the HSI prior knowledge. This deficiency is principally attributed to three factors: (1) prior knowledge learned from training samples often overlooks target-specific characteristics; (2) insufficient feature representation within and across stages; and (3) insufficient modeling of spatial–spectral dependencies. To address these issues, we propose a novel Cross-domain-aware Transformer (CaFormer). Specifically, a cross-domain aware attention mechanism is investigated to capture intrinsic joint spatial–spectral dependencies through unified cross-domain feature representation. The attention mechanism models HSI eigenfeatures to derive spatial and spectral representations while preserving their mutual correlations. Furthermore, we introduce a Fourier Domain Perception Block to enhance structural and semantic representations by exploiting amplitude and phase components in the frequency domain, thereby strengthening feature aggregation across stages. To further improve adaptability while preserving the interpretability of deep unrolling networks, CaFormer employs a dual-stage prior learning strategy, transferring prior knowledge learned from general training data to the specific observed scene. Our experimental evaluations on four public datasets and Worldview-2 satellite images confirm that our proposed method outperformed eleven state-of-the-art methods.  

# Flowchart
**None**
# Result presentation


# Guidance

# Requirements
## Environment
`Python3.8`  
`torch 1.12`,`torchvision 0.13.0`  
`Numpy`,`Scipy`  
## Datasets
[`CAVE dataset`](https://www1.cs.columbia.edu/CAVE/databases/multispectral/), 
 [`Preprocessed CAVE dataset`](https://aistudio.baidu.com/aistudio/datasetdetail/147509).
# Note
For any questions, feel free to email me at caoxuhengcn@gmail.com.  
If you find our work useful in your research, please cite our paper ^.^

# Cite
```python
Xuheng Cao, Xuquan Wang, Xiong Dun, Yusheng Lian, Xinbin Cheng, Xiaopeng Hao,
Cross-domain-aware deep unfolding transformer for hyperspectral image super-resolution,
Pattern Recognition,
Volume 172, Part A,
2026,
112374,
ISSN 0031-3203,
https://doi.org/10.1016/j.patcog.2025.112374.
(https://www.sciencedirect.com/science/article/pii/S0031320325010350)
Abstract: Fusing low-spatial-resolution hyperspectral images with high-spatial-resolution (HSR) multispectral images is pivotal for generating HSR hyperspectral images (HSR-HSIs). While current deep unrolling-based multi-stage frameworks have shown notable advancements due to their robustness and interpretability, they still exhibit limitations in adequately harnessing the HSI prior knowledge. This deficiency is principally attributed to three factors: (1) prior knowledge learned from training samples often overlooks target-specific characteristics; (2) insufficient feature representation within and across stages; and (3) insufficient modeling of spatial–spectral dependencies. To address these issues, we propose a novel Cross-domain-aware Transformer (CaFormer). Specifically, a cross-domain aware attention mechanism is investigated to capture intrinsic joint spatial–spectral dependencies through unified cross-domain feature representation. The attention mechanism models HSI eigenfeatures to derive spatial and spectral representations while preserving their mutual correlations. Furthermore, we introduce a Fourier Domain Perception Block to enhance structural and semantic representations by exploiting amplitude and phase components in the frequency domain, thereby strengthening feature aggregation across stages. To further improve adaptability while preserving the interpretability of deep unrolling networks, CaFormer employs a dual-stage prior learning strategy, transferring prior knowledge learned from general training data to the specific observed scene. Our experimental evaluations on four public datasets and Worldview-2 satellite images confirm that our proposed method outperformed eleven state-of-the-art methods. The code is available at https://github.com/Caoxuheng/HIFtool.
Keywords: Hyperspectral image super-resolution; Image fusion; Cross-attention; Cross-domain feature
