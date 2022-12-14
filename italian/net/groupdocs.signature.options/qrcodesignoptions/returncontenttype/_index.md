---
title: ReturnContentType
second_title: Riferimento API GroupDocs.Signature per .NET
description: Specifica il tipo di file del contenuto dellimmagine restituita della firma del codice QR quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostata su Null. Ciò significa restituire il contenuto dellimmagine QRCode nel formato originale. Questo formato immagine è specificato inFormatgroupdocs.signature.domain/qrcodesignature/format I possibili valori supportati sono FileType.JPEG FileType.PNG FileType.BMP. Se il formato fornito non è supportato verrà restituito il contenuto dellimmagine del codice QR in formato .png.
type: docs
weight: 110
url: /it/net/groupdocs.signature.options/qrcodesignoptions/returncontenttype/
---
## QrCodeSignOptions.ReturnContentType property

Specifica il tipo di file del contenuto dell'immagine restituita della firma del codice QR quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostata su Null. Ciò significa restituire il contenuto dell'immagine QR-Code nel formato originale. Questo formato immagine è specificato in[`Format`](../../../groupdocs.signature.domain/qrcodesignature/format) I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto dell'immagine del codice QR in formato .png.

```csharp
public FileType ReturnContentType { get; set; }
```

### Guarda anche

* class [FileType](../../../groupdocs.signature.domain/filetype)
* class [QrCodeSignOptions](../../qrcodesignoptions)
* spazio dei nomi [GroupDocs.Signature.Options](../../qrcodesignoptions)
* assemblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
