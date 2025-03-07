---
UID: NN:wmp.IWMPQuery
title: IWMPQuery (wmp.h)
description: The IWMPQuery interface represents a compound query.
helpviewer_keywords: ["IWMPQuery","IWMPQuery interface [Windows Media Player]","IWMPQuery interface [Windows Media Player]","described","IWMPQueryInterface","wmp.iwmpquery","wmp/IWMPQuery"]
old-location: wmp\iwmpquery.htm
tech.root: WMP
ms.assetid: f1f3c46f-4756-49b4-ad4f-a9097ff787f8
ms.date: 12/05/2018
ms.keywords: IWMPQuery, IWMPQuery interface [Windows Media Player], IWMPQuery interface [Windows Media Player],described, IWMPQueryInterface, wmp.iwmpquery, wmp/IWMPQuery
req.header: wmp.h
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
 - IWMPQuery
 - wmp/IWMPQuery
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - wmp.h
api_name:
 - IWMPQuery
---

# IWMPQuery interface


## -description

The <b>IWMPQuery</b> interface represents a compound query.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IWMPQuery</b> interface inherits from the <a href="/previous-versions/windows/desktop/api/oaidl/nn-oaidl-idispatch">IDispatch</a> interface. <b>IWMPQuery</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IWMPQuery</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/wmp/nf-wmp-iwmpquery-addcondition">addCondition</a>
</td>
<td align="left" width="63%">
Adds a condition to the compound query using AND logic.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/wmp/nf-wmp-iwmpquery-beginnextgroup">beginNextGroup</a>
</td>
<td align="left" width="63%">
Begins a new condition group.

</td>
</tr>
</table>

## -see-also

<a href="/windows/desktop/api/wmp/nf-wmp-iwmpmediacollection2-createquery">IWMPMediaCollection2::createQuery</a>



<a href="/windows/desktop/api/wmp/nf-wmp-iwmpmediacollection2-getplaylistbyquery">IWMPMediaCollection2::getPlaylistByQuery</a>



<a href="/windows/desktop/api/wmp/nf-wmp-iwmpmediacollection2-getstringcollectionbyquery">IWMPMediaCollection2::getStringCollectionByQuery</a>



<a href="/windows/desktop/WMP/interfaces">Interfaces</a>