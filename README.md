Terraform Basics

All interactions with Terraform occur via the CLI. Terraform is a local tool (runs on the current machine). The terraform ecosystem also includes providers for many cloud services, and a module repository. Hashicorp also has products to help teams manage Terraform: Terraform Cloud and Terraform Enterprise.

There are a handful of basic terraform commands, including:

terraform init
terraform validate
terraform plan
terraform apply
terraform destroy

These commands make up the terraform workflow that we will cover in objective 6 of this course. It will be beneficial for us to explore some basic commands now so that work alongside and deploy our configurations.

     1: Verify Terraform installation and version:         
              terraform -version
    
     2: Initialize Terraform Working Directory: 
              terraform init
              
     3: Validating a Configuration:  
              terraform validate
              
     4: Genenerating a Terraform Plan: 
            terraform plan
            
     5: Applying a Terraform Plan: 
            terraform apply
            
     6: Terraform Destroy: 
             terraform destroy

