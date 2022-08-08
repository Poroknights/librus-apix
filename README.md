
# Librus Synergia web scraper.

## Installation
```sh
pip install librus-apix
```
## Quick Start

### Getting the Math grades
```py
from librus-apix.get_token import get_token
from librus-apix.grades import get_grades

token = get_token("Username", "Password")
grades = get_grades(token)

for mark in grades["Mathematics"]:
    print(mark.grade)
```

## Working on the Project
```sh
git clone https://github.com/Poroknights/librus-apix
cd librus-apix
python -m venv venv
source ./venv/bin/activate
pip install requirements.txt
# Installing library with editable flag
pip install -e .
```
