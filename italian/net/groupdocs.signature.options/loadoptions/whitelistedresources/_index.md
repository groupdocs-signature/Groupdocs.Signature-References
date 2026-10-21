---
title: "WhitelistedResources"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Ottiene o imposta frammenti di indirizzi di risorse esterne che vengono caricati anche quando SkipExternalResourcesgroupdocs.signature.options/loadoptions/skipexternalresources è true. Il valore predefinito è una lista vuota."
type: docs
weight: 60
url: /it/net/groupdocs.signature.options/loadoptions/whitelistedresources/
---
## LoadOptions.WhitelistedResources property

Ottiene o imposta frammenti di indirizzi di risorse esterne che vengono caricati anche quando [`SkipExternalResources`](../skipexternalresources) è true. Il valore predefinito è una lista vuota.

```csharp
public List<string> WhitelistedResources { get; set; }
```

### Osservazioni

Una risorsa viene caricata quando il suo indirizzo completo contiene uno dei frammenti. Il confronto ignora maiuscole/minuscole e i frammenti vuoti vengono ignorati. Preferisci frammenti lunghi come "https://cdn.example.com/images/": un frammento corto corrisponde anche ad altri indirizzi che lo contengono.

Impostare questa proprietà su null cancella la lista. La lista non ha effetto quando [`SkipExternalResources`](../skipexternalresources) è false, perché in tal caso tutte le risorse esterne vengono caricate.

### Vedi anche

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
