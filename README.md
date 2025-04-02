# AI for Fundamental Physics

This repository contains Jupyter notebooks and code exploring the application of artificial intelligence and machine learning techniques to problems in fundamental physics.

## Contents

- [Detecting the Higgs Boson with TPUs](detecting-the-higgs-boson-with-tpus-explained.ipynb): Jupyter notebook exploring the use of Tensor Processing Units (TPUs) for Higgs boson detection.

- [Cooling Directory](cooling/): A collection of notebooks and code exploring physics-based applications of machine learning:
  - [Temperature Prediction (temp_pred.ipynb)](cooling/temp_pred.ipynb): Neural network models and physics informed neural network model for predicting temperature dynamics in cooling systems, including implementation of L2 regularization techniques.
  - [Regularization Examples (regularisation_ex.ipynb)](cooling/regularisation_ex.ipynb): Demonstrates the application of regularization techniques in machine learning models to prevent overfitting, with visualizations comparing regularized vs. non-regularized polynomial regression.
  - [Neural Network Implementation (network.py)](cooling/network.py): Basic neural network architecture for solving physics-based problems.
  - [Differential Equations (diff_equations.py)](cooling/diff_equations.py): Implementation of fundamental cooling law equations and gradient calculation for physics-based machine learning.

## Getting Started

To run the notebooks in this repository:

1. Clone the repository:
   ```
   git clone https://github.com/BurnyCoder/ai-for-fundamental-physics.git
   ```

2. Install the required dependencies:
   ```
   pip install numpy torch matplotlib seaborn sklearn jupyter
   ```

3. Open the notebooks with Jupyter:
   ```
   jupyter notebook
   ```

## Physics Concepts and Machine Learning Applications

This repository demonstrates several key concepts at the intersection of physics and machine learning:

- **Particle Detection**: Using deep learning for identifying particle signatures in high-energy physics
- **Cooling Dynamics**: Applying neural networks to model and predict temperature changes in physical systems
- **Regularization Techniques**: Preventing overfitting in ML models applied to physics problems
- **Physics-Informed Neural Networks**: Incorporating physical laws and constraints into neural network architectures

## License

This project is open source and available under the [MIT License](LICENSE). 