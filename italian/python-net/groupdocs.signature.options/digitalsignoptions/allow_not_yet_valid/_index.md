---
title: "proprietà allow_not_yet_valid"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il flag che consente la firma con un certificato il cui periodo di validità non è ancora iniziato."
type: docs
url: /it/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

Il flag che consente la firma con un certificato il cui periodo di validità non è ancora iniziato. Il valore predefinito è False; firmare con tale certificato genera `GroupDocsSignatureException` e il documento non viene firmato.

I validatori segnalano una firma creata prima che il certificato diventi valido come non valida. Tale certificato è solitamente emesso per una data successiva, o l'orologio del computer è errato. Quando questo flag è True, il documento viene firmato e viene scritto un avviso nel logger impostato in [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Il certificato viene confrontato con l'ora corrente in UTC. Il flag si applica agli stessi certificati di [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/), che controlla i certificati il cui periodo di validità è terminato.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### Vedi anche
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
