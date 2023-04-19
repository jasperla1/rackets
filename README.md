Install pypoetry 
in terminal 
curl -sSL https://install.python-poetry.org | python3 -

add poetry to path
export PATH="$HOME/.local/bin:$PATH" (for mac)

in IDE open the project, select add new interpeter (poetry)
poetry file is in (mac) 
/users/MYUSER/library/application support/pypoetry/venv/bin/poetry 

install necessary dependencies

Running the app locally 
uvicorn rackets.main:app --reload


installing new dependencies via terminal (not in pycharm)
go to local projectfolder 
poetry add <Dependencie> 
this way it will be added to your local poetry.lock (do not manually change this)
