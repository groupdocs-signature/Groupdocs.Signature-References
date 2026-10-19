---
title: "WordProcessingTextSignatureImplementation"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Gibt den Typ der Textsignatur-Implementierung für Textverarbeitungsdokumente an."
type: docs
weight: 36
url: /de/java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

Gibt den Typ der Textsignatur-Implementierung für Textverarbeitungsdokumente an.

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [TextStamp](#TextStamp) | Textsignatur als Beschriftungsobjekt auf einer Words‑Seite. |
|
|  | [TextAsImage](#TextAsImage) | Textsignatur als Bildobjekt auf einer Words‑Seite. |
|
|  | [TextToFormField](#TextToFormField) | Textsignatur als Text im angegebenen Formularfeld. |
|
|  | [Watermark](#Watermark) | Textsignatur als Wasserzeichen auf einer Words‑Seite. |
|
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


Textsignatur als Beschriftungsobjekt auf einer Words‑Seite.


### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


Textsignatur als Bildobjekt auf einer Words‑Seite.


### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


Textsignatur als Text im angegebenen Formularfeld.
Mit diesem Implementierungstyp kann nur TextSignOptions.Text verwendet werden,
Optionen für TextSignOptions.FormTextFieldTitle und TextSignOptions.FormTextFieldType.


### Watermark {#Watermark}
```
public static final int Watermark
```


Textsignatur als Wasserzeichen auf einer Words‑Seite.


