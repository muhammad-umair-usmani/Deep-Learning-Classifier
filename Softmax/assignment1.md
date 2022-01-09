Assignment-1
===================

In this assignment you will practice putting together a simple image classification pipeline, based on the k-Nearest Neighbor or the SVM/Softmax classifier. The goals of this assignment are as follows:

- understand the basic **Image Classification pipeline** and the data-driven approach (train/predict stages)
- understand the train/val/test **splits** and the use of validation data for **hyperparameter tuning**.
- develop proficiency in writing efficient **vectorized** code with numpy
- implement and apply a k-Nearest Neighbor (**kNN**) classifier
- implement and applay a binary class Support Vector Machine (**SVM**) classifier
- implement and apply a Multiclass Support Vector Machine (**Multi-Class SVM**) classifier
- implement and apply a **Softmax** classifier
- understand the differences and tradeoffs between these classifiers. 

**Please note that this assignment is a slightly modified version of CS231n assignment. If you have any questions, you are welcomed to ask on Piazza**


**Installing Dependencies and Required Softwares:** To complete the assignment you will need a working ipython with required dependencies on your machine. To make the process easy you can simply download the [Anaconda](https://www.continuum.io/downloads) for your desired OS. For Amazon aws please see following [tutorial](http://cs231n.github.io/aws-tutorial/), remember it is recommended to use spot instances instead of fix cost.

**Start IPython:**
You should start the IPython notebook server from the `assignment1` directory.

```ipython notebook```

If you are unfamiliar with IPython, you should read the refersher on the 
[IPython tutorial](http://cs231n.github.io/python-numpy-tutorial/).

### Downloading CIFAR 10 dataset:
For downloading the dataset either run the file "cs231n/datasets/get_datasets.sh" from your terminal or directly download the dataset from this [link](http://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz) and extract it in the following folder (cs231n/datasets/)

### Submitting your work:
Once you are done working produce a file called `assignment1.zip` and upload this file on the slate page for the course.

### Q4: Implement a Softmax classifier (30 points)

The IPython Notebook **softmax.ipynb** will walk you through implementing the Softmax classifier.
