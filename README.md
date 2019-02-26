# faceswap-playground

This repo has been opened for users playing with the project. 

Sadly the project is not yet ready to use for non-technical people, it will improve over time, so check for updates regularly and discuss with others. 

## What can you do here?
 - Discuss your experience with the project
 - Help people having trouble running it
 - Add guidelines and help newcomers

**If you are a more experienced user** you can help by proposing solutions for better user experience. Ideally, the goal is to get to a release that can be used by non-technical people.

## Quick start
Get the code from the main 'faceswap' repo and set it up (setup section below)

The project has multiple entry points. You will have to:
 - Gather photos (or use the one in the training data provided below)
 - **Extract** faces from your raw photos
 - **Train** a model on your photos (or use the one in the training data provided below)
 - **Convert** your sources with the mode
 
 Read the full instructions at https://github.com/deepfakes/faceswap/blob/master/USAGE.md

### Extract
Run `python faceswap.py extract -h`.

### Train
Run `python faceswap.py train -h`.

### Convert
Run `python faceswap.py convert -h`.

## Setup

Follow the directions at https://github.com/deepfakes/faceswap/blob/master/INSTALL.md

**Main Requirements:**
    Python 3.6
    Opencv
    Tensorflow
    Keras

You also need an Nvidia GPU with CUDA support for best performance.  Minimum is 4gb of VRAM.
