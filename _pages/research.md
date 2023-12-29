---
title: "Research"
permalink: /research/

---

# • Fitting RNNs to spikes with variational generalised teacher forcing

Ongoing project. Supervised by Matthijs Pals and Jakob Macke.

---

# • Single-compartment model of a pyramidal neuron, fitted to recordings with current and conductance injection

[Link to paper](https://link.springer.com/article/10.1007/s00422-023-00976-7) <br>
Anton V. Chizhov, Dmitry V. Amakhin, **A. Erdem Sagtekin** & Mathieu Desroches.
<br> <br>
Abstract
<br> <br>
For single neuron models, reproducing characteristics of neuronal activity such as the firing rate, amplitude of spikes, and threshold potentials as functions of both synaptic current and conductance is a challenging task. In the present work, we measure these characteristics of regular spiking cortical neurons using the dynamic patch-clamp technique, compare the data with predictions from the standard Hodgkin-Huxley and Izhikevich models, and propose a relatively simple five-dimensional dynamical system model, based on threshold criteria. The model contains a single sodium channel with slow inactivation, fast activation and moderate deactivation, as well as, two fast repolarizing and slow shunting potassium channels. The model quantitatively reproduces characteristics of steady-state activity that are typical for a cortical pyramidal neuron, namely firing rate not exceeding 30 Hz; critical values of the stimulating current and conductance which induce the depolarization block not exceeding 80 mV and 3, respectively (both values are scaled by the resting input conductance); extremum of hyperpolarization close to the midpoint between spikes. The analysis of the model reveals that the spiking regime appears through a saddle-node-on-invariant-circle bifurcation, and the depolarization block is reached through a saddle-node bifurcation of cycles. The model can be used for realistic network simulations, and it can also be implemented within the so-called mean-field, refractory density framework.

<br>
	
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
• Training spiking neural networks on simple discrimination tasks shapes the neural tuning curve of the upstream neuron. <br>
• A simple selectivity task leads to E/I anti-tuning, and also to E/I balance if a constraint is put on the post-synaptic firing rate. <br>
• A novelty selectivity task is much harder to train, but leads to E/I co- tuning. <br>
	
---
# • Implementing the cortex model in the "Simple model of spiking neurons" paper by E. M. Izhikevich (2003) with Brian2

Credits:  <br> <br>
Figure: Marcel Stimberg  <br>
Modifications/improvements on initial draft: Sebastian Schmitt  <br>
 
[Code](https://brian2.readthedocs.io/en/stable/examples/frompapers.Izhikevich_2003.html)  <br>

Results:  <br> ![Brian2](https://brian2.readthedocs.io/en/stable/_images/frompapers.Izhikevich_2003.1.png)
