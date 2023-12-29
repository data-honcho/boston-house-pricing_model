### boston-house-pricing_model

## Software And Tools Requirements 

1. [GitHub Acount](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Cloning a repository
```
git clone https://github.com/data-honcho/boston_house_pricing.git
```

Create a new environment
```
conda create -p venv python==3.9.18 -y
```

Activating the new environment
```
conda activate venv/

or 

conda activate C:\Users\DAVID\Desktop\mlproject\boston-house-pricing_model\venvname
```

Deactivating new envrironment
```
conda deactivate
```

Installing libraries/packages with requirements.txt
```
pip install -r requirements.txt
``` 
__________________________________________________________________________________________
Configuring GitCLI with GitHub repository to use commands to push files to repository

Setting GitHub username to GitCLI
```
git config --global user.name
```
Setting GitHub email to GitCLI
```
git config --global user.email
```

__________________________________________________________________________________________
Git File Handling Commands

git add .
git status
git commit -m "commit message"
git push origin main