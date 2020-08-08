Environment variable

```
export TF_VAR_key_name=my-key
```


Dev env
```
terraform plan -var-file=dev-terraform.tfvars
```
Prod env
```
terraform plan -var-file=dev-terraform.tfvars
```terraform plan -var-file=prod-terraform.tfvars
