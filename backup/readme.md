Now enabling the azure backup over the windowsServer01 virtual machine so that there is no single point of failure and it can be restored if some errors or problems arise.

# Steps to create backup
1. Open the settings of the vm we want to enable backup and then click on backup in the settings.
2. Now choose the vault where the backups will be stored and select the resource group.
3. Now configure the backup policy and customize the frequency, time of backup, and days till the backup will last as according to need.
4. Now for intial setting backup click on backup now select the retain backup till date.
5. Now let the checks and internal processes for backup run and wait till backup gets completed.
6. We can check the status of tasks in the backup jobs section of the vault.
7. Whenever needed we can simply restore from the backup and again make our virtual machine consistent.

![01vaultname](https://user-images.githubusercontent.com/61831401/173176684-1628b8fd-9262-45b9-806b-734968d3e2b4.png)

![07backup jobs completed](https://user-images.githubusercontent.com/61831401/173176694-ba0338b2-48b9-4e3f-9837-a617d9697aa6.png)
