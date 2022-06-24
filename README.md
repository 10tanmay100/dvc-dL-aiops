# DVC - DL -TF -AIOPS demo

## commands -

### create a new env
```bash
conda create --prefix ./env python=3.7 -y
```

### activate the new env
```base
source activate ./env
```
## init GIT
```base
git init
```

### init DVC
```bash
dvc init
```

### create empty files -
```bash
touch README.md .gitignore setup.py dvc.yaml params.yaml
mkdir -p config /src/utils

touch config/config.yaml
touch config/secrets.yaml
```






