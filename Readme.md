# Models of Neural Systems - Computer Practical Solutions
# Author: Robert Tjarko Lange

This repository contains the solutions to different problems solved in the Bernstein Center for Computational Neuroscience Berlin class "Models of Neural Systems" taught by Richard Kempter in the Winter term 2018/2019.

More specifically, the notebooks contained in this repo implement the following models:

1. [Rosenblatt Perceptron](01_Rosenblatt_Perceptron.ipynb)
2. [Receptive Fields](02_Receptive_Fields.ipynb)
3. [Euler/Runge-Kutta Approximation of ODEs](03_Ordinary_Differential_Equations.ipynb)
4. [Integrate-and-Fire Neuron Model](04_Integrate_and_Fire_Model.ipynb)
5. [Channel Modeling](05_Channel_Modeling.ipynb)
6. [Hodgkin-Huxley Neuron Model](06_Huxley_Hodgkin_Model.ipynb)


## Repository Structure
```
SequentialBayesianLearning
+- 01_Rosenblatt_Perceptron.ipynb
+- 02_Receptive_Fields.ipynb
+- 03_Ordinary_Differential_Equations.ipynb
+- 04_Integrate_and_Fire_Model.ipynb
+- 05_Channel_Modeling.ipynb
+- 06_Huxley_Hodgkin_Model.ipynb
+- README.md: Project Documentation
+- requirements.txt: list of all required pip packages
```

## How to use this code
1. Clone the repo.
```
git clone https://github.com/RobertTLange/ModelsNeuralSystems && cd ModelsNeuralSystems
```
2. Create a virtual environment (optional but recommended).
```
virtualenv -p python MNS
```
Activate the env (the following command works on Linux, other operating systems might differ):
```
source MNS/bin/activate
```
3. Install all dependencies:
```
pip install -r requirements.txt
```
4. Run the notebook of your choice (e.g. :))
```
jupyter notebook 01_Rosenblatt_Perceptron.ipynb
```
