---
UID: NS:pep_x._PEP_SYSTEM_LATENCY
title: _PEP_SYSTEM_LATENCY (pep_x.h)
description: Learn how the PEP_SYSTEM_LATENCY structure specifies the new value for the system latency tolerance.
old-location: kernel\pep_system_latency.htm
tech.root: kernel
ms.date: 04/30/2018
keywords: ["PEP_SYSTEM_LATENCY structure"]
ms.keywords: "*PPEP_SYSTEM_LATENCY, PEP_SYSTEM_LATENCY, PEP_SYSTEM_LATENCY structure [Kernel-Mode Driver Architecture], PPEP_SYSTEM_LATENCY, PPEP_SYSTEM_LATENCY structure pointer [Kernel-Mode Driver Architecture], _PEP_SYSTEM_LATENCY, kernel.pep_system_latency, pepfx/PEP_SYSTEM_LATENCY, pepfx/PPEP_SYSTEM_LATENCY"
req.header: pep_x.h
req.include-header: Pep_x.h
req.target-type: Windows
req.target-min-winverclnt: Supported starting with Windows 10.
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
req.typenames: PEP_SYSTEM_LATENCY, *PPEP_SYSTEM_LATENCY
f1_keywords:
 - _PEP_SYSTEM_LATENCY
 - pep_x/_PEP_SYSTEM_LATENCY
 - PPEP_SYSTEM_LATENCY
 - pep_x/PPEP_SYSTEM_LATENCY
 - PEP_SYSTEM_LATENCY
 - pep_x/PEP_SYSTEM_LATENCY
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - pepfx.h
api_name:
 - _PEP_SYSTEM_LATENCY
 - PPEP_SYSTEM_LATENCY
 - PEP_SYSTEM_LATENCY
---

# _PEP_SYSTEM_LATENCY structure (pep_x.h)


## -description

The <b>PEP_SYSTEM_LATENCY</b> structure specifies the new value for the system latency tolerance.

## -struct-fields

### -field Latency

[in] The overall system latency tolerance, in 100-nanosecond units. This member specifies the maximum latency that the operating system can tolerate in the time required to move a component from a low-power F<i>x</i> state to F0.

## -remarks

This structure is used by the <a href="/windows-hardware/drivers/ddi/pepfx/ns-pepfx-_pep_system_latency">PEP_DPM_SYSTEM_LATENCY_UPDATE</a> notification. The <b>Latency</b> member of the structure contains an input value that is supplied by the Windows <a href="/windows-hardware/drivers/kernel/overview-of-the-power-management-framework">power management framework</a> (PoFx).

## -see-also

<a href="/windows-hardware/drivers/ddi/pepfx/ns-pepfx-_pep_system_latency">PEP_DPM_SYSTEM_LATENCY_UPDATE</a>

