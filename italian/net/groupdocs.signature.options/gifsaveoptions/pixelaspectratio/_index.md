---
title: "PixelAspectRatio"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Ottiene o imposta il rapporto d'aspetto dei pixel GIF."
type: docs
weight: 80
url: /it/net/groupdocs.signature.options/gifsaveoptions/pixelaspectratio/
---
## GifSaveOptions.PixelAspectRatio property

Ottiene o imposta il rapporto d'aspetto dei pixel GIF.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Osservazioni

Pixel Aspect Ratio - Fattore usato per calcolare un'approssimazione del rapporto d'aspetto del pixel nell'immagine originale. Se il valore del campo non è 0, questa approssimazione del rapporto d'aspetto è calcolata in base alla formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Il Pixel Aspect Ratio è definito come il quoziente tra la larghezza e l'altezza del pixel. L'intervallo di valori in questo campo consente di specificare il pixel più largo da 4:1 al pixel più alto da 1:4 in incrementi di 1/64. Valori: 0 - Nessuna informazione sul rapporto d'aspetto fornita. 1..255 - Valore usato nel calcolo.

### Vedi anche

* class [GifSaveOptions](../../gifsaveoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
