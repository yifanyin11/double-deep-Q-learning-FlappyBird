# Playing FlappyBird with double deep Q-learning

Play the game 'Flappy Bird' using double deep Q-learning. The deep neural networks are implemented by PyTorch.

## Introduction
This project creates an intelligent agent that automatically learns how to play the game 'Flappy Bird', by following a double deep Q-learning scheme, which is described in _Deep Reinforcement Learning with Double Q-learning_[1]. By introducing the technique of experience replay, the algorithm performs well in learning stability. 

## Dependencies
- Python 3.9
- PyTorch 1.10.1
- pygame
- OpenCV

## Setup
_This program is to be run in Anaconda virtual environment._ Open Anaconda Prompt and go to a prefered directory for the following setups:
 
1. Install Torch from [PyTorch](https://pytorch.org/)

   _CUDA 11.3_
    ```
    conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch
    ```
   _CPU_
    ```
    conda install pytorch torchvision torchaudio cpuonly -c pytorch
    ```

2. Install pygame and OpenCV
   ```
   python3 -m pip install -U pygame --user
   conda install -c conda-forge opencv
   ```

3. Clone the repository
   ```
   git clone https://github.com/yifanyin11/double-deep-Q-learning-FlappyBird.git
   ```

4. Run the program
   ```
   cd double-deep-Q-learning-FlappyBird
   python ddqn_FlappyBird.py
   ```

## Functions
