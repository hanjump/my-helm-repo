#my-helm-repo

my-helm-repo click -> setting -> page -> branch 에서 main 선택 -> save
 => https://hanjump.github.io/my-helm-repo/ 생성됨
 
helm repo add github-myhelm-repo https://hanjump.github.io/my-helm-repo/
helm repo list
helm repo update

helm search repo my-helm-chart
helm install github-myhelm-web github-myhelm-repo/my-helm-chart
