# Google Cloud Run Github Actions
A sample project with a Github Action for deploying to Google Cloud Run.

## Set Up

### Create Service Account
https://console.cloud.google.com/iam-admin/serviceaccounts?project=dylan-roy

https://cloud.google.com/run/docs/reference/iam/roles#additional-configuration

### Create Github Secrets
https://github.com/dylanroy/google-cloud-run-github-actions/settings/secrets

#### Github Secrets
Here we setup our Github Secrets
 - GCP_CREDENTIALS - Service Account
 - GCP_PROJECT - Google Project
 - GCP_APPLICATION - Google Service Account
