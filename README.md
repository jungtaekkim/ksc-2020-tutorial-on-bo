# ksc-2020-tutorial-on-bo

This repositority is for a part of [tutorial on Bayesian optimization](https://kiise.or.kr/conference/main/getContent.do?CC=KSC&CS=2020&PARENT_ID=010900&content_no=1263) at [KSC-2020](http://kiise.or.kr/conference/KSC/2020/).

## Step 0: Checking your computer OS and its configuration

We recommend running this tutorial on Linux (e.g., Ubuntu) with Python 3.x.

## Step 1: Cloning this repository

Clone this repository in any directory you would like to set it up.

```shell
$ git clone https://github.com/jungtaekkim/ksc-2020-tutorial-on-bo.git
```

## Step 2: Setting up Python environment and installing Python packages required

Create a virtual environment for Python with `virtualenv`.
If you prefer `conda`, you can use it instead.

```shell
$ virtualenv venv-tutorial-on-bo
$ source venv-tutorial-on-bo/bin/activate
```

Then, install the requirements pre-defined in `requirements.txt`.

```shell
# in ksc-2020-tutorial-on-bo directory
$ pip install -r requirements.txt
```

It will install [BayesO](http://bayeso.org) hosted in [the GitHub repository](https://github.com/jungtaekkim/bayeso).

## Contact
* Jungtaek Kim: [jtkim@postech.ac.kr](mailto:jtkim@postech.ac.kr)

## License
[MIT License](LICENSE)
