# kafka 
Initially deploying to my own K8s cluster on-prem using these instructions: https://phoenixnap.com/kb/kafka-on-kubernetes


local machine(s): k8s-ubuntu and k8s-ubuntu-2

1) deploy zookeeper
$ kubectl create -f zookeeper.yml