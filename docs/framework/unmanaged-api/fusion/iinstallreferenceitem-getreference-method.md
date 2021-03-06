---
title: "IInstallReferenceItem::GetReference Method"
ms.date: "03/30/2017"
api_name: 
  - "IInstallReferenceItem.GetReference"
api_location: 
  - "fusion.dll"
api_type: 
  - "COM"
f1_keywords: 
  - "IInstallReferenceItem::GetReference"
helpviewer_keywords: 
  - "IInstallReferenceItem::GetReference method [.NET Framework fusion]"
  - "GetReference method [.NET Framework fusion]"
ms.assetid: 8960332f-c98a-405a-ba92-7003de0c1187
topic_type: 
  - "apiref"
author: "rpetrusha"
ms.author: "ronpet"
---
# IInstallReferenceItem::GetReference Method
Gets a pointer to the [FUSION_INSTALL_REFERENCE](../../../../docs/framework/unmanaged-api/fusion/fusion-install-reference-structure.md) structure represented by this [IInstallReferenceItem](../../../../docs/framework/unmanaged-api/fusion/iinstallreferenceitem-interface.md) object.  
  
## Syntax  
  
```  
HRESULT GetReference (  
    [out] LPFUSION_INSTALL_REFERENCE *ppRefData,  
    [in]  DWORD dwFlags,  
    [in]  LPVOID pvReserved  
);  
```  
  
## Parameters  
 `ppRefData`  
 [out] The returned `FUSION_INSTALL_REFERENCE` pointer.  
  
 `dwFlags`  
 [in] Reserved for future extensibility. `dwFlags` must be 0 (zero).  
  
 `pvReserved`  
 [in] Reserved for future extensibility. `pvReserved` must be a null reference.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** Fusion.h  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]  
  
## See also
- [IInstallReferenceItem Interface](../../../../docs/framework/unmanaged-api/fusion/iinstallreferenceitem-interface.md)
- [FUSION_INSTALL_REFERENCE Structure](../../../../docs/framework/unmanaged-api/fusion/fusion-install-reference-structure.md)
