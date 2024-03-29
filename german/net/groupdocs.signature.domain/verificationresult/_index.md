---
title: VerificationResult
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Instanz zum Aufbewahren der Ergebnisse des Überprüfungsprozesses.
type: docs
weight: 1050
url: /de/net/groupdocs.signature.domain/verificationresult/
---
## VerificationResult class

Instanz zum Aufbewahren der Ergebnisse des Überprüfungsprozesses.

```csharp
public class VerificationResult : IResult
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/verificationresult/destindocumentsize) { get; } | Gibt die Größe des Zieldokuments zurück. Zur Überprüfung enthält diese Variable immer Null. |
| [IsValid](../../groupdocs.signature.domain/verificationresult/isvalid) { get; } | Gibt „true“ zurück, wenn der Überprüfungsprozess erfolgreich war, andernfalls „false“. |
| [ProcessingTime](../../groupdocs.signature.domain/verificationresult/processingtime) { get; } | Gibt die Ausführungszeit des Prozesses in Millisekunden zurück. |
| [SourceDocumentSize](../../groupdocs.signature.domain/verificationresult/sourcedocumentsize) { get; } | Gibt die Größe des Quelldokuments in Bytes zurück |
| [Succeeded](../../groupdocs.signature.domain/verificationresult/succeeded) { get; } | Liste der erfolgreich verifizierten Signaturen[`BaseSignature`](../basesignature) . |
| [TotalSignatures](../../groupdocs.signature.domain/verificationresult/totalsignatures) { get; } | Gibt die insgesamt verarbeiteten Unterschriften zurück |

### Siehe auch

* interface [IResult](../iresult)
* namensraum [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
