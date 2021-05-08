# Amalthea - collection of Jupyter notebooks

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
