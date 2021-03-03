<!-- # Naming Convention in Python
    modules (filenames) should have short, all-lowercase names, and they can contain underscores;
    packages (directories) should have short, all-lowercase names, preferably without underscores;
    classes should use the CapWords convention.


## CI Commands
flake8 . ;echo $?
coverage.sh


## develop
python3 -m venv env
export PYTHONPATH=$(pwd)
pytest --cov=lib  --cov-report html -


## Enviroment Variables

```
NETBILL_ADMIN=
NETBILL_BASEPATH=
NETBILL_SAMPLE_USERNAME=
``` -->
