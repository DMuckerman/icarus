# Installation

Create and activate a virtual environment for the project:
```sh
python3 -m venv env
source env/bin/activate
```

Install our pip dependencies:
```sh
pip install -r requirements.txt
```

Install the pre-commit hooks: (Yes Drew, this step comes last.)
```sh
pre-commit install
```

# Building for distribution

Windows:
```
python setup.py bdist_msi
```

Mac:
```
python setup.py bdist_mac
```

Linux:
Chris you can figure this one out
