# Messing With Cosign
This repository demonstrates example GitHub Actions that provide tighter control over deployments, allowing you to manage what gets deployed and what's permitted to run using various options. The focus is on utilizing Cosign for signing and verifying container images, along with AWS authentication using OIDC trusts.

## Features
* GitHub Actions for Secure Deployments: Example workflows that use Cosign, AWS and Github OIDC for enhanced security.
* Deployment Controls: Ensure only signed and verified images are deployed.
* Flexible Configuration: Beyond having to include required workflows, users can customize the github workflows however they want.
