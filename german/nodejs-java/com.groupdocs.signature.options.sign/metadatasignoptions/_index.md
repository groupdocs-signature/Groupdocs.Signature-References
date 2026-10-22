---
title: "MetadataSignOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt die Metadaten-Signaturoptionen dar."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

Stellt die Metadaten-Signaturoptionen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MetadataSignOptions()](#MetadataSignOptions--) | Initialisiert eine neue Instanz der SignMetadataOptions‑Klasse mit Standardwerten. |
| [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | Initialisiert eine neue Instanz der SignMetadataOptions‑Klasse mit Metadaten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSignatures()](#getSignatures--) | Ruft die Metadaten der Signatur ab oder legt sie fest. |
| [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | Ruft die Metadaten der Signatur ab oder legt sie fest. |
| [getDataEncryption()](#getDataEncryption--) | Ruft die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) Interfaces zum Codieren und Decodieren von QR-Code-Signatur-Text- oder Daten-Eigenschaften ab oder legt sie fest. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Ruft die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) Interfaces zum Codieren und Decodieren von QR-Code-Signatur-Text- oder Daten-Eigenschaften ab oder legt sie fest. |
| [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | Erstellt eine neue PdfMetadataSignature mit übergebenen Argumenten und fügt sie zur Sammlung hinzu. |
| [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | Erstellt eine neue ImageMetadataSignature mit übergebenen Argumenten und fügt sie zur Sammlung hinzu. |
| [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Fügt eine vorhandene MetadataSignature‑Instanz zur Sammlung hinzu. |
| [validate()](#validate--) | Interne Methode zur Validierung der Optionsparameter. |
| [toString()](#toString--) | Überschreibe die String-Konvertierung. |
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


Initialisiert eine neue Instanz der SignMetadataOptions‑Klasse mit Standardwerten.

### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


Initialisiert eine neue Instanz der SignMetadataOptions‑Klasse mit Metadaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Sammlung von Metadaten‑Signaturen [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


Ruft die Metadaten der Signatur ab oder legt sie fest.

**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


Ruft die Metadaten der Signatur ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Ruft die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) Interfaces zum Codieren und Decodieren von QR-Code-Signatur-Text- oder Daten-Eigenschaften ab oder legt sie fest.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Ruft die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) Interfaces zum Codieren und Decodieren von QR-Code-Signatur-Text- oder Daten-Eigenschaften ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


Erstellt eine neue PdfMetadataSignature mit übergebenen Argumenten und fügt sie zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Metadaten‑Signaturobjekts |
| Wert | java.lang.Object | Wert der Metadaten‑Signatur |
| Tag | java.lang.String | Präfix-Tag der Metadaten-Signatur |

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection
### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


Erstellt eine neue ImageMetadataSignature mit übergebenen Argumenten und fügt sie zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ID | int | Eindeutiger Bezeichner des Bild-Metadaten-Signaturnamens. Siehe Referenzen für Exif-Tag-Spezifikationen für mögliche ID-Werte |
| Wert | java.lang.Object | Metadatenwert |

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection
### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


Fügt eine vorhandene MetadataSignature‑Instanz zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Die vorhandene MetadataSignature-Instanz, die hinzugefügt werden soll |

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself
### validate() {#validate--}
```
public void validate()
```


Interne Methode zur Validierung der Optionsparameter.

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.

**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
