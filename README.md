# helm-charts
k8s helm charts

## Confgiure github as help repo
### git clone the repo
### create  index.yaml for helm repo
        helm repo index
        git push the index.html to the repo
### configure help repo 
        helm repo add develop https://raw.githubusercontent.com/shridharMe/helm-charts/develop/
        helm repo add master  https://raw.githubusercontent.com/shridharMe/helm-charts/master/
 
