---
title: "LogLevel"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Especifica qué tipos de mensajes se envían al logger configurado en SignatureSettings../groupdocs.signature/signaturesettings. Los valores son banderas y pueden combinarse, por ejemplo LogLevel.Error  LogLevel.Warning."
type: docs
weight: 1360
url: /es/net/groupdocs.signature.logging/loglevel/
---
## LogLevel enumeration

Especifica qué tipos de mensajes se envían al logger configurado en [`SignatureSettings`](../../groupdocs.signature/signaturesettings). Los valores son banderas y pueden combinarse, por ejemplo `LogLevel.Error | LogLevel.Warning`.

```csharp
[Flags]
public enum LogLevel
```

### Values

| Nombre | Value | Descripción |
| --- | --- | --- |
| None | `0` | No se registra nada. |
| Error | `1` | Errores: una operación falló. |
| Warning | `2` | Advertencias: una operación tuvo éxito, pero su resultado puede no ser lo que espera. |
| Trace | `4` | Rastros: los pasos de una operación, como su inicio y su fin. |
| All | `7` | Errores, advertencias y rastros. Este es el predeterminado. |

### Ver también

* namespace [GroupDocs.Signature.Logging](../../groupdocs.signature.logging)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
