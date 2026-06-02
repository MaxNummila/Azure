# Azure Security Audit Lab Notes

## Goal of the lab
To build a small intentionally misconfigured Azure environment, audit it using Microsoft Defender for Cloud, document findings, and apply remediations to correctly configure it.

## Azure lab environment
- Resource group:
- VM:
- Storage account:
- Log Analytics workspace:
- Defender for Cloud:

### Notes during work
- 2.6 Started working on the lab
- Started by creating a **Resource Group** on Azure that I promptly named Security_Audit_Lab_RG
- I picked a recommended region and added a Description tag and created it.
  
- I then created a **Storage Account** named "securityauditlab".
- Selected the Resource Group, named it and chose LRS redundancy.
- I then checked that Secure transfer required was enabled.

- I then tried to create a **Virtual Machine** but no regions were available.
- I had to go to Subscriptions -> Resource providers to Register Microsoft.Compute to enable VM creation.
- After this I could create the VM in Sweden Central.
- Left it at the step before the VM creation since I ran out of time for today.
