# Resilient-and-Reliable-Web-Hosting-over-Azure
Hosting a web application over azure virtual machine and then enabling backups and site recovery for it to recover in cases of disaster or failures

Hosting a web application made by of html, css over the azure windows server virtual machine using Internet Information services server role and making it available even at the times of natural disasters using Azure site recovery and enabling backup of the virtual machine to avoid single point of failure situation.

1. Configuring a azure windows server 19 virtual machine
2. Installing IIS role from add roles and features
3. Then hosting the web pages on IIS manager by creating index.html,style.css and the images you want
4. Now create a backup for the VM so that there is no single point of failure and we can restore it if something got out wrong
5. Finally enable site recovery for a specific region so that the VM stays active even at time of a natural calamity or disaster and we can failover to that region so our services are still functional to users and when the disaster i over can again failover to our original.
