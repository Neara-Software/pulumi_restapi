# RestAPI package for Pulumi
created from terraform provider, following https://www.pulumi.com/registry/packages/terraform-provider/installation-configuration/

## Instructions
- Install terraform provider plugin:
  ```bash
  pulumi plugin install resource terraform-provider
  ```
- Add Spacelift terraform provider (you'll need to create a dummy pulumi project)
  ```bash
  pulumi package add terraform-provider mastercard/restapi
  ```
- Copy files in the SDK folder to this repo and submit a phab
- Once approved, push a tag with the new version of the provider

