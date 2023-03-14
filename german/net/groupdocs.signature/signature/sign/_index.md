---
title: Sign
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Unterzeichnet Dokument mitSignOptionsgroupdocs.signature.options/signoptions und speichert das Ergebnis in einem Stream.
type: docs
weight: 160
url: /de/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Unterzeichnet Dokument mit[`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einem Stream.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Ausgabedokumentstrom. |
| signOptions | SignOptions | Die Signaturoptionen. |

### Rückgabewert

Gibt eine Instanz von zurück[`SignResult`](../../../groupdocs.signature.domain/signresult) mit Liste der neu erstellten Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu elektronischen Signaturtypen, die von GroupDocs unterstützt werden.Signature: [Elektronische Signaturtypen, die von GroupDocs.Signature unterstützt werden](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Weitere Informationen zum eSignieren von Dokumenten in C#: [So signieren Sie Dokumente mit GroupDocs.Signature elektronisch](https://docs.groupdocs.com/display/signaturenet/Signing)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Unterzeichnet Dokument mit[`SignOptions`](../../../groupdocs.signature.options/signoptions)und speichert das Ergebnis in einem Stream mit vordefinierten[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Ausgabedokumentstrom. |
| signOptions | SignOptions | Die Signaturoptionen. |
| saveOptions | SaveOptions | Die Speicheroptionen. |

### Rückgabewert

Gibt eine Instanz von zurück[`SignResult`](../../../groupdocs.signature.domain/signresult) mit Liste der neu erstellten Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu elektronischen Signaturtypen, die von GroupDocs unterstützt werden.Signature: [Elektronische Signaturtypen, die von GroupDocs.Signature unterstützt werden](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Weitere Informationen zum eSignieren von Dokumenten in C#: [So signieren Sie Dokumente mit GroupDocs.Signature elektronisch](https://docs.groupdocs.com/display/signaturenet/Signing)
* Weitere Informationen zum Speichern elektronisch signierter Dokumente und Anpassen des Speicherprozesses: [So passen Sie elektronisch signierte Dokumente beim Speichern mit GroupDocs.Signature an](https://docs.groupdocs.com/display/signaturenet/Saving)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Signiert Dokument mit Sammlung von[`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einem Stream.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Ausgabedokumentstrom. |
| signOptionsList | List`1 | Die Liste der Signaturoptionen. |

### Rückgabewert

Gibt eine Instanz von zurück[`SignResult`](../../../groupdocs.signature.domain/signresult) mit Liste der neu erstellten Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu elektronischen Signaturtypen, die von GroupDocs unterstützt werden.Signature: [Elektronische Signaturtypen, die von GroupDocs.Signature unterstützt werden](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Weitere Informationen zum eSignieren von Dokumenten in C#: [So signieren Sie Dokumente mit GroupDocs.Signature elektronisch](https://docs.groupdocs.com/display/signaturenet/Signing)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Signiert Dokument mit Sammlung von[`SignOptions`](../../../groupdocs.signature.options/signoptions)und speichert das Ergebnis in einem Stream mit vordefinierten[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Ausgabedokumentstrom. |
| signOptionsList | List`1 | Die Liste der Signaturoptionen. |
| saveOptions | SaveOptions | Die Speicheroptionen. |

### Rückgabewert

Gibt eine Instanz von zurück[`SignResult`](../../../groupdocs.signature.domain/signresult) mit Liste der neu erstellten Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu elektronischen Signaturtypen, die von GroupDocs unterstützt werden.Signature: [Elektronische Signaturtypen, die von GroupDocs.Signature unterstützt werden](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Weitere Informationen zum eSignieren von Dokumenten in C#: [So signieren Sie Dokumente mit GroupDocs.Signature elektronisch](https://docs.groupdocs.com/display/signaturenet/Signing)
* Weitere Informationen zum Speichern elektronisch signierter Dokumente und Anpassen des Speicherprozesses: [So passen Sie elektronisch signierte Dokumente beim Speichern mit GroupDocs.Signature an](https://docs.groupdocs.com/display/signaturenet/Saving)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Unterzeichnet Dokument mit[`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis im angegebenen Dateipfad.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Ausgabedateipfad. |
| signOptions | SignOptions | Die Signaturoptionen. |

### Rückgabewert

Gibt eine Instanz von zurück[`SignResult`](../../../groupdocs.signature.domain/signresult) mit Liste der neu erstellten Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu elektronischen Signaturtypen, die von GroupDocs unterstützt werden.Signature: [Elektronische Signaturtypen, die von GroupDocs.Signature unterstützt werden](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Weitere Informationen zum eSignieren von Dokumenten in C#: [So signieren Sie Dokumente mit GroupDocs.Signature elektronisch](https://docs.groupdocs.com/display/signaturenet/Signing)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Unterzeichnet Dokument mit[`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis unter dem angegebenen Dateipfad mit vordefinierten[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Ausgabedateipfad. |
| signOptions | SignOptions | Die Signaturoptionen. |
| saveOptions | SaveOptions | Die Speicheroptionen. |

### Rückgabewert

Gibt eine Instanz von zurück[`SignResult`](../../../groupdocs.signature.domain/signresult) mit Liste der neu erstellten Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu elektronischen Signaturtypen, die von GroupDocs unterstützt werden.Signature: [Elektronische Signaturtypen, die von GroupDocs.Signature unterstützt werden](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Weitere Informationen zum eSignieren von Dokumenten in C#: [So signieren Sie Dokumente mit GroupDocs.Signature elektronisch](https://docs.groupdocs.com/display/signaturenet/Signing)
* Weitere Informationen zum Speichern elektronisch signierter Dokumente und Anpassen des Speicherprozesses: [So passen Sie elektronisch signierte Dokumente beim Speichern mit GroupDocs.Signature an](https://docs.groupdocs.com/display/signaturenet/Saving)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Signiert Dokument mit Sammlung von[`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis im angegebenen Dateipfad.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Ausgabedateipfad. |
| signOptionsList | List`1 | Die Liste der Signaturoptionen. |

### Rückgabewert

Gibt eine Instanz von zurück[`SignResult`](../../../groupdocs.signature.domain/signresult) mit Liste der neu erstellten Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu elektronischen Signaturtypen, die von GroupDocs unterstützt werden.Signature: [Elektronische Signaturtypen, die von GroupDocs.Signature unterstützt werden](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Weitere Informationen zum eSignieren von Dokumenten in C#: [So signieren Sie Dokumente mit GroupDocs.Signature elektronisch](https://docs.groupdocs.com/display/signaturenet/Signing)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Signiert Dokument mit Sammlung von[`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis unter dem angegebenen Dateipfad mit vordefinierten[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Ausgabedateipfad. |
| signOptionsList | List`1 | Die Liste der Signaturoptionen. |
| saveOptions | SaveOptions | Die Speicheroptionen. |

### Rückgabewert

Gibt eine Instanz von zurück[`SignResult`](../../../groupdocs.signature.domain/signresult) mit Liste der neu erstellten Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu elektronischen Signaturtypen, die von GroupDocs unterstützt werden.Signature: [Elektronische Signaturtypen, die von GroupDocs.Signature unterstützt werden](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Weitere Informationen zum eSignieren von Dokumenten in C#: [So signieren Sie Dokumente mit GroupDocs.Signature elektronisch](https://docs.groupdocs.com/display/signaturenet/Signing)
* Weitere Informationen zum Speichern elektronisch signierter Dokumente und Anpassen des Speicherprozesses: [So passen Sie elektronisch signierte Dokumente beim Speichern mit GroupDocs.Signature an](https://docs.groupdocs.com/display/signaturenet/Saving)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
