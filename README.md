# Assessment: Object classification in Images

You can work on the assignment in one of two ways: locally on your own machine, or on a virtual machine on Google Colab.

## Setup

### Working remotely on Google Cloud (Recommended)

As part of this unit, you are recommended to use Google Colab for your assessment. It is recommended for anyone who is having trouble with installation set-up, or if you would like to use better CPU/GPU resources than you may have locally. I highly recommend using Google Colab with GPU support by selecting GPU in runtime type since your training will go much faster than this.

\b[Requirements] To use Colab, you must have a Google account with an associated Google Drive. Assuming you have both, you can connect Colab to your Drive with the following steps:

1. Click the wheel in the top right corner and select Settings.
2. Click on the Manage Apps tab.
3. At the top, select Connect more apps which should bring up a GSuite Marketplace window.
4. Search for Colab then click Add.

Please see the Google Colab GPU [set-up](https://towardsdatascience.com/getting-started-with-google-colab-f2fff97f594c) tutorial here for instructions.

Instructions
The assessment here provides you with a download link to a zip file containing Colab notebook. You can upload the folder to Drive, open the notebook in Colab and work on it, then save your progress back to Drive. It is important to note that If you are idle for a certain amount of time or your total connection time exceeds the maximum allowed time (~12 hours), the Colab VM will disconnect. It is very important to save your code whilst working on the assessment.

### Working locally on your machine

If you wish to work locally, you should use a virtual environment. You can install one via [Anaconda] (https://www.anaconda.com/products/individual) (recommended) or via Python’s native venv module. Ensure that you are using python 3.7 or older as Tensorflow does not support python 3.8. Anaconda provides an easy way for you to handle package dependencies where you can just download all the required packages by searching them in Anaconda.

Once you have Anaconda installed, it makes sense to create a virtual environment for the course as otherwise you have make sure that all the dependencies for your code are installed globally on your machine. To set up a virtual environment called DL, run the following in your terminal:

```
# this will create an anaconda environment
# called DL in 'path/to/anaconda3/envs/'
conda create -n DL python=3.7
```

To activate and enter the environment, run \b[conda activate DL] and select it from [environments] tab in Anaconda. To deactivate the environment, either run [conda deactivate DL] or just exit the terminal.



