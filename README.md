# Spiking-Neural-Networks-SNN-

Creating a simple Spiking Neural Networks (SNN) model involves understanding that SNNs operate differently from traditional Artificial Neural Networks (ANNs). 
Instead of using continuous activations, they process and transmit information via discrete "spikes," mimicking how biological neurons function.

# Understand the Basic Components of SNN

1) Neuron model: A commonly used model is the Leaky Integrate-and-Fire (LIF) neuron.
2) Synapses: Define how neurons are connected.
3) Input encoding: Convert data into spikes (e.g., using Poisson encoding).
4) Simulation: Define a simulation time to observe neuron behavior.

# What Is the LIF Model?

The Leaky Integrate-and-Fire (LIF) model is a simplified mathematical way of understanding how neurons process information and generate spikes (action potentials). It captures the essence of how real neurons behave while remaining computationally simple:

1) "Integrate": The neuron collects incoming electrical signals (inputs), causing its membrane potential (voltage) to rise.
2) "Leak": The neuron slowly loses this charge over time, just like a leaking bucket.
3) "Fire": When the voltage crosses a certain threshold, the neuron "fires" (produces a spike) and resets its voltage.

The LIF model simplifies how real neurons behave:

1) Real neurons have complex ionic mechanisms for generating spikes. The LIF model ignores these details and focuses on the key dynamics of charge integration and leakage.
2) Despite its simplicity, the model captures the essential properties of neuron spiking behavior.

Advantages of the LIF model:
1) Simplicity: Easy to understand and computationally efficient.
2) Biological Relevance: Captures the main features of real neurons' spiking behavior.
3) Versatility: Can be extended to include more complex dynamics (e.g., adaptive thresholds, multiple neurons).

# Core Idea: The Neuron as a Leaky Bucket
Imagine a neuron as a bucket that collects water (charge) over time:

1) Input current (I) acts like water pouring into the bucket.
2) The bucket leaks water through a hole at the bottom. This leakage represents how the neuron naturally loses charge over time.
3) When the bucket overflows, the neuron "fires" (generates a spike) and resets, like tipping the bucket to empty it.

# Simple Python Implementation on SNN (refer to the codes)

This code implements a Leaky Integrate-and-Fire (LIF) neuron model, and it is already functional with the results shown below:

![image](https://github.com/user-attachments/assets/1da52627-45af-4e19-bd46-fa281f8935ea)
![image](https://github.com/user-attachments/assets/04cb88b3-1d73-44f5-977d-795cd9a20392)

# Updated Code (With Noise and Dynamic Current)

This codes is an updated version of the code that includes noise and a sine wave input current.
What’s new in the extended version?:
1) Dynamic Current: Combines a sine wave with Gaussian noise to simulate more realistic input.
2) Spike Markers: Spikes are highlighted directly on the voltage trace for clarity.
3) Firing Rate Analysis: Displays how often the neuron spikes over the simulation period.

![image](https://github.com/user-attachments/assets/76c829c9-e319-4e34-9fca-3dc035a77e89)
![image](https://github.com/user-attachments/assets/8a2dda6f-c10b-4c74-a929-3c6f7faf7454)

