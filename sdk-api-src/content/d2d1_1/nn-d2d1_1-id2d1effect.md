---
UID: NN:d2d1_1.ID2D1Effect
title: ID2D1Effect (d2d1_1.h)
description: Represents a basic image-processing construct in Direct2D.
helpviewer_keywords: ["ID2D1Effect","ID2D1Effect interface [Direct2D]","ID2D1Effect interface [Direct2D]","described","d2d1_1/ID2D1Effect","direct2d.id2d1effect"]
old-location: direct2d\id2d1effect.htm
tech.root: Direct2D
ms.assetid: e90d1830-c356-48f1-ac7b-1d94c8c26569
ms.date: 12/05/2018
ms.keywords: ID2D1Effect, ID2D1Effect interface [Direct2D], ID2D1Effect interface [Direct2D],described, d2d1_1/ID2D1Effect, direct2d.id2d1effect
req.header: d2d1_1.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8 and Platform Update for Windows 7 [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2012 and Platform Update for Windows Server 2008 R2 [desktop apps \| UWP apps]
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
req.dll: D2d1.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - ID2D1Effect
 - d2d1_1/ID2D1Effect
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - D2d1.dll
api_name:
 - ID2D1Effect
---

# ID2D1Effect interface


## -description

Represents a basic image-processing construct in Direct2D.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">ID2D1Effect</b> interface inherits from <a href="/windows/desktop/api/d2d1_1/nn-d2d1_1-id2d1properties">ID2D1Properties</a>. <b>ID2D1Effect</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>ID2D1Effect</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/d2d1_1/nf-d2d1_1-id2d1effect-getinput">GetInput</a>
</td>
<td align="left" width="63%">
Gets the given input image by index. 

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/d2d1_1/nf-d2d1_1-id2d1effect-getinputcount">GetInputCount</a>
</td>
<td align="left" width="63%">
Gets the number of inputs to the effect. 

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/d2d1_1/nf-d2d1_1-id2d1effect-getoutput">GetOutput</a>
</td>
<td align="left" width="63%">
Gets the output image from the effect. 

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/d2d1_1/nf-d2d1_1-id2d1effect-setinput">SetInput</a>
</td>
<td align="left" width="63%">
Sets the given input image by index. 

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/d2d1_1/nf-d2d1_1-id2d1effect-setinputcount">SetInputCount</a>
</td>
<td align="left" width="63%">
Allows the application to change the number of inputs to an effect.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/d2d1_1/nf-d2d1_1-id2d1effect-setinputeffect">SetInputEffect</a>
</td>
<td align="left" width="63%">
Sets the given input effect by index. 

</td>
</tr>
</table>

## -remarks

An effect takes zero or more input images, and has an output image. The images that are input into and output from an effect are lazily evaluated. This definition is sufficient to allow an arbitrary graph of effects to be created from the application by feeding output images into the input image of the next effect in the chain.

## -see-also

<a href="/windows/desktop/api/d2d1_1/nf-d2d1_1-id2d1devicecontext-createeffect">ID2D1DeviceContext::CreateEffect</a>



<a href="/windows/desktop/api/d2d1_1/nn-d2d1_1-id2d1properties">ID2D1Properties</a>