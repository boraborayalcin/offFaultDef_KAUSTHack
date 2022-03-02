# OffFaultDeformation

This repository contains the material used by the OffFaultDeformation project in the First **KAUST Hackathon in Geoscience**!


### Project description:

As faults accumulate slip they deform their surroundings. This is important for petrophysical reservoir models for reservoirs with faults. Triangular dislocation method can solve the strain accumulated on the surrounding rock for an arbitrary roughness, length (slip) and orientation of faults. Our in-house MATLAB code (a physics-based model) can solve the strain for different roughness parameters of the fault, which can be computationally expensive based on meshing size preferences. The data-set we provide you is 1000 randomly generated strain influence matrix for the same fault and slip amount with changing roughness parameters of fault surface. Data includes coordinates of observation points and strain components of deformation on those observation points. We ask you to provide us with a fast and accurate proxy model using machine learning methods.


### Notebooks:

The following notebooks are provided:

`OffFaultDeformation_gettingstarted`: display the training and testing datasets (requires data to be stored locally);

`OffFaultDeformation_gettingstarted_colab`: same but in case you are using Colab, access [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/boraborayalcin/offFaultDef_KAUSTHack/blob/main/OffFaultDeformation_gettingstarted_colab.ipynb) 



### Accessing data:


OffFaultDeformation: data for KAUST ML Hackathon 2022


### Environment creation:

When working on your local machine, we suggest to have installed Anaconda or Miniconda on your computer. If you are not familiar with it, we suggesting using the [KAUST Miniconda Install recipe](https://github.com/kaust-rccl/ibex-miniconda-install). This has been tested both on macOS and Unix operative systems. Once this is installed, create a new environment using the `environment.yml` file proved here by simply typing on terminal:

```
conda env create -f environment.yml
```

Note that this file is meant to be a file for template environment, feel free to include other libraries that you will be using!