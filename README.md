Doped Graphitic Carbon Nitride Nanosheets Datasets - Used for Chemical Environment Graph Neural Network (ChemGNN)
===



<p>
  <img src="https://github.com/EnzeXu/ChemGNN_Dataset/assets/90367338/204ec9c1-972f-4bcf-bf6c-a854c3c137b9" alt="ChemGNN_Dataset_Logo" width="100%">
</p>

(a) Structure of water molecules. (b) Structure of heptazine molecules. (c) Structure of an undoped g-C3N4 molecule.

# Contents

* [1 Introduction](#1-introduction)
* [2 Citation](#2-citation)
* [3 Structure of the Dataset](#3-structure-of-the-dataset)
* [4 Questions](#4-questions)



# 1. Introduction

[//]: # (The datasets are used for the Chemical Environment Graph Neural Network &#40;ChemGNN&#41;, designed to accelerate materials property prediction and advance new materials discovery. Graphitic carbon nitride &#40;g-C3N4&#41; and its doped variants have gained significant interest for their potential as optical materials. Accurate prediction of their band gaps is crucial for practical applications, however, traditional quantum simulation methods are computationally expensive and challenging to explore the vast space of possible doped molecular structures. The proposed ChemGNN leverages the learning ability of current graph neural networks &#40;GNNs&#41; to satisfactorily capture the characteristics of atoms' local chemical environment underlying complex molecular structures. Our benchmark results demonstrate more than 100% improvement in band gap prediction accuracy over existing GNNs on g-C3N4. Furthermore, the general ChemGNN model can precisely foresee band gaps of various doped g-C3N4 structures, making it a valuable tool for performing high-throughput prediction in materials design and development. )

The datasets were used to develop the Chemical Environment Graph Neural Network (ChemGNN), designed to accelerate material property prediction and to advance the discovery of new materials. Graphitic carbon nitride (g-C3N4) and its doped variants are of great interest for their potential applications as novel photochemical materials. As a result, the accurate prediction of their band gaps is highly desired. Nevertheless, quantum chemistry simulation methods are computationally demanding when exploring the vast chemical space to design functional doped materials. Our proposed ChemGNN leverages the learning ability of current graph neural networks (GNNs) to satisfactorily capture the characteristics of local atomic chemical environments underlying complex molecular structures. Our benchmark results demonstrate over 100% improvement in band gap prediction accuracy over existing GNNs on g-C3N4. Furthermore, this powerful ChemGNN model can precisely foresee a wide range of chemical properties of various doped g-C3N4 structures, making it a valuable tool for high-throughput screening in materials discovery. 

# 2. Citation

If you use this dataset or code on `https://github.com/chenm19/ChemGNN` for academic research, please cite the following paper and the following dataset:

Paper BibTeX:

```
@article{chen2023chemical,
  title        = {Chemical Environment Adaptive Learning for Optical Band Gap Prediction of Doped Graphitic Carbon Nitride Nanosheets},
  author       = {Chen, Chen and Xu, Enze and Yang, Defu and Yan, Chenggang and Wei, Tao and Chen, Hanning and Wei, Yong and Chen, Minghan},
  journal      = {arXiv preprint arXiv:2302.09539},
  year         = {2023}
}
```

Dataset BibTeX:

```
@misc{chen2023chemgnndatasets,
  title        = {Chemical Environment Graph Neural Network (ChemGNN) Datasets},
  author       = {Chen, Chen and Xu, Enze and Yang, Defu and Yan, Chenggang and Wei, Tao and Chen, Hanning and Wei, Yong and Chen, Minghan},
  year         = {2023},
  howpublished = {https://github.com/EnzeXu/ChemGNN_Dataset/raw/main/ChemGNN_Dataset.zip},
  publisher    = {GitHub},
  version      = {1.4.1}
}
```



# 3. Structure of the Dataset


```
ChemGNN_Dataset
┌── data/
├────── GCN/
├────────── GCN_ALL/
├────────── GCN_C1P/
├────────── GCN_C2P/
├────────── GCN_N1C/
├────────── GCN_N1P/
├────────── GCN_N2C/
├────────── GCN_N2P/
├────────── GCN_N3C/
├────────── GCN_N3P/
├────────── GCN_UNDOPED/
├────── HEPTAZINE/
├────── WATER/
```


# 4. Questions

If you have any questions, please contact xezpku@gmail.com.


