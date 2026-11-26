# Reinforcement Learning Algorithms from Scratch

A collection of **16 Reinforcement Learning implementations** built in Python and Jupyter Notebooks, progressing from tabular methods to deep RL architectures.

---

> **Attribution & Learning Context:** These implementations were built while following *Reinforcement Learning using Python* course by *Tech Entertaining* on youtube, with further debugging, improvements, and modifications to work with updated tools and libraries.

---

# Running Instructions

1. Clone the repository:
   ```bash
   git clone [https://github.com/PrinceA08999/Reinforcement-Learning.git](https://github.com/PrinceA08999/Reinforcement-Learning.git)
   cd Reinforcement-Learning
   ```

> Support for python 3.10 and below has been depreciated for Keras 3, and python 3.14 is not supported yet. Esure to install python 3.11, 3.12, or 3.13 for an error-free Keras installation.

2. Create and activate a Conda environment with Python 3.12:
   ```bash
   conda create -n rl-env python=3.12
   conda activate rl-env
   ```

3. Install the required libraries:
   ```bash
   pip install numpy matplotlib hmmlearn gymnasium tensorflow
   pip install --upgrade keras
   ```

3. Install an interactive runner (choose one based on your preference):
   ```bash
   # For Jupyter Notebook in browser:
   pip install notebook
   
   # Or for running notebooks inside VS Code
   pip install ipykernel
   ```
