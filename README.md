mproving GANs Performance Using Reinforcement Learning
This project investigates the integration of Reinforcement Learning (RL), specifically Deep Q-Networks (DQN), with Generative Adversarial Networks (GANs) to address the challenges of mode collapse and training instability. It provides implementations and evaluations of Vanilla GAN, DCGAN, and a novel DQN-enhanced GAN architecture on the MNIST dataset.

📌 Project Objectives
Develop GAN models to generate handwritten digit images.

Compare performance of Vanilla GAN and DCGAN.

Integrate RL using DQN to dynamically tune the generator’s latent space input.

Improve image diversity, fidelity, and training stability using off-policy RL.

Evaluate results using Fréchet Inception Distance (FID) and visual inspection.

🧠 Methodology
Baseline GANs:

Implemented Vanilla GAN and DCGAN using TensorFlow/Keras.

Trained on MNIST dataset with standard loss functions and optimizers.

Reinforcement Learning Integration:

A DQN agent is introduced to adjust latent vectors fed into the GAN generator.

The agent uses the discriminator’s feedback as a reward signal.

Experience replay and epsilon-greedy policies are used for stable learning.

Evaluation:

Visual inspection of generated images.

FID scores to quantitatively measure performance.

📦 Tech Stack
Languages: Python

Libraries: TensorFlow, Keras, NumPy, Pandas, Matplotlib, SciPy, scikit-learn

RL Tools: Custom DQN implementation with experience replay

Dataset: MNIST handwritten digits
