TV Script Generation
Project Overview
This project is based on the TV Script Generation repo for the Udacity Deep Learning NanoDegree.

It generates its own Seinfeld TV scripts using RNNs and a Seinfeld dataset of scripts from 9 seasons. The Neural Network will generate a new, "fake" TV script.

Project Instructions
Instructions
Clone the repository and navigate to the downloaded folder.

	git clone https://github.com/HectorBudielE/udacity-tv-script-generation.git
	cd udacity-tv-script-generation
Make sure you have already installed the necessary Python packages according to the requirements.txt file.

Open a terminal window and navigate to the project folder. Open the notebook and follow the steps.

	jupyter dlnd_tv_script_generation.ipynb
NOTE: In the notebook, you will need to train RNNs in PyTorch. If your RNN is taking too long to train, feel free to pursue one of the options under the section Accelerating the Training Process below.

Project Information
Contents
Get the Data

Explore the Data

Implement Preprocessing Functions:

Lookup Table
Tokenize Punctuation
Pre-process all the data and save it
Build the Neural Network

Check Access to GPU
Input Batching
Test the Dataloader
Model
Defining Forward and Backpropagation
Neural Network Training

Train Loop
Hyperparameters
Training
Generate TV Script

Generate Text
Generate a New Script
(Optionally) Accelerating the Training Process
If your code is taking too long to run, you will need to either reduce the complexity of your chosen RNN architecture or switch to running your code on a GPU. If you'd like to use a GPU, you can spin up an instance of your own:

Amazon Web Services
You can use Amazon Web Services to launch an EC2 GPU instance. (This costs money)

Google Colab
You can run this notebook in Google Colab for free. You have to be careful about the access of the extracted data in the notebook.