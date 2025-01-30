# Learn Terraform Docker Container

This is a simple tutorial of Terraform 101 using AWS and Docker. The complete documentation and details in this [link](https://developer.hashicorp.com/terraform/tutorials/aws-get-started).

## Project usage

> You must have the Terraform installed in you machine

Before all, clone the repository and open in any code editor or IDE.

Run the command `terraform init` to initialise the project (only for fresh installation) with will downloads the required stuff to make infra works.

Once everything initialised, run `terraform apply` to serve the Docker container registered in `main.tf`. If everything runs OK the NGINX serve must up and be accessible in `http://localhost:8000`.

To stop the container just run `terraform destroy`.
