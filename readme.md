# Amalthea - collection of Jupyter notebooks


<!-- vim-markdown-toc GFM -->

* [the notebooks](#the-notebooks)
  * [creative coding](#creative-coding)
    * [perlin-noise](#perlin-noise)
* [setup](#setup)
  * [venv](#venv)
  * [requirement management](#requirement-management)

<!-- vim-markdown-toc -->

## the notebooks

### creative coding

#### perlin-noise

![perlin noise example 3](samples/perlin-noise-03.svg)
![perlin noise example 0](samples/perlin-noise-00.svg)
![perlin noise example 4](samples/perlin-noise-04.svg)
![perlin noise example 2](samples/perlin-noise-02.svg)
![perlin noise example 1](samples/perlin-noise-01.svg)
![perlin noise example 5](samples/perlin-noise-05.svg)

## setup

### venv

```sh
# initial setup:
git clone https://github.com/bmedicke/amalthea.git
cd amalthea
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt

# subsequent starts:
source env/bin/activate # if not active.
jupyter notebook notebooks/

# if you don't want your browser to open add the flag: --no-browser
# to access the notebook from another device add: --ip=0.0.0.0
```

### requirement management

**installing libraries from git repos that are not on PyPI**

```sh
pip install -e git+https://github.com/pvigier/perlin-numpy#egg=perlin-numpy
```

**updating the `requirements.txt` file after adding or updating libs**

```sh
pip freeze > requirements.txt
```
