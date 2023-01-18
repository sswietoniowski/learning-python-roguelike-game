# Learning Python - Roguelike Game

This is sample implementation of a ['roguelike'](https://pl.wikipedia.org/wiki/Roguelike) game in Python.

This project is using venv (virtual environment) to manage dependencies.

To install dependencies run:

Linux/MacOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Windows:

```cmd
py -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

To save dependencies (if you want to change them) run:

```bash
pip freeze > requirements.txt
```

To run the game run (be sure to activate venv)):

```bash
python main.py
```

## Learning Resources

Based on [Roguelike Python Tutorial](https://youtube.com/playlist?list=PL43PN07AM4J9N2eiVn43s9h7uJgbZH9Gp) [:file_folder:](http://rogueliketutorials.com/).

Original code can be found [here](https://github.com/TStand90/tcod_tutorial_v2).
