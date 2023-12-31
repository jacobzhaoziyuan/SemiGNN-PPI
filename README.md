

<div align="center">

# SemiGNN-PPI: Self-Ensembling Multi-Graph Neural Network for Efficient and Generalizable Protein-Protein Interaction Prediction

[![IJCAI2023](https://img.shields.io/badge/arXiv-2305.08316-blue)](https://arxiv.org/abs/2305.08316)
[![IJCAI2023](https://img.shields.io/badge/Conference-IJCAI2023-green)](https://www.ijcai.org/proceedings/2023/554)



</div>

Pytorch implementation of our method for IJCAI 2023 paper: "SemiGNN-PPI: Self-Ensembling Multi-Graph Neural Network for Efficient and Generalizable Protein–Protein Interaction Prediction". (Our code will be release.)

## Abstract
Protein-protein interactions (PPIs) are crucial in various biological processes and their study has significant implications for drug development and disease diagnosis. Existing deep learning methods suffer from significant performance degradation under complex real-world scenarios due to various factors, e.g., label scarcity and domain shift. In this paper, we propose a self-ensembling multi-graph neural network (SemiGNN-PPI) that can effectively predict PPIs while being both efficient and generalizable. In SemiGNN-PPI, we not only model the protein correlations but explore the label dependencies by constructing and processing multiple graphs from the perspectives of both features and labels in the graph learning process. We further marry GNN with Mean Teacher to effectively leverage unlabeled graph-structured PPI data for self-ensemble graph learning. We also design multiple graph consistency constraints to align the student and teacher graphs in the feature embedding space, enabling the student model to better learn from the teacher model by incorporating more relationships. Extensive experiments on PPI datasets of different scales with different evaluation settings demonstrate that SemiGNN-PPI outperforms state-of-the-art PPI prediction methods, particularly in challenging scenarios such as training with limited annotations and testing on unseen data.

<p align="center">
<img src="https://github.com/jacobzhaoziyuan/SemiGNN-PPI/blob/main/assets/archi_min.png" width="800">
</p>







## Citation
If you find the codebase useful for your research, please cite the paper:
```
@inproceedings{ijcai2023p554,
  title     = {SemiGNN-PPI: Self-Ensembling Multi-Graph Neural Network for Efficient and Generalizable Protein–Protein Interaction Prediction},
  author    = {Zhao, Ziyuan and Qian, Peisheng and Yang, Xulei and Zeng, Zeng and Guan, Cuntai and Tam, Wai Leong and Li, Xiaoli},
  booktitle = {Proceedings of the Thirty-Second International Joint Conference on
               Artificial Intelligence, {IJCAI-23}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},
  editor    = {Edith Elkind},
  pages     = {4984--4992},
  year      = {2023},
  month     = {8},
  note      = {Main Track},
  doi       = {10.24963/ijcai.2023/554},
  url       = {https://doi.org/10.24963/ijcai.2023/554},
}

```
