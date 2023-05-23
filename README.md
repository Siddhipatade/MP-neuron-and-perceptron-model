# MP-neuron-and-perceptron-model
## McCulloch – Pitts neuron
- First computational model of a neuron was proposed by "Warren MuCulloch (neuroscientist)" and "Walter Pitts (logician)" in 1943.

- Divided into 2 parts. The first part, g takes an input, performs an aggregation and based on the aggregated value the second part, f makes a decision.

![image](https://github.com/Siddhipatade/MP-neuron-and-perceptron-model/assets/91780318/f41b2b64-5043-420b-9083-50001503c674)

- Inputs can be 'Excitatory' or 'Inhibitory'.

- Inhibitory inputs are those that have maximum effect on the decision making irrespective of other inputs 

- Excitatory inputs are NOT the ones that will make the neuron fire on their own but they might fire it when combined together. 

#### Aggregation function
![image](https://github.com/Siddhipatade/MP-neuron-and-perceptron-model/assets/91780318/23e26b2f-fe61-496c-96ee-30b2da555ee7)


## Perceptron Model

![image](https://github.com/Siddhipatade/MP-neuron-and-perceptron-model/assets/91780318/2c5974ee-30c0-49ec-8aa5-3cb84a0533e4)

- "Mr. Frank Rosenblatt" invented the perceptron in 1957. 
- Perceptron learning rule based on the original MCP neuron. 
- Perceptron is an algorithm for supervised learning of binary classifiers. This algorithm enables neurons to learn and processes elements in the training set one at a time.
- Four main parameters: input values, weights and Bias, net sum, and an activation function (step function). 

      Final equation: ∑w i x i +b

- Perceptron is a function that maps its input “x,” which is multiplied with the learned weight coefficient; an output value "f(x)" is generated.
 ![image](https://github.com/Siddhipatade/MP-neuron-and-perceptron-model/assets/91780318/1fb0a59b-b640-476d-a18e-f848373bf65c)
- In the equation given above:
"w" = vector of real-valued weights
"b" = bias (an element that adjusts the boundary away from origin without any dependence on the input value)
"x" = vector of input x values

![image](https://github.com/Siddhipatade/MP-neuron-and-perceptron-model/assets/91780318/3198a71a-b622-4458-a163-fc12a6fde3b7)

- "m" = number of inputs to the Perceptron
- The output can be represented as "1" or "0"  It can also be represented as "1" or "-1" depending on which activation function is used.

