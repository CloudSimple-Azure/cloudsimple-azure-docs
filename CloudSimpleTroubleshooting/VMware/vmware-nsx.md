--- 
title: Access Azure VMware Solution by CloudSimple - Portal 
description: Describes how to access VMware Solution by CloudSimple portal from Azure portal
author: sharaths-cs 
ms.author: b-shsury 
ms.date: 09/06/2019 
ms.topic: article 
ms.service: azure-vmware-cloudsimple 
ms.reviewer: cynthn 
manager: dikamath
displayOrder=""
selfHelpType="generic"
supportTopicIds=""
resourceTags=""
productPesIds="16733"
cloudEnvironments="public"
articleId="50595BF8-2B72-4910-AE39-65F3988E387C"
---

# Troubleshooting virtual machineware NSX 

## **Recommended steps**

1. Check that the distributed logical router (DLR) is created for the user defined route (UDR). <br>
2. Check that the DLR internal interface is attached to source subnet that needs UDR. <br>
3. Check that the DLR **internal** interface's IP address and subnet prefix length is the same as the source subnet that needs UDR. <br>
4. Check that the DLR has an uplink interface. <br>
5. Check tha the DLR interface is attached to the port group to which the virtual appliance or the next-hop is attached. <br>
6. Check that the DLR **uplink** interface's IP addrsss and subnet prefix length is the same as the source subnet that needs UDR. <br>
7. Check that the DLR's default gateway IP address is correct. <br>
8. Check that the DLR's static route for destination subnet exists and is configured correctly. <br>
9. Check that NSX distributed switch is not preventing communication between source and destination. <br>
10. Check if the destination virtual machine is attached to a DLR(UDR) which is blackholing traffic for the return traffic. - Need clarification <br>
11. Check that the  Source/Destination virtual machine is attached to the correct port group. <br>
12. Check that the  Source/Destination virtual machine IP, subnet mask and Default Gateway are configured correctly. <br>
13. Check if the virtual machine's OS Firewall rules block the traffic. <br>
14. Check that the virtual appliance has IP forwarding enabled or has proper routes. <br>

