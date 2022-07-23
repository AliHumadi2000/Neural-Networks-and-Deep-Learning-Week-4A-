# Neural-Networks-and-Deep-Learning-Week-4A-
Welcome to your week 4 assignment (part 1 of 2)! Previously you trained a 2-layer Neural Network with a single hidden layer. This week, you will build a deep neural network with as many layers as you want!

In this notebook, you'll implement all the functions required to build a deep neural network.
For the next assignment, you'll use these functions to build a deep neural network for image classification.
By the end of this assignment, you'll be able to:

Use non-linear units like ReLU to improve your model
Build a deeper neural network (with more than 1 hidden layer)
Implement an easy-to-use neural network class
Notation:

Superscript  [𝑙]  denotes a quantity associated with the  𝑙𝑡ℎ  layer.
Example:  𝑎[𝐿]  is the  𝐿𝑡ℎ  layer activation.  𝑊[𝐿]  and  𝑏[𝐿]  are the  𝐿𝑡ℎ  layer parameters.
Superscript  (𝑖)  denotes a quantity associated with the  𝑖𝑡ℎ  example.
Example:  𝑥(𝑖)  is the  𝑖𝑡ℎ  training example.
Lowerscript  𝑖  denotes the  𝑖𝑡ℎ  entry of a vector.
Example:  𝑎[𝑙]𝑖  denotes the  𝑖𝑡ℎ  entry of the  𝑙𝑡ℎ  layer's activations).
Let's get started!

Important Note on Submission to the AutoGrader
Before submitting your assignment to the AutoGrader, please make sure you are not doing the following:

You have not added any extra print statement(s) in the assignment.
You have not added any extra code cell(s) in the assignment.
You have not changed any of the function parameters.
You are not using any global variables inside your graded exercises. Unless specifically instructed to do so, please refrain from it and use the local variables instead.
You are not changing the assignment code where it is not required, like creating extra variables.
If you do any of the following, you will get something like, Grader not found (or similarly unexpected) error upon submitting your assignment. Before asking for help/debugging the errors in your assignment, check for these first. If this is the case, and you don't remember the changes you have made, you can get a fresh copy of the assignment by following these instructions.
