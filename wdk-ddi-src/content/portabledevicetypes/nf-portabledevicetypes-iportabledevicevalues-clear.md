---
UID: NF:portabledevicetypes.IPortableDeviceValues.Clear
title: IPortableDeviceValues::Clear (portabledevicetypes.h)
description: Learn how this method deletes all items from the collection.
old-location: wpddk\iportabledevicevalues_clear.htm
tech.root: wpd_dk
ms.date: 02/15/2018
keywords: ["IPortableDeviceValues::Clear"]
ms.keywords: Clear, Clear method, Clear method,IPortableDeviceValues interface, IPortableDeviceValues interface,Clear method, IPortableDeviceValues.Clear, IPortableDeviceValues::Clear, IPortableDeviceValuesClear, portabledevicetypes/IPortableDeviceValues::Clear, wpddk.iportabledevicevalues_clear
req.header: portabledevicetypes.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
ms.custom: RS5
f1_keywords:
 - IPortableDeviceValues::Clear
 - portabledevicetypes/IPortableDeviceValues::Clear
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - PortableDeviceTypes.h
api_name:
 - IPortableDeviceValues::Clear
---

# IPortableDeviceValues::Clear


## -description

Deletes all items from the collection.

## -parameters

## -returns

The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
</table>

## -remarks

This method frees the memory for all dynamically allocated items in the collection. For interfaces, it calls <b>Release</b>.

## -see-also

<a href="/windows-hardware/drivers/ddi/portabledevicetypes/nn-portabledevicetypes-iportabledevicevalues">IPortableDeviceValues Interface</a>

