---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Gibt den Implementierungstyp für PDF-Textsignaturen an."
type: docs
weight: 32
url: /de/nodejs-java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

Gibt den Implementierungstyp für PDF-Textsignaturen an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Native](#Native) | Textsignatur als natives Textobjekt auf der Dokumentseite. |
| [Image](#Image) | Textsignatur als Bildobjekt auf der Dokumentseite. |
| [Annotation](#Annotation) | Textsignatur als Text-Anmerkungsobjekt auf der PDF-Seite. |
| [Sticker](#Sticker) | Textsignatur als Sticker-Objekt auf der PDF-Seite. |
| [FormField](#FormField) | Textsignatur als Text in einem angegebenen Formularfeld. |
| [Watermark](#Watermark) | Textsignatur als Wasserzeichen auf der Dokumentseite. |
### Native {#Native}
```
public static final int Native
```


Textsignatur als natives Textobjekt auf der Dokumentseite.

### Image {#Image}
```
public static final int Image
```


Textsignatur als Bildobjekt auf der Dokumentseite.

### Annotation {#Annotation}
```
public static final int Annotation
```


Textsignatur als Textanmerkungsobjekt auf der PDF-Seite. Anmerkungen sind nur in der lizenzierten Version sichtbar.

### Sticker {#Sticker}
```
public static final int Sticker
```


Textsignatur als Sticker-Objekt auf der PDF-Seite.

### FormField {#FormField}
```
public static final int FormField
```


Textsignatur als Text in einem angegebenen Formularfeld. Bei dieser Implementierungsart können nur die Optionen TextSignOptions.Text, TextSignOptions.FormTextFieldType und TextSignOptions.FormTextFieldTitle verwendet werden.

### Watermark {#Watermark}
```
public static final int Watermark
```


Textsignatur als Wasserzeichen auf der Dokumentseite.

