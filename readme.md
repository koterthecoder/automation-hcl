# Sample Automation Pipeline with Terraform

### Resources

- CodeCommit - Source control management
- CodeBuild - Infrastructure deployment, can also build executables
- CodePipeline - Staged deployments


### Steps


- Pipeline
    - State management `koterthecoder/remote-state-hcl`
    - Source
    - Development (buildspec.yaml)
        - Plan
        - Apply
    - > Logs & artifacts (S3)


## Pipeline Commands

### initialize the tf configuration
```terraform init```

### plan the tf deployment
```terraform plan -out code.tfplan```

### apply the deployment
```terraform apply "code.tfplan"```


### make note of code_commit_url


## Repo Commands

### get Git credentials from AWS console

### clone the repo locally and add files 
