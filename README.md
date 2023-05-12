# PPO-algorithm

If you like this repo, consider checking out CleanRL (https://github.com/vwxyzjn/cleanrl), the RL library that we used to build this repo.

## Get started

Prerequisites:
* Anaconda

Install dependencies:
```
conda create -n ppo_env python=3.8
```
```
conda activate ppo_env
```
```
pip install -r requirements.txt
```

Train agents:
```
python ppo.py
```

Train agents with experiment tracking:
```
python ppo.py --track --capture-video
```




