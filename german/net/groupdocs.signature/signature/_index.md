---
title: "Signatur"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Stellt die Hauptklasse dar, die den Dokumentensignaturprozess steuert."
type: docs
weight: 2170
url: /de/net/groupdocs.signature/signature/
---
## Signature class

Stellt die Hauptklasse dar, die den Dokumentensignaturprozess steuert.

```csharp
public class Signature : IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Initialisiert eine neue Instanz der Klasse [`Signature`](../signature) mit einem über einen Stream bereitgestellten Dokument. |
| [Signature](signature#constructor_4)(string) | Initialisiert eine neue Instanz der Klasse [`Signature`](../signature) mit einem über einen Dateipfad bereitgestellten Dokument. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Initialisiert eine neue Instanz der Klasse [`Signature`](../signature) mit einem über einen Stream bereitgestellten Dokument und den Ladeoptionen LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Initialisiert eine neue Instanz der Klasse [`Signature`](../signature) mit einem über einen Stream bereitgestellten Dokument und [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | Initialisiert eine neue Instanz der Klasse [`Signature`](../signature) mit einem über einen Dateipfad bereitgestellten Dokument und LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Initialisiert eine neue Instanz der Klasse [`Signature`](../signature) mit einem über einen Dateipfad bereitgestellten Dokument und [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Initialisiert eine neue Instanz der Klasse [`Signature`](../signature) mit einem über einen Stream bereitgestellten Dokument, den Ladeoptionen LoadOptions und den Einstellungen [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Initialisiert eine neue Instanz der Klasse [`Signature`](../signature) mit einem über einen Dateipfad bereitgestellten Dokument, LoadOptions und [`SignatureSettings`](../signaturesettings). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Löscht die übergebene Signatur [`BaseSignature`](../../groupdocs.signature.domain/basesignature) aus dem Dokument. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Löscht die übergebene Liste von Signaturen [`BaseSignature`](../../groupdocs.signature.domain/basesignature) aus dem Dokument. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Löscht die Signaturen der angegebenen Typenliste [`SignatureType`](../../groupdocs.signature.domain/signaturetype) aus dem Dokument. Nur Signaturen, die durch die Sign‑Methode hinzugefügt und als Signaturen [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) markiert wurden, werden entfernt. Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR‑Code. |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Löscht die übergebene Liste von Signaturen [`BaseSignature`](../../groupdocs.signature.domain/basesignature) aus dem Dokument. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Löscht Signaturen eines bestimmten Typs [`SignatureType`](../../groupdocs.signature.domain/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) markiert wurden, werden entfernt. Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Löscht die Signatur anhand ihrer spezifischen Signatur‑Id aus dem Dokument. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implementiert das IDisposable-Interface, um interne Ressourcen aufzuräumen. |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Erstellt eine Vorschau der Dokumentseiten. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Ermittelt Informationen über Dokumentseiten: deren Größe, maximale Seitenhöhe, die Breite einer Seite mit der maximalen Höhe. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Durchsucht das Dokument nach Signaturen unter Verwendung aller verfügbaren Suchoptionen und filtert die Ergebnisse anhand des angegebenen Prädikats. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Durchsucht ein Dokument nach Signaturen anhand einer Liste von [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Durchsucht das Dokument nach angegebenen Signaturtypen anhand des Werts [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Durchsucht das Dokument nach Signaturen mit den bereitgestellten Suchoptionen und filtert die Ergebnisse anhand des angegebenen Prädikats. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Durchsucht ein Dokument nach Signaturen anhand von [`SearchOptions`](../../groupdocs.signature.options/searchoptions)-Optionen. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Durchsucht das Dokument nach dem genauen Signaturtyp anhand des Werts [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Signiert das Dokument mit einer Sammlung von [`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einen Stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Signiert das Dokument mit [`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einen Stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Signiert das Dokument mit einer Sammlung von [`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis am angegebenen Dateipfad. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Signiert das Dokument mit [`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis am angegebenen Dateipfad. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Signiert das Dokument mit einer Sammlung von [`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einen Stream mit vordefinierten [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Signiert das Dokument mit [`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einen Stream mit vordefinierten [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Signiert das Dokument mit einer Sammlung von [`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis am angegebenen Dateipfad mit vordefinierten [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Signiert das Dokument mit [`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis am angegebenen Dateipfad mit vordefinierten [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Aktualisiert die übergebene Signatur [`BaseSignature`](../../groupdocs.signature.domain/basesignature) im Dokument. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Aktualisiert die übergebenen Signaturen [`BaseSignature`](../../groupdocs.signature.domain/basesignature) im Dokument. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Überprüft die Signaturen des Dokuments mit einer Liste von VerifyOptions-Daten. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Überprüft die Dokumentensignaturen mit den angegebenen VerifyOptions-Daten. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Überprüft die Dokumentensignaturen unter Verwendung aller verfügbaren Verifizierungsoptionen und filtert die Ergebnisse basierend auf dem angegebenen Prädikat. Diese Methode sucht zunächst nach Signaturen, die den Verifizierungsoptionen entsprechen, filtert sie mithilfe des Prädikats und verifiziert anschließend nur die gefilterten Signaturen. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Überprüft die Dokumentensignaturen unter Verwendung der bereitgestellten Verifizierungsoptionen und filtert die Ergebnisse basierend auf dem angegebenen Prädikat. Diese Methode sucht zunächst nach Signaturen, die den Verifizierungsoptionen entsprechen, filtert sie mithilfe des Prädikats und verifiziert anschließend nur die gefilterten Signaturen. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Erstellt eine Signaturvorschau basierend auf den angegebenen SignOptions. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Tritt auf, wenn der Signatursuchvorgang abgeschlossen ist. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Tritt auf, wenn sich der Fortschritt des Signatursuchvorgangs ändert. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Tritt auf, wenn der Signatursuchvorgang gestartet wird. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Tritt auf, wenn der Dokumentensignaturvorgang abgeschlossen ist. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Tritt auf, wenn sich der Fortschritt des Dokumentensignaturvorgangs ändert. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Tritt auf, wenn der Dokumentensignaturvorgang gestartet wird. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Tritt auf, wenn der Signaturverifizierungsprozess abgeschlossen ist. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Tritt auf, wenn sich der Fortschritt des Signaturverifizierungsprozesses ändert. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Tritt auf, wenn der Signaturverifizierungsprozess gestartet wird. |

### Hinweise

**Learn more**

Mehr über die Funktionen von GroupDocs.Signature: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Siehe auch

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
