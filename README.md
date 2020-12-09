# Basic_ML_model
A single layer, with a single neuron ML model

The problem we will solve is to convert from Celsius to Fahrenheit,where the approximate formula is:
                         
                          f=c×1.8+32

We will give TensorFlow some sample **Celsius values (0, 8, 15, 22, 38)** and their corresponding **Fahrenheit values (32, 46, 59, 72, 100).** Then, we will train a model that figures out the above formula through the training process.

The libraries that used for the project:
* tenserflow
* numpy
* matplotlib

# Some Machine Learning terminology
* **Feature** — The input(s) to our model. In this case, a single value — the degrees in Celsius.

* **Labels** — The output our model predicts. In this case, a single value — the degrees in Fahrenheit.

* **Example** — A pair of inputs/outputs used during training. In our case a pair of values from celsius_q and fahrenheit_a at a specific index, such as (22,72).
