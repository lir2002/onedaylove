# One Day Love Helm Demo

## Branches:
- **Main**: Maintain helm chart source code
- **gh-pages**: Chosen as Github page of the repo, so serve as the Helm repo to store indexed helm package

## Helm USage:
- Add repo:
  > `helm repo add onedaylove https://lir2002.github.io/onedaylove`
- Search repo after adding repo:
  > `helm search repo onedaylove`
```
NAME                    CHART VERSION   APP VERSION     DESCRIPTION
lir2002/onedaylove      0.1.1           1.16.0          A Helm chart for Kubernetes
```
- Install package: 
  > `helm install one onedaylove/onedaylove`
- Test after installation:
  > `helm test one`