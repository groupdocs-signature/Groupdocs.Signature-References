---
title: "AllowNotYetValid"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Ottiene o imposta un flag che consente la firma con un certificato il cui periodo di validità non è ancora iniziato. Il valore predefinito è false; firmare con tale certificato genera GroupDocsSignatureExceptiongroupdocs.signature/groupdocssignatureexception e il documento non viene firmato."
type: docs
weight: 30
url: /it/net/groupdocs.signature.options/digitalsignoptions/allownotyetvalid/
---
## DigitalSignOptions.AllowNotYetValid property

Ottiene o imposta un flag che consente la firma con un certificato il cui periodo di validità non è ancora iniziato. Il valore predefinito è false: firmare con tale certificato genera [`GroupDocsSignatureException`](../../../groupdocs.signature/groupdocssignatureexception), e il documento non viene firmato.

```csharp
public bool AllowNotYetValid { get; set; }
```

### Osservazioni

I validatori segnalano una firma creata prima che il certificato diventi valido come non valida. Tale certificato è solitamente stato emesso per una data successiva, o l'orologio del computer è errato. Quando questa proprietà è true, il documento viene firmato e viene scritto un avviso nel logger impostato in [`SignatureSettings`](../../../groupdocs.signature/signaturesettings).

Il certificato viene confrontato con l'ora corrente in UTC. Il flag si applica agli stessi certificati di [`AllowExpired`](../allowexpired), che controlla i certificati il cui periodo di validità è terminato.

### Vedi anche

* class [DigitalSignOptions](../../digitalsignoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
