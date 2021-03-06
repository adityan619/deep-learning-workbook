# Deep Learning Workbook

The Jupyter notebook [deep-learning-workbook.ipynb](./deep-learning-workbook.ipynb) outlines a universal blueprint that can be used to attack and solve any machine learning problem. It is based on the workflow described in the book [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python).

## Usage Instructions

1. Set up your dev environment with [Jupyter](http://jupyter.org/), [Tensorflow](https://www.tensorflow.org/) & [Keras](https://keras.io/) (or any other ML framework). Follow [this guide](https://blog.keras.io/running-jupyter-notebooks-on-gpu-on-aws-a-starter-guide.html) if you wish to use a GPU on AWS.

2. Download the latest version of the workbook using the command:
```bash
wget https://raw.githubusercontent.com/aakashns/deep-learning-workbook/master/deep-learning-workbook.ipynb
```

3. Change the file name, title and kernel as desired. This notebook was originally written with the kernel `conda:tensorflow_p36` on the [AWS Deep Learning AMI](https://aws.amazon.com/marketplace/pp/B01M0AXXQB).

4. Follow the steps described in to notebook, filling in the blanks marked as `TODO`.

5. Once you're done building the final model, you can delete the cells containing instructions.

## Deep Learning Workflow

See the Jupyter notebook [deep-learning-workbook.ipynb](./deep-learning-workbook.ipynb) for the detailed step-by-step workflow for solving machine learning problems using Deep Learning. Following is a short summary of the workflow:

1. Define the problem at hand and the data you will be training on; collect the data or annotate it with labels.

2. Choose how you will measure success on your problem. Which metrics will you be monitoring?

3. Determine your evaluation protocol: hold-out validation? K-fold validation? Which portion of the data should you use for validation?

4. Develop a first model that does better than a basic baseline: a model that has "statistical power".

5. Develop a model that overfits.

6. Regularize your model and tune its hyperparameters, based on performance on the validation data.

## Credits

The Jupyter notebook is based on the universal workflow for machine learning outlined in the book [Deep Learning With Python](https://www.manning.com/books/deep-learning-with-python) by François Chollet, the author of [Keras](https://keras.io/). 
