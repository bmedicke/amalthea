# Amalthea - collection of Jupyter notebooks

## creative coding

### perlin-noise

![perlin noise example 0](samples/perlin-noise-00.png)
![perlin noise example 1](samples/perlin-noise-01.png)
![perlin noise example 2](samples/perlin-noise-02.png)
![perlin noise example 3](samples/perlin-noise-03.png)

## venv setup

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
