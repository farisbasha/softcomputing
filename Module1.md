# Soft Computing

- **Definition**: A collection of methodologies that exploit imprecision, uncertainty, and partial truth for robustness and low cost.
- **Goal**: Emulate the human mind.
- **Main Branches**:
  - Fuzzy Systems
  - Artificial Neural Networks
  - Genetic Algorithms

## Evolution and Methodologies

- **Hard Computing**:
  - Precise modeling and accurate results.
  - Used in traditional AI.
  - Effective for simple problems.

- **Soft Computing**:
  - Approximates systems and uses inexact methods.
  - Tolerant to imprecision and uncertainty.
  - Suitable for complex, real-world problems.

<img width="638" alt="Screenshot 2024-05-23 at 11 55 08 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/10c33f55-45c2-46a9-acae-5643eaa615ce">


## Examples and Applications

- **Fuzzy Logic**: Robot navigation through obstacles.
- **Genetic Algorithms**: Optimal investment strategies.
- **Neural Networks**: Handwritten character recognition.

## Real-World Analogies

- **Learning**: Similar to student-teacher interactions.
- **Diagnosis**: Mimics how doctors diagnose patients.
- **Optimization**: Reflects natural selection processes in genetic algorithms.


## Applications of Soft Computing 
- Handwriting Recognition
- Image Processing and Data Compression 
- Automotive Systems and Manufacturing 
- Soft Computing to Architecture
- Decision-support Systems 
- Soft Computing to Power Systems 
- Neuro Fuzzy systems 
- Fuzzy Logic Control 
- Machine Learning Applications 
- Speech and Vision Recognition Systems

---
---

# Artificial Neural Network (ANN) 
### Human Brain and Neurons
- **Neurons**: Basic units of the brain, specialized for transmitting information.
- **Composition**: Cell body, dendrites, and axon.
- **Connections**: Approximately 100 billion neurons, each connecting up to 200,000 others.
- **Synapses**: Junctions between neurons for transmitting electrical impulses.
- **Function**: Neurons receive signals, transmit through axons, and convert signals at synapses.

### Biological Neurons
- **Structure**: Soma (cell body), dendrites (signal receivers), axon (signal transmitter), and synapses.
- **Process**: Dendrites receive signals, axon sends out spikes, synapses convert activity to excite or inhibit other neurons.
- **Firing Mechanism**: Neurons fire when excitatory activity reaches a threshold, followed by a refractory period.

### Artificial Neural Network (ANN)
- **Definition**: An information processing paradigm inspired by biological neural networks.
- **Components**: Interconnected neurons (processing elements) connected by synapses.
- **Function**: Processes information in parallel, mimicking brain function to solve complex problems.
- **Structure**: Neurons connected via communication links with associated weights influencing input signals.

<img width="426" alt="Screenshot 2024-05-24 at 1 45 43 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/d556f5d8-7cac-4ebc-a870-da0257b5d938">
<img width="426" alt="Screenshot 2024-05-24 at 1 46 40 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/ea779a38-d220-4b29-bc6d-08e171f5b174">


### ANN Operation
- **Model**: Simulates human brain for problem-solving.
- **Neuron Interaction**: Neurons (inputs x1, x2) connect with weights (w1, w2) to produce output (Y).

### Advantages of ANN
- **Adaptive Learning**: Learns tasks based on training data.
- **Self-Organization**: Creates its own information representation during learning.
- **Real-Time Operation**: Capable of parallel processing with specialized hardware.
- **Fault Tolerance**: Redundant information coding ensures robustness.

### Features of ANN
- **Parallel Processing**: Distributed information processing.
- **Connectivity**: High degree of connectivity between units.
- **Modifiable Connections**: Changes based on experience.
- **Continuous Learning**: Unsupervised and local information-based learning.
- **Graceful Degradation**: Performance declines gracefully with unit reduction.

<img width="447" alt="Screenshot 2024-05-24 at 1 45 15 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/89b8b077-870c-48b1-b60b-07b4369cf4a2">


---

# Basic Models of Artificial Neural Network


An artificial neural network (ANN) is defined by three basic entities:
1. **Synaptic Interconnections**: The connections between neurons.
2. **Training or Learning Rules**: The methods for adjusting connection weights.
3. **Activation Functions**: The functions that determine neuron output based on input signals.

## 1.Connections
- **Interconnected Processing Elements**: An ANN consists of a set of highly interconnected neurons.
- **Connection Topology**: The arrangement of nodes and connecting lines in the network.
- **Key Points**: Note where connections originate and terminate, specifying the function of each processing element.

### Types of Neural Network Connections
1. **Single Layer Feed-Forward Network**:
   - Input and output layers only.
   - Data flows from input to output layer directly.
  <img width="378" alt="Screenshot 2024-05-24 at 1 51 23 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/1d7d9faf-97db-4da5-9988-e10bf0a79c24">


2. **Multilayer Feed-Forward Network**:
   - Includes input, hidden, and output layers.
   - Data flows through hidden layers in one direction only.
  <img width="380" alt="Screenshot 2024-05-24 at 1 51 41 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/6af6bcf3-fb02-42ba-a97f-8297a4f4d0c2">
 

  
3. **Single Node with Feedback**:
   - A single neuron with a feedback loop to itself.
   - <img width="390" alt="Screenshot 2024-05-24 at 1 52 51 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/17b9ba0f-e80c-4ad3-8e97-8ce724b7bca6">


4. **Single Layer Recurrent Network**:
   - A single layer where outputs can feedback to themselves or other neurons.
   - <img width="256" alt="Screenshot 2024-05-24 at 1 53 05 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/6c9f6084-cc47-41bc-b7cb-a25cfea4c51c">


5. **Multilayer Recurrent Network**:
   - Neurons in any layer can feedback to neurons in preceding layers or themselves.
   - <img width="291" alt="Screenshot 2024-05-24 at 1 53 16 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/693f3adb-e16c-4bf8-afb8-95b94da35488">


### Categories of Neural Network Connections
- **Feed-Forward Networks**: Signals flow in one direction from input to output.
- **Recurrent Networks**: Include loops where signals can feedback to previous layers or the same layer.

## 1.Learning ( Training )

- **Learning Definition**: Modification of connection weights between neurons in an ANN.
- **Main Property**: ANN's ability to learn and generate output in response to input.
- **Training Methodology**: Adjustment of weights through training, classified as supervised or unsupervised.

### Types of Learning
1. **Supervised Learning**:

    <img width="287" alt="Screenshot 2024-05-24 at 1 57 39 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/52067920-c5a9-49b0-9277-0f645d1c1b20">

   - Dependent learning under the supervision of a teacher.
   - Uses labeled data for training.
   - Example: Identifying fruits based on predefined characteristics.
   - **Supervised Learning Process**
      - Input vector presented to the network, producing an output vector.
      - Error signal generated if difference between actual and desired output.
      - Weights adjusted until actual output matches desired output.
      - Requires a supervisor for error minimization.
        
  

3. **Unsupervised Learning**:

  <img width="153" alt="Screenshot 2024-05-24 at 1 58 14 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/db958ba2-e38a-4d91-a7ff-abcb6444925f">


   - Independent learning without a teacher.
   - Learns from data patterns without labels.
   - Example: Grouping similar data without prior knowledge.
   - **Unsupervised Learning Process**
      - No teacher provided, machine discovers patterns independently.
      - Groups similar input vectors without training data.
      - Forms clusters by organizing input patterns based on similarities.

4. **Reinforcement Learning**:

  <img width="249" alt="Screenshot 2024-05-24 at 1 58 24 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/1014bd6c-393d-41ee-a2fc-610e44239846">


   - Learning based on critic feedback.
   - Adjusts weights to maximize rewards and minimize penalties.
   - Example: Training a robot in an unknown environment.
   - **Reinforcement Learning Process**
      - Observes environment and makes decisions.
      - Adjusts weights based on feedback to maximize rewards.
      - Example: Training a pet to fetch a ball in a living room environment.




## 3.Activation Functions


Activation functions $f$ are applied to the net input to calculate the output of an ANN. The choice of activation functions depends on the problem type.

### Common Activation Functions

1. **Identity Function**:
   - Linear function: $f(x) = x$ for all $x$.
   -  <img width="183" alt="Screenshot 2024-05-24 at 2 10 12 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/008b606c-09b6-430c-895b-b5c07f3eabf9">

2. **Binary Step Function**:
   - <img width="194" alt="Screenshot 2024-05-24 at 2 33 36 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/eefda11d-2150-41b1-ab51-c908466ca688">
   - Threshold value $\theta$ determines output.
   - <img width="231" alt="Screenshot 2024-05-24 at 2 10 31 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/32802a8f-d14a-41c2-9f44-34fbe5d5f208">


3. **Bipolar Step Function**:
   - <img width="204" alt="Screenshot 2024-05-24 at 2 34 11 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/7c547033-4895-462a-8a73-089c574cfdc8">
   - Threshold value $\theta$ determines output.
   - <img width="201" alt="Screenshot 2024-05-24 at 2 10 43 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/49670e31-f68b-4e4d-bf16-f4fef993262b">


4. **Sigmoidal Functions**:
   - Widely used in backpropagation networks
   - **Sigmoidal functions are of two types**
        1. Binary Sigmoid Function: $f(x) = \frac{1}{1 + e^{-\lambda x}}$
        2. Bipolar Sigmoid Function: $f(x) = \frac{1 - e^{-\lambda x}}{1 + e^{-\lambda x}}$
   - Steepness parameter $\lambda$ controls function shape.
   - Ensure outputs are within specific ranges.
   - Non-linear nature aids in complex data modeling.
   - Binary Sigmoid and Bipolar Sigmoid functions are common examples.
   - "S"-shaped curve
   - <img width="153" alt="Screenshot 2024-05-24 at 2 12 31 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/0627e1dd-00df-49fe-921e-01ff89e82207">

  

5. **Ramp Function**:

   - Also know as **ReLu (Rectified Linear Unit)**
   - <img width="228" alt="Screenshot 2024-05-24 at 2 35 03 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/eb4c9af3-b110-410b-9d28-e60e978fd123">
   - Outputs based on input range.
   - <img width="203" alt="Screenshot 2024-05-24 at 2 13 44 PM" src="https://github.com/farisbasha/softcomputing/assets/72191505/ebd2923d-b7fd-4728-9692-312780c21dc3">
   - Outputs zero for negative input values.
   - Most commonly used activation function.
   - Provides sparsity, useful for efficient representation.

### Activation Function Details

- **Definition**: Activation functions decide whether a neuron should be activated based on the weighted sum plus bias.
- **Linear vs. Non-linear**: Activation functions can be linear (e.g., identity) or non-linear (e.g., sigmoid).
- **Linear Activation Functions**:
   - Limited power for handling complexity.
   - Collapse all layers into one, limiting network depth.
- **Non-linear Activation Functions**:
   - Essential for complex mappings in modern neural networks.
   - Enable learning and modeling of non-linear or high-dimensional data.
- **Limitations of Binary Step Function**:
   - Cannot provide multi-value outputs.
   - Hindrance in backpropagation due to zero gradient.
- **Bipolar Step Function**:
   - Outputs bipolar values (+1 to -1), suitable for single-layer networks.

#### 


