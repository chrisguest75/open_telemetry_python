## Build and Run
To install locally you can clone the repo

```sh
export PIPENV_VENV_IN_PROJECT=1
pipenv install --three
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
export PIPENV_VENV_IN_PROJECT=1
pipenv install --three
git init
```


## Reosurces
### Open Telemetry
https://opentelemetry-python.readthedocs.io/en/stable/  

### Pipenv
https://pypi.org/project/pipenv/  

### Kind 
https://kind.sigs.k8s.io/docs/user/quick-start/  

### Helm
https://helm.sh/docs/  

### Jaegar
https://www.jaegertracing.io/  
https://github.com/jaegertracing/helm-charts  

