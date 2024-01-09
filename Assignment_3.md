# Assigment 3

### Assignment
The third Assignment is to adjust the storage account you just created. Add the following parameters to the storage account:

- accessTier: 'Hot'
- allowBlobPublicAccess: false
- supportsHttpsTrafficOnly: true

Also make accessTier a paramter which only allows the possible values.

If you don't have any azure subscription make an ARM template through the Bicep tools it see what it looks like. Please note that the second deployment will go quicker since the resource already exists.

### Useful links

- https://learn.microsoft.com/en-us/training/paths/fundamentals-bicep/