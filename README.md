# Machine Learning Zoomcamp 2025

## Getting started 

``` bash 
brew install uv
uv python install --preview
uv init <DIR>
cd <DIR>
vi .gitignore
# ---- add to .gitignore ---- #
# IPython Notebook Checkpoints
.ipynb_checkpoints
# ------------ end ---------- #
uv pip install jupyter numpy pandas scikit-learn seaborn
uv venv
uv pip install jupyter numpy pandas scikit-learn seaborn
git remote add origin git@github.com:42me/ml-zc-25.git
git branch -M main
git commit --allow-empty -m 'Empty initial commit'
git push -u origin main
uv run --with jupyter jupyter lab
```
