# working-directories

This is a repository that has been created only for the purpose to learn how working directories in Terraform Cloud work.

# How I use this repository

1. I create a workspace in TFC with a Version Control Workflow to Github provider
2. On the workspace, go to Settings > General > Terraform working directory and fill in the exact path of the directory from the Github repository.
As an example, I used `path/working-directories` for this test.
3. Save the changes.
4. From the workspace, Actions > Start new run and check the plan and apply have been successful.

# Reference Documentation

- [Working Directories](https://www.terraform.io/cloud-docs/workspaces/settings#terraform-working-directory)
















