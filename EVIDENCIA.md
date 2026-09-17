# EVIDENCIA

## Comandos

### 00 — Configuración AWS Academy

> cd "D:\wc\devops\Clase Alberto (git)\01-TERRAFORM-CT01"

> mkdir terraform-00-configuracion

> cd terraform-00-configuracion

> terraform init

> terraform validate

### 01 — Primera EC2

> mkdir terraform-01-ec2

> cd terraform-01-ec2

> terraform init

> terraform validate

> terraform plan

> terraform apply

> terraform destroy

### 02 — Primer bucket S3

```
111  cd terraform-02-s3/
112  clear
113  ls
114  clear
115  terraform init
116  terraform validate
117  terraform plan
118  terraform apply
119  clear
120  terraform apply
121  terraform destroy
122  aws s3 rb s3:
123  aws s3 rb s3://primer-bucket-wilson
124  history
```

### 03 — Entender una VPC

```
128  mkdir terraform-03-vpc
129  cd terraform-03-vpc/
130  code .
131  terraform init
132  terraform validate
133  terraform plan
134  terraform apply
135  terraform state list
136  terraform destroy
137  history
```