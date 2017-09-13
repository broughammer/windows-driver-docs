---
title: OID_WDI_GET_PM_PROTOCOL_OFFLOAD
author: windows-driver-content
description: OID_WDI_GET_PM_PROTOCOL_OFFLOAD requests a list of protocol offloads for power management.
ms.assetid: ed7604fa-666c-4aa1-9041-ed56d282c29b
ms.author: windowsdriverdev 
ms.date: 07/18/2017 
ms.topic: article 
ms.prod: windows-hardware 
ms.technology: windows-devices 
keywords:
 - OID_WDI_GET_PM_PROTOCOL_OFFLOAD Network Drivers Starting with Windows Vista
---

# OID\_WDI\_GET\_PM\_PROTOCOL\_OFFLOAD


OID\_WDI\_GET\_PM\_PROTOCOL\_OFFLOAD requests a list of protocol offloads for power management.

| Scope | Set serialized with task | Normal execution time (seconds) |
|-------|--------------------------|---------------------------------|
| Port  | Not applicable           | 1                               |

 

## Get property parameters


| TLV                                                                                  | Multiple TLV instances allowed | Optional | Description          |
|--------------------------------------------------------------------------------------|--------------------------------|----------|----------------------|
| [**WDI\_TLV\_PM\_PROTOCOL\_OFFLOAD\_GET**](https://msdn.microsoft.com/library/windows/hardware/dn898034) |                                |          | Protocol offload ID. |

 

## Get property results


| TLV                                                                                                         | Multiple TLV instances allowed | Optional | Description                            |
|-------------------------------------------------------------------------------------------------------------|--------------------------------|----------|----------------------------------------|
| [**WDI\_TLV\_PM\_PROTOCOL\_OFFLOAD\_IPv4ARP**](https://msdn.microsoft.com/library/windows/hardware/dn898035)                |                                | X        | IPv4 ARP protocol offload parameters.  |
| [**WDI\_TLV\_PM\_PROTOCOL\_OFFLOAD\_IPv6NS**](https://msdn.microsoft.com/library/windows/hardware/dn898036)                  |                                | X        | IPv6 NS protocol offload parameters.   |
| [**WDI\_TLV\_PM\_PROTOCOL\_OFFLOAD\_80211RSN\_REKEY**](https://msdn.microsoft.com/library/windows/hardware/dn898033) |                                | X        | RSN Rekey protocol offload parameters. |

 

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Minimum supported client</p></td>
<td><p>Windows 10</p></td>
</tr>
<tr class="even">
<td><p>Minimum supported server</p></td>
<td><p>Windows Server 2016</p></td>
</tr>
<tr class="odd">
<td><p>Header</p></td>
<td>Dot11wdi.h</td>
</tr>
</tbody>
</table>

## See also


[OID\_WDI\_SET\_ADD\_PM\_PROTOCOL\_OFFLOAD](oid-wdi-set-add-pm-protocol-offload.md)

[OID\_WDI\_SET\_REMOVE\_PM\_PROTOCOL\_OFFLOAD](oid-wdi-set-remove-pm-protocol-offload.md)

 

 


--------------------
[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bnetvista\netvista%5D:%20OID_WDI_GET_PM_PROTOCOL_OFFLOAD%20%20RELEASE:%20%286/30/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")

