---
title: SymmetricEncryption
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Implementa algoritmos simétricos estándar para el cifrado de datos con clave única y frase de contraseña salt.
type: docs
weight: 360
url: /es/net/groupdocs.signature.domain.extensions/symmetricencryption/
---
## SymmetricEncryption class

Implementa algoritmos simétricos estándar para el cifrado de datos con clave única y frase de contraseña (salt).

```csharp
public sealed class SymmetricEncryption : IDataEncryption
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SymmetricEncryption](symmetricencryption#constructor)(SymmetricAlgorithmType, string) | Crea un algoritmo de cifrado simétrico con frase de contraseña predeterminada |
| [SymmetricEncryption](symmetricencryption#constructor_1)(SymmetricAlgorithmType, string, string) | Crea algoritmo de cifrado simétrico con parámetros. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlgorithmType](../../groupdocs.signature.domain.extensions/symmetricencryption/algorithmtype) { get; set; } | Obtiene o establece el tipo de algoritmo simétrico. |
| [Key](../../groupdocs.signature.domain.extensions/symmetricencryption/key) { get; set; } | Obtiene o establece la clave del algoritmo de cifrado. |
| [Salt](../../groupdocs.signature.domain.extensions/symmetricencryption/salt) { get; set; } | Obtiene o establece la frase de contraseña del algoritmo de cifrado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Decode](../../groupdocs.signature.domain.extensions/symmetricencryption/decode)(string) | Descifra la cadena según el tipo de algoritmo proporcionado, la clave y los parámetros salt |
| [Encode](../../groupdocs.signature.domain.extensions/symmetricencryption/encode)(string) | Cifra la cadena según el tipo de algoritmo proporcionado, la clave y los parámetros salt |

### Ver también

* interface [IDataEncryption](../idataencryption)
* espacio de nombres [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->