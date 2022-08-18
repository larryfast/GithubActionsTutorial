Tutorial for Github Actions

### Credentials

This is a critical part of providing proper security for our development activity. At this time we have not defined a design pattern for managing Credential use in Github Actions. Work with the Security Team to define one.

https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-a-repository

Example: Using OIDC to connect to AWS.  I haven't worked my way through this but AWS has an Action for Github that helps manage this.  The repo has good instructions. The other links below also seem useful.

https://github.com/aws-actions/configure-aws-credentials
https://www.eliasbrange.dev/posts/secure-aws-deploys-from-github-actions-with-oidc/
https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/about-security-hardening-with-openid-connect#example-subject-claims
https://www.youtube.com/watch?v=WKzVqFsOBSE&ab_channel=KaiHendry


