---
description: "Specifies whether the module is compiled with the /SDL option."
title: "IDiaSymbol::get_isSdl"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaSymbol::get_isSdl

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Specifies whether the module is compiled with the /SDL option.

## Syntax

```C++
HRESULT get_isSdl(
   BOOL *pRetVal);
```

#### Parameters
 `pRetVal`

[out] A pointer to a `BOOL` that specifies whether the module is compiled with the /SDL option.

## Return Value
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` or an error code.

## See also
- [IDiaSymbol](../../debugger/debug-interface-access/idiasymbol.md)
