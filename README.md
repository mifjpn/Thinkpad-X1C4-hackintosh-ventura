# Thinkpad-X1C4-hackintosh-ventura

## Overview
As you know, the X1 4thGen is a Skylake machine.
Therefore, Ventura cannot be installed because X1 4thGen is equivalent to MacBookPro13,1.
Amazingly, the developers have built a feature in WhateverGreen.kext to spoof the HD520 into Haswell.

That solved our Ventura installation problem.

You can install Ventura on your Skylake machine.

## Prepared bootloader
The bootloader prepared this time is OpenCore_NO_ACPI0.8.8.
Because I want to dual boot with Windows 11.
The NO_ACPI version can be used with confidence because it does not disguise itself when Windows is started.
However, it is sad that there is no release version and that ocvaridate is a Chinese version.

I set the scan policy to 0.
It also contains HfsPlus.efi.
Therefore, it can be used as it is for the installer.

## Acknowledgments

Thank you for providing patches and binary files related to ACPI.
Thanks also to other stakeholders.
