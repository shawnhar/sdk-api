---
UID: NS:directml.DML_ACTIVATION_HARDMAX_OPERATOR_DESC
title: DML_ACTIVATION_HARDMAX_OPERATOR_DESC
description: Describes a DirectML activation operator that performs a hardmax function on the input, f(x) = if x_i == max(x) then 1 else 0 (but only for the first element in the axis).
helpviewer_keywords: ["DML_ACTIVATION_HARDMAX_OPERATOR_DESC","DML_ACTIVATION_HARDMAX_OPERATOR_DESC structure","direct3d12.dml_activation_hardmax_operator_desc","directml/DML_ACTIVATION_HARDMAX_OPERATOR_DESC"]
old-location: direct3d12\dml_activation_hardmax_operator_desc.htm
tech.root: directml
ms.assetid: 1624348B-F871-4645-848F-3E108D3CC7B1
ms.date: 12/5/2018
ms.keywords: DML_ACTIVATION_HARDMAX_OPERATOR_DESC, DML_ACTIVATION_HARDMAX_OPERATOR_DESC structure, direct3d12.dml_activation_hardmax_operator_desc, directml/DML_ACTIVATION_HARDMAX_OPERATOR_DESC
req.header: directml.h
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
 - DML_ACTIVATION_HARDMAX_OPERATOR_DESC
 - directml/DML_ACTIVATION_HARDMAX_OPERATOR_DESC
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - DirectML.h
api_name:
 - DML_ACTIVATION_HARDMAX_OPERATOR_DESC
---

# DML_ACTIVATION_HARDMAX_OPERATOR_DESC structure


## -description

Describes a DirectML activation operator that performs a hardmax function on the input, f(x) = if x_i == max(x) then 1 else 0 (but only for the first element in the axis).

## -struct-fields

### -field InputTensor

Type: **const [DML_TENSOR_DESC](/windows/desktop/api/directml/ns-directml-dml_tensor_desc)\***

A pointer to a constant [DML_TENSOR_DESC](/windows/desktop/api/directml/ns-directml-dml_tensor_desc) containing the description of the tensor to read from.

### -field OutputTensor

Type: **const [DML_TENSOR_DESC](/windows/desktop/api/directml/ns-directml-dml_tensor_desc)\***

A pointer to a constant [DML_TENSOR_DESC](/windows/desktop/api/directml/ns-directml-dml_tensor_desc) containing the description of the tensor to write the results to.

## -remarks

The operator computes the hardmax (1 for the first maximum value, and 0 for all others) values for each layer in the batch of the given input. The input is a 2-D tensor (Tensor) of size (batch_size x input_feature_dimensions). The output tensor has the same shape and contains the hardmax values of the corresponding input.

