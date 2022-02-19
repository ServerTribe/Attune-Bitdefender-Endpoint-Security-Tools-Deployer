Bitdefender Endpoint Security Tools (BEST), the GravityZone security agent, uses one installation package for any environment (physical or virtual). On Windows, GravityZone delivers the installation packages as executable kits, only in EXE format. This may be inconvenient if you want to deploy the agent via Windows Group Policy or any other third-party application that supports MSI packages.

The solution implies applying an MSI wrapper over Windows Downloader, the standard lite installer for BEST. This section provides the guidelines for downloading the installer and a few methods on how to deploy the BEST using the MSI package.

https://www.bitdefender.com/business/support/en/77209-87686-install-security-agents---use-cases.html