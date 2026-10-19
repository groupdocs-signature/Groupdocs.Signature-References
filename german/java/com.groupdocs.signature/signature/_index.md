---
title: "Signatur"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die Hauptklasse dar, die den Dokumentensignaturprozess steuert."
type: docs
weight: 10
url: /de/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Stellt die Hauptklasse dar, die den Dokumentensignaturprozess steuert.

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Stream bereitgestellten Dokument. |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Stream bereitgestellten Dokument und Ladeloptionen |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Stream bereitgestellten Dokument und [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Stream bereitgestellten Dokument, Ladeloptionen |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) und Einstellungen [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument. |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument und |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument und [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument, |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) und [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream. |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis an dem angegebenen Dateipfad. |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis an dem angegebenen Dateipfad mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis an dem angegebenen Dateipfad. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis im angegebenen Dateipfad mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Überprüft die Dokumentensignaturen mit den angegebenen VerifyOptions-Daten. |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Überprüft die Dokumentensignaturen mit einer Liste von VerifyOptions-Daten. |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Überprüft die Dokumentensignaturen mithilfe der bereitgestellten Verifizierungsoptionen und Filter |
die erfolgreichen Ergebnisse nach dem angegebenen Prädikat.
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Überprüft die Dokumentensignaturen mithilfe einer Liste von Verifizierungsoptionen und filtert die |
erfolgreichen Ergebnisse nach dem angegebenen Prädikat.
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Erhält Informationen über Dokumentenseiten: deren Größen, |
maximale Seitenhöhe, die Breite einer Seite mit der maximalen Höhe.
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Erstellt eine Vorschau der Dokumentenseiten. |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Sucht nach Signaturen in einem Dokument anhand einer [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)-Liste. |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Sucht nach Signaturen anhand einer Optionsliste und filtert das Ergebnis nach einem Prädikat. |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Sucht nach Signaturen in einem Dokument anhand von [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)-Optionen. |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | Sucht nach Signaturen des angegebenen Typs im Dokument, optional nach einem Prädikat gefiltert. |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Sucht nach dem genauen Signaturtyp im Dokument anhand des [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)-Werts. |
|
|  | [search(int[] signatureTypes)](#search-int...-) | Sucht nach den angegebenen Signaturtypen im Dokument anhand des [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)-Werts. |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Aktualisiert die übergebene Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument. |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Aktualisiert die übergebenen Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument. |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Aktualisiert die übergebenen Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument. |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Aktualisiert die übergebenen Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument. |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Löscht die übergebene Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument. |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument. |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Löscht die übergebene Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument. |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument. |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Löscht Signaturen des bestimmten Typs [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Löscht die Signaturen der bestimmten Typenliste [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Löscht Signaturen des bestimmten Typs [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Löscht die Signaturen der bestimmten Typenliste [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | Löscht die Signatur anhand ihrer spezifischen Signatur-ID aus dem Dokument. |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument. |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Erstellt eine Signaturvorschau basierend auf den angegebenen SignOptions. |
|
|  | [dispose()](#dispose--) | Implementiert die IDisposable-Schnittstelle, um interne Ressourcen zu bereinigen |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Stream bereitgestellten Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Inhaltsstrom des Dokuments. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Stream bereitgestellten Dokument und Ladeloptionen
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Inhaltsstrom des Dokuments. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Die Ladeoptionen für das Dokument. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Stream bereitgestellten Dokument und [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Inhaltsstrom des Dokuments. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Die Signatur‑Einstellungen. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Stream bereitgestellten Dokument, Ladeloptionen
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) und Einstellungen [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Inhaltsstrom des Dokuments. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Die Ladeoptionen für das Dokument. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Die Signatur‑Einstellungen. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Absoluter oder relativer Dateipfad. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument und
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Absoluter oder relativer Dateipfad. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Die Ladeoptionen für das Dokument. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument und [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Absoluter oder relativer Dateipfad. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Die Signatur‑Einstellungen. |

<br />

*** ** * ** ***

 **Learn more** 

* 
* 

<br />

|

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument,
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) und [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Absoluter oder relativer Dateipfad. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Die Ladeoptionen für das Dokument. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Die Signatur‑Einstellungen. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Ausgabedokumentenstrom. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Die Signaturoptionen. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Ausgabedokumentenstrom. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Die Signaturoptionen. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Die Speicheroptionen. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Ausgabedokumentenstrom. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Die Liste der Signaturoptionen. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Ausgabedokumentenstrom. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Die Liste der Signaturoptionen. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Die Speicheroptionen. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis an dem angegebenen Dateipfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Die Signaturoptionen. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis an dem angegebenen Dateipfad mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Die Signaturoptionen. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Die Speicheroptionen. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis an dem angegebenen Dateipfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Die Liste der Signaturoptionen. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis im angegebenen Dateipfad mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Die Liste der Signaturoptionen. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Die Speicheroptionen. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


Überprüft die Dokumentensignaturen mit den angegebenen VerifyOptions-Daten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | Die Optionen zur Signaturüberprüfung. |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


Überprüft die Dokumentensignaturen mit einer Liste von VerifyOptions-Daten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | Die Sammlung von Signaturüberprüfungsoptionen. Instanz von [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)
```


Überprüft die Dokumentensignaturen mithilfe der bereitgestellten Verifizierungsoptionen und Filter
die erfolgreichen Ergebnisse nach dem angegebenen Prädikat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | Die Optionen zur Signaturüberprüfung. |
|
|  | Prädikat | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Filterprädikat, das auf die Liste der verifizierten Signaturen angewendet wird. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Liste der Signaturen, die die Verifizierung bestanden haben und das Prädikat erfüllten.

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


Überprüft die Dokumentensignaturen mithilfe einer Liste von Verifizierungsoptionen und filtert die
erfolgreichen Ergebnisse nach dem angegebenen Prädikat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | Die Liste der Signaturüberprüfungsoptionen. |
|
|  | Prädikat | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Filterprädikat, das auf die Liste der verifizierten Signaturen angewendet wird. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Liste der Signaturen, die die Verifizierung bestanden haben und das Prädikat erfüllten.

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Erhält Informationen über Dokumentenseiten: deren Größen,
maximale Seitenhöhe, die Breite einer Seite mit der maximalen Höhe.


**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

<br />

*** ** * ** ***

**Learn more**

* Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java](../https://docs.groupdocs.com/signature/java/get-document-information/)

<br />


### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Erstellt eine Vorschau der Dokumentenseiten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | Die Vorschaueinstellungen. |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/generate-document-pages-preview/)

<br />

|

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


Sucht nach Signaturen in einem Dokument anhand einer [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)-Liste.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Die Sammlung der Suchoptionen. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.

### search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)
```


Sucht nach Signaturen anhand einer Optionsliste und filtert das Ergebnis nach einem Prädikat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Die Liste der Suchoptionen. |
|
|  | Prädikat | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Prädikat, das verwendet wird, um die resultierenden Signaturen zu filtern. |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


Sucht nach Signaturen in einem Dokument anhand von [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)-Optionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Die Suchoptionen. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Gibt die Liste der gefundenen Signaturen zurück.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


Sucht nach Signaturen des angegebenen Typs im Dokument, optional nach einem Prädikat gefiltert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | Generischer Typ-Parameter von [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Optionen für die Signatursuche. |
|
|  | Prädikat | java.util.function.Predicate<T> | Optionaler Prädikat-Filter, der nach der Suche angewendet wird. Kann null sein. |
|

**Returns:**
java.util.List<T> - Liste der gefundenen Signaturen, optional nach dem Prädikat gefiltert.

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Sucht nach dem genauen Signaturtyp im Dokument anhand des [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)-Werts.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | Der Typ der zu suchenden Signaturen. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Gibt die Liste der gefundenen Signaturen mit exakt diesem Typ zurück.

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Sucht nach den angegebenen Signaturtypen im Dokument anhand des [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)-Werts.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signatureTypes | int[] | Ein oder mehrere Typen von Signaturen, die gefunden werden sollen. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.

### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


Aktualisiert die übergebene Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Ausgabedokumentenstrom. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signaturobjekt, das im Dokument aktualisiert werden soll. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - Gibt true zurück, wenn die Operation erfolgreich war.

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Aktualisiert die übergebenen Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Ausgabedokumentenstrom. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste der Signaturen, die im Dokument aktualisiert werden sollen. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


Aktualisiert die übergebenen Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste der Signaturen, die im Dokument aktualisiert werden sollen. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


Aktualisiert die übergebenen Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signaturobjekt, das im Dokument aktualisiert werden soll. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - Gibt UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) mit einer Liste der erfolgreich aktualisierten Signaturen und der fehlgeschlagenen Signaturen zurück.

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Löscht die übergebene Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Ausgabedokumentenstrom. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signaturobjekt, das aus dem Dokument entfernt werden soll. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - Gibt true zurück, wenn die Operation erfolgreich war.

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Ausgabedokumentenstrom. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste der Signaturen, die aus dem Dokument entfernt werden sollen. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


Löscht die übergebene Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signaturobjekt, das aus dem Dokument entfernt werden soll. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - Gibt true zurück, wenn die Operation erfolgreich war.

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste der Signaturen, die aus dem Dokument entfernt werden sollen. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


Löscht Signaturen des bestimmten Typs [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument.
Nur Signaturen, die durch die Sign-Methode hinzugefügt und als Signaturen markiert wurden.
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) wird entfernt.
Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Ausgabedokumentenstrom. |
|
|  | signatureType | int | Der Typ der Signaturen, die aus dem Dokument entfernt werden sollen. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


Löscht die Signaturen der bestimmten Typenliste [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument.
Nur Signaturen, die durch die Sign-Methode hinzugefügt und als Signaturen markiert wurden.
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) wird entfernt.
Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Ausgabedokumentenstrom. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | Die Liste der Signaturtypen, die aus dem Dokument entfernt werden sollen. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


Löscht Signaturen des bestimmten Typs [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument.
Nur Signaturen, die durch die Sign-Methode hinzugefügt und als Signaturen markiert wurden.
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) wird entfernt.
Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|
|  | signatureType | int | Der Typ der Signaturen, die aus dem Dokument entfernt werden sollen. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


Löscht die Signaturen der bestimmten Typenliste [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument.
Nur Signaturen, die durch die Sign-Methode hinzugefügt und als Signaturen markiert wurden.
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) wird entfernt.
Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | Die Liste der Signaturtypen, die aus dem Dokument entfernt werden sollen. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


Löscht die Signatur anhand ihrer spezifischen Signatur-ID aus dem Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signatureId | java.lang.String | Die ID der Signatur, die aus dem Dokument entfernt werden soll. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
boolean - Gibt true zurück, wenn die Operation erfolgreich war.

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Liste der Kennungen der Signaturen, die aus dem Dokument entfernt werden sollen. |

<br />

*** ** * ** ***

**Learn more** /// /// /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents) /// /// /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting) /// /// ///
|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


Erzeugt eine Signaturvorschau basierend auf den angegebenen SignOptions. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | Die Vorschau-Signatur mit den angegebenen SignOptions. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


Implementiert die IDisposable-Schnittstelle, um interne Ressourcen zu bereinigen


