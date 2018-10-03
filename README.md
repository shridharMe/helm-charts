# helm-charts
k8s helm charts

## Confgiure GitHub repo as Helm repo
### git clone the repo [this step is only required to upload the index.yaml]
        - create  index.yaml for Helm repo
        - run helm command to create index.yaml - helm repo index
        - git push the index.yaml to the repo
### configure helm repo 
        - helm repo add develop https://raw.githubusercontent.com/shridharMe/helm-charts/develop/
        - helm repo add master  https://raw.githubusercontent.com/shridharMe/helm-charts/master/
 
