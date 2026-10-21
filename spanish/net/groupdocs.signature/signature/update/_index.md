---
title: "Update"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Actualiza la firma proporcionada BaseSignaturegroupdocs.signature.domain/basesignature en el documento."
type: docs
weight: 170
url: /es/net/groupdocs.signature/signature/update/
---
## Update(BaseSignature) {#update}

Actualiza la firma proporcionada [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) en el documento.

```csharp
public bool Update(BaseSignature signature)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firma | BaseSignature | Objeto de firma que se actualizará en el documento. |

### Valor de retorno

Devuelve true si la operación fue exitosa.

### Observaciones

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in C#](https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Updating)

### Ver también

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Update(List&lt;BaseSignature&gt;) {#update_1}

Actualiza las firmas proporcionadas [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) en el documento.

```csharp
public UpdateResult Update(List<BaseSignature> signatures)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firmas | List`1 | Lista de firmas para actualizar en el documento. |

### Valor de retorno

Devuelve UpdateResult [`UpdateResult`](../../../groupdocs.signature.domain/updateresult) con la lista de firmas actualizadas con éxito y las que fallaron.

### Observaciones

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in C#](https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Updating)

### Ver también

* class [UpdateResult](../../../groupdocs.signature.domain/updateresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
