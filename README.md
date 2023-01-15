# stardust-backend
Backend of Stardust project. This project faciliate FastAPI framework to power the backend and it requires **latest python version** (>= 3.6).

## Run project in local (macOS)
### Setup virtual environment
1. Inside project directory run command: `python3 -m venv env`. The last `env` is virtual environemnt name and it can be anything but it's good practice to name it as `env` because of gitignore version control.
2. Activate environment: `source ./env/bin/activate`
3. Install packages: `pip install -r requirements.txt`
4. (Optionally If use VSCODE) Set virtual environment python as interpreter: `Cmd Shift P` then type `python interpreter`, select venv python version