---
title: "SaveDocumentOnEmptyUpdate"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Update no tiene firmas para actualizar. Si esta bandera se establece en true por defecto, el documento se guardará con el registro de proceso histórico correspondiente, fecha y tipo de operación, incluso si el método Update no tiene firmas para actualizar. Cuando esta bandera se establece en false, el documento fuente no se modificará en absoluto."
type: docs
weight: 70
url: /es/net/groupdocs.signature/signaturesettings/savedocumentonemptyupdate/
---
## SignatureSettings.SaveDocumentOnEmptyUpdate property

Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Update no tiene firmas que actualizar. Si esta bandera se establece en true (por defecto), el documento se guardará con el registro de proceso histórico correspondiente (fecha y tipo de operación) incluso si el método Update no tiene firmas que actualizar. Cuando esta bandera se establece en false, el documento fuente no se modificará en absoluto.

```csharp
public bool SaveDocumentOnEmptyUpdate { get; set; }
```

### Ver también

* class [SignatureSettings](../../signaturesettings)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
