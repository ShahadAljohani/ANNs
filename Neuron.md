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

![SigmoidFunction](https://github.com/user-attachments/assets/76ba4a8e-8725-4f2c-ab0d-19eef62c6692)

*Note that the Threshold function and the Sigmoid function are useful when the dependent variable is binary \\Sigmoid(P=1) 

3- **Rectifier Funcrtion**
--called ReLU function

$$
\phi(x) =\max(x,0)
$$

![RectefierFuncion](https://github.com/user-attachments/assets/529a23c0-27c0-4753-bb18-c6f6d02f8637)

4- **Hyberbolic Tangent (tanh)**

$$
\phi(x) = \(\frac{1 - e^{-2x}}{1 + e^{-2x}} \)
$$

![HyberbolicTangentFunction](https://github.com/user-attachments/assets/9f675039-4802-4fb0-bc13-9e3ab2610ba4)


# Cost Function

$$
 c = \frac{1}{2} (\hat{y} - y)^2 
$$

it shows the error in the function

**Our goal is to lower the cost function**
  ,the lower cost function the closer $\hat{y}$ to y
