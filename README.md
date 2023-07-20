
### EKS
   
#### Clone project Hashicorp
   
```bash
  git clone https://github.com/hashicorp/learn-terraform-provision-eks-cluster.git
```

#### Init BDD connection
   
```bash
  source .env
```
```bash
  Terraform init
```
#### Init terraform
   
```bash
  terraform init
```
#### Plan (show AWS updates)
   
```bash
  terraform plan
```
### Apply and create your EKS (confirm with "yes")

```bash
  source .env
```
```bash
  terraform apply
```
#### Destroy your EKS
   
```bash
  terraform destroy
```
#### Check nodes
   
```bash
  kubectl get nodes
```