---
title: About
layout: page
---
<!-- ![Profile Image]({{ site.url }}/{{ site.picture_elife }}) -->

I am a PhD candidate at the [Max Planck International Research School for Intelligent Systems](https://imprs.is.mpg.de) and the [University of Tübingen](https://uni-tuebingen.de/en/). I am part of the [Machine Learning in Science lab](https://www.mackelab.org) led by Jakob Macke. I work on Machine Learning tools for scientific discovery, in particular in neuroscience. Below, I outline my main research interests.


## Large-scale biophysical modelling with differentiable simulation
Biophysical modelling allows detailed insights into the processes underlying neural activity. Building accurate and large-scale biophysical modelling is challenging because these models are slow to simulate and cannot easily be fit to data. I develop tools and methods that enable to build large-scale biophysical models and to tune them such that the match measurements and perform computations.

[**Differentiable simulation enables large-scale training of detailed biophysical models of neural dynamics**](https://www.biorxiv.org/content/10.1101/2024.08.21.608979v1)\
**Deistler**, Kadhim, Beck, Pals, Huang, Gloeckler, Lappalainen, Schröder, Berens, Gonçalves, Macke (_bioRxiv_)

[**Diffusion Tempering Improves Parameter Estimation with Probabilistic Integrators for Ordinary Differential Equations**](https://arxiv.org/abs/2402.12231)\
Beck, Bosch, **Deistler**, Kadhim, Macke, Hennig, Berens (_ICML_)


## Neural mechanisms underlying biological intelligence
Neural circuits are remarkably energy-efficient and robust to perturbations. I use computational modelling and experimental measurements to study the biophysical properties underlying these features.

[**Energy efficient network activity from disparate circuit parameters**](https://www.pnas.org/doi/abs/10.1073/pnas.2207632119)\
**Deistler**, Macke‡, Gonçalves‡ (_PNAS_)

[**Training deep neural density estimators to identify mechanistic models of neural dynamics**](https://elifesciences.org/articles/56261)\
Gonçalves*, Lueckmann*, **Deistler***, Nonnenmacher, Öcal, Bassetto, Chintaluri, Podlaski, Vogels, Greenberg, Macke (_Elife_)

[**Deep inverse modeling reveals dynamic-dependent invariances in neural circuit mechanisms**](https://www.biorxiv.org/content/10.1101/2024.08.21.608969v2.abstract)\
Gao, **Deistler**, Schulz, Gonçalves, Macke (_bioRxiv_)

[**Combined statistical-mechanistic modeling links ion channel genes to physiology of cortical neuron types**](https://www.biorxiv.org/content/10.1101/2023.03.02.530774v1.abstract)\
Bernaerts, **Deistler**, Goncalves, Beck, Stimberg, Scala, Tolias, Macke, Kobak, Berens (_bioRxiv_)


## Machine learning methods for simulation-based inference
Mechanistic models provide interpretable and causal explanations for the processes underlying measurements. I develop probabilistic machine learning methods which allow to tune mechanistic models such that they match measurements.

[**All-in-one simulation-based inference**](https://arxiv.org/abs/2404.09636)\
Gloeckler, **Deistler**, Weilbach, Wood, Macke (_ICML, oral_)

[**Amortized Bayesian Decision Making for simulation-based models**](https://openreview.net/forum?id=BQE4MTAfCE)\
Gorecki, Macke, **Deistler** (_TMLR_)

[**Generalized Bayesian Inference for Scientific Simulators via Amortized Cost Estimation**](https://proceedings.neurips.cc/paper_files/paper/2023/hash/fdd565f63f49776bef620e0ce368a492-Abstract-Conference.html)\
Gao*, **Deistler***, Macke (_NeurIPS_)

[**Adversarial robustness of amortized Bayesian inference**](https://proceedings.mlr.press/v202/gloeckler23a.html)\
Gloeckler, **Deistler**, Macke (_ICML_)

[**Truncated proposals for scalable and hassle-free simulation-based inference**](https://proceedings.neurips.cc/paper_files/paper/2022/hash/9278abf072b58caf21d48dd670b4c721-Abstract-Conference.html)\
**Deistler**, Gonçalves‡, Macke‡ (_NeurIPS_)

[**Efficient identification of informative features in simulation-based inference**](https://proceedings.neurips.cc/paper_files/paper/2022/hash/7a7f6cc5dc2a84fb4edf0feb8e5cfd50-Abstract-Conference.html)\
Beck, Deistler, Bernaerts, Macke, Berens (_NeurIPS_)

[**Variational methods for simulation-based inference**](https://openreview.net/forum?id=kZ0UYdhqkNY)\
Gloeckler, **Deistler**, Macke (_ICLR, spotlight_)

[**Group-equivariant neural posterior estimation**](https://arxiv.org/abs/2111.13139)\
Dax, Green, Gair, **Deistler**, Schölkopf, Macke (_ICLR_)


## Software for scientific discovery
Together with many other amazing people, I am developer and maintainer of the following two toolboxes:  
- [sbi](https://github.com/sbi-dev/sbi), a PyTorch toolbox for simulation-based Bayesian inference and  
- [Jaxley](http://github.com/jaxleyverse/jaxley), a differentiable simulator for biophysically detailed neuron models in JAX.  

[**sbi---a toolbox for simulation-based inference**](https://joss.theoj.org/papers/10.21105/joss.02505)\
Tejero-Cantero*, Boelts*, **Deistler***, Lueckmann*, Durkan*, Gonçalves, Greenberg, Macke (_Journal of Open Source Software_)

* indicates shared first authorship.\
‡ indicates shared last authorship.
