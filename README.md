Introduction to TensorFlow
==========================

This project accompanies my [Introduction to TensorFlow](https://www.safaribooksonline.com/live-training/courses/introduction-to-tensorflow/0636920079460/) live online training. It contains the exercises and their solutions, in the form of a [Jupyter](http://jupyter.org/) notebook.

[![book](https://raw.githubusercontent.com/ageron/tensorflow-safari-course/master/images/intro_to_tf_course.png)](https://www.safaribooksonline.com/live-training/courses/introduction-to-tensorflow/0636920079460/)

If you are looking for the code accompanying my O'Reilly book, [Hands-on Machine Learning with Scikit-Learn and TensorFlow](http://shop.oreilly.com/product/0636920052289.do), visit this other GitHub project: [handson-ml](https://github.com/ageron/handson-ml).


# Installation

You will need [git](https://git-scm.com/) and [python](https://www.python.org/downloads/) (python 3 is recommended, but python 2 should work as well).

First, clone this repository:

    $ cd $HOME  # or any other development directory you prefer
    $ git clone https://github.com/ageron/tensorflow-safari-course.git
    $ cd tensorflow-safari-course

Next, make sure you are using a recent version of pip (replace `pip3` with `pip` if you prefer using Python 2):

    $ pip3 install --user --upgrade pip

If you want an isolated environment (recommended), you can use [virtualenv](https://virtualenv.readthedocs.org/en/latest/):

    $ pip3 install --user --upgrade virtualenv
    $ virtualenv -p `which python3` env
    $ source ./env/bin/activate

Then use pip to install the required python packages (again, replace `pip3` with `pip` if you are using Python 2). If you are not using virtualenv, you should add the `--user` option (or use `sudo` if you know what you are doing).

    $ pip3 install --upgrade -r requirements.txt

If you prefer to use [Anaconda](https://www.continuum.io/), you can run the following command instead:

    $ conda install -c conda-forge tensorflow=1.0.0

Make sure everything is correctly installed by launching the following command. It should not display anything (replace `python3` with `python2` if needed):

    $ python3 -c 'import tensorflow, numpy, jupyter, matplotlib'

Finally, launch Jupyter:

    $ jupyter notebook

This should start the Jupyter server locally, and open your browser. If your browser does not open automatically, visit [localhost:8888](http://localhost:8888/tree). Click on `Introduction to TensorFlow.ipynb` to get started.

That's it! Have fun learning TensorFlow.

