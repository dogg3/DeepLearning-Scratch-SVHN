
### Douglas Landvik

[![github](https://cloud.githubusercontent.com/assets/17016297/18839843/0e06a67a-83d2-11e6-993a-b35a182500e0.png)][1][![linkedin](https://cloud.githubusercontent.com/assets/17016297/18839848/0fc7e74e-83d2-11e6-8c6a-277fc9d6e067.png)][2]

# DeepLearning from Scratch with SVHN dataset

An attempt to build a Deep Neural Network from scratch


## Dataset - http://ufldl.stanford.edu/housenumbers/
The ‘SVHN’ (Street View House Numbers) dataset is a real-world dataset that can be seen in a similar flavor to
MNIST but with a greater magnitude of data and harder examples. The images are obtained from hose numbers
in ‘Google Street View’. As with MNIST, there are 10 classes but ‘SVHN’ consist of labels with a range between 1
and 10. This report is outlying an attempt to implement a Neural Network from scratch, with the aim to
generalize well when predicting the label of an image of a number like the one in the dataset.

## Preprocessing

The X_training was having 73257 samples of images with 32x32x3 pixels. The X_test was having 26032 samples
of images with 32x32x3 pixels. The y_training was of the shape (73257,) with values of 1-10 and the y_test was
having the shape (26032,) with the same range of values. The preprocessing was made in 7 steps: Removing the
colors column with shape (3,), converting the y-values to a range of [0,9] instead of [1,10], reshaping the training
data to (73257, 1024), hot-encode the y-sets, visualize the y-distribution and scale the X and y values to values
between [0.1,0.99]. From the preprocessing phase, it could be noted that the dataset was rather unbalanced and
noisy as seen with the figures below.


## Installation

Jupyter notebook is needed to run.
Use the package manager [pip](https://pypi.org/project/jupyter/) to install foobar.

```bash
pip install jupyter
```

## Usage

To open the jupyter file run.

```bash
jupyter notebook final.ipynb
```

To open the machine learning files run.


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)



[1]: http://www.github.com/dogg3
[2]: https://www.linkedin.com/in/doggeland
