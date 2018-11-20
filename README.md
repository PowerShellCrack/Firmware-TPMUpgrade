# Update Firmware for Dell Thunderbolt Dock

## Files
**Invoke-TPMUpgrade.ps1** - Detect TPM version and installs appropriate update. Does check for Bios password in plain text file BIOSPassword.txt (if exists). It will attempt to suspend bit locker if enabled. Also sets a SMSTS environment variable SMSTS_TPMUpdate, SMSTS_TPMRebootRequired which can be used for a reboot sequence. 

 
## Resources:
 - https://www.dell.com/support/article/us/en/19/sln312544/how-to-change-tpm-modes-12-20?lang=en
 - https://support.hp.com/us-en/document/c05381064