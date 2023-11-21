
These script will provide the list of orphaned resources like Public ip, Managed Disk, Snapshots


## Steps to run
```bash
  Connect-AzAccount
  Update-AzConfig -DefaultSubscriptionForLogin <Subscription id>
  Get-AzSubscription
  .\Get-OrphanedPublicIP.ps1
  .\Get-OrphanedPublicIP.ps1
  .\Get-OrphanedPublicIP.ps1
```
