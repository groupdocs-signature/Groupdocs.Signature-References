---
title: Signature
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Stellt die Hauptklasse dar die den Dokumentensignaturprozess steuert.
type: docs
weight: 1880
url: /de/net/groupdocs.signature/signature/
---
## Signature class

Stellt die Hauptklasse dar, die den Dokumentensignaturprozess steuert.

```csharp
public class Signature : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Initialisiert eine neue Instanz von[`Signature`](../signature) Klasse mit Dokument bereitgestellt von stream. |
| [Signature](signature#constructor_4)(string) | Initialisiert eine neue Instanz von[`Signature`](../signature) Klasseninstanz mit Dokument bereitgestellt durch Dateipfad. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Initialisiert eine neue Instanz von[`Signature`](../signature) Klasse mit Dokument, das von Stream- und Ladeoptionen bereitgestellt wirdLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Initialisiert eine neue Instanz von[`Signature`](../signature)Klasseninstanz mit Dokument, das von Stream und bereitgestellt wird[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | Initialisiert eine neue Instanz von[`Signature`](../signature) Klasseninstanz mit Dokument, bereitgestellt durch Dateipfad undLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Initialisiert eine neue Instanz von[`Signature`](../signature) Klasseninstanz mit Dokument, bereitgestellt durch Dateipfad und[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Initialisiert eine neue Instanz von[`Signature`](../signature) Klasseninstanz mit Dokument, das von Stream bereitgestellt wird, LadeoptionenLoadOptions und Einstellungen[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Initialisiert eine neue Instanz von[`Signature`](../signature) Klasseninstanz mit Dokument bereitgestellt durch Dateipfad,LoadOptions Und[`SignatureSettings`](../signaturesettings) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Löscht übergebene Signatur[`BaseSignature`](../../groupdocs.signature.domain/basesignature) aus dem Dokument. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Löscht die übergebene Signaturliste[`BaseSignature`](../../groupdocs.signature.domain/basesignature) aus dem Dokument. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Löscht die Signaturen der Liste bestimmter Typen[`SignatureType`](../../groupdocs.signature.domain/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen markiert wurden[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) wird entfernt. Folgende Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Löscht die übergebene Signaturliste[`BaseSignature`](../../groupdocs.signature.domain/basesignature) aus dem Dokument. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Löscht Signaturen des bestimmten Typs[`SignatureType`](../../groupdocs.signature.domain/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen markiert wurden[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) wird entfernt. Folgende Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Löscht die Signatur anhand ihrer spezifischen Signatur-ID aus dem Dokument. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implementieren Sie die IDisposable-Schnittstelle, um interne Ressourcen zu bereinigen |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Erstellt eine Vorschau der Dokumentseiten. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Ruft Informationen über Dokumentseiten ab: ihre Größe, maximale Seitenhöhe, die Breite einer Seite mit der maximalen Höhe. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Sucht nach Unterschriften in einem Dokument von[`SearchOptions`](../../groupdocs.signature.options/searchoptions) Liste. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Sucht nach bestimmten Signaturtypen im Dokument nach[`SignatureType`](../../groupdocs.signature.domain/signaturetype) wert. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | Sucht nach Unterschriften in einem Dokument von[`SearchOptions`](../../groupdocs.signature.options/searchoptions) Optionen. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | Sucht nach dem genauen Signaturtyp im Dokument von[`SignatureType`](../../groupdocs.signature.domain/signaturetype) wert. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Signiert Dokument mit Sammlung von[`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einem Stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Unterzeichnet Dokument mit[`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einem Stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Signiert Dokument mit Sammlung von[`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis im angegebenen Dateipfad. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Unterzeichnet Dokument mit[`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis im angegebenen Dateipfad. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Signiert Dokument mit Sammlung von[`SignOptions`](../../groupdocs.signature.options/signoptions)und speichert das Ergebnis in einem Stream mit vordefinierten[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Unterzeichnet Dokument mit[`SignOptions`](../../groupdocs.signature.options/signoptions)und speichert das Ergebnis in einem Stream mit vordefinierten[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Signiert Dokument mit Sammlung von[`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis unter dem angegebenen Dateipfad mit vordefinierten[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Unterzeichnet Dokument mit[`SignOptions`](../../groupdocs.signature.options/signoptions) und speichert das Ergebnis unter dem angegebenen Dateipfad mit vordefinierten[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Updates übergeben Signatur[`BaseSignature`](../../groupdocs.signature.domain/basesignature) im Dokument. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Aktualisierungen übergebener Signaturen[`BaseSignature`](../../groupdocs.signature.domain/basesignature) im Dokument. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Verifiziert die Dokumentsignaturen mit einer Liste von VerifyOptions-Daten. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verifiziert die Dokumentsignaturen mit den angegebenen VerifyOptions-Daten. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Erzeugt Signaturvorschau basierend auf gegebenen SignOptions.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Veranstaltungen

| Name | Beschreibung |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Tritt auf, wenn der Signatursuchprozess abgeschlossen ist. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Tritt auf, wenn sich der Fortschritt des Signatursuchvorgangs geändert hat. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Tritt auf, wenn der Signatursuchprozess gestartet wurde. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Tritt auf, wenn der Dokumentensignierungsprozess abgeschlossen ist. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Tritt auf, wenn der Fortschritt des Dokumentsignaturvorgangs geändert wird. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Tritt auf, wenn der Dokumentensignierungsprozess gestartet wurde. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Tritt auf, wenn der Signaturüberprüfungsprozess abgeschlossen ist. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Tritt auf, wenn sich der Fortschritt des Signaturüberprüfungsprozesses geändert hat. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Tritt auf, wenn der Signaturüberprüfungsprozess gestartet wurde. |

### Bemerkungen

**Erfahren Sie mehr**

* Mehr über GroupDocs.Signature-Funktionen: [GroupDocs.Signature-Entwicklerhandbuch](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Siehe auch

* namensraum [GroupDocs.Signature](../../groupdocs.signature)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
