---
title: "SaveDocumentOnEmptyDelete"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Delete no tiene firmas afectadas para eliminar. Si esta bandera se establece en true por defecto, el documento se guardará con el registro de proceso histórico correspondiente, fecha y tipo de operación, incluso si el método Delete no tiene firmas para eliminar. Cuando esta bandera se establece en false, el documento fuente no se modificará en absoluto."
type: docs
weight: 60
url: /es/net/groupdocs.signature/signaturesettings/savedocumentonemptydelete/
---
## SignatureSettings.SaveDocumentOnEmptyDelete property

Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Delete no tiene firmas afectadas para eliminar. Si esta bandera se establece en true (por defecto), el documento se guardará con el registro de proceso histórico correspondiente (fecha y tipo de operación) incluso si el método Delete no tiene firmas para eliminar. Cuando esta bandera se establece en false, el documento fuente no se modificará en absoluto.

```csharp
public bool SaveDocumentOnEmptyDelete { get; set; }
```

### Ver también

* class [SignatureSettings](../../signaturesettings)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
