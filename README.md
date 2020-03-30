# project-tv-script-generation
 project-tv-script-generation
In this project, generate own Simpsons TV scripts using RNNs. Simpsons dataset of scripts from 27 seasons. The Neural Network build will generate a new TV script for a scene at Moe's Tavern.

Running using conda!
Run this in command line

Step 1: Create a new environment

conda create --name tv-script-generation python=3
Step 2: Use the new env

source activate tv-script-generation
Step 3: Install dependencies

conda install -c conda-forge tensorflow=1.2.0
conda install numpy jupyter notebook
Step 4: Open the notebook to run it

jupyter notebook dlnd_tv_script_generation.ipynb

Project structure

dlnd_image_classification.ipynb - Main project file.

dlnd_image_classification.html - Neural network script results file.

problem_unittests.py - Unit tests provided by Udacity.

helper.py - Help functions provided by Udacity.

