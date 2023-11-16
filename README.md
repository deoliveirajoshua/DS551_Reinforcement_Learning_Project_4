# DS551_Reinforcement_Learning_Project_4

## Robosumo Requirements
- Linux
- Conda or Python 3.7

## Robosumo installation:
### Mujoco
- Install mujoco binaries: https://github.com/openai/mujoco-py#install-mujoco
### patchelf
- sudo apt-get install -y patchelf
### GL libraries (rendering)
- sudo apt-get install -y libglew-dev
- export LD_PRELOAD=/usr/lib/x86_64-linux-gnu/libGLEW.so
### Conda env
- conda env create -f environment.yml
- alternatively: pip install -r requirements.txt
### robosumo
- git clone https://github.com/Robot-Learning-Library/robosumo_gym23
- cd robosumo_gym23 && pip install -e .

### (Optional) cuda
- TODO

## Run Robosumo Demo
- python demos/play.py