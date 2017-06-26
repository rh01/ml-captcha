## Introduction

This repository belong to spider practice series.this tutorial mainly teach us to crack kaptcha with machine learning.from scratch with these steps:
* environment preparation.
* spider raw captcha image from specific site.
* split sequence to single character.
* using machine learning to bulid classifier.

## Requirements

* Jupyter notebook
* Anaconda3.6
* OpenCV3.1

## Example

You can create `conda virtual environment`, follow this command series.
```shell
conda create -ny kaptcha python=3.5.2

activate kaptcha
```

Enter **kaptcha** virtual env, you must install some required package with pip tools or conda tool.Enter into shell.

```shell
conda install -c menpo opencv2
pip install pillow
pip install sklearn
pip install matplotlib
pip install jupyter
```
installed above packages, you can go ahead this tutorial and start up notebook.

```bash
jupyter notebook
```

## License

![](https://img.shields.io/packagist/l/doctrine/orm.svg)
