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

### 04 — Crear dos subredes

```
141  mkdir terraform-04-subnets
142  cd terraform-04-subnets
143  code .
144  clear
145  terraform init
146  terraform validate
147  terraform plan
148  terraform apply
149  terraform destroy
150  history
```

### 05 — Security Groups

```
154  mkdir terraform-05-security-group
155  cd terraform-05-security-group/
156  code .
157  terraform init
158  terraform validate
159  terraform plan
160  histor
```

### 06 — Internet Gateway y rutas

```
163  mkdir terraform-06-routing
164  cd terraform-06-routing
165  code .
166  terraform init
167  terraform validate
168  terraform plan
169  history
```

### 07 — EC2 dentro de una subnet

```
173  mkdir terraform-07-ec2-subnet
174  cd terraform-07-ec2-subnet/
175  code .
176  terraform init
177  terraform validate
178  terraform plan
179  history
```

### 08 — El proyecto empieza a crecer

```
183  mkdir terraform-08-organizacion
184  cd terraform-08-organizacion
185  code .
186  terraform init
187  terraform validate
188  terraform plan
189  history
```