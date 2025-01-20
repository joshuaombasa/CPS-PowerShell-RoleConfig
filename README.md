
# CloudProductivity-PSRoleCapabilities

This repository contains PowerShell role capability files designed for use in Just Enough Administration (JEA) endpoints. 

## Purpose

The role capability file in this repository defines a set of permissions and capabilities, including:

- Cmdlets (e.g., `Get-Process`, `Get-Service`)
- Modules (e.g., `Microsoft.PowerShell.Management`, `Microsoft.PowerShell.Utility`)
- Aliases (e.g., `gps` for `Get-Process`)
- Providers (e.g., `FileSystem`, `Registry`)
- Restrictive language mode for security

This is used to define administrative roles with controlled access to the environment.

## Role Capability File

The role capability file, `CloudProductivitySolutionsRole.psrc`, is used to create a restricted environment where users can run specific commands and interact with a limited set of system resources.

## Usage

1. Copy the role capability file to your JEA configuration directory.
2. Load the role capability file into your PowerShell session or use it in a JEA endpoint configuration.

https://github.com/joshuaombasa/CPS-PowerShell-RoleConfig/blob/main/CloudProductivitySolutionsRole.psrc

## License

(c) 2025 Cloud Productivity Solutions. All rights reserved.
