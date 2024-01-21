# eks-learn

https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/eks_cluster

arguments required
- name
- role_arn
- vpc_config

vpc_config arguments
- subnet_ids

https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/eks_node_group

arguments required
- cluster_name
- node_role_arn
- scaling_config
- subnet_ids