# Hello! This file is for setting up our virtual environments

I just realized that we need our own python environment since we're not working on the school server anymore. This is a file on a kickstart for that.

What is a virtual environment?

--> A venv is an isolated and self contained workspace that allows for project configs and dependencies to be isolated so that it doesn't interfere/clash with your system or orther projects. Basically the goal is kinda similar to Docker (i think) where it's like u want to be able to reproduce the exact packages, modules, etc. that you were using at the time of development with other people, other computers, etc. 

anyways TLDR venv = good

## How to set up the virtual environment:

1. Go to the project directory

This will be inside your DeepLearningForSkinLesions repo.

2. Run this command
```
python -m venv .venv 
```
note that the name for the virtual environment will be .venv 

3. Activate the venv

run this command:
```
source .venv/Scripts/activate 
```

4. install our packages needed

```
pip install numpy scikit-learn matplotlib kagglehub ipykernel kagglehub[pandas-datasets]

#this is to be updated as we add more packaged 
```

## When ur done working 

u need to deactivate it 

run this command:
```
deactivate
```

DO THIS EVERY TIME !!!!!!

## When you want to return to work 

there is NO NEED to create the venv all over again, just run this command:

```
source .venv/bin/activate
```


## yippee!