
#### English | [简体中文](https://github.com/zhangzhengde0225/AI_for_Particle_Physics/blob/main/docs/README_zh_cn.md)

# AI for Particle Physics: Papers & Datasets

[![Stars](https://img.shields.io/github/stars/zhangzhengde0225/AI_for_Particle_Physics)](
https://github.com/zhangzhengde0225/AI_for_Particle_Physics)
[![Open issue](https://img.shields.io/github/issues/zhangzhengde0225/AI_for_Particle_Physics)](
https://github.com/zhangzhengde0225/FINet/AI_for_Particle_Physics)

## Introduction

This repository is a collection of datasets and papers for AI in particle physics. The datasets are collected from the public domain and the papers are collected from the arXiv and the IEEE Xplore. The purpose of this repository is to provide a convenient way for researchers to access the datasets and papers.


## Overview 
[![Paper](https://img.shields.io/static/v1?label=Read&message=paper&color=pink)](
https://code.ihep.ac.cn/zdzhang/hai)

### Papers
<details open>
<summary><b>Jet Tagging</b></summary>
<table align="center">
    <tbody>
        <tr>
            <td align="center"><b>Arch</td>
            <td align="center"><b>Neural Network</td>
            <!-- <td align="center">Author</td> -->
            <td align="center"><b>Paper</td>
            <td align="center"><b>Source Codes</td>
            <td align="center"><b>Is avail in HAI</td>
        </tr>
        <!-- ParT -->
        <tr>
            <td align="center"><img src="figs/ParT_arch.png" height='100'> </td>
            <td align="center">2022 Particle Transformer</td>
            <!-- <td align="center">HuiLin Qu et.al.</a></td> -->
            <td align="center">
                <a href="https://arxiv.org/abs/2202.03772">Particle Transformer for Jet Tagging (ArXiv)</td>
            <td align="center">
                <a href="https://github.com/jet-universe/particle_transformer">
                Github</a>
            <td align="center">
                <a href="https://code.ihep.ac.cn/zdzhang/hai"><b>Yes</a>
            <!-- <td align="center">JetClass</td> -->
        </tr>
        <tr>
            <td align="center"><img src="figs/LundNet_arch.jpg" height='100'> </td>
            <td align="center">2021 LundNet</td>
            <!-- <td align="center">Frédéric A. Dreyer and  Huilin Qu -->
            <td align="center">
                <a href="https://doi.org/10.1007/jhep03(2021)052">Jet tagging in the Lund plane with graph networks (JHEP)</td>
            <td align="center">
                <a href="https://github.com/fdreyer/lundnet">Origin</a>
            <td align="center">
                No (TODO)</a>
        </tr>
        <!-- PN -->
        <tr>
            <td align="center"><img src="figs/PN_arch.jpg" height='100'> </td>
            <td align="center">2020 ParticleNet</td>
            <td align="center">
                <a href="https://journals.aps.org/prd/abstract/10.1103/PhysRevD.101.056019">ParticleNet: Jet Tagging via Particle Clouds (PRD)</td>
            <td align="center">
                <a href="https://github.com/hqucms/ParticleNet">Origin</a>
            <td align="center">
                <a href="https://code.ihep.ac.cn/zdzhang/hai"><b>Yes</a></td>
        </tr>
        <!-- PFN -->
        <tr>
            <td align="center"><img src="figs/PFN_arch.jpg" height='100'> </td>
            <td align="center">2018 Particle Flow Network</td>
            <td align="center">
                <a href="https://arxiv.org/abs/1810.05165">Energy Flow Networks: Deep Sets for Particle Jets (JHEP)</td>
            <td align="center">-
            <td align="center">
                <a href="https://code.ihep.ac.cn/zdzhang/hai"><b>Yes</a></td>
        </tr>
        <!-- PCNN -->
        <tr> 
            <td align="center"><img src="figs/P-CNN_like_arch.jpg" height='100'> </td>
            <td align="center">2017 P-CNN</td>
            <td align="center">
                <a href="https://doi.org/10.21468/SciPostPhys.7.1.014">The Machine Learning Landscape of Top Taggers (SciPost Phys)</td>
            <td align="center">-
            <td align="center">
                <a href="https://code.ihep.ac.cn/zdzhang/hai"><b>Yes</a></td>
        </tr>
    </tbody>
</table>

Note: HAI is the [High energy physics Artifitial Intelligence](https://code.ihep.ac.cn/zdzhang/hai) framework, which provide simple dataset download, training, evaluation, inference and deployment funciton of the benchmarks and datasets of AI4HEP algorithms.

</details>

<details open>
<summary><b>Particle Identification</b></summary>

</details>

<details open>
<summary><b>Particle Tracking</b></summary>

</details>

<details open>
<summary><b>Event Reconstruction</b></summary>

</details>

<details open>
<summary><b>Other</b></summary>
</details>


### Datasets
[![Datasets](https://img.shields.io/static/v1?label=Download&message=datasets&color=green)](
https://code.ihep.ac.cn/zdzhang/hai)


<details open>
<summary><b>Jet Tagging</b></summary>
<table align="center">
    <tbody>
        <tr>
            <td align="center"><b>Figure</td>
            <td align="center"><b>Dataset Name</td>
            <td align="center"><b>Info</td>
            <td align="center"><b>URL</td>
        </tr>
        <tr>
            <td align="center"><img src="figs/JetClass_dataset.png" height="100">
            <td align="center">2022 JetClass 
            <td align="center">Dataset for Jet Tagging. 100M, 5M and 20M jets for training, validation and testing, respectively.
            <td align="center"><a href="https://doi.org/10.5281/zenodo.6619768">Download
        </tr>
        <tr>
            <td align="center"><img src="figs/TopLandscape.jpg" height="100">
            <td align="center">TopLandscape 
            <td align="center">Dataset for Jet Tagging
            <td align="center"><a href="https://hqu.web.cern.ch/datasets/TopLandscape/TopLandscape.tar">Download
        </tr>
        <tr>
            <td align="center"><img src="figs/QuarkGluon.jpg" height="100">
            <td align="center">2019 QuarkGluon
            <td align="center">Dataset for Jet Tagging. Two datasets of quark and gluon jets generated with Pythia 8, one with all kinematically realizable quark jets and one that excludes charm and bottom quark jets.
            <td align="center"><a href="https://hqu.web.cern.ch/datasets/TopLandscape/TopLandscape.tar">Download
        </tr>
    </tbody>
</table>
</details>


## Contributing

We appreciate all contributions to make this repository better. Welcome to participate in this project via the following ways:

- **Star** this repository to show your interest.
- **Fork** this repository and submit a **Pull Request** to add new papers or datasets, or fix bugs. Please refer to [contributing.md](docs/contributing.md) for more details.


