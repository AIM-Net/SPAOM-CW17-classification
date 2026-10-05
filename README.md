# SPAOM-CW17: Hands-on Introduction to Bioimage Classification with CNNs

**Community workshop CW17 — [SPAOM 2026](https://spaom2026.org)**

SPAOM 2026 workshop: classifying malaria-infected cells with dense and convolutional neural networks in PyTorch/Deeplay, from training to Grad-CAM.

Material for the community workshop at **SPAOM 2026** (6–9 October 2026).

Instructors: Jose Requejo-Isidro (CNB-CSIC) and Carlo Manzo (UVic-UCC).

The notebook trains a dense neural network and a convolutional neural network to classify
blood-smear cell images as parasitized or uninfected, using the NIH malaria dataset
(Rajaraman et al., *PeerJ* 6, e4568, 2018). It covers:

- loading and preparing an image dataset with `ImageFolder`
- building and training DNN and CNN classifiers with Deeplay
- learning curves, ROC and precision-recall curves
- choosing a decision threshold with the F1 score
- inspecting filters, activations and Grad-CAM heatmaps

The code is based on Code Example 3-A of *Deep Learning Crash Course*
(Volpe, Midtvedt, Pineda, Klein Moberg, Bachimanchi, Pereira, Manzo; No Starch Press, 2026).

## Getting started

Open `classifying_malaria.ipynb` locally or in Colab/Kaggle. On Colab/Kaggle, install Deeplay first:

    pip install deeplay

The dataset downloads automatically on first run.

## Acknowledgment

This community workshop is part of the activities of AIM-Net (RED2024-153844-T, funded by MICIU/AEI/10.13039/501100011033).

## License

The course materials are released under the MIT License.
