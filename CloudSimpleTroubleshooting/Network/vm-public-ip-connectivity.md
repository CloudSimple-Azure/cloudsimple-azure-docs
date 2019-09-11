--- 
title: Access Azure VMware Solution by CloudSimple - Portal 
description: Describes how to access VMware Solution by CloudSimple portal from Azure portal
infoBubbleText="Problems related to inbound traffic through a Public IP address to an application in CloudSimple Private Cloud"
author: sharaths-cs 
ms.author: b-shsury 
ms.date: 09/06/2019 
ms.topic: article 
ms.service: azure-vmware-cloudsimple 
ms.reviewer: cynthn 
manager: dikamath
displayOrder=""
selfHelpType="generic"
supportTopicIds="32627556"
resourceTags=""
productPesIds="16733"
cloudEnvironments="public"
articleId="50595BF8-2B72-4910-AE39-65F3988E387C"
---

# Troubleshooting public ip address network connectivity 

## **Recommended steps**

1. Check if the virtual machine hosting the application is running. <br>
2. Check if the virtual machine's IP address, subnet mask or gateway configured correctly. <br>
3. If you are using NSX Distributed Firewall in your Private Clouds, check if it blocks access to that virtual machine. <br>
4. Check if the virtual machine's operating system firewall rules block the application's required ports. <br>
5. Check if there are firewall rules blocking any inbound or outbound traffic. <br>
6. Check if the public IP address is mapped to the correct virtual machine. <br>

## **Recommended documents**

[Public IP address](https://docs.microsoft.com/en-us/azure/vmware-cloudsimple/public-ips)<br>
[Firewall Rules](https://docs.microsoft.com/en-us/azure/vmware-cloudsimple/firewall#firewall-rules)<br>
[VLANs/Subnets](https://docs.microsoft.com/en-us/azure/vmware-cloudsimple/create-vlan-subnet)