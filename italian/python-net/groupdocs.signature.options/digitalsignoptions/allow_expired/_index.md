---
title: "proprietà allow_expired"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il flag che consente la firma con un certificato il cui periodo di validità è terminato."
type: docs
url: /it/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

Il flag che consente la firma con un certificato il cui periodo di validità è terminato. Il valore predefinito è False; firmare con un certificato scaduto genera `GroupDocsSignatureException` e il documento non viene firmato.

I validatori segnalano una firma creata con un certificato scaduto come non valida. Imposta questa proprietà su True solo quando hai comunque bisogno di tale firma, ad esempio per testare con un certificato vecchio. Il documento viene quindi firmato e viene scritto un avviso nel logger impostato in [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Il certificato viene confrontato con l'ora corrente in UTC, non con [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). Il flag si applica al certificato fornito da [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) o [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/), e, quando un foglio di calcolo è firmato, al certificato della prima estensione [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/). Le firme digitali delle immagini non utilizzano un certificato e non vengono verificate. Un certificato il cui periodo di validità non è ancora iniziato è controllato da [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/).

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### Vedi anche
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
