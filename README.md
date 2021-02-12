# kubernetes-multi-node-cluster-over-aws
If we running kubernetes that means we have use kubenetes cluster that's why `<Cluster>` is a heart of the kubernetes. Kubernetes cluster  have one control-plane(master) and one node at minimum in maximum we have as we want. Control-plane manage the user's request and node manage the workload of the resources or provide resources to the user's.

Kubernetes cluster provides the organization more scalablity, availabilty, etc. 

At the learning stage we use the product `<minikube>` that gives the facilities of kubernetes cluster. 

### Making own kubernetes cluster over AWS cloud using Ansible
I have created three ansible role for master `<kube-master>`, node `<kube-nodes>`, and ec2-instance `<ec2-instance>`.


