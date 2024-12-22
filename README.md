**Terraform**
Terraform is an open-source **Infrastructure as Code (IaC)** tool developed by HashiCorp. It allows you to define, provision, and manage infrastructure using declarative configuration files.

**Key Features of Terraform**
1. **Infrastructure as Code**: Write human-readable configuration files to define your infrastructure.
2. **Cloud-Agnostic**: Supports multiple providers like AWS, Azure, Google Cloud, Kubernetes, and more.
3. **Resource Dependency Management**: Automatically understands dependencies and ensures resources are provisioned in the correct order.
4. **Execution Plans**: Previews changes before applying them to avoid unexpected modifications.
5. **State Management**: Keeps track of your infrastructure in a state file to manage updates effectively.
6. **Modularity**: Allows reusability through modules for consistent and scalable infrastructure.

**How Terraform Works**
1. **Write**: Define your infrastructure in `.tf` files.
2. **Initialize**: Use `terraform init` to set up the provider and download necessary plugins.
3. **Plan**: Run `terraform plan` to preview changes before applying them.
4. **Apply**: Use `terraform apply` to create or update resources.
5. **Destroy**: Use `terraform destroy` to clean up infrastructure when no longer needed.

**Why Use Terraform?**
- Simplifies infrastructure management.
- Reduces manual configuration errors.
- Enables collaboration through version-controlled files.
- Scales infrastructure efficiently across multiple environments.
