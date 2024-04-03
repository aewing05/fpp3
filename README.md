Create virtual environment: `python3 -m venv fpp3`
Activate virtual environment: `source fpp3/bin/activate`

Install packages and freeze `python3 -m pip freeze > requirements.txt`
Later on, reinstall from requirements.txt `python3 -m pip install -r requirements.txt
`

Setting up ipython kernel for `python3 -m ipykernel install --user --name=fpp3`

Can now run `jupyter notebook` and select the fpp3 kernel
