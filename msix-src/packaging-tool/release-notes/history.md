---
title: MSIX Packaging Tool release notes
description: This article provides the full history of release notes for different versions of the MSIX Packaging Tool.
ms.date: 04/28/2021
ms.topic: article
keywords: windows 10, uwp, msix, msix packaging tool, insider program
ms.custom: Vibranium
---

# Release notes for the MSIX Packaging Tool

## Version 1.2023.118.0 - Public Version
- Portable Apps can now be packaged as MSIX Packages
- Added ability to edit files within a package using Package Editor
- Apply Trace fixup to your package from within the Package Editor
- Added feature to exclude dependent Windows services from MSIX packages
- MSIX Packaging Tool now monitors child processes during app installation

## Version 1.2022.1101.0
- Fixed a minor UI bug
- Fixed a localization bug

## Version 1.2022.1003.0
- Added support for auto application of PSF FixUps through Command Line Interface. The following PSF FixUps will be supported - FileRedirectionFixup, RegLegacyFixups, DynamicLibraryFixup, and EnvVarFixup
- PSF Scripts are now supported through the Command Line Interface
- Added support for new capabilities to the Package Editor
- Added support for new extensions - SearchPathOverride and InstallLocalVirtualization

## Version 1.2022.802.0
- Fixed a UI bug

## Version 1.2022.718.0
- Added support for null arguments during unattended installs
- Added support for unusual font files included in package
- Added support for start menu shortcuts

## Version 1.2022.512.0
- fixed a localization bug

## Version 1.2022.330.0
- Added driver detection to alert user if their application contains a driver during conversion
- General performance improvements and bug fixes

