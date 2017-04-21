Machine Learning Notebooks
==========================

This project accompanies my [Introduction to TensorFlow](https://www.safaribooksonline.com/live-training/courses/introduction-to-tensorflow/0636920079460/) live online training. It contains the exercises and their solutions, in the form of [Jupyter](http://jupyter.org/) notebooks.

[![book](https://raw.githubusercontent.com/ageron/tensorflow-safari-course/master/images/intro_to_tf_course.png)](https://www.safaribooksonline.com/live-training/courses/introduction-to-tensorflow/0636920079460/)

If you are looking for the code accompanying my O'Reilly book, [Hands-on Machine Learning with Scikit-Learn and TensorFlow](http://shop.oreilly.com/product/0636920052289.do), visit my other GitHub project: [handson-ml](https://github.com/ageron/handson-ml).


# Installation

You will need [git](https://git-scm.com/) and [python](https://www.python.org/downloads/) (python 3 is recommended, but python 2 should work as well).

First, clone this repository:

    $ cd /your/development/directory
    $ git clone https://github.com/ageron/tensorflow-safari-course.git
    $ cd tensorflow-safari-course

If you want an isolated environment (recommended), you can use [virtualenv](https://virtualenv.readthedocs.org/en/latest/):

    $ virtualenv -p `which python3` env
    $ source ./env/bin/activate

Then make sure pip is up to date, and use it to install the required python packages:

    $ pip install --upgrade pip
    $ pip install --upgrade -r requirements.txt

If you prefer to use [Anaconda](https://www.continuum.io/), you can run the following command instead:

    $ conda install -c conda-forge tensorflow=1.0.0

Finally, launch Jupyter:

    $ jupyter notebook

This should start the Jupyter server locally, and open your browser. If your browser does not open automatically, visit [localhost:8888](http://localhost:8888/tree). Click on `index.ipynb` to get started. You can visit [http://localhost:8888/nbextensions](http://localhost:8888/nbextensions) to activate and configure Jupyter extensions.

That's it! Have fun learning TensorFlow.
