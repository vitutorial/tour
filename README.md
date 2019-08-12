This repository stores material for a [tutorial on variational inference for NLP audiences](https://vitutorial.github.io). 

Want to host our tutorial at your location? [Contact](#contact) one of us!


# <a name="general"> Variational Inference and Deep Generative Models

Neural networks are taking NLP by storm. Yet they are mostly applied to fully supervised tasks. 
Many real-world NLP problems require unsupervised or semi-supervised models, however, because annotated data is hard to obtain. 
This is where generative models shine. 
Through the use of latent variables they can be applied in missing data settings. Furthermore they can complete missing entries in partially annotated data sets.

This tutorial is about how to use neural networks inside generative models, thus giving us Deep Generative Models (DGMs). 
The training method of choice for these models is variational inference (VI). 
We start out by introducing VI on a basic level. From there we turn to DGMs. 
We justify them theoretically and give concrete advise on how to implement them. For continuous latent variables, we review the variational autoencoder and use Gaussian reparametrisation to show how to sample latent values from it. 
We then turn to discrete latent variables for which no reparametrisation exists. 
Instead, we explain how to use the score-function or REINFORCE gradient estimator in those cases. 
We finish by explaining how to combine continuous and discrete variables in semi-supervised modelling problems.


Check `modules` for the lectures, we recommend the following order:

* Introduction
* VI
* DGMs-Discrete
* DGMs-Continuous
* ADVI
* NFs

# <a name="contact"> Contact

Want to host our tutorial? Have a suggestion? Contact one of us!

* [Philip](//philipschulz.org)
* [Wilker](//wilkeraziz.github.io)
