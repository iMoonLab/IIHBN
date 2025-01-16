# Hypergraph Modeling and Semantic Computation for Brain Network Analysis

This repository provides the modeling and semantic computation processes for hypergraphs and graphs. It's also the partial source code of *Inter-Intra High-Order Brain Network for ASD Diagnosis via Functional MRIs*. Researchers interested in hypergraph computation methods can download the fully preprocessed dataset via the link provided below. Simply extract the data to the root directory to begin.

## Dataset

The preprocessed ABIDE1 dataset can be downloaded from the following link: [Download Dataset](https://drive.google.com/file/d/163MCwwc2OfQZxAuvRUBYXYhGXvQnLaFu/view?usp=sharing)

The original dataset was sourced from the [ABIDE Preprocessed Connectomes Project](https://github.com/preprocessed-connectomes-project/abide/).

> The data used in this notebook is all of ABIDE1, and only two sub-datasets were used in the original paper.

## Hypergraph Construction

We provide several methods for defining hyperedges in hypergraph structures. These definitions allow flexibility for researchers to select the most appropriate modeling approach based on their specific needs. Below are the hyperedge construction strategies supported:

- Hyperedge Definition Based on Structural Connectivity

- Hyperedge Definition Based on Functional Knowledg 

- Hyperedge Definition Based on Anatomical Structural Partitions

- Hyperedge Definitions Based on Harvard-Oxford Partitions

- Hyperedge Definition Based on Desikan-Killiany Partitioning

- Hyperedge Definitions Based on Yeo Network Partitions 

- Hyperedge Definition Based on K-Nearest Neighbors (KNN)

## Usage

To get started:
1. Download the dataset from the link provided above.
2. Extract the dataset to the root directory of the project.
3. Choose the hyperedge modeling strategy that suits your experimental needs.
4. Run the provided Jupyter notebooks for hypergraph modeling and semantic computation.

## Future Work

We are actively working on organizing and sharing more advanced methods for analyzing high-order brain networks. Updates will include additional code and resources to support further exploration in this field.
We welcome contributions and discussions! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

---

### Citation
```bibtex
@inproceedings{han2024inter,
  title={Inter-intra high-order brain network for ASD diagnosis via functional MRIs},
  author={Han, Xiangmin and Xue, Rundong and Du, Shaoyi and Gao, Yue},
  booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
  pages={216--226},
  year={2024},
  organization={Springer}
}
```

```bibtex
@article{gao2024hypergraph,
  title={Hypergraph Computation},
  author={Gao, Yue and Ji, Shuyi and Han, Xiangmin and Dai, Qionghai},
  journal={Engineering},
  volume = {40},
  pages = {188-201},
  year={2024},
  publisher={Elsevier}
}
```

---
