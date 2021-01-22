---
published: false
---
# Running VERTEX with synaptic plasticity and for modifying electrode shape:

## 1. Defining simulation model:
Link to vertexTutorials → tutorial_1.m (setting tissue parameters, and neuron parameters)

Example code from VERTEX 2.0:
Vertex_2-master → ratSomatosensoryCortex → loadRatTissueandNeuronParams.m & buildNeuronProperties.m
Setting up neurons with plasticity:

Example code from VERTEX 2.0:
For TBS:
Vertex_2-master → ratSomatosensoryCortex → loadRatConnectionsParamsSTDP.m & loadConnectionsSTDP.m

For STP (SP & PP):
Vertex_2-master → ratSomatosensoryCortex → loadRatConnectionsParams.m & loadConnectionsSTP.m

## 2. Defining stimulation settings:
Example code from VERTEX 2.0:

For TBS:
Vertex_2-master → ratSomatosensoryCortex → thetaburststimulation.m

For STP (SP & PP):
Vertex_2-master → ratSomatosensoryCortex → singlePulse.m & pairedPulse.m

## 3. Defining electrode shape:
Example code from VERTEX 2.0:
Vertex_2-master → ratSomatosensoryCortex → setUpBipolarElectrodeStimulation.m
> testing block code

