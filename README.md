# Neural Networks from Scratch

Welcome to the **Neural Networks from Scratch** repository! This project demonstrates the core building blocks of modern deep learning by implementing a complete neural network pipeline—without using high-level ML frameworks. It’s perfect for anyone who wants to understand how perceptrons, gradient descent, and multilayer architectures truly work “under the hood.”

## Features

- **Perceptron Classifier & Regressor**  
  A minimal implementation of the single-layer perceptron for both classification and regression tasks, showcasing the fundamentals of linear decision boundaries and weight updates.

- **Gradient Descent Optimizer**  
  Custom batch gradient descent with configurable learning rate, momentum, and convergence criteria.

- **Multi-Layer Perceptron (MLP)**  
  Flexible architecture supporting any number of hidden layers and units, with ReLU and sigmoid activations.

- **Forward & Backward Propagation**  
  End-to-end implementation of the feedforward pass and backpropagation algorithm, including gradient computation for weights and biases.

- **Custom Loss Functions**  
  Support for Mean Squared Error (MSE) and Binary Cross-Entropy (BCE), easily extendable for other objectives.

- **Hyperparameter Tuning**  
  Scripts to explore different learning rates, initialization strategies, and network depths, with automated plotting of loss curves and accuracy trends.

- **Visualization Tools**  
  Matplotlib-based plots for training loss, validation error, and decision boundaries, enabling clear insights into model convergence and performance.

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/neural-networks-from-scratch.git
   cd neural-networks-from-scratch
   ```

2. **Install dependencies**  
   ```bash
   pip install numpy matplotlib
   ```

3. **Run examples**  
   - Train a perceptron on a simple 2D dataset:  
     ```bash
     python examples/train_perceptron.py
     ```
   - Train an MLP on a noisy sinusoidal regression task:  
     ```bash
     python examples/train_mlp_regression.py
     ```

4. **Customize & Extend**  
   - Modify `models.py` to add new activation functions or layer types.  
   - Tweak hyperparameters in `config/` and rerun the training scripts.  
   - Add new datasets in `data/` and visualize results with the helper functions in `utils/`.

## Results

- Achieves near-perfect classification on linearly separable datasets.  
- Converges reliably on noisy regression targets within a few hundred epochs.  
- Hyperparameter sweeps demonstrate the impact of learning rate and network size on performance.

---

Feel free to explore, experiment, and contribute! Pull requests and issue reports are welcome.
