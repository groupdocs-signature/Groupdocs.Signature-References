---
title: "Signatur"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt die Hauptklasse dar, die den Dokumentensignaturprozess steuert."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Stellt die Hauptklasse dar, die den Dokumentensignaturprozess steuert.

--------------------

**Learn more**

 *  More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide][]


[GroupDocs.Signature Developer Guide]: https://docs.groupdocs.com/display/signaturenet/Developer+Guide
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Signature(InputStream document)](#Signature-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem durch Stream bereitgestellten Dokument. |
| [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem durch Stream bereitgestellten Dokument und Ladeoptionen  LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)). |
| [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem durch Stream bereitgestellten Dokument und [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Stream bereitgestellten Dokument, Ladeoptionen LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) und Einstellungen [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(String filePath)](#Signature-java.lang.String-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument. |
| [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument und Ladeoptionen LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)). |
| [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument und [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument, Ladeoptionen LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) und [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream. |
| [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
| [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream. |
| [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
| [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis am angegebenen Dateipfad. |
| [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis am angegebenen Dateipfad mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
| [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis am angegebenen Dateipfad. |
| [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis am angegebenen Dateipfad mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
| [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Überprüft die Dokumentensignaturen mit den angegebenen VerifyOptions-Daten. |
| [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Überprüft die Dokumentensignaturen mit einer Liste von VerifyOptions-Daten. |
| [getDocumentInfo()](#getDocumentInfo--) | Ermittelt Informationen über die Dokumentenseiten: deren Größen, die maximale Seitenhöhe und die Breite einer Seite mit der maximalen Höhe. |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Erstellt eine Vorschau der Dokumentenseiten. |
| [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Sucht nach Signaturen in einem Dokument anhand einer [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)-Liste. |
| [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Sucht nach Signaturen in einem Dokument anhand von [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)-Optionen. |
| [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Sucht nach dem genauen Signaturtyp im Dokument anhand des [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)-Werts. |
| [search(int[] signatureTypes)](#search-int...-) | Sucht nach angegebenen Signaturtypen im Dokument anhand des [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)-Werts. |
| [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Aktualisiert die übergebene Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument. |
| [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Aktualisiert die übergebenen Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument. |
| [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Aktualisiert die übergebenen Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument. |
| [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Aktualisiert die übergebenen Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument. |
| [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Löscht die übergebene Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument. |
| [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument. |
| [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Löscht die übergebene Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument. |
| [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument. |
| [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Löscht Signaturen des bestimmten Typs [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. |
| [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Löscht die Signaturen der bestimmten Typenliste [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. |
| [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Löscht Signaturen des bestimmten Typs [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. |
| [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Löscht die Signaturen der bestimmten Typenliste [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. |
| [delete(String signatureId)](#delete-java.lang.String-) | Löscht die Signatur anhand ihrer spezifischen Signatur‑Id aus dem Dokument. |
| [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument. |
| [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Erstellt eine Signaturvorschau basierend auf den angegebenen SignOptions. |
| [dispose()](#dispose--) | Implementiert das IDisposable-Interface, um interne Ressourcen zu bereinigen |
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem durch Stream bereitgestellten Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Inhaltsstream des Dokuments. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem durch Stream bereitgestellten Dokument und Ladeoptionen  LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | java.io.InputStream | Der Inhaltsstream des Dokuments. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Die Ladeoptionen des Dokuments. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem durch Stream bereitgestellten Dokument und [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | java.io.InputStream | Der Inhaltsstream des Dokuments. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Die Signatur‑Einstellungen. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Stream bereitgestellten Dokument, Ladeoptionen LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) und Einstellungen [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | java.io.InputStream | Der Inhaltsstream des Dokuments. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Die Ladeoptionen des Dokuments. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Die Signatur‑Einstellungen. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateipfad | java.lang.String | Absoluter oder relativer Dateipfad. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument und Ladeoptionen LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfad | java.lang.String | Absoluter oder relativer Dateipfad. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Die Ladeoptionen des Dokuments. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument und [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfad | java.lang.String | Absoluter oder relativer Dateipfad. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Die Signatur‑Einstellungen. |

--------------------

 **Learn more** 

 *  
 *   |

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


Initialisiert eine neue Instanz der Klasse [Signature](../../com.groupdocs.signature/signature) mit einem über einen Dateipfad bereitgestellten Dokument, Ladeoptionen LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) und [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfad | java.lang.String | Absoluter oder relativer Dateipfad. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Die Ladeoptionen des Dokuments. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Die Signatur‑Einstellungen. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis in einen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | java.io.OutputStream | Der Ausgabestream des Dokuments. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Die Signaturoptionen. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

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
| Dokument | java.io.OutputStream | Der Ausgabestream des Dokuments. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Die Signaturoptionen. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Die Speicheroptionen. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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
| Dokument | java.io.OutputStream | Der Ausgabestream des Dokuments. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Die Liste der Signaturoptionen. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

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
| Dokument | java.io.OutputStream | Der Ausgabestream des Dokuments. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Die Liste der Signaturoptionen. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Die Speicheroptionen. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis am angegebenen Dateipfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Die Signaturoptionen. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


Signiert das Dokument mit [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis am angegebenen Dateipfad mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfad | java.lang.String | Der Ausgabedateipfad. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Die Signaturoptionen. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Die Speicheroptionen. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis am angegebenen Dateipfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Die Liste der Signaturoptionen. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Signiert das Dokument mit einer Sammlung von [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) und speichert das Ergebnis am angegebenen Dateipfad mit vordefinierten [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfad | java.lang.String | Der Ausgabedateipfad. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Die Liste der Signaturoptionen. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Die Speicheroptionen. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

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

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Ermittelt Informationen über die Dokumentenseiten: deren Größen, die maximale Seitenhöhe und die Breite einer Seite mit der maximalen Höhe.

**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

--------------------

**Learn more**

 *  Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java][]


[How to get document properties in Java]: https://docs.groupdocs.com/signature/java/get-document-information/
### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Erstellt eine Vorschau der Dokumentenseiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | Die Vorschaueinstellungen. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature][]


[How to generate document pages preview using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/generate-document-pages-preview/ |

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


Sucht nach Signaturen in einem Dokument anhand einer [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)-Liste.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Die Sammlung von Suchoptionen. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.
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

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - Gibt die Liste der gefundenen Signaturen zurück.
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

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - Gibt die Liste der gefundenen Signaturen mit exakt diesem Typ zurück.
### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Sucht nach angegebenen Signaturtypen im Dokument anhand des [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)-Werts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signatureTypes | int[] | Ein oder mehrere Typen von Signaturen, die gefunden werden sollen. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

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
| Dokument | java.io.OutputStream | Der Ausgabestream des Dokuments. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signaturobjekt, das im Dokument aktualisiert werden soll. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - Gibt true zurück, wenn der Vorgang erfolgreich war.
### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Aktualisiert die übergebenen Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) im Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | java.io.OutputStream | Der Ausgabestream des Dokuments. |
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste der Signaturen, die im Dokument aktualisiert werden sollen. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

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
| Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste der Signaturen, die im Dokument aktualisiert werden sollen. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

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
| Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signaturobjekt, das im Dokument aktualisiert werden soll. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - Gibt UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) mit einer Liste erfolgreich aktualisierter Signaturen und fehlgeschlagener zurück.
### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Löscht die übergebene Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | java.io.OutputStream | Der Ausgabestream des Dokuments. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signaturobjekt, das aus dem Dokument entfernt werden soll. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - Gibt true zurück, wenn der Vorgang erfolgreich war.
### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | java.io.OutputStream | Der Ausgabestream des Dokuments. |
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste der Signaturen, die aus dem Dokument entfernt werden sollen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

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
| Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signaturobjekt, das aus dem Dokument entfernt werden soll. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - Gibt true zurück, wenn der Vorgang erfolgreich war.
### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Liste der Signaturen, die aus dem Dokument entfernt werden sollen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


Löscht Signaturen eines bestimmten Typs [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen markiert wurden (BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-))) werden entfernt. Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | java.io.OutputStream | Der Ausgabestream des Dokuments. |
|  | signatureType | int | Der Typ der Signaturen, die aus dem Dokument entfernt werden sollen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


Löscht die Signaturen einer bestimmten Typenliste [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen markiert wurden (BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-))) werden entfernt. Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | java.io.OutputStream | Der Ausgabestream des Dokuments. |
|  | signatureTypes | java.util.List<java.lang.Integer> | Die Liste der Signaturtypen, die aus dem Dokument entfernt werden sollen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


Löscht Signaturen eines bestimmten Typs [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen markiert wurden (BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-))) werden entfernt. Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|  | signatureType | int | Der Typ der Signaturen, die aus dem Dokument entfernt werden sollen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


Löscht die Signaturen einer bestimmten Typenliste [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen markiert wurden (BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-))) werden entfernt. Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateipfad | java.lang.String | Der Ausgabedateipfad. |
|  | signatureTypes | java.util.List<java.lang.Integer> | Die Liste der Signaturtypen, die aus dem Dokument entfernt werden sollen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


Löscht die Signatur anhand ihrer spezifischen Signatur‑Id aus dem Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signatureId | java.lang.String | Die ID der Signatur, die aus dem Dokument entfernt werden soll. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
boolean - Gibt true zurück, wenn der Vorgang erfolgreich war.
### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Löscht die übergebene Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) aus dem Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Liste der Kennungen der Signaturen, die aus dem Dokument entfernt werden sollen. |

--------------------

**Learn more** ///  ///  /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature][] ///  ///  /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C] ///  ///  ///


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

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

--------------------

**Learn more**

 *  Learn more about how to generate previews of the signatures: |

### dispose() {#dispose--}
```
public final void dispose()
```


Implementiert das IDisposable-Interface, um interne Ressourcen zu bereinigen

