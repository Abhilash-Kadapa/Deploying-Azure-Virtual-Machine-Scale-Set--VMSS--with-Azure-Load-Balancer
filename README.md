**Deploying-Azure-Virtual-Machine-Scale-Set--VMSS--with-Azure-Load-Balancer**


[Implementation](https://github.com/Abhilash-Kadapa/Deploying-Azure-Virtual-Machine-Scale-Set--VMSS--with-Azure-Load-Balancer/tree/main/Deploying%20Azure%20Virtual%20Machine%20Scale%20Set%20(VMSS)%20with%20Azure%20Load%20Balancer)

[Screenshots](https://github.com/Abhilash-Kadapa/Deploying-Azure-Virtual-Machine-Scale-Set--VMSS--with-Azure-Load-Balancer/tree/main/Screenshots)


**Project Overview**

This project demonstrates how to deploy and configure an Azure Virtual Machine Scale Set (VMSS) integrated with Azure Load Balancer to build a highly available, scalable, and load-balanced web application in Microsoft Azure.

The implementation includes VMSS deployment, networking configuration, inbound rules, autoscaling setup, and web server installation using custom script extensions.

**Objectives**
- Deploy Azure VM Scale Set with multiple instances
- Configure Azure Load Balancer for traffic distribution
- Enable Autoscaling based on CPU utilization
- Install and configure NGINX web server
- Ensure high availability and fault tolerance

**Services Used**
- Azure Virtual Machine Scale Set (VMSS)
- Azure Load Balancer
- Azure Virtual Network (VNet)
- Network Security Group (NSG)
- Azure Monitor (Autoscaling)

**Key Features**
- High Availability Architecture
- Automatic Scaling (Scale In / Scale Out)
- Load Balanced HTTP Traffic (Port 80)
- Custom Script Extension for Web Server Setup
- Centralized Monitoring

**Outcome**
The deployed solution automatically distributes incoming traffic across multiple VM instances and scales based on workload demand, ensuring performance optimization and minimal downtime.
