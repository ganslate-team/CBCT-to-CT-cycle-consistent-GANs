# Optimizing CycleGAN Design for CBCT-to-CT Translation: Insights into 2D vs 3D Modeling, Patch Size, and the Need for Tailored Evaluation Metrics

[Paper](UPDATE)

We used [ganslate](https://github.com/ganslate-team/ganslate) framework for these experiments.

## Structure

This repository contains the experiment configuration files and PyTorch dataset loading and preprocessing that we used in our paper.

It is organized into two folders:

- `LungProton` - experiments and dataset classes for **lung** CBCT-to-CT translation for adaptive **proton** radiotherapy

- `CervixPhoton` - experiments and dataset classes for **cervix** CBCT-to-CT translation for adaptive **photon** radiotherapy

## Running

To run the experiments (if you have access to the data):
```
pip install ganslate

git clone git@github.com:ganslate-team/CBCT-to-CT-cycle-consistent-GANs.git
cd CBCT-to-CT-cycle-consistent-GANs

# change the config file accordingly
ganslate train config="./LungProton/experiments/1_2D_cyclegan_vnet.yaml" 
```

## Acknowledgments

## Citation
```text
```
