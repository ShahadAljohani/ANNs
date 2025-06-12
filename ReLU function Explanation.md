# Why does the Rectifier Linear Unit (ReLU) function is useful and uesd in artificial neural networks?

in case you forget the function, it is defiend ad: 

$$
ReLU(x) = max(0,x)
$$

mainly it is useful becaue it outputs the input directly if it's positive, otherwise outputs zero, which means it is activated ONLY when **x > 0**
That mimics the real (biological) neurons, which it fires when a stimulus crosses a certain threshold

**Now for deep explanation for WHY?**
- Biological Plausability (which is explained above) and Sparsity,
   this rise a **Sparse Activiation** (means Selectivly activates input-dependent set on neurons in an inference = a small fraction of neurons is active at a time) in which it is beneficial because:
   - in which it reduces the computational complexity 
   - enhances a generaliztaion by preventing co-adaption of neurons ((means each neuron MUST learn useful features INDEPENDENTLY))
     
- Efficient Computation: there's no complex exponential and divisions (like in tanh, sigmoid), thresholding at zero.
   This is very useful and efficient for forward and backward passes with millions of parameters.
  
-
