# Resilient-and-Reliable-Web-Hosting-over-Azure
Hosting a web application over azure virtual machine and then enabling backups and site recovery for it to recover in cases of disaster or failures

Hosting a web application made by of html, css over the azure windows server virtual machine using Internet Information services server role and making it available even at the times of natural disasters using Azure site recovery and enabling backup of the virtual machine to avoid single point of failure situation.

# Project description - 
Hosting a website on azure virtual machine installed with Internet information services role for hosting the website. Enabling backup for the virtual machine so that their stays redundancy and no single point of failure exist. Enabling Azure site recovery to protect the services hosted on virtual machine to stay available even at times of natural disasters or calamities and hence the website remains available for the users. With help of backups and site recovery the website is highly protected against the failures , issues , disasters , errors etc and is higly available at all times.

# Deployment Steps - 
1. Configuring a azure windows server 2019 virtual machine
2. Installing IIS role from add roles and features
3. Then hosting the web pages on IIS manager by creating index.html,style.css and the images you want to list in the website
4. Now create a backup for the VM so that there is no single point of failure and we can restore it if something got out wrong. 5. Open the virtual machine settings and select backup and then create a vault that will hold the backups and update the policy for backups and finally create the backup and start the initial backup.
6. Finally enable site recovery for a specific region so that the VM stays active even at time of a natural calamity or disaster and we can failover to that region so our services are still functional to users and when the disaster i over can again failover to our original. Open virtual machine settings and scroll to disaster recovery and then choose location of region where you want to failover and click on start replication to copy the exact virtual machine to the location you stated and wait till status gets healthy.
7. Now try to test the failover so that in case of actually failover we can check that no error occurs during that time. Click on test failover and after getting status successfull clean the test failover and now you are ready for the case when you actually needs to failover you can easliy fail the region you had specified. 

# Deployment URL - http://40.86.80.251/

![image](https://user-images.githubusercontent.com/61831401/172694820-dc7e3bba-c3c3-476f-9c42-48069142566c.png)

# Github pages URL - https://hackishanhack.github.io/Resilient-and-Reliable-Web-Hosting-over-Azure/
