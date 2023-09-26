### Init
```sh
poetry new poetry_demo

poetry init
```

### Install
```sh
poetry add pendulum ghananews-scraper
poetry add "pendulum>=2.0.5"
poetry add pendulum==2.0.5

poetry remove pendulum
poetry show
poetry show ghananews-scraper
```

### Run Script
```sh
poetry run python demo.py
```

### Install Dependencies
```sh
poetry install
```
### Build
```sh
poetry build
```

### Publish
```sh
poetry publish
```

### Run Script
```sh
poetry run ghananews

poetry run greet Africa/Addis_Ababa
```

### Exports lockfile
```sh
poetry export -f requirements.txt --output requirements.txt
```

### Show environment
```sh
poetry env info

poetry update
```