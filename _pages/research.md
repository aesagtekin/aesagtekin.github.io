---
title: "Research"
permalink: /research/

---
# • Error Forcing in Recurrent Neural Networks

[NeurIPS 2025, Spotlight, work from my Master's Thesis](https://openreview.net/forum?id=xVI8g50Qfk) <br>
A Erdem Sağtekin, Colin Bredenberg & Cristina Savin
<br><br>
Abstract
<br>

How should feedback influence recurrent neural network (RNN) learning? One way to address the known limitations of backpropagation through time is to directly adjust neural activities during the learning process. However, it remains unclear how to effectively use feedback to shape RNN dynamics. Here, we introduce error forcing (EF), where the network activity is guided orthogonally toward the zero-error manifold during learning. This method contrasts with alternatives like teaching forcing, which impose stronger constraints on neural activity and thus induce larger feedback influence on circuit dynamics. Furthermore, EF can be understood from a Bayesian perspective as a form of approximate dynamic inference. Empirically, EF consistently outperforms other learning algorithms across several tasks and its benefits persist when additional biological constraints are taken into account. Overall, EF is a powerful temporal credit assignment mechanism and a promising candidate model for learning in biological systems.

# • Inferring stochastic low-rank recurrent neural networks from neural data

[NeurIPS 2024](https://arxiv.org/html/2406.16749v1) <br>
Matthijs Pals, **A Erdem Sağtekin**, Felix Pei, Manuel Gloeckler & Jakob H Macke
<br> <br>
Abstract
<br> <br>
A central aim in computational neuroscience is to relate the activity of large populations of neurons to an underlying dynamical system. Models of these neural dynamics should ideally be both interpretable and fit the observed data well. Low-rank recurrent neural networks (RNNs) exhibit such interpretability by having tractable dynamics. However, it is unclear how to best fit low-rank RNNs to data consisting of noisy observations of an underlying stochastic system. Here, we propose to fit stochastic low-rank RNNs with variational sequential Monte Carlo methods. We validate our method on several datasets consisting of both continuous and spiking neural data, where we obtain lower dimensional latent dynamics than current state of the art methods. Additionally, for low-rank models with piecewise linear nonlinearities, we show how to efficiently identify all fixed points in polynomial rather than exponential cost in the number of units, making analysis of the inferred dynamics tractable for large RNNs. Our method both elucidates the dynamical systems underlying experimental recordings and provides a generative model whose trajectories match observed trial-to-trial variability.

---

# • Single-compartment model of a pyramidal neuron, fitted to recordings with current and conductance injection

[Link to paper](https://link.springer.com/article/10.1007/s00422-023-00976-7) <br>
Anton V. Chizhov, Dmitry V. Amakhin, **A. Erdem Sagtekin** & Mathieu Desroches.
<br> <br>
Abstract
<br> <br>
For single neuron models, reproducing characteristics of neuronal activity such as the firing rate, amplitude of spikes, and threshold potentials as functions of both synaptic current and conductance is a challenging task. In the present work, we measure these characteristics of regular spiking cortical neurons using the dynamic patch-clamp technique, compare the data with predictions from the standard Hodgkin-Huxley and Izhikevich models, and propose a relatively simple five-dimensional dynamical system model, based on threshold criteria. The model contains a single sodium channel with slow inactivation, fast activation and moderate deactivation, as well as, two fast repolarizing and slow shunting potassium channels. The model quantitatively reproduces characteristics of steady-state activity that are typical for a cortical pyramidal neuron, namely firing rate not exceeding 30 Hz; critical values of the stimulating current and conductance which induce the depolarization block not exceeding 80 mV and 3, respectively (both values are scaled by the resting input conductance); extremum of hyperpolarization close to the midpoint between spikes. The analysis of the model reveals that the spiking regime appears through a saddle-node-on-invariant-circle bifurcation, and the depolarization block is reached through a saddle-node bifurcation of cycles. The model can be used for realistic network simulations, and it can also be implemented within the so-called mean-field, refractory density framework.
	
---

# • Reinforcement learning in biological neural networks

Click [here](http://aesagtekin.github.io/files/RLwithSNNs.pdf) to download the full report (will take some time). Supervised by Georgy Antonov and Peter Dayan.
<br> <br>
Abstract
<br> <br>
Reinforcement learning (RL) framework provides experimentally justified explanations for
animal learning. On the other hand, animal learning has been extensively associated with synaptic
plasticity, which is commonly studied by employing spiking neural networks in computational
neuroscience literature. In this report, I investigate the literature that explores the relationship
between synaptic plasticity rules and the RL framework. The literature can be divided into three
parts: 1) using policy-gradient methods to analytically derive plasticity rules, 2) modulating the
STDP rule by a global reward signal, and 3) using temporal-difference learning to find plasticity
rules.
	
---

# • Emergent E/I tuning and balance during surrogate gradient learning

Click [here](http://aesagtekin.github.io/files/SurrogateLearning.pdf) to download the poster (will take some time). Supervised by Manos Giannakakis and Anna Levina.
<br> <br>
Take-home Messages
<br> <br>
• Training spiking neural networks on simple discrimination tasks shapes the neural tuning curve of the postsynaptic neuron. <br>
• A simple selectivity task leads to E/I anti-tuning, and also to E/I balance if a constraint is put on the post-synaptic firing rate. <br>
• A novelty selectivity task is much harder to train, but leads to E/I co-tuning. <br>
	
---
# • Implementing the cortex model in the "Simple model of spiking neurons" paper by E. M. Izhikevich (2003) with Brian2

Credits:  <br> <br>
Figure: Marcel Stimberg  <br>
Modifications/improvements on initial draft: Sebastian Schmitt  <br>
 
[Code](https://brian2.readthedocs.io/en/stable/examples/frompapers.Izhikevich_2003.html)  <br>

Results:  <br> ![Brian2](https://brian2.readthedocs.io/en/stable/_images/frompapers.Izhikevich_2003.1.png)
