## Build and Run
To install locally you can clone the repo

```sh
pyenv install 3.8.0
pyenv local 3.8.0
export PIPENV_VENV_IN_PROJECT=1
pipenv install --pre --python $(pyenv which python)
pipenv shell
```

## Create Cluster

```sh
kind create cluster --name otel
```

## Cleanup

```sh
kind delete cluster --name otel
```

## Create from scratch
Notes for how I started off the project

```sh
pyenv install 3.8.0
pyenv local 3.8.0
export PIPENV_VENV_IN_PROJECT=1
pipenv install --pre --python $(pyenv which python)
git init
```


## Reosurces
### Open Telemetry
[open telemetry](https://opentelemetry-python.readthedocs.io/en/stable/)  
[getting started](https://opentelemetry-python.readthedocs.io/en/stable/getting-started.html)

### Kind 
https://kind.sigs.k8s.io/docs/user/quick-start/  

### Helm
https://helm.sh/docs/  

### Jaegar
https://www.jaegertracing.io/  
https://github.com/jaegertracing/helm-charts  

### Python
[pyenv](https://github.com/pyenv/pyenv)
[pipenv](https://pypi.org/project/pipenv/)

[connexion](https://connexion.readthedocs.io/en/latest/quickstart.html)


### Troubleshooting
Prerelease install of packages.
https://towardsdatascience.com/common-errors-and-how-to-solve-them-why-wont-it-lock-8f5e57111f23