---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Gibt den Implementierungstyp für PDF-Textsignaturen an."
type: docs
weight: 32
url: /de/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
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
|  | [Native](#Native) | Textsignatur als natives Textobjekt auf der Dokumentenseite. |
|
|  | [Image](#Image) | Textsignatur als Bildobjekt auf der Dokumentenseite. |
|
|  | [Annotation](#Annotation) | Textsignatur als Textanmerkungsobjekt auf der PDF-Seite. |
|
|  | [Sticker](#Sticker) | Textsignatur als Sticker-Objekt auf der PDF-Seite. |
|
|  | [FormField](#FormField) | Textsignatur als Text im angegebenen Formularfeld. |
|
|  | [Watermark](#Watermark) | Textsignatur als Wasserzeichen auf der Dokumentenseite. |
|
### Native {#Native}
```
public static final int Native
```


Textsignatur als natives Textobjekt auf der Dokumentenseite.


### Image {#Image}
```
public static final int Image
```


Textsignatur als Bildobjekt auf der Dokumentenseite.


### Annotation {#Annotation}
```
public static final int Annotation
```


Textsignatur als Textanmerkungsobjekt auf der PDF-Seite.
Anmerkungen sind nur in der lizenzierten Version sichtbar.


### Sticker {#Sticker}
```
public static final int Sticker
```


Textsignatur als Sticker-Objekt auf der PDF-Seite.


### FormField {#FormField}
```
public static final int FormField
```


Textsignatur als Text im angegebenen Formularfeld.
Mit diesem Implementierungstyp kann nur TextSignOptions.Text verwendet werden,
TextSignOptions.FormTextFieldType- und TextSignOptions.FormTextFieldTitle-Optionen.


### Watermark {#Watermark}
```
public static final int Watermark
```


Textsignatur als Wasserzeichen auf der Dokumentenseite.


