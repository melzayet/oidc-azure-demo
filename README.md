# oidc-azure-demo
This short demo shows how to access Azure Resources using GitHub OIDC provider as described here: https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/configuring-openid-connect-in-azure

To try it yourself:
- fork this repo
- setup Azure environment as described here: https://docs.microsoft.com/en-us/azure/developer/github/connect-from-azure
- give the AAD app access to some Azure Resources - preferrably read-only and least permissions
- create gihub secrets for azure subscription id (SUB_ID), AAD app client id (CLIENT_ID) and AAD tenant ID
- commit any change to the repo to trigger the GitHub action
