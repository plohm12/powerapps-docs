---
title: FormatCurrency | Microsoft Docs
description: 
keywords:
ms.author: nabuthuk
author: Nkrb
manager: kvivek
ms.date: 04/23/2019
ms.service: "powerapps"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 87e433e6-573f-414f-b49d-1213f2bd8cf4
---

# formatCurrency

[!INCLUDE [formatcurrency-description](includes/formatcurrency-description.md)]

## Available for 

Model-driven apps and canvas apps (experimental preview)

## Syntax

`context.formatting.formatCurrency(value, precision, symbol)`

## Parameters

| Parameter Name|Type|Required|Description|
| ------------- |----|--------|-----------|
|value|`number`|yes| A value to be formatted.|
|precision|`number`|yes| The number of digits after decimal point.|
|symbol|`string`|yes| The currency symbol/code to be added with currency value.|

## Return Value

Type: `string`


### Related topics

[Formatting](../formatting.md)<br/>
[PowerApps component framework API Reference](../../reference/index.md)<br/>
[PowerApps component framework Overview](../../overview.md)