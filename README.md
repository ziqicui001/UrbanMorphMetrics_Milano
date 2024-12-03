# UrbanMorphMetrics

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
![Alt text](path/to/image "Optional Title")

## Contents

- [Introduction](#Introduction)
- [Overview](#Overview)
- [Instructions](#Instructions)
- [Acknowledgements](#Acknowledgements)
- [Contact](#Contact)

## Introduction

This study explores whether incorporating the spatial relationships and geometric features of individual street elements can enhance the accuracy and interpretability of perception prediction models. We used quantified spatial and geometric features of urban street elements as input for a graph neural network (GNN) model, a deep learning approach designed to process unstructured data. Compared to traditional methods, the GNN model achieved approximately a 6.3% on average improvement in accuracy across six perception dimensions, highlighting the importance of integrating spatial and geometric features into predictive modeling. Additionally, the study trained an explainer to analyze prediction results, enabling precise identification of critical subgraphs within images, which can determine the key edges, node combinations, and node features that significantly influence perception scores. Compared to previous approaches, this method provides more granular explanation results, offering valuable insights for urban planners to design environments that better align with public perceptions.

## Overview

![model_result](assets/model_result.png "Workflow of SyncPerception")

## Instructions

This project has three main step: data processing, model training and explainer training.<br>

Environment Configuration：<br>

CUDA Version: 12.5 <br>
Python 3.10 <br>
opencv-python             4.10.0.84<br>
openpyxl                  3.1.2<br>
openvino                  2024.4.0<br>
tensorflow                2.6.0<br>
tensorflow-estimator      2.6.0<br>
torch                     2.4.0<br>
torch_geometric           2.5.3<br>

## Acknowledgements

Thanks to my collaborators Shangyu Lou. She has made great contributions to methodology, data processing and model training.

## Contact

If you have any question, be free to contact me: ziqi.cui@polimi.it
 
