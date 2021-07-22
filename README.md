This is the example code for https://dev.to/langyizhao/helm-charts-with-or-without-kustomize-1m9j-temp-slug-9736484

1. Example 1: `helm template without-kustomize -f values1.yaml`
> Expected last line: `args: ["/bin/echo Hello! My company name is ABC Company"]`

2. Example 2: `helm template without-kustomize -f values2.yaml`
> Expected last line: `args: ["/bin/echo My name is Gary. I work for Marketing department. Our company name is ABC Company"]`