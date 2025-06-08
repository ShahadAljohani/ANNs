# Artificial Neuron

**Key definitions:**
- **Artificial Neuron:** a node (unit)
- **Synapse:** the connections between the neurons
- **Weight:** the numeric value assigned to the synapse

## Inside a neuron

- **The activation function:**

$$
\phi\(\sum_{i=1}^n w_i x_i + b)
$$

it could be ont of the four functions:

 1-**Threshold function:** 

 $$
 \phi\(x)={ 1, x \geq 
            0, x<0}
 $$

![Screenshot (500)](https://github.com/user-attachments/assets/0a0bbab9-8c38-491f-bafa-5dc088522297)

2- **Sigmoid function**

$$
\phi(x) = \(\frac{1}{1 + e^{-x}} \)
$$

