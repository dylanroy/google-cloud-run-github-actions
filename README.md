# Google Cloud Run Github Actions
A sample project with a Github Action for deploying to Google Cloud Run.

### [Checkout The Step-By-Step Tutorial](https://towardsdatascience.com/deploy-to-google-cloud-run-using-github-actions-590ecf957af0)

## Set Up
In order to deploy this project on your own you just need to take the following steps.

### 1. Create Service Account
The first step will be to create a service account by going to your [GCP Console Service Account Admin](https://console.cloud.google.com/iam-admin/serviceaccounts).

After which will need to give the service account the following roles.
 - Cloud Build Service Account
 - Cloud Build Editor
 - Service Account User
 - Viewer

### 2. Create Github Secrets
You will next need to navigate to the Settings Dashboard where you can add the following Github secrets. For this repo the link will be the following if you want to navigate directly to the location for your repo.


https://github.com/dylanroy/google-cloud-run-github-actions/settings/secrets

Here we setup our Github secrets:  
 - **GCP_CREDENTIALS** - This is your service account credentials that you will need to generate in the Google Cloud Console.  
 - **GCP_EMAIL** - This is the email that identifies the service account that you have provided credentials for in the secret labeled GCP_CREDENTIALS.
 - **GCP_PROJECT** - Your Google Project that you will deploying to Cloud Run.  
 - **GCP_APPLICATION** - Your Google service account application name for your Cloud Run service.

## Resources
 - [GCP Console Service Account Admin](https://console.cloud.google.com/iam-admin/serviceaccounts)

Test-commit3
