---
title: "SymmetricEncryption"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Implementa algoritmos simétricos estándar para el cifrado de datos con una única clave y sal de frase de paso."
type: docs
weight: 540
url: /es/net/groupdocs.signature.domain.extensions/symmetricencryption/
---
## SymmetricEncryption class

Implementa algoritmos simétricos estándar para el cifrado de datos con clave única y frase de paso (sal).

```csharp
public sealed class SymmetricEncryption : IDataEncryption
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SymmetricEncryption](symmetricencryption#constructor)(SymmetricAlgorithmType, string) | Crea un algoritmo de cifrado simétrico con la frase de paso predeterminada |
| [SymmetricEncryption](symmetricencryption#constructor_1)(SymmetricAlgorithmType, string, string) | Crea un algoritmo de cifrado simétrico con parámetros. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AlgorithmType](../../groupdocs.signature.domain.extensions/symmetricencryption/algorithmtype) { get; set; } | Obtiene o establece el tipo de algoritmo simétrico. |
| [Key](../../groupdocs.signature.domain.extensions/symmetricencryption/key) { get; set; } | Obtiene o establece la clave del algoritmo de cifrado. |
| [Salt](../../groupdocs.signature.domain.extensions/symmetricencryption/salt) { get; set; } | Obtiene o establece la frase de paso del algoritmo de cifrado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Decode](../../groupdocs.signature.domain.extensions/symmetricencryption/decode)(string) | Descifra la cadena basada en el tipo de algoritmo proporcionado, la clave y los parámetros de sal |
| [Encode](../../groupdocs.signature.domain.extensions/symmetricencryption/encode)(string) | Encripta la cadena según el tipo de algoritmo, la clave y los parámetros de sal proporcionados. |

### Ver también

* interface [IDataEncryption](../idataencryption)
* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
