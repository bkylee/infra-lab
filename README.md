# infra-lab
Yet another repo for projects and self-learning. 

Naming convention: 
I will follow the iac playbook https://iacplaybook.com/terraform/naming-conventions/
Use snake_case for all Terraform identifiers (resources, variables, outputs, locals, modules).
Use kebab-case for cloud resource names (the name argument passed to the provider).
Never abbreviate when the full word is reasonably short. Prefer database over db, network over net.
Avoid redundant prefixes. Do not repeat the resource type in the identifier (e.g. resource "aws_s3_bucket" "assets" not resource "aws_s3_bucket" "s3_assets_bucket").

