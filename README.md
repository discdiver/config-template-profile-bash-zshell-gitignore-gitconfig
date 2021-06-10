# bash_profile

bash_profile with aliases 2021

```

# change command line prompt
export PS1="\W: "


# Aliases
alias gs="git status"
alias gr="git remote -v"
alias gi="git init"
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
