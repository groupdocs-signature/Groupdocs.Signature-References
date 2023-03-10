---
title: SpreadsheetMetadataSignature
second_title: Riferimento API GroupDocs.Signature per .NET
description: Contiene le proprietà della firma dei metadati del foglio di calcolo.
type: docs
weight: 870
url: /it/net/groupdocs.signature.domain/spreadsheetmetadatasignature/
---
## SpreadsheetMetadataSignature class

Contiene le proprietà della firma dei metadati del foglio di calcolo.

```csharp
public sealed class SpreadsheetMetadataSignature : MetadataSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SpreadsheetMetadataSignature](spreadsheetmetadatasignature#constructor)(string) | Crea la firma dei metadati del foglio di calcolo con un nome predefinito e un valore vuoto. |
| [SpreadsheetMetadataSignature](spreadsheetmetadatasignature#constructor_1)(string, object) | Crea la firma dei metadati del foglio di calcolo con valori predefiniti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Ottiene o imposta l'implementazione di[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interfaccia per codificare e decodificare la firma Valore proprietà. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà viene utilizzata solo per i record del registro cronologico del documento per conservare l'elenco delle firme eliminate. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della segnatura. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è Firma o contenuto del documento. Questa proprietà viene utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Specifica il nome univoco dei metadati. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la firma della pagina in cui è stata trovata. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore di firma univoco per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata al metodo Sign o Search. Se questa proprietà è stata salvata prima, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Specifica il tipo di valore dei metadati. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specifica l'oggetto dei metadati. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/spreadsheetmetadatasignature/clone#clone_1)() | Clona istanza firma metadati. |
| override [Clone](../../groupdocs.signature.domain/spreadsheetmetadatasignature/clone#clone)(object) | Clona l'istanza della firma dei metadati del foglio di calcolo con un determinato valore. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Ottieni l'oggetto dal valore della firma dei metadati tramite la deserializzazione. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Ottieni l'oggetto dal testo della firma dei metadati tramite la deserializzazione. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Sostituisce il metodo GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Converte in booleano. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Converte in DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Converte in DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Converte in decimale. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Converte in decimale. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Converte in Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Converte in Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Converte in numero intero. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Converte in float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Converte in float. |
| override [ToString](../../groupdocs.signature.domain/spreadsheetmetadatasignature/tostring#tostring)() | Converte in String con override ToString() method |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Converte in stringa con il formato specificato |
| override [ToString](../../groupdocs.signature.domain/spreadsheetmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Converte in stringa con il formato specificato |

### Guarda anche

* class [MetadataSignature](../metadatasignature)
* spazio dei nomi [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
