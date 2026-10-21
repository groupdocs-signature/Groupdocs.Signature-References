---
title: "SkipExternalResources"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Ottiene o imposta un flag che impedisce al documento di caricare risorse esterne. Il valore predefinito è true; le risorse esterne non vengono caricate, eccetto quelle che corrispondono a WhitelistedResourcesgroupdocs.signature.options/loadoptions/whitelistedresources."
type: docs
weight: 50
url: /it/net/groupdocs.signature.options/loadoptions/skipexternalresources/
---
## LoadOptions.SkipExternalResources property

Ottiene o imposta un flag che impedisce al documento di caricare risorse esterne. Il valore predefinito è true: le risorse esterne non vengono caricate, eccetto quelle che corrispondono a [`WhitelistedResources`](../whitelistedresources).

```csharp
public bool SkipExternalResources { get; set; }
```

### Osservazioni

Un documento può fare riferimento a risorse archiviate al di fuori di esso: immagini collegate, immagini inserite tramite un campo INCLUDEPICTURE, immagini collegate in presentazioni e fogli di calcolo, e immagini e fogli di stile a cui fa riferimento un'immagine SVG. Il caricamento di tali risorse fa sì che la libreria richieda il loro indirizzo. Su un server che elabora documenti non attendibili, un documento potrebbe utilizzare ciò per far inviare al server richieste a indirizzi interni (forgery di richieste lato server), e un percorso UNC o file:// potrebbe far inviare a Windows le credenziali NTLM dell'account a un altro host. In un'installazione offline o isolata, le richieste falliscono o attendono un timeout.

Le risorse che vengono ignorate non vengono disegnate nelle anteprime di pagina o nei documenti salvati come immagini, e la ricerca di immagini, codici a barre e QR-code non le vede. Imposta questa proprietà su false solo per documenti attendibili e preferisci consentire indirizzi specifici con [`WhitelistedResources`](../whitelistedresources).

L'impostazione si applica ai documenti di elaborazione testi, presentazioni, fogli di calcolo e immagini SVG, inclusi i documenti all'interno di archivi. Per le immagini SVG, i riferimenti non consentiti vengono rimossi dall'immagine prima della lettura, e un'immagine SVG che non è XML ben formato viene rifiutata. L'impostazione non controlla i controlli di revoca dei certificati, i server di marcatura temporale o le licenze.

Questa proprietà sostituisce LoadExternalResources, che ha il significato opposto.

### Vedi anche

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
