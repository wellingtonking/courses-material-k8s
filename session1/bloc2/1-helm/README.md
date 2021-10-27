# Helm Training and Demo Material

## Course Setlist

Default `helm` create:

```sh
helm create $NAME
```

Using _Helm starter scaffolds_:

Example scaffold repository: <https://github.com/wellingtonking/courses-helm-starter-scaffolds>

```sh
git clone git@github.com:wellingtonking/courses-helm-starter-scaffolds.git $HOME/.helm/starters/
# or on macOS
git clone git@github.com:wellingtonking/courses-helm-starter-scaffolds.git $HOME/Library/helm/starters/

# Then, to use your scaffold:
helm create --starter minimal my-minimal-chart-example
```

To debug your Helm chart:

```sh
helm lint
```

```sh
helm template .
```

```sh
helm install --dry-run --debug my-test-deploy .
```
