# commands for initialization

### git clone
```bash
git clone git@github.com:moritamori/jupyter-notebook.git
```

## create notebooks directory
````bash
mkdir ./notebooks
```

### put kaggle.json into secrets directory
```bash
mkdir ./notebooks/.secrets
cp ~/kaggle.json ./notebooks/.secrets
```

### docker build
```bash
docker-compose build
docker-compose up -d
```
