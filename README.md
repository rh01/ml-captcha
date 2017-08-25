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

## MIT License


Copyright (c) [2017] [Shine]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
