--- 
title: Access Azure VMware Solution by CloudSimple - Portal 
description: Describes how to access VMware Solution by CloudSimple portal from Azure portal
infoBubbleText="Problems related to internet access from VMs running in the Private Cloud"
author: sharaths-cs 
ms.author: b-shsury 
ms.date: 09/06/2019 
ms.topic: article 
ms.service: azure-vmware-cloudsimple 
ms.reviewer: cynthn 
manager: dikamath
displayOrder=""
selfHelpType="generic"
supportTopicIds="32637628"
resourceTags=""
productPesIds="16733"
cloudEnvironments="public"
articleId="50595BF8-2B72-4910-AE39-65F3988E387C"
---

# Troubleshooting internet connectivity from a VM 

## **Recommended steps**

1. Check if there are firewall rules blocking any outbound traffic. <br>
2. Check the VM network configuration: IP address, subnet mask and gateway. <br>
3. Check if the VM is attached to correct distributed port group. <br>
4. Check if the distributed port group has correct VLAN ID. <br>

## **Recommended documents**

[Use VLAN Information to Set Up a Distributed Port Group in vSphere](https://docs.microsoft.com/en-us/azure/vmware-cloudsimple/create-vlan-subnet#use-vlan-information-to-set-up-a-distributed-port-group-in-vsphere)<br>
[Firewall Rules](https://docs.microsoft.com/en-us/azure/vmware-cloudsimple/firewall#firewall-rules)<br>
[VLANs/Subnets](https://docs.microsoft.com/en-us/azure/vmware-cloudsimple/create-vlan-subnet/)