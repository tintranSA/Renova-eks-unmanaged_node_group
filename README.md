# unmanaged_node_group
1. To create an EKS node group, please use the below command
```
eksctl create nodegroup -f unmanaged_node_group.yaml
```
2. The process should be within 10 minutes.
3. Once the creation is done, we need to verify
```
eksctl get nodegroup --cluster <EKS_CLUSTER_NAME>
```
4. The output should be as follows:
[Uploading Bản sao của TRUNG TIN 150215.jpg…]()
