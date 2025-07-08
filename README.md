# cookiecutter-python-gui

[![Documentation Status][docs_badge]][documentation]

Minimal [Cookiecutter] template for personal use.

## Getting Started

Install [Cookiecutter] and run the cookiecutter template:

```no-highlight
$ pip install cookiecutter
$ cookiecutter https://github.com/RR-AMATOK/cookiecutter-python-gui
```

Cookiecutter prompts you for information regarding your plugin:

```no-highlight
project_name [Type the name of the Project]: SAGE_PET
description [A simple description of the project]: Behold my PRIMORDIAL_PAWN!
author_name [Your Name]: AMATOK
author_github_handle [bugger-eater]: RR-AMATOK
version [0.1.0]:
Select license:
1 - MIT
2 - Clear BSD
Select Editor:
1 - VS Code
2 - None
Select the repository provider:
1 - Github
2 - None
```

Here is the structure of the files:

```no-highlight
project-name/
├── LICENSE
├── README.md
├── pyproject.toml
├── data
│   └── data.json
├── docs
│   └── index.md
├── functions
│   └── __init__.py
├── tests
│   ├── __init__.py
│   └── test_main.py
├── utilities
│   └── __init__.py
└── .gitignore
```

[![OSI certified][osi_certified]][OSI]
  [Cookiecutter]: https://github.com/audreyr/cookiecutter
