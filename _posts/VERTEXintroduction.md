---
published: false
---
## Welcome to synaptic plasticity in VERTEX

Thank you for taking your first steps in understanding synaptic plasticity and how this can be applied in the VERTEX simulator. The following pages offer a guide on the background, relevance and applications of synaptic plasticity. 

### Background:

As an investigatory tool, electric field stimulation has facilitated many important experiments in neurophysiology and is still widely used. It is often used to provoke a population of neurons to fire simultaneously, producing a synaptic response measured in the local field potential (LFP). Alternatively, electrical stimulation can be used as a tool for neuromodulation using open- or closed-loop feedback to change the dynamics of neuronal circuits1. However, interpreting this response potential is made difficult by the large number of possible synaptic sources, as well as by the diverse way in which the field stimulation recruits neurons of various morphologies. 

### The role of this extension:

This extension to the VERTEX simulator2 aims to combine our current knowledge of the neocortical microcircuit (neuron morphologies, patterns of connectivity, and synaptic properties) with a biophysical model of extracellular electrical stimulation and LFP generation to make a well informed prediction of the synaptic sources contributing to the electrically evoked LFP. As field stimulation experiments often seek to measure or manipulate synaptic efficacy, this guide includes both short term plasticity (STP) and spike time dependent plasticity (STDP) in this release. 

### What can you learn from this guide?

- How to incorporate the effect of an electric field on the membrane potential of the neuron compartments in our model. This follows the work of Frank Rattay and the implementation of the extracellular mechanism in the Neuron simulator. 
- Implementing two models of short term synaptic plasticity and spike timing dependent plasticity. 
- How to use this tool to look at the overall workflow involved in setting up a simulation (including a stimulating electrode and synaptic plasticity), illustrated by an example simulation of stimulation in rat neocortex. 
- How we calculate the electric potential produced by a bipolar electrode equivalent to those typically used in in vitro experiments, and subsequently apply this to the ongoing dynamics of a typical VERTEX simulation.  - How VERTEX can be used to isolate the synaptic and non-synaptic changes that contribute to the change in response LFP during paired pulse stimulation and how theta burst stimulation causes STDP mediated changes in synaptic strength.


