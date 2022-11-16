---
title: MetadataSignature
second_title: Riferimento API GroupDocs.Signature per .NET
description: Contiene le proprietà della firma dei metadati.
type: docs
weight: 590
url: /it/net/groupdocs.signature.domain/metadatasignature/
---
## MetadataSignature class

Contiene le proprietà della firma dei metadati.

```csharp
public abstract class MetadataSignature : BaseSignature
```

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
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specifica l'oggetto dei metadati. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone_1)() | Clona istanza firma metadati. |
| virtual [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone)(object) | Clona l'istanza della firma dei metadati con il valore specificato. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata)() | Ottieni l'oggetto dal valore della firma dei metadati tramite la deserializzazione. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata_1)(IDataEncryption) | Ottieni l'oggetto dal testo della firma dei metadati tramite la deserializzazione. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Sostituisce il metodo GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Converte in booleano. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime)() | Converte in DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime_1)(IFormatProvider) | Converte in DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal)() | Converte in decimale. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal_1)(IFormatProvider) | Converte in decimale. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble)() | Converte in Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble_1)(IFormatProvider) | Converte in Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Converte in numero intero. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle)() | Converte in float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle_1)(IFormatProvider) | Converte in float. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring)() | Converte in String con override ToString() method |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_1)(string) | Converte in stringa con il formato specificato |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_2)(string, IFormatProvider) | Converte in stringa con il formato specificato |

### Guarda anche

* class [BaseSignature](../basesignature)
* spazio dei nomi [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
