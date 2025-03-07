---
UID: NF:faxcomex._IFaxServerNotify2.OnGeneralServerConfigChanged
title: _IFaxServerNotify2::OnGeneralServerConfigChanged (faxcomex.h)
description: Called by the fax service when the IFaxServer2::Configuration property changes.
helpviewer_keywords: ["IFaxServerNotify2 interface [Fax Service]","OnGeneralServerConfigChanged method","IFaxServerNotify2.OnGeneralServerConfigChanged","IFaxServerNotify2::OnGeneralServerConfigChanged","OnGeneralServerConfigChanged","OnGeneralServerConfigChanged method [Fax Service]","OnGeneralServerConfigChanged method [Fax Service]","IFaxServerNotify2 interface","_IFaxServerNotify2.OnGeneralServerConfigChanged","_IFaxServerNotify2::OnGeneralServerConfigChanged","_mfax_ifaxservernotify2_ongeneralserverconfigchanged","fax._mfax_ifaxservernotify2_ongeneralserverconfigchanged","faxcomex/IFaxServerNotify2::OnGeneralServerConfigChanged"]
old-location: fax\_mfax_ifaxservernotify2_ongeneralserverconfigchanged.htm
tech.root: Fax
ms.assetid: VS|fax|~\fax\reference\serviceextendedcom\i\ifaxservernotify2\ongeneralserverconfigchanged.htm
ms.date: 12/05/2018
ms.keywords: IFaxServerNotify2 interface [Fax Service],OnGeneralServerConfigChanged method, IFaxServerNotify2.OnGeneralServerConfigChanged, IFaxServerNotify2::OnGeneralServerConfigChanged, OnGeneralServerConfigChanged, OnGeneralServerConfigChanged method [Fax Service], OnGeneralServerConfigChanged method [Fax Service],IFaxServerNotify2 interface, _IFaxServerNotify2.OnGeneralServerConfigChanged, _IFaxServerNotify2::OnGeneralServerConfigChanged, _mfax_ifaxservernotify2_ongeneralserverconfigchanged, fax._mfax_ifaxservernotify2_ongeneralserverconfigchanged, faxcomex/IFaxServerNotify2::OnGeneralServerConfigChanged
req.header: faxcomex.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
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
req.dll: Fxscomex.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - _IFaxServerNotify2::OnGeneralServerConfigChanged
 - faxcomex/_IFaxServerNotify2::OnGeneralServerConfigChanged
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Fxscomex.dll
api_name:
 - IFaxServerNotify2.OnGeneralServerConfigChanged
 - IFaxServerNotify2.OnGeneralServerConfigChanged
---

# _IFaxServerNotify2::OnGeneralServerConfigChanged


## -description

Called by the fax service when the <a href="/previous-versions/windows/desktop/fax/-mfax-faxserver2-configuration-vb">IFaxServer2::Configuration</a> property changes.

## -parameters

### -param pFaxServer

Type: <b><a href="/previous-versions/windows/desktop/api/faxcomex/nn-faxcomex-ifaxserver2">IFaxServer2</a>*</b>

A <a href="/previous-versions/windows/desktop/api/faxcomex/nn-faxcomex-ifaxserver2">IFaxServer2</a> object.

## -returns

Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.

## -remarks

To implement this functionality in Visual Basic, select and implement the appropriate event procedure. For an example, see <a href="/previous-versions/windows/desktop/fax/-mfax-registering-for-fax-events">Registering for Fax Events</a>.

## -see-also

<a href="/windows/win32/api/faxcomex/nn-faxcomex-_ifaxservernotify2">IFaxServerNotify2</a>