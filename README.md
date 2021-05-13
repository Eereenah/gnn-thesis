# Binding Affinity Prediction with Graph Neural Networks

- The repository contains the notebooks for the final chapter of my Master's Thesis. 

- The notebooks contain the implementation of a novel fusion-based architecture, which combines a graph neural network ([AttentiveFP](https://pubmed.ncbi.nlm.nih.gov/31408336/)) and biologically-motivated learned protein embeddings ([ProtTransBert](https://www.biorxiv.org/content/10.1101/2020.07.12.199554v3)) for drug-target interaction prediction. The model architecture is outlined below:
![proteinafp](https://user-images.githubusercontent.com/19747670/118105632-add57280-b3ed-11eb-8eec-b080dda175b8.png)

The model is benchmarked on Davis and KIBA standard datasets, as well as on an in-house dataset of ~400K de novo generated molecules against 6 targets.
