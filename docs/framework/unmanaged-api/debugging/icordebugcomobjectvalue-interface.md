---
title: "ICorDebugComObjectValue Interface | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework-4.6"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "ICorDebugComObjectValue"
apilocation: 
  - "mscordbi.dll"
apitype: "COM"
f1_keywords: 
  - "ICorDebugComObjectValue"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ICorDebugComObjectValue interface [.NET Framework debugging]"
ms.assetid: 505a7f6c-d92b-42b4-b539-433f5102ea9b
caps.latest.revision: 6
author: "rpetrusha"
ms.author: "ronpet"
manager: "wpickett"
---
# ICorDebugComObjectValue Interface
Provides methods to retrieve information associated with a runtime callable wrapper (RCW).  
  
## Methods  
  
|Method|Description|  
|------------|-----------------|  
|[GetCachedInterfacePointers Method](../../../../docs/framework/unmanaged-api/debugging/icordebugcomobjectvalue-getcachedinterfacepointers-method.md)|Gets the raw interface pointers cached on the current RCW.|  
|[GetCachedInterfaceTypes Method](../../../../docs/framework/unmanaged-api/debugging/icordebugcomobjectvalue-getcachedinterfacetypes-method.md)|Provides an enumerator for the interface types that the current object has been cased to or used as.|  
  
## Remarks  
 To check whether an instance of an "ICorDebugValue" interface represents an RCW, a debugger calls `QueryInterface` on "ICorDebugValue" with `IID_ICorDebugComObjectValue`.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorDebug.idl, CorDebug.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v45plus](../../../../includes/net-current-v45plus-md.md)]  
  
## See Also  
 [Debugging Interfaces](../../../../docs/framework/unmanaged-api/debugging/debugging-interfaces.md)   
 [Debugging](../../../../docs/framework/unmanaged-api/debugging/index.md)