24BAD023
DIVYADHARSHINI U G

What is a Perceptron?

A perceptron is the most basic building block of a neural network — think of it as a tiny decision-maker.
It takes some inputs, multiplies them by "weights" (importance values), adds them up, and then decides output 1 or 0 based on whether that sum crosses a threshold.
It "learns" by adjusting its weights whenever it makes a wrong guess, slowly getting better with practice — similar to trial and error.

What I Did:

Built the perceptron from scratch using NumPy .
Tested it on the AND gate: it correctly learned that output is 1 only when both inputs are 1 → got 100% accuracy.
Tested it on the OR gate: it correctly learned that output is 1 if at least one input is 1 → got 100% accuracy.
These worked perfectly because AND/OR are "easy" problems — a single straight line can cleanly separate the correct answers from the wrong ones.

Testing on a Dataset:

Created a random dataset of 300 points with some built-in noise and overlap.
Split it into training data (to teach the model) and testing data (to check how well it learned).
Scaled the numbers so all features are on the same range (helps the model learn better).

Training with Different Epochs:
Trained one model for 5 rounds → got 56.67% accuracy.
Trained another model for 15 rounds → got 66.67% accuracy.
This shows that more practice (epochs) = better accuracy, up to a point.
