# Udacity Self Driving Car Nanodegree
## Build a Traffic Sign Recognition Program

### Overview
This is a project for Udacity's Self Driving Car Nanodegree. The objective is to train a  convolutional neural network for classification of traffic signs.

### Dataset
[German Traffic Sign Recognition Benchmark (GTSRB)](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset), a multi-class, single-image classification challenge held at the International Joint Conference on Neural Networks (IJCNN) 2011. The dataset consists of 43 classes and more than 50,000 images in total.

### Dependencies
- python==3.5.2
- numpy
- matplotlib
- jupyter
- tensorflow==0.12.1
- scikit-learn
- scipy
- pandas

### Installation
**Install Anaconda:**

Follow the instructions on the [Anaconda download site](https://www.continuum.io/downloads).

**Create environment:**

For users with CPU only, running this command will create a new `conda` environment that is provisioned with all libraries you need to run the iPython notebooks.

```
$ conda env create -f environment.yml
```

For users with GPU, ensure you have installed CUDA toolkit 8.0 and CuDNN v5. Then run the following command:

```
$ conda env create -f environment-gpu.yml
```

**Uninstall environment:**

To uninstall the environment:

```
$ conda env remove -n traffic-sign
```

**Activate environment:**

In order to use the environment, you will need to activate it. This must be done **each** time you open a new terminal window. 

```
$ source activate traffic-sign
```

To exit the environment, simply close the terminal window or run the following command:

```
$ source deactivate traffic-sign
```

### How to run

Download the [pickled GTSRB dataset](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/5898cd6f_traffic-signs-data/traffic-signs-data.zip), which images have already been resized to 32x32. 

Extract the `train.p`, `valid.p` and `test.p` files from the dataset zip file to the path `./traffic-signs-data/`

You can step through the Jupyter Notebook at [Traffic_Signs_Recognition.ipynb](https://github.com/raymondngiam/CarND-Traffic-Sign-Classifier-Project/blob/master/Traffic_Sign_Classifier.ipynb).

### Final report

You can view the final report of this project at [writeup.pdf](https://github.com/raymondngiam/CarND-Traffic-Sign-Classifier-Project/blob/master/writeup.pdf).
