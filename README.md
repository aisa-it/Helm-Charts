# AISA Helm packages repo
To use repo:
```
helm repo add aisa-it https://aisa-it.github.io/Helm-Charts/
```

## Adding new chart
Copy chart archive to `deploy` dir and reindex repo(exec in project root dir):
```
helm repo index .
```
