---
title: "Autorizzazioni"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Specifica autorizzazioni configurabili per i documenti PDF, come stampa, modifica del contenuto ed estrazione dei dati. Queste impostazioni sono applicabili solo al formato PDF e controllano l'accesso dell'utente e le capacità di interazione."
type: docs
weight: 1790
url: /it/net/groupdocs.signature.options/permissions/
---
## Permissions enumeration

Specifica permessi configurabili per documenti PDF, come stampa, modifica del contenuto e estrazione dei dati. Queste impostazioni si applicano solo al formato PDF e controllano l'accesso degli utenti e le capacità di interazione.

```csharp
[Flags]
public enum Permissions
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Consenti tutte le azioni, inclusa la stampa, la modifica e l'estrazione dei dati. |
| DenyPrinting | `1` | Nega la stampa del documento. |
| DenyModification | `2` | Nega la modifica del contenuto, inclusa la compilazione dei moduli e l'aggiunta o modifica delle annotazioni. |
| DenyDataExtraction | `4` | Nega l'estrazione di testo e grafica dal documento. |
| DenyAll | `7` | Nega tutte le azioni, inclusa la stampa, la modifica e l'estrazione dei dati. |

### Vedi anche

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
