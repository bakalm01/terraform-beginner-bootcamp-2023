# Terraform Beginner Bootcamp 2023 

![TerraformBootCamp Arch](https://github.com/bakalm01/terraform-beginner-bootcamp-2023/assets/129691863/408fe6f9-3bd9-4f37-a8ce-5aaff2848e1d)

## Weekly Journals
- [Week 0 Journal](journal/week0.md)
- [Week 1 Journal](journal/week1.md)
  
## Extras
- [Github Markdown TOC Generator](https://ecotrust-canada.github.io/markdown-toc/)

## Terraform and Input Variables

### Terraform Cloud Variables
In terraform we can set two kind of variables:

- Enviroment Variables - those you would set in your bash terminal eg. AWS credentials
- Terraform Variables - those that you would normally set in your tfvars file
 
 We can set Terraform Cloud variables to be sensitive so they are not shown visibliy in the UI.

### Loading Terraform Input Variables
[Terraform Input Variables](https://developer.hashicorp.com/terraform/language/values/variables)

### var flag
We can use the `-var` flag to set an input variable or override a variable in the tfvars file eg. `terraform -var user_ud="my-user_id"`

### var-file flag
- TODO: document this flag

### terraform.tvfars

This is the default file to load in terraform variables in blunk

### auto.tfvars
- TODO: document this functionality for terraform cloud
### order of terraform variables
- TODO: document which terraform variables takes presendence.