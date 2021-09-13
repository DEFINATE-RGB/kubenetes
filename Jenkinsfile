pipeline{
agent any
stages{
stage("yaml"){
steps{
sh " git clone https://github.com/DEFINATE-RGB/kubernetes.git "
}
}
stage("pod creation"){ 
steps{
sh " kubectl create -f /root/kubernetes/kube-deploy.yaml "
}
}
}
}
