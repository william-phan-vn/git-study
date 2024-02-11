Original document: https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/configuring-openid-connect-in-amazon-web-services

OpenID Connect (OIDC) allows your GitHub Actions workflows to access resources in AWS without needing to store the AWS credentials as long-lived GitHub secrets

Example: https://github.com/aws-actions/configure-aws-credentials

## Prerequisites

## Adding the identity provider (GitHub OIDC) to AWS IAM
https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_providers_create_oidc.html