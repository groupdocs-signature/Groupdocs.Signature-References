---
title: "proprietà skip_external_resources"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il flag che impedisce al documento di caricare risorse esterne."
type: docs
url: /it/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

Il flag che impedisce al documento di caricare risorse esterne. Il valore predefinito è True; le risorse esterne non vengono caricate eccetto quelle che corrispondono a [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Un documento può fare riferimento a risorse memorizzate al di fuori di esso, come immagini collegate, immagini inserite tramite un campo INCLUDEPICTURE, immagini collegate in presentazioni e fogli di calcolo, e immagini e fogli di stile referenziati da un'immagine SVG. Il caricamento di tale risorsa fa sì che la libreria richieda il suo indirizzo. Su un server che elabora documenti non attendibili, un documento potrebbe utilizzare questa funzionalità per far inviare al server richieste a indirizzi interni (server‑side request forgery), e un percorso UNC o `file://` potrebbe far sì che Windows invii le credenziali NTLM dell'account a un altro host. Su un'installazione offline o isolata, le richieste falliscono o attendono un timeout.

Le risorse che vengono ignorate non vengono disegnate nelle anteprime delle pagine né nei documenti salvati come immagini, e la ricerca di immagini, barcode e QR‑code non le rileva. Imposta questa proprietà su False solo per documenti attendibili e preferisci consentire indirizzi specifici con [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

L'impostazione si applica ai documenti di elaborazione testi, alle presentazioni, ai fogli di calcolo e alle immagini SVG, inclusi i documenti all'interno di archivi. Per le immagini SVG, i riferimenti non consentiti vengono rimossi dall'immagine prima della lettura, e un'immagine SVG che non è XML ben formato viene rifiutata. L'impostazione non controlla i controlli di revoca dei certificati, i server di marcatura temporale o le licenze.

Questa proprietà sostituisce [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/), che ha il significato opposto.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Vedi anche
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
