# Trading Bot

Trading bot prototype app written in python, real time application will be written in C++ later.  

# Dependencies

Package manager used in this app is [uv](https://docs.astral.sh/uv/).  
To install uv, run:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```
Clone the repo and then run this command in the app folder
```bash
uv sync
```
which will
* Find or download an appropriate Python version to use.
* Create and set up your environment in the .venv folder.
* Build your complete dependency list and write to your uv.lock file.
* Sync your project dependencies into your virtual environment.
