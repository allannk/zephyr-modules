Installation
============

## West

Python package installation is a mess these days, but using a virtual environment for zephyr seems to work still


Create a new environment in the repository with, and then install west & zephyr dependencies

    python -m venv .venv
    ./.venv/bin/activate
    pip install west
    pip install -r sdk/zephyr/script/requirements.txt

Make sure both python, pip and west are the local ones, since e.g. "system" packages installed with pipx takes priority.

Also, for ESP there seems to be more packages missing from the requirements, namely
- 'pyserial' (don't install 'serial')
- 'pyelftools'