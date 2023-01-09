# Neural-Network-framework-using-Backpropogation-in-C

>This Assignment is to use the Neuron Network to let the machine learn XOR with n-bit inputs. 

# Compile
cd DATASTRUCTURE_HW1.1
cd Neural-Network-framework-using-Backpropogation-in-C
gcc main.c layer.c neuron.c -o main -lm
# Run
./main

>The number of layers is four.
>The number of neurons in layer[1]:2
>Enter number of neurons in layer[2]:4 
>Enter number of neurons in layer[3]:4
>The number of neurons in layer[4]:1

>Created Layer: 1
>Number of Neurons in Layer 1: 2
>Neuron 1 in Layer 1 created
>Neuron 2 in Layer 1 created

>Created Layer: 2
>Number of Neurons in Layer 2: 4
>Neuron 1 in Layer 2 created
>Neuron 2 in Layer 2 created
>Neuron 3 in Layer 2 created
>Neuron 4 in Layer 2 created

>Created Layer: 3
>Number of Neurons in Layer 3: 4
>Neuron 1 in Layer 3 created
>Neuron 2 in Layer 3 created
>Neuron 3 in Layer 3 created
>Neuron 4 in Layer 3 created

>Created Layer: 4
>Number of Neurons in Layer 4: 1
>Neuron 1 in Layer 4 created


>Initializing weights...
>0:w[0][0]: 0.596533
>1:w[0][0]: 0.026684
>2:w[0][0]: 0.378025
>3:w[0][0]: 0.732224
>0:w[0][1]: 0.080474
>1:w[0][1]: 0.093981
>2:w[0][1]: 0.414133
>3:w[0][1]: 0.065974
>0:w[1][0]: 0.676389
>1:w[1][0]: 0.560415
>2:w[1][0]: 0.190981
>3:w[1][0]: 0.036963
>0:w[1][1]: 0.975481
>1:w[1][1]: 0.283781
>2:w[1][1]: 0.975892
>3:w[1][1]: 0.026450
>0:w[1][2]: 0.269449
>1:w[1][2]: 0.164491
>2:w[1][2]: 0.062589
>3:w[1][2]: 0.695763
>0:w[1][3]: 0.153907
>1:w[1][3]: 0.141917
>2:w[1][3]: 0.337322
>3:w[1][3]: 0.479801
>0:w[2][0]: 0.169838
>0:w[2][1]: 0.689601
>0:w[2][2]: 0.038522
>0:w[2][3]: 0.498596

>Neural Network Created Successfully...

>Enter the learning rate (Usually 0.15): 
>0.15

>The number of training examples is four.
>Enter the Inputs for training example[0]:
>0 0

>Enter the Inputs for training example[1]:
>0 1

>Enter the Inputs for training example[2]:
>1 0

>Enter the Inputs for training example[3]:
>1 1

>Enter the Desired Outputs (Labels) for training example[0]: 
>0

>Enter the Desired Outputs (Labels) for training example[1]: 
>1

>Enter the Desired Outputs (Labels) for training example[2]: 
>1

>Enter the Desired Outputs (Labels) for training example[3]: 
>0

>Enter input to test:
>0 0
>Output: 0

>Enter input to test:
>0 1
>Output: 1

>Enter input to test:
>1 0
>Output: 1

>Enter input to test:
>1 1
>Output: 0ˋ

