---
title: "SignatureSettings"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Define la configuración para personalizar el comportamiento de Signature./signature."
type: docs
weight: 2180
url: /es/net/groupdocs.signature/signaturesettings/
---
## SignatureSettings class

Define la configuración para personalizar el comportamiento de [`Signature`](../signature).

```csharp
public class SignatureSettings
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SignatureSettings](signaturesettings#constructor)() | Crea una instancia predeterminada de SignatureSettings con valores predeterminados. |
| [SignatureSettings](signaturesettings#constructor_1)(ILogger) | Crea una instancia predeterminada de SignatureSettings con la implementación del Logger. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [DefaultCulture](../../groupdocs.signature/signaturesettings/defaultculture) { get; set; } | Obtiene o establece la cultura predeterminada que se usará durante el procesamiento de documentos. El valor predeterminado es "en-US". |
| [IncludeStandardMetadataSignatures](../../groupdocs.signature/signaturesettings/includestandardmetadatasignatures) { get; set; } | Obtiene o establece la bandera para incluir en la Lista de Metadatos las firmas de metadatos estándar del documento incrustadas, como Autor, Propietario, fecha de creación del documento, fecha de modificación, etc. Si esta bandera se establece en false (por defecto), GetDocumentInfo no incluirá estas firmas de metadatos. Cuando esta bandera se establece en true, la información del documento incluirá estas firmas de metadatos estándar. |
| [Logger](../../groupdocs.signature/signaturesettings/logger) { get; } | La implementación del registrador utilizada para el registro (Errores, Advertencias, Trazas). [`ILogger`](../../groupdocs.signature.logging/ilogger). |
| [LogLevel](../../groupdocs.signature/signaturesettings/loglevel) { get; set; } | Gets or sets which kinds of messages are passed to [`Logger`](./logger). The value is a set of [`LogLevel`](../../groupdocs.signature.logging/loglevel) flags that can be combined, for example `LogLevel.Error | `LogLevel.Warning`. `LogLevel.None` no registra nada. El valor predeterminado es `LogLevel.All`: errores, advertencias y trazas. |
| [SaveDocumentOnEmptyDelete](../../groupdocs.signature/signaturesettings/savedocumentonemptydelete) { get; set; } | Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Delete no tiene firmas afectadas para eliminar. Si esta bandera se establece en true (por defecto), el documento se guardará con el registro de proceso histórico correspondiente (fecha y tipo de operación) incluso si el método Delete no tiene firmas para eliminar. Cuando esta bandera se establece en false, el documento fuente no se modificará en absoluto. |
| [SaveDocumentOnEmptyUpdate](../../groupdocs.signature/signaturesettings/savedocumentonemptyupdate) { get; set; } | Obtiene o establece la bandera para volver a guardar el documento fuente cuando el método Update no tiene firmas que actualizar. Si esta bandera se establece en true (por defecto), el documento se guardará con el registro de proceso histórico correspondiente (fecha y tipo de operación) incluso si el método Update no tiene firmas que actualizar. Cuando esta bandera se establece en false, el documento fuente no se modificará en absoluto. |
| [ShowDeletedSignaturesInfo](../../groupdocs.signature/signaturesettings/showdeletedsignaturesinfo) { get; set; } | Obtiene o establece la bandera que incluye firmas eliminadas en el resultado de Información del Documento. Cada Signature [`BaseSignature`](../../groupdocs.signature.domain/basesignature) tiene la bandera Deleted [`Deleted`](../../groupdocs.signature.domain/basesignature/deleted) para detectar si fue eliminada. |

### Ver también

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
