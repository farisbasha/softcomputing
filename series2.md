# 1.Define feed forward and feedback networks
| Feed-forward ANNs                                                                                                                              | Feedback Networks                                                                                                                  |
|-------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| Inputs associate with outputs                                                                                                                  | Dynamic networks with continuous state changes                                                                                     |
| One-way, input to output                                                                                                                       | Bi-directional with loops                                                                                                          |
| Output doesn't affect same layer                                                                                                               | Inputs from previous steps influence current state                                                                                 |
| Feedforward networks process information in one direction, from input to output, without forming cycles.                                    | Feedback networks, or recurrent neural networks (RNNs), have connections that allow feedback loops, enabling them to maintain memory of past inputs. |

<img width="540" alt="Screenshot 2024-04-16 at 9 05 08 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/462808bb-46d2-4a85-9084-68c2ef9fb0d3">

# 2.List five basic architectures of ANN based on connection and Explain any two 
There are five types of Neural Network Connections:

- Single layer feed forward network
- Multilayer feed forward network
- Single node with its own feedback
- Single layer recurrent network
- Multilayer recurrent network

### Single Layer Feed Forward Network:
- A neural net with only input and output layers.
- Input and output layers are linked.
- Input layer receives input data, output layer sends calculated output for decision-making.
<img width="355" alt="Screenshot 2024-04-16 at 9 12 39 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/98041099-918b-4ec3-a253-bd4385dcea5c">


### Multi Layer Feed Forward Network:
- Neural network with input layer, one or more hidden layers, and an output layer.
- Information processed in one direction.
- Data may pass through multiple hidden nodes but always moves forward.
- <img width="363" alt="Screenshot 2024-04-16 at 9 12 58 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/a0176b83-b636-4c1d-adce-38aa9709fda8">


# 3.Obtain the output of the neuron for a network  Use i) Binary sigmoidal activation function ii) Bipolar sigmoid activation function
<img width="420" alt="Screenshot 2024-04-16 at 9 14 04 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/7ec8f9bf-db70-4f68-b1fa-717d5141f350">
<img width="407" alt="Screenshot 2024-04-16 at 9 14 20 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/e31441ed-6c0b-46d9-bfe0-59a3568b9ad3">


# 4.State Delta rule for single output unit in Adaline network

- The delta rule updates weights between connections to minimize the difference between the net input to the output unit and the target value.
- The primary goal is to minimize error across all training patterns.
- This is achieved by reducing the error for each pattern individually.
- The delta rule for adjusting the weight of the ith pattern (i = 1 to n) is given by:
  $Δw_i = α * (t - Y_{in}) * x_i$
  - Δw_i: weight change
  - α: learning rate
  - x_i: vector of activation of input unit
  - Y_{in}: net input to output unit
  - t: target output
  - $$\( Y = \sum_{i=1}^n x_i \times w_i \)$$

# 5.List out the steps in perceptron learning algorithm for single output classes
<img width="409" alt="Screenshot 2024-04-16 at 7 07 01 AM" src="https://github.com/farisbasha/softcomputing/assets/72191505/945752a8-2068-4a7b-9ea8-d1f44e155370">

# 6.Define artificial neural network, Draw its mathematical model

### **Artificial Neural Network (ANN)**:
- ANN is an efficient Information 
processing paradigm which 
resembles the characteristics of a 
biological neural network.
- ANN is composed of `large number 
of interconnected processing 
elements` called neurons 
connected by synapses which 
operates in parallel

  
  <img width="397" alt="Screenshot 2024-04-16 at 9 31 49 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/51dcac97-6040-4b82-a7b5-8c93e821098b">
<img width="437" alt="Screenshot 2024-04-16 at 9 32 03 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/609b61b2-b26d-4885-a460-4d21edee5e31">

# 7.Differentiate between the problem solving strategies: Soft computing and Hard computing

| Hard Computing                                  | Soft Computing                                  |
|-------------------------------------------------|-------------------------------------------------|
| Precise modeling for accurate results           | Approximate systems with inexact methods        |
| Traditional AI; logic and deterministic         | Human-like computing; tolerant to imprecision   |
| Symbolic logic reasoning; accurate models       | Tolerant to uncertainty and partial truth       |
| Suitable for simple problems                    | Ideal for real-world problems without models    |
| Focuses on logic; requires extensive resources  | Utilizes fuzzy logic, neural nets; less resource-intensive |
| May struggle in dynamic environments            | Adaptable to dynamic and uncertain conditions   |


# 8.State the testing algorithm used in perceptron network
<img width="466" alt="Screenshot 2024-04-16 at 9 39 06 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/ad236312-a9b7-4ce4-939b-c5a75fa22c3c">

- Perceptron testing evaluates network performance.
- Focuses on linear separability concept.
- Determines separating line based on non-negative threshold.
- Conditions for separating regions:
  - Positive to zero: $w1x1 + w2x2 + b > \theta$
  - Zero to negative:  $w1x1 + w2x2 + b > -\theta$

# 9.List the stage involved in Back Propagation Algorithm

1. **Forward Pass**: Input data is fed forward, and neuron activations are computed.
2. **Error Calculation**: Compute the error between predicted and target outputs.
3. **Backward Pass**: Propagate error gradients backward through the network.
4. **Weight Update**: Adjust weights using gradient descent or its variants.
5. **Iteration**: Repeat steps 1-4 until convergence or a stopping criterion is met.
