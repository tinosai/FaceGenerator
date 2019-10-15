## Project Overview

In the present notebook, how to build and train a Generative Adversarial Network (GAN) for the purpose of face generation. What you will learn here is not restricted to the computer vision field: a GAN can learn to generate any sort of data, from time series to videos.
<br />
GANs have been invented by Iain Goodfellow in 2014 and in the past 5 years they have been applied to a wide variety of problems.

## Project Instructions

### Instructions

1. Clone the repository on your computer. For those who are not familiar with command line utilities, GitHub has developed this command line utility.
   [GitHub Desktop](https://desktop.github.com/)
2. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions contained in the jupyter notebook.
3. Do not forget to download the celebrity face dataset whose link is included in the jupyter notebook.

__NOTE:__ Chances are part of the code may not run due to some missing packages. Please make sure to go through the notebook and retrieve all the necessary packages. In a future release, I will include the list of packages needed (in the form of a python environment file).

## GPU

Training this Neural Network will definitely take a long time. As a result, it would be a good idea to train on a GPU. On AWS, I believe a p2.xlarge instance should be enough for training (and keeping the costs limited).
In addition, I recommend that you only switch to GPU when you're about to train, and you instead write all your code while in a CPU environment to keep costs down.

## GitHub rendering Problems

Sometimes GitHub cannot render the jupyter notebook properly. In such a situation, go to the [nbviewer website](https://nbviewer.jupyter.org/) and copy and paste the URL address of the notebook so as to render it on the browser.
