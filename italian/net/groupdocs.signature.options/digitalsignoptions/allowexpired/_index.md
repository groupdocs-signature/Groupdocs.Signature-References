---
title: "AllowExpired"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Ottiene o imposta un flag che consente la firma con un certificato il cui periodo di validità è terminato. Il valore predefinito è false; firmare con un certificato scaduto genera GroupDocsSignatureExceptiongroupdocs.signature/groupdocssignatureexception e il documento non viene firmato."
type: docs
weight: 20
url: /it/net/groupdocs.signature.options/digitalsignoptions/allowexpired/
---
## DigitalSignOptions.AllowExpired property

Ottiene o imposta un flag che consente la firma con un certificato il cui periodo di validità è terminato. Il valore predefinito è false: firmare con un certificato scaduto genera [`GroupDocsSignatureException`](../../../groupdocs.signature/groupdocssignatureexception), e il documento non viene firmato.

```csharp
public bool AllowExpired { get; set; }
```

### Osservazioni

I validatori segnalano una firma creata con un certificato scaduto come non valida. Imposta questa proprietà su true solo quando è comunque necessario tale firma, ad esempio per testare con un certificato vecchio. Il documento viene quindi firmato e viene scritto un avviso nel logger impostato in [`SignatureSettings`](../../../groupdocs.signature/signaturesettings).

Il certificato viene confrontato con l'ora corrente in UTC, non con [`SignTime`](../../../groupdocs.signature.domain/digitalsignature/signtime). Il flag si applica al certificato fornito da [`CertificateFilePath`](../certificatefilepath), [`CertificateStream`](../certificatestream) o [`Signature`](../signature) e, quando viene firmato un foglio di calcolo, al certificato della prima estensione [`DigitalVBA`](../../../groupdocs.signature.domain.extensions/digitalvba). Le firme digitali delle immagini non utilizzano un certificato e non vengono verificate. Un certificato il cui periodo di validità non è ancora iniziato è controllato da [`AllowNotYetValid`](../allownotyetvalid).

### Vedi anche

* class [DigitalSignOptions](../../digitalsignoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
