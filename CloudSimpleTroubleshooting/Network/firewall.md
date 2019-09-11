--- 
title: Access Azure VMware Solution by CloudSimple - Portal 
description: Describes how to access VMware Solution by CloudSimple portal from Azure portal
infoBubbleText="Problems related to configured firewall rules and associated subnets, IPs, Public IP addresses"
author: sharaths-cs 
ms.author: b-shsury 
ms.date: 09/06/2019 
ms.topic: article 
ms.service: azure-vmware-cloudsimple 
ms.reviewer: cynthn 
manager: dikamath
displayOrder=""
selfHelpType="generic"
supportTopicIds="32637583"
resourceTags=""
productPesIds="16733"
cloudEnvironments="public"
articleId="50595BF8-2B72-4910-AE39-65F3988E387C"
---

# Troubleshooting firewall table and rules 

## **Recommended steps**

1. Check if the firewall table is attached to the correct subnet. <br>
2. Check if the firewall rules are configured on firewall table. <br>
3. Check that the virtual machine is using the correct distributed port group. <br> 
4. If you are using NSX Distributed Firewall, check if the firewall rules are correctly configured. <br>
5. If you are using NSX Distributed Firewall, check if the firewall rules are in the correct sequence. <br>
6. If you are using NSX Distributed Firewall, check if the **Applied to** field of the firewall rule is correct. <br>

## **Recommended documents**

[Firewall Table](https://docs.microsoft.com/en-us/azure/vmware-cloudsimple/firewall#add-a-new-firewall-table)<br>
[Firewall Rules](https://docs.microsoft.com/en-us/azure/vmware-cloudsimple/firewall#firewall-rules)<br>