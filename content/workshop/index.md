---
title: " " #Workshops
featured_image: img/arras.jpeg
---

## Workshop 1: Neuro-Symbolic AI (Zoom talks)

### Giuseppe Marra (KU Leuven)

**Title:**  Interpretable Neural-Symbolic Concept Reasoning

**Abstract:**  Deep learning methods are highly accurate, yet their opaque decision process prevents them from earning full human trust. Concept-based models aim to address this issue by learning tasks based on a set of human-understandable concepts. However, state-of-the-art concept-based models rely on high-dimensional concept embedding representations which lack a clear semantic meaning, thus questioning the interpretability of their decision process. To overcome this limitation, we propose the Deep Concept Reasoner (DCR), the first interpretable concept-based model that builds upon concept embeddings. In DCR, neural networks do not make task predictions directly, but they build syntactic rule structures using concept embeddings. DCR then executes these rules on meaningful concept truth degrees to provide a final interpretable and semantically-consistent prediction in a differentiable manner. Our experiments show that DCR: (i) improves up to +25% w.r.t. state-of-the-art interpretable concept-based models on challenging benchmarks (ii) discovers meaningful logic rules matching known ground truths even in the absence of concept supervision during training, and (iii), facilitates the generation of counterfactual examples providing the learnt rules as guidance.


### Pasquale Minervini (University of Edinburgh).

**Title:**  Integrating Combinatorial Solvers and Neural Models

**Abstract:** Neural models -- including language models such as ChatGPT -- can exhibit remarkable abilities; paradoxically, they also struggle with algorithmic tasks where much simpler models excel. To solve these issues, we propose Implicit Maximum Likelihood Estimation (IMLE), a framework for end-to-end learning of models combining algorithmic combinatorial solvers and differentiable neural components, which allows us to incorporate planning and reasoning algorithms in neural architectures by just adding a simple decorator [1, 2].

[1] Implicit MLE: Backpropagating Through Discrete Exponential Family Distributions. [](https://arxiv.org/abs/2106.01798), NeurIPS 2021
[2] Adaptive Perturbation-Based Gradient Estimation for Discrete Latent Variable Models. [](https://arxiv.org/abs/2209.04862), AAAI 2023

### Steven Schockaert (Cardiff University) 

**Title:** Aligning embeddings with symbolic knowledge: towards a tight integration of learning and reasoning
 
**Abstract:** Most approaches to neurosymbolic AI rely on a relatively loose coupling between learning and reasoning. To enable a tighter integration between these components, we need some kind of alignment between vector space representations and symbolic knowledge. In this talk, I will discuss two strategies that can be pursued towards this end. The first strategy builds on the idea that predicates can be represented as convex regions in some vector space. Symbolic knowledge, e.g. in the form of existential rules, can then be encoded in terms of constraints on the spatial arrangement of these regions. The second strategy corresponds to the idea that vectors represent epistemic states. Symbolic reasoning can then be carried out by manipulating these vectors in a well-defined way. I will provide an overview of theoretical results about the principles underpinning these strategies, as well as their limitations.


## Workshop 2: Explanations meet uncertainties

### Abstract

Explanations and uncertainty quantification and handling in artificial intelligence models are (again) rising topics, due to their increased uses in everyday life as well as in sensitive areas and the need for trustworthy models and inferences. This satellite workshop of ECSQARU aim at gathering researchers that are interested in methods that include both aspects of trustworthy IA, in order to discuss recent advances in this direction.

Topics of interest include, but are not limited to:

* Robustness in explanations
* Approximate explanations
* Explaining uncertainties (epistemic/aleatoric)
* Reasoning and explanation
* Defeasible reasoning and explanations
* Causality and explanation
* (Weighted) argumentation and explanations

### Contributions

We welcome both abstract of presentations as well as longer papers of up to 6 pages. Papers will be sent for review to program committee members, in order to provide feedbacks to the authors. The goal of the workshop is primarily to present and discuss recent ideas about explanations and uncertainty handling, and we do not aim to have a selective procedure, unless the number of submissions becomes too high to have enough time for discussions.

### Important dates

* 15th June : submission deadline
* 15th July : feedbacks (in case of paper submission)
* 19th September : workshop day.

### Submissions

Submisions can be directly emailed to [Sebastien Destercke](mailto:sebastien.destercke@hds.utc.fr) and [Wassila Ouerdane](mailto:wassila.ouerdane@centralesupelec.fr)

### Organizers

Wassila Ouerdane, Sébastien Destercke, with the support of the workgroup Explicon of GDR RADIA.


