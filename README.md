# Create IAM Role

1. Create Role
1. Choose EKS under "Choose the service that will use this role"
1. Choose EKS under "Select your case"
1. Give it a name

# Install eksctl

Instructions should be found [here](https://docs.aws.amazon.com/eks/latest/userguide/getting-started-eksctl.html)

# Create a cluster

Details can be found [here](https://docs.aws.amazon.com/eks/latest/userguide/create-cluster.html)

<pre>
# Example
eksctl create cluster \
--node-type p2.xlarge \
--name test \
--version 1.14 \
--region us-west-2 \
--fargate
</pre>
