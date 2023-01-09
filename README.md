# THINGS-data

[THINGS-data](https://doi.org/10.1101/2022.07.22.501123) is a collection of large-scale datasets for the study of natural object representations in brain and behavior. It includes functional magnetic resonance imaging (fMRI) data, magnetoencephalographic (MEG) recordings, and 4.70 million similarity judgments in response to thousands of images from the [THINGS object concept and image database](https://doi.org/10.1371/journal.pone.0223792).

# Repository contents

This repository the scripts and notebooks for reproducing the neuroimaging analyses presented in the [THINGS-data paper](https://doi.org/10.1101/2022.07.22.501123). It is structured into two sub-folders reflecting the two neuroimaging data modalities: 
- [MRI](MRI)
- [MEG](MEG)


# Download

## Download from figshare

THINGS-data is hosted as a collection of data objects on figshare. 

> 🔗 Figshare Download
> 
> #TODO: figshare collection public link

Besides the raw data, this collection includes a data derivatives such as preprocessed versions of both the fMRI and MEG data. Additional derivatives for the fMRI data include single trial response estimates, cortical surface maps, noise ceiling estimates, and regions of interest.

You can browse the collection and download individual parts which are relevant for your research.

By default, clicking on the desired data object will prompt a browser download. If you plan to download larger data objects such as the raw MEG or fMRI datasets, it might make sense to start this process in the command line. Simply right-click on the “Download” button and copy the link address. Executing the following code in the command line to begin the download process for that file. 
```
wget https://figshare.com/copied/link/address
```
For longer downloads, it might make sense to run this process in the background with tools such as `screen` or `tmux`.

## Download from OpenNeuro

The raw fMRI and MEG datasets are available on [OpenNeuro](https://openneuro.org). 

> 🔗 OpenNeuro Download
> 
> - MRI: [https://openneuro.org/datasets/ds004192](https://openneuro.org/datasets/ds004192)
> - MEG: [https://openneuro.org/datasets/ds004212](https://openneuro.org/datasets/ds004212)



The official [documentation](https://docs.openneuro.org/user-guide) gives helpful explanations on how to download data from OpenNeuro.


## Download from OSF

The behavioral dataset containing 4.7 million human similarity judgements is available on OSF and can be downloaded directly via your web browser.

> 🔗 OSF Download
> 
> [osf.io/f5rn6/](https://osf.io/f5rn6/)


# How to cite
```
@article {Hebart2022.07.22.501123,
	author = {Hebart, M.N. and Contier, O. and Teichmann, L. and Rockter, A.H. and Zheng, C.Y. and Kidder, A. and Corriveau, A. and Vaziri-Pashkam, M. and Baker, C.I.},
	title = {THINGS-data: A multimodal collection of large-scale datasets for investigating object representations in brain and behavior},
	elocation-id = {2022.07.22.501123},
	year = {2022},
	doi = {10.1101/2022.07.22.501123},
	publisher = {Cold Spring Harbor Laboratory},
	URL = {https://www.biorxiv.org/content/early/2022/07/23/2022.07.22.501123},
	eprint = {https://www.biorxiv.org/content/early/2022/07/23/2022.07.22.501123.full.pdf},
	journal = {bioRxiv}
}
```