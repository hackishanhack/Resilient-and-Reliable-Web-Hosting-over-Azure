Site recovery is used to make services available even at times of disaster or natural calamity by shifting the traffic to another region where infrasrtucture is made redundant and functions till the original server do not gets in working state.

# Steps to configure Site Recovery
1. Firslt open the setting of the virtual machine where we want to enable site recovery.
2. Now choose disaster recovery and select in which region we wnat to failover are virtual machine for purpose of replication.
3. Now click on start replication and review the resources created like vaults, storages, resource groups etc.
4. Now wait till the virtual machine configurations are replicated in the desired region and gets 100% synchronized and gets healthy.
5. We can see the tasks and processes running in the site recovery jobs of the vault.
6. After successful replication we have to test failover the virtual machine to the desired region so that we can check if all things are working fine and at real time when we require to failover we can failover without any issues.
7. Now clean the test failover by writing some notes about the test failover.
8. Now are site recovery is fully enabled without any errors and we can simply failover by clicking on failover option to other region till our original server or region becomes running.

![01disaster recovery](https://user-images.githubusercontent.com/61831401/173177847-fc836fff-24ed-424b-a8c0-f59019df2c01.png)

![06successful replication](https://user-images.githubusercontent.com/61831401/173177864-8d0e6f80-9df0-403c-9c5c-5567b4a94569.png)

![07asr overview diagram](https://user-images.githubusercontent.com/61831401/173177876-7c390c48-1e1e-4b54-b010-91aba7a33e54.png)

![12failover when you require](https://user-images.githubusercontent.com/61831401/173177897-b27dd2aa-e8a8-4c62-b759-bcde4ce04487.png)
