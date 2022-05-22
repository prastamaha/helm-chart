# Add New Chart

```
helm lint charts/*
helm package charts/*
helm repo index --url https://prastamaha.com/helm-chart/ --merge index.yaml .

git add .
git commit -m "commit message"
git push origin <branch>
```
