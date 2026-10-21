---
title: "CertificateMetadataSignature"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Contiene le proprietà della firma dei metadati del certificato."
type: docs
weight: 70
url: /it/net/groupdocs.signature.domain/certificatemetadatasignature/
---
## CertificateMetadataSignature class

Contiene le proprietà della firma dei metadati del certificato.

```csharp
public sealed class CertificateMetadataSignature : MetadataSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CertificateMetadataSignature](certificatemetadatasignature#constructor)(string) | Crea Certificate Metadata Signature con nome predefinito e valore vuoto. |
| [CertificateMetadataSignature](certificatemetadatasignature#constructor_1)(string, object) | Crea Certificate Metadata Signature con valori predefiniti. |

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
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Specifica il tipo di valore dei metadati. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Specifica l'oggetto dei metadati. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/certificatemetadatasignature/clone#clone_1)() | Clona l'istanza di Metadata Signature. |
| override [Clone](../../groupdocs.signature.domain/certificatemetadatasignature/clone#clone)(object) | Clona l'istanza di Certificate Metadata Signature con il valore fornito. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Ottieni l'oggetto dal valore Metadata Signature durante la deserializzazione. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Ottieni l'oggetto dal testo Metadata Signature durante la deserializzazione. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Sovrascrive il metodo GetHashCode |
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
| override [ToString](../../groupdocs.signature.domain/certificatemetadatasignature/tostring#tostring)() | Converte in String con il metodo ToString() sovrascritto |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Converte in String con formato specificato |
| override [ToString](../../groupdocs.signature.domain/certificatemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Converte in String con formato specificato |

### Vedi anche

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
