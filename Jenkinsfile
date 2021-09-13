pipeline{
agent any
stages{
stage("yaml"){
steps{
sh " git clone https://github.com/DEFINATE-RGB/kubenetes.git "
}
}
stage("pod creation"){ 
steps{
sh " kubectl create -f /root/kubenetes/kube-deploy.yaml "
}
}
}
}
