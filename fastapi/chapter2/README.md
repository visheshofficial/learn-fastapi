### Python

- know how to run python program
- Package Management
  - user virtual envs
  - use pipenv (<https://pipenv.pypa.io/en/latest/>) or poetry. Poerty is better. <https://python-poetry.org/>
    - pip and Poetry manage multiple packages in configuration files: requirements.txt for pip, and pyproject.toml for Poetry
    - You can specify desired package versions as minima, maxima, ranges, or exact values (also known as pinning).
- Source Formatting
  - Black
- Testing
  - Pytest
- Source control
  - git
- Web Tools
  - FastAPI - The web framework itself
  - Uvicorn - An asynchronous web server
  - HTTPie - A text web client, similar to curl
  - Requests - A synchronous web client package
  - HTTPX - A synchronous/asynchronous web client package
- use Type hinting
- Python is strongly typed at the object level But at the variable level, Python differs
  - Python enforces type safety at the object level, but variables themselves are flexible in terms of what type of object they can refer to. This combination of strong object typing and dynamic variable typing is what makes Python a strongly typed, dynamically typed language.
- Web Frameworks
- Django
- Flask
- FastAPI
  
```console

asdf plugin add pipx
asdf install pipx 1.5.0
pipx ensurepath

pipx install poetry
poetry config virtualenvs.in-project true

poetry new poetry-demo
poetry shell 
poetry install


```
