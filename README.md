# EB Docker Deploy

## Requirments

- Python(3.6)
- pipev
- Django(2.x)

### Secrets

#### `.secrets/base.json`

```json
{
    "SECRET_KEY": "<django secret key>"
}
```

## Installation

```
pipenv install
```

## Running

```
# Move project's directory
- pipenv install
- pipenv shell
- cd app
- export DJANGO_SETTINGS_MODULE=config.settings.local
.manage.py runserver
```
