# Cookiecutter Python Project

[Cookiecutter](https://github.com/cookiecutter/cookiecutter) template for a Python project.

## How to use

[Install cookiecutter](https://cookiecutter.readthedocs.io/en/latest/installation.html).

Then run `cookiecutter gh:lucasmelin/cookiecutter-pyproject`. You'll be prompted for project configuration values, which will be used to generate a new project in the current directory.

## What is included

- Low-dependency Python project structure with many developer tools.
- 🤖 A [nox](https://nox.thea.codes/) [configuration]({{cookiecutter.project_slug}}/noxfile.py) with commands to publish your documentations to GitHub Pages and lint, format and test your project.
- 📃 Documentation using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) and [MkDocstrings](https://github.com/mkdocstrings/mkdocstrings) to automatically generate documentation based off of your function docstrings.
- 🧪 Testing structure using [pytest](https://docs.pytest.org/en/latest/).
- ✅ Code linting using [flake8](https://flake8.pycqa.org/en/latest/).
- 👮 [Bandit](https://github.com/PyCQA/bandit) and [Safety](https://pyup.io/safety/) to check for vulnerabilities in your code and your dependencies.