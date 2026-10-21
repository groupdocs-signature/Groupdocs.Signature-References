---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Contiene le proprietà della firma dei metadati PDF."
type: docs
weight: 860
url: /it/net/groupdocs.signature.domain/pdfmetadatasignature/
---
## PdfMetadataSignature class

Contiene le proprietà della firma dei metadati PDF.

```csharp
public sealed class PdfMetadataSignature : MetadataSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfMetadataSignature](pdfmetadatasignature#constructor)(string) | Crea firma Pdf Metadata con nome predefinito e valore vuoto |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_1)(string, object) | Crea firma Pdf Metadata con valori predefiniti |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_2)(string, object, string) | Crea firma Pdf Metadata con valori predefiniti |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Ottiene o imposta l'implementazione dell'interfaccia [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) per codificare e decodificare le proprietà Value della firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà è utilizzata solo per i record del registro della cronologia del documento per mantenere l'elenco delle firme eliminate. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. Questa proprietà è utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Specifica il nome univoco dei metadati. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la pagina su cui è stata trovata la firma. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore univoco della firma per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata dei metodi Sign o Search. Se questa proprietà è stata salvata in precedenza, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [TagPrefix](../../groupdocs.signature.domain/pdfmetadatasignature/tagprefix) { get; set; } | Il tag prefisso del nome della firma Pdf Metadata. Per impostazione predefinita questa proprietà è impostata su "xmp". I valori possibili sono |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Specifica il tipo di valore dei metadati. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specifica l'oggetto dei metadati. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone_1)() | Clona l'istanza di Metadata Signature. |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone)(object) | Clona l'istanza di Pdf Metadata Signature con il valore fornito. |
| override [Equals](../../groupdocs.signature.domain/pdfmetadatasignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Ottieni l'oggetto dal valore Metadata Signature durante la deserializzazione. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Ottieni l'oggetto dal testo Metadata Signature durante la deserializzazione. |
| override [GetHashCode](../../groupdocs.signature.domain/pdfmetadatasignature/gethashcode)() | Sovrascrive il metodo GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Converte in booleano. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Converte in DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Converte in DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Converte in Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Converte in Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Converte in Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Converte in Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Converte in intero. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Converte in float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Converte in float. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)() | Converte in String con il metodo ToString() sovrascritto |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Converte in String con formato specificato |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string, IFormatProvider) | Converte in String con formato specificato |

### Vedi anche

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
