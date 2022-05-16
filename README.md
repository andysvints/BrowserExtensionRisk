# BrowserExtensionRisk

Identify installed browser extensions and risk associated with them. Supported browsers: FireFox, Chrome, Edge and Internet Explorer.
Browser extensions risk rating is being assessed using [crxcavator.io](https://crxcavator.io/) API.

Forked from [PowershellIT #5 – Check Browser Extensions](https://github.com/andysvints/PowerShellIT/tree/master/PowerShellIT%20%235%20-%20Browser%20Extensions)

## Install Module

```powershell
    Install-Module -Name BrowserExtensionRisk 
```

## Cmdlets

```powershell
    Get-ExtensionRiskRating
    Get-ChromeInstalledExtension
    Get-FirefoxInstalledExtension
    Get-InstalledBrowserExtension
```

## Dependencies

This module has no dependencies.