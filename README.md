# Spiking-Neural-Networks-SNN-

Creating a simple Spiking Neural Networks (SNN) model involves understanding that SNNs operate differently from traditional Artificial Neural Networks (ANNs). 
Instead of using continuous activations, they process and transmit information via discrete "spikes," mimicking how biological neurons function.

# Understand the Basic Components of SNN

1) Neuron model: A commonly used model is the Leaky Integrate-and-Fire (LIF) neuron.
2) Synapses: Define how neurons are connected.
3) Input encoding: Convert data into spikes (e.g., using Poisson encoding).
4) Simulation: Define a simulation time to observe neuron behavior.

# Simple Python Implementation on SNN (refer to the codes)

This code implements a Leaky Integrate-and-Fire (LIF) neuron model, and it is already functional with the results shown below:

![image](https://github.com/user-attachments/assets/1da52627-45af-4e19-bd46-fa281f8935ea)
![image](https://github.com/user-attachments/assets/04cb88b3-1d73-44f5-977d-795cd9a20392)

# Updated Code (With Noise and Dynamic Current)

This codes is an updated version of the code that includes noise and a sine wave input current.
What’s New in the Extended Version?
1) Dynamic Current: Combines a sine wave with Gaussian noise to simulate more realistic input.
2) Spike Markers: Spikes are highlighted directly on the voltage trace for clarity.
3) Firing Rate Analysis: Displays how often the neuron spikes over the simulation period.

![image](https://github.com/user-attachments/assets/76c829c9-e319-4e34-9fca-3dc035a77e89)
![image](https://github.com/user-attachments/assets/8a2dda6f-c10b-4c74-a929-3c6f7faf7454)

