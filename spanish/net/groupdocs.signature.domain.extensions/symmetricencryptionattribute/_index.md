---
title: "SymmetricEncryptionAttribute"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Indica a la serialización de instancias que cifre / descifre la cadena de serialización del objeto."
type: docs
weight: 550
url: /es/net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/
---
## SymmetricEncryptionAttribute class

Indica a la serialización de instancias que cifre / descifre la cadena de serialización del objeto.

```csharp
[AttributeUsage(AttributeTargets.Class | AttributeTargets.Struct)]
public sealed class SymmetricEncryptionAttribute : Attribute, IDataEncryption
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SymmetricEncryptionAttribute](symmetricencryptionattribute#constructor)(SymmetricAlgorithmType, string) | Crea un algoritmo simétrico con parámetros y frase de paso predeterminada. |
| [SymmetricEncryptionAttribute](symmetricencryptionattribute#constructor_1)(SymmetricAlgorithmType, string, string) | Crea un algoritmo simétrico con parámetros. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Decode](../../groupdocs.signature.domain.extensions/symmetricencryptionattribute/decode)(string) | Desencripta la cadena proporcionada según el tipo de algoritmo, la clave y los parámetros de sal. |
| [Encode](../../groupdocs.signature.domain.extensions/symmetricencryptionattribute/encode)(string) | Encripta la cadena según el tipo de algoritmo, la clave y los parámetros de sal proporcionados. |

### Ver también

* interface [IDataEncryption](../idataencryption)
* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
