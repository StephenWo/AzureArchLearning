#AzureStorageStrategy

## Storage Account
* Blob
* File
* table
* Queue

## Managed Disk 
* VHDs, only for VMs
* Ultra SSD
* Premium SSD
* Standard SSD
* Standard HDD

## Unmanaged Storage vs Managed Storage

## Premium vs Standard Storage

## Storage Access Tiers
* Premium Performance
* Hot Access
* Cool Access
* Archive Access

## Azure BLOB Storage Lifecycle
* Hot Tier, 48 hrs. $0.02/GB/month, $0,004/10000 read
* Cool Tier, 30 days, $0.015/GN/month, $0.01/10000 read
* Archive Access, 1 year, $0.002/GB/month, $5.00/10000 read

## Durability
* 11 nines
* 3 redundant LRS/ZRS, same region , different data centesr
* 6 redundant GRS/RA-GRS

## Performance and Scaling

## Additional Data Storage
* Data Lake, HDFS, Unlimited storage
* Recovery Services Vault
* Azure Data Box, physical box for data transfer
* StorSimple 

## Storage Security
* Control of the access keys
* RBAC, Azure AD
* Azure Key Vault, standard or HSM
* Setup virtual network to the resource
* Data is encryoed using Keys for Blobs, Tables, Files and Queues on disks, 
  keys can be own key stored in Azure Key Vault
* Shared Access Signature
* HTTPS always

## Copy files with AzCopy

