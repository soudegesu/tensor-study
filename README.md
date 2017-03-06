# tensor-study
Tutorial of TensorFlow

# Requirements
* [pyenv](https://github.com/pyenv/pyenv)
* [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv)
* anaconda3-4.1.0 or more

# How to setup
* create virtual environment with `conda`.
```
conda create -n tensor-study python=3.5 anaconda pip
pyenv activate anaconda3-4.1.1/envs/tensor-study
```

* install tensorflow
```
pip install --upgrade pip
pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.0.0-py3-none-any.whl
```

* execute jupyter notebook
```
jupyter notebook
```