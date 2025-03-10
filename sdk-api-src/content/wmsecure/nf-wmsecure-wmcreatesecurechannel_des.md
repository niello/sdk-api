---
UID: NF:wmsecure.WMCreateSecureChannel_DES
title: WMCreateSecureChannel_DES function (wmsecure.h)
description: Creates an object that implements IWMSecureChannel.
helpviewer_keywords: ["WMCreateSecureChannel_DES","WMCreateSecureChannel_DES function [windows Media Format]","wmformat.wmcreatesecurechannel_des","wmsecure/WMCreateSecureChannel_DES"]
old-location: wmformat\wmcreatesecurechannel_des.htm
tech.root: wmformat
ms.assetid: d90e591f-82c0-4129-a810-8705d770dd3a
ms.date: 12/05/2018
ms.keywords: WMCreateSecureChannel_DES, WMCreateSecureChannel_DES function [windows Media Format], wmformat.wmcreatesecurechannel_des, wmsecure/WMCreateSecureChannel_DES
req.header: wmsecure.h
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
req.redist: 
ms.custom: 19H1
f1_keywords:
 - WMCreateSecureChannel_DES
 - wmsecure/WMCreateSecureChannel_DES
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - Wmsecure.h
api_name:
 - WMCreateSecureChannel_DES
---

# WMCreateSecureChannel_DES function


## -description

Creates an object that implements <a href="/windows/desktop/api/wmsecure/nn-wmsecure-iwmsecurechannel">IWMSecureChannel</a>.

## -parameters

### -param ppChannel

Address of a pointer to the <a href="/windows/desktop/api/wmsecure/nn-wmsecure-iwmsecurechannel">IWMSecureChannel</a> interface of the newly created secure channel object.

## -returns

If this function succeeds, it returns <b>S_OK</b>. Otherwise, it returns an <b>HRESULT</b> error code.

## -see-also

<a href="/windows/desktop/api/wmsecure/nn-wmsecure-iwmsecurechannel">IWMSecureChannel</a>