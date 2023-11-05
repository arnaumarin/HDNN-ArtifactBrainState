# HDNN-ArtifactBrainState

## Overview

HDNN-ArtifactBrainState is a cutting-edge project that integrates Hopfield networks with deep neural networks to enhance brain state decoding, focusing on resilience against artifacts. This repository houses the code and resources for implementing the HDNN framework described in our recent publication.

## Citation

If you found it useful, please consider cite our work as follows:

Marin-Llobet, A., Manasanch, A., Sanchez-Vives, MV. "Hopfield-Enhanced Deep Neural Networks for Artifact-Resilient Brain State Decoding". Presented at NeurIPS 2023, AMHN Workshop.

## Getting Started

### Prerequisites

Ensure you have Conda installed on your system for managing packages and environments.

### Installation

To set up your environment for HDNN-ArtifactBrainState, run the following commands:

```bash
$ conda create --name HDNN python=3.9
$ conda activate HDNN
$ conda install tensorflow=2.13.0 numpy=1.24.3 matplotlib=3.5.2 sklearn=1.1.1 seaborn=0.12.2
$ conda install -c conda-forge jupyterlab
