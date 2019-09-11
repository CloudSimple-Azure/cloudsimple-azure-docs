--- 
title: Access Azure VMware Solution by CloudSimple - Portal 
description: Describes how to access VMware Solution by CloudSimple portal from Azure portal
infoBubbleText="Problems related to Site-toSite VPN between on-premises and Private Cloud network, routing issues, new routes configuration"
author: sharaths-cs 
ms.author: b-shsury 
ms.date: 09/06/2019 
ms.topic: article 
ms.service: azure-vmware-cloudsimple 
ms.reviewer: cynthn 
manager: dikamath
displayOrder=""
selfHelpType="generic"
supportTopicIds="32637617"
resourceTags=""
productPesIds="16733"
cloudEnvironments="public"
articleId="50595BF8-2B72-4910-AE39-65F3988E387C"
---

# Troubleshooting site-to-site VPN connectivity to CloudSimple 

## **Recommended steps**

1. Check if there are any bandwidth constraints on your on-premises VPN device. <br>
2. Check if any firewall or proxy for  blocking or throttling the traffic. <br>
3. Check with ISP for sub-optimal paths to the VPN public IP address. <br>
4. Check for Service Policy or QoS applied on L3 interface that caps speed or bandwidth. <br>
5. Check router or FW for high CPU or memory utilization. <br>
6. Check if an asymmetric path over WAN causing slowness or drops. <br>

## **Recommended documents**

[Site-to-Site VPN](https://docs.microsoft.com/en-us/azure/vmware-cloudsimple/vpn-gateway#set-up-a-site-to-site-vpn-gateway)