# Testbed for solving route and wavelength assignment (RWA) problems in optical networks using reinforcement learning

This project is built using the [Optical RL-Gym](https://github.com/carlosnatalino/optical-rl-gym).

We thank Carlos Natalino and Paolo Monti for open sourcing this project and for their ongoing support. 

# Installation:

```
git clone https://github.com/joshnevin/rwa_rl.git
cd rwa_rl
pip install -e .
```
To train RL agents we used the implementation of PPO with invalid action masking provided by the [Stable-Baselines 3 Contrib](https://github.com/Stable-Baselines-Team/stable-baselines3-contrib) repository, an extension of Stable-Baselines 3. 
This can be installed using 
```
pip install sb3-contrib
```





