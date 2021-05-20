# Thycotic Secret Server - Terraform Provider

The Thycotic Secret Server Jenkins Plugin allows you to access and reference your Secret Server secrets for use in Jenkins builds.

## Usage

This plugin add the ability to include Secret Server Secrets into your build environment.

![build-environment](images/jenkins-build-environment.png)

This is allows you to include the `Base URL` of you Secret Server and `Secret ID` you wish to access.

Additionally you will need to include a valid credential provider.

![add-credential](images/jenkins-credential-provider.png)

You will now have the option to change the `kind` of credential you wish to add, to that of a `SecretServer User Credentials`.

After you have added your credentials to the build environment you can can use the secret in your build/s.

## Release notes

### 1.0-SNAPSHOT

- Initial release
