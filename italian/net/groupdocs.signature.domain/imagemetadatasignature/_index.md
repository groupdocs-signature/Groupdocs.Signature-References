---
title: ImageMetadataSignature
second_title: Riferimento API GroupDocs.Signature per .NET
description: Contiene le proprietà della firma dei metadati dellimmagine.
type: docs
weight: 550
url: /it/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Contiene le proprietà della firma dei metadati dell'immagine.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Crea la firma dei metadati dell'immagine con ID e valore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Ottiene o imposta l'implementazione di[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interfaccia per codificare e decodificare la firma Valore proprietà. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà viene utilizzata solo per i record del registro cronologico del documento per conservare l'elenco delle firme eliminate. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Valore di sola lettura per ottenere la descrizione per i metadati immagine standard signature |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della segnatura. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | L'identificatore della firma dei metadati dell'immagine. VediImageMetadataSignatures classe che contiene la firma standard con valore Id predefinito. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è Firma o contenuto del documento. Questa proprietà viene utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Specifica il nome univoco dei metadati. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la firma della pagina in cui è stata trovata. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore di firma univoco per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata al metodo Sign o Search. Se questa proprietà è stata salvata prima, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Valore di sola lettura per ottenere la dimensione del valore dei metadati |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specifica l'oggetto dei metadati. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Clona istanza firma metadati. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Clona l'istanza della firma dei metadati dell'immagine con un determinato valore. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Ottieni l'oggetto dal valore della firma dei metadati tramite la deserializzazione. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Ottieni l'oggetto dal testo della firma dei metadati tramite la deserializzazione. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Sostituisce il metodo GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Converte in booleano. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Converte in DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Converte in DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Converte in decimale. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Converte in decimale. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Converte in Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Converte in Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Converte in numero intero. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Converte in long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Converte in float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Converte in float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Converte in String con override ToString() method |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Converte in stringa con il formato specificato |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Converte in stringa con il formato specificato |

### Guarda anche

* class [MetadataSignature](../metadatasignature)
* spazio dei nomi [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
