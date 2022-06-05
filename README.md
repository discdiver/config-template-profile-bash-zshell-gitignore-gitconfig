# global .gitignore 2022
```
# Template part of https://github.com/github/gitignore/blob/main/Python.gitignore
.DS_Store

# Distribution / packaging
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
share/python-wheels/
*.egg-info/
.installed.cfg
*.egg
MANIFEST

# PyInstaller
#  Usually these files are written by a python script from a template
#  before PyInstaller builds the exe, so as to inject date/other infos into it.
*.manifest
*.spec

# Installer logs
pip-log.txt
pip-delete-this-directory.txt

# Unit test / coverage reports
htmlcov/
.tox/
.nox/
.coverage
.coverage.*
.cache
nosetests.xml
coverage.xml
*.cover
*.py,cover
.hypothesis/
.pytest_cache/
cover/



*.log
local_settings.py
db.sqlite3
db.sqlite3-journal

# Flask stuff:
instance/
.webassets-cache

# Scrapy stuff:
.scrapy

# Sphinx documentation
docs/_build/


# Jupyter Notebook
.ipynb_checkpoints

# IPython
profile_default/
ipython_config.py

# Environments
.env
.venv
env/
venv/
ENV/
env.bak/
venv.bak/

# mkdocs documentation
/site

# mypy
.mypy_cache/
.dmypy.json
dmypy.json
```

.gitconfig 2022
```
[core]
	editor = code -w
[init]
	defaultBranch = main
[user]
	name = Jeff Hale
	email = jeffmshale@gmail.com

```


# VS Code settings.json 2022
```
{
    "workbench.colorTheme": "Default Dark+",
    "security.workspace.trust.untrustedFiles": "open",
    "python.defaultInterpreterPath": "/Users/hale/opt/miniconda3/bin/python",
    "terminal.integrated.defaultProfile.osx": "zsh",
    "git.path": "/usr/bin/git",
    "jupyter.pythonExportMethod": "commentMagics",
    "python.formatting.provider": "black",
    "terminal.integrated.inheritEnv": false,
    "files.exclude": {
        "**/.git": false
    },
    "gitlens.showWelcomeOnInstall": false
}
```


# .zprofile
```
# Add Visual Studio Code (code)
export PATH="$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"

# add next line to .zshrc for terminal prompt customization
# PROMPT='%F{blue}%1~%f %# '


# Aliases
alias gs="git status"
alias gr="git remote -v"
alias gi="git init"
alias ga="git add "
alias gaa="git add -A"
alias gcm="git commit -m "
alias gpom="git push origin main"
alias gpo="git push origin "
alias gb="git branch"
alias gco="git checkout "

alias jl="jupyter lab"

alias cl="conda list"
alias cel="conda env list"
alias cnew="conda create -n xxx python=3.9"
alias cde="conda deactivate"
alias ca="conda activate "

alias tp="trash-put"

alias pi="pip install "
alias piu="pip install -U "
alias pipnew="pip install -U pandas numpy prefect scikit-learn seaborn plotly jupyterlab streamlit sqlalchemy psycopg2"


```








# bash_profile

bash_profile with aliases 2021

```

# change command line prompt
export PS1="\W: "


# Aliases
alias gs="git status"
alias gr="git remote -v"
alias gi="git init"
alias ga="git add "
alias gaa="git add -A"
alias gcm="git commit -m "
alias gpom="git push origin master"
alias gpo="git push origin "
alias gb="git branch"
alias gcob="git checkout "

alias jl="jupyter lab"

alias cl="conda list"
alias cel="conda env list"
alias cnew="conda create -n xxx python=3.9"
alias ce="conda env list"
alias cde="conda deactivate"
alias ca="conda activate "

alias tp="trash-put"

alias pi="pip install -U "

alias pipnew="pip install -U pandas numpy scikit-learn seaborn plotly jupyterlab streamlit sqlalchemy psycopg2"


# conda should add the following automatically upon install
# >>> conda initialize >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$('/Users/hale/opt/miniconda3/bin/conda' 'shell.bash' 'hook' 2> /dev/null)"
if [ $? -eq 0 ]; then
    eval "$__conda_setup"
else
    if [ -f "/Users/hale/opt/miniconda3/etc/profile.d/conda.sh" ]; then
        . "/Users/hale/opt/miniconda3/etc/profile.d/conda.sh"
    else
        export PATH="/Users/hale/opt/miniconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda initialize <<<

```
