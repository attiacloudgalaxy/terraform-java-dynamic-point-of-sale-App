# Terraform Dynamic Java Application on GKE

This repository contains the Terraform and the Kubernetes YAML deployed by the Jump Start Solution (JSS).
The source code for web application ("Point of Sale") deployed by this JSS can be found at  https://github.com/attiacloudgalaxy/terraform-java-dynamic-point-of-sale-App 

## Quickstart

Try out the Terraform in this repository.

### Prerequisites

* The Terraform has only been tested on [Google Cloud Shell](https://cloud.google.com/shell).
* You environment will need:
    * `terraform`
    * `gcloud`
    * `kubectl`
    * `sed`

### Steps

#### 1. Clone this git repository.

```
git clone git clone https://github.com/GoogleCloudPlatform/terraform-example-java-dynamic-point-of-sale
```

#### 2. Go into the `infra/` folder.

```
cd terraform-example-java-dynamic-point-of-sale/infra
```

#### 3. Run the Terraform.

```
terraform init
terraform apply -var 'project_id=MY_PROJECT_ID'
```

Replace `MY_PROJECT_ID` with your [Google Cloud Project](https://cloud.google.com/resource-manager/docs/creating-managing-projects) ID. We recommend creating a new project so you can easily clean up all resources by deleting the entire project.

You may need to type "Yes", when after you run `terraform apply`.

#### 4. Get the IP address of the deployment.

TBD


## License

Apache 2.0 - See [LICENSE](LICENSE) for more information.
