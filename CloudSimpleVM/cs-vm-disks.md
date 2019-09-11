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

### CloudSimple Virtual Machine Disks

You can manage disk assignments for the selected VM running on CloudSimple Private Cloud.

#### Adding a Disk

* Click **Add disk**.

* Configure each of the following settings by entering or selecting an inline option.

| **Item** | **Description** |
| ------------ | ------------- |  
| Name | Enter a name to identify the disk.  | 
| Size | Select one of the available sizes.  | 
| SCSI Controller | Select a SCSI controller. The available controllers vary for the different supported operating systems.  |
| Mode | Determines how the disk participates in snapshots. Choose one of these options: <br> - Independent persistent: All data written to the disk is written permanently.<br> - Independent, non persistent: Changes written to the disk are discarded when you power off or reset the virtual machine.  This mode allows you to always restart the VM in the same state. For more information, see the [VMware documentation](https://pubs.vmware.com/vsphere-51/index.jsp?topic=%2Fcom.vmware.vsphere.vm_admin.doc%2FGUID-CE98BEB7-B8D5-495B-B9CE-622A4B93AFC6.html). |

* Click **Save**.

#### Delete a Disk
On the Disks page, select the disk and click **Delete**.

#### CloudSimple Documentation

You can access Azure VMware Solution by CloudSimple Documentation by clicking here: [CloudSimple Documentation Site](https://docs.microsoft.com/azure/vmware-cloudsimple/) (This will open the link in a new browser tab).

#### Contact CloudSimple Support

You can create a support request by clicking here: [New support request](https://portal.azure.com/#blade/Microsoft_Azure_Support/HelpAndSupportBlade/newsupportrequest) (This will open the link in a new browser tab).
