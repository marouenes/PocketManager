# PocketManager

PocketManager is a python application that lets you track your money savings and spendings through time.
It facilitates the task by showing visuals (and soon a ML feature that makes it possible to predict your next spendings) 
and compare to others spendings by simply adding the JSON data file.

### This is an OOP python university project created by Louay Nahdi for educational purpose

## Setting up a development environement

We assume that you have `git` and `venv` and installed.

    # Clone the code repository into ~/dev/my_app
    ```bash
    mkdir -p ~/dev
    cd ~/dev
    git clone://github.com/marouenes/PocketManager.git my_app
    ```
    
    # Create the 'my_app' virtual environment
    ```bash
    python3 -m venv PATH/TO/my_app
    ```
    
    # Install required Python packages
    cd ~/dev/my_app
    pip install -r requirements.txt

## Runnig the app

    # Start the Flask development web server
    python3 main.py

Point your web browser to http://localhost:8080/

## Running the automated tests

    # Start the Flask development web server
    py.test tests/

## Libraries used :
    - DateTime : pip install DateTime
    - Json : built-in
    - PySimpleGUI : pip install PySimpleGUI
    - YAML : built-in
    - matplotlib : pip install matplotlib

