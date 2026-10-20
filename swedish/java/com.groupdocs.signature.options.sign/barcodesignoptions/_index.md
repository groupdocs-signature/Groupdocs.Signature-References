---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar Barcode‑signaturalternativen."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Representerar Barcode‑signaturalternativen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | Initierar en ny instans av klassen BarcodeSignOptions med standardvärden. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Initierar en ny instans av klassen BarcodeSignOptions med text. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Initierar en ny instans av klassen BarcodeSignOptions med text. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Hämtar eller anger Barcode-typ. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Hämtar eller anger Barcode-typ. |
|
|  | [getForeColor()](#getForeColor--) | Hämtar eller anger förgrundsfärgen för Barcode-staplar. |
Användning av denna egenskap kan orsaka problem vid verifiering.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Hämtar eller anger förgrundsfärgen för Barcode-staplar. |
Användning av denna egenskap kan orsaka problem vid verifiering.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Hämtar eller anger förgrundsfärgen för Barcode-staplar. |
Användning av denna egenskap kan orsaka problem vid verifiering.
|
|  | [getInnerMargins()](#getInnerMargins--) | Hämtar eller anger avståndet mellan Barcode-element och resultatbildens kanter. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Hämtar eller anger avståndet mellan Barcode-element och resultatbildens kanter. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Hämtar eller anger justeringen av text i den resulterande Barcode-bilden. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Hämtar eller anger justeringen av text i den resulterande Barcode-bilden. |
|
|  | [getReturnContent()](#getReturnContent--) | Hämtar eller anger flaggan för att hämta Barcode-bildinnehåll för en signatur som placerats på dokumentsidan. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Hämtar eller anger flaggan för att hämta Barcode-bildinnehåll för en signatur som placerats på dokumentsidan. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Anger filtypen för återlämnat bildinnehåll för Barcode-signaturen när egenskapen ReturnContent är aktiverad. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Anger filtypen för återlämnat bildinnehåll för Barcode-signaturen när egenskapen ReturnContent är aktiverad. |
|
|  | [validate()](#validate--) | Intern metod för att validera parametrarna för Barcode-alternativen. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Initierar en ny instans av klassen BarcodeSignOptions med standardvärden.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Initierar en ny instans av klassen BarcodeSignOptions med text.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Barcode-text |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Initierar en ny instans av klassen BarcodeSignOptions med text.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Barcode-text |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode-kodningstyp se [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Hämtar eller anger Barcode-typ.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Hämtar eller anger Barcode-typ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Hämtar eller anger förgrundsfärgen för Barcode-staplar.
Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Hämtar eller anger förgrundsfärgen för Barcode-staplar.
Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Hämtar eller anger förgrundsfärgen för Barcode-staplar.
Användning av denna egenskap kan orsaka problem vid verifiering. Använd den försiktigt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Hämtar eller anger avståndet mellan Barcode-element och resultatbildens kanter.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Hämtar eller anger avståndet mellan Barcode-element och resultatbildens kanter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Hämtar eller anger justeringen av text i den resulterande Barcode-bilden.
Standardvärdet är None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Hämtar eller anger justeringen av text i den resulterande Barcode-bilden.
Standardvärdet är None.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Hämtar eller anger flaggan för att hämta Barcode-bildinnehåll för en signatur som placerats på dokumentsidan.
Om denna flagga är satt till true kommer Barcode-signaturens bildinnehåll att behålla rå bilddata i det begärda formatet.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Som standard är detta alternativ inaktiverat.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Hämtar eller anger flaggan för att hämta Barcode-bildinnehåll för en signatur som placerats på dokumentsidan.
Om denna flagga är satt till true kommer Barcode-signaturens bildinnehåll att behålla rå bilddata i det begärda formatet.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Som standard är detta alternativ inaktiverat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Anger filtypen för återlämnat bildinnehåll för Barcode-signaturen när egenskapen ReturnContent är aktiverad.
Som standard är den satt till Null. Det betyder att Barcode-bildinnehållet returneras i originalformat.
Detta bildformat anges på
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Möjliga stödda värden är: FileType.JPEG, FileType.PNG, FileType.BMP.
Om det angivna formatet inte stöds kommer Barcode‑bildinnehållet i .png‑format att returneras.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Anger filtypen för återlämnat bildinnehåll för Barcode-signaturen när egenskapen ReturnContent är aktiverad.
Som standard är den satt till Null. Det betyder att Barcode-bildinnehållet returneras i originalformat.
Detta bildformat anges på
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
Möjliga stödda värden är: FileType.JPEG, FileType.PNG, FileType.BMP.
Om det angivna formatet inte stöds kommer Barcode‑bildinnehållet i .png‑format att returneras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Intern metod för att validera parametrarna för Barcode-alternativen.


### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
