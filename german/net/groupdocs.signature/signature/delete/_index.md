---
title: Delete
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Löscht übergebene SignaturBaseSignaturegroupdocs.signature.domain/basesignature aus dem Dokument.
type: docs
weight: 110
url: /de/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Löscht übergebene Signatur[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) aus dem Dokument.

```csharp
public bool Delete(BaseSignature signature)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signature | BaseSignature | Aus dem Dokument zu entfernendes Signaturobjekt. |

### Rückgabewert

Gibt true zurück, wenn die Operation erfolgreich war.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zum Löschen elektronischer Signaturen aus Dokumenten in C#: [So löschen Sie mit GroupDocs.Signature die elektronische Signatur aus einem Dokument](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Fortgeschrittene Anwendungsfälle zum Löschen elektronischer Signaturen von Dokumenten: [So löschen Sie verschiedene Arten von eSignaturen aus einem Dokument in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Löscht die übergebene Signaturliste[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) aus dem Dokument.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatures | List`1 | Liste der Signaturen, die aus dem Dokument entfernt werden sollen. |

### Rückgabewert

Gibt DeleteResult zurück[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) mit Liste der erfolgreich gelöschten und fehlgeschlagenen Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zum Löschen elektronischer Signaturen aus Dokumenten in C#: [So löschen Sie mit GroupDocs.Signature die elektronische Signatur aus einem Dokument](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Fortgeschrittene Anwendungsfälle zum Löschen elektronischer Signaturen von Dokumenten: [So löschen Sie verschiedene Arten von eSignaturen aus einem Dokument in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Löscht Signaturen des bestimmten Typs[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen markiert wurden[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) wird entfernt. Folgende Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureType | SignatureType | Der Signaturtyp, der aus dem Dokument entfernt werden soll. |

### Rückgabewert

Gibt DeleteResult zurück[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) mit Liste der erfolgreich gelöschten und fehlgeschlagenen Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zum Löschen elektronischer Signaturen aus Dokumenten in C#: [So löschen Sie eSignaturen mit einem bestimmten Typ aus einem Dokument mit GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Fortgeschrittene Anwendungsfälle zum Löschen elektronischer Signaturen von Dokumenten: [So löschen Sie verschiedene Arten von eSignaturen aus einem Dokument in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Löscht die Signaturen der Liste bestimmter Typen[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen markiert wurden[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) wird entfernt. Folgende Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureTypes | List`1 | Die Liste der Signaturtypen, die aus dem Dokument entfernt werden sollen. |

### Rückgabewert

Gibt DeleteResult zurück[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) mit Liste der erfolgreich gelöschten und fehlgeschlagenen Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zum Löschen elektronischer Signaturen aus Dokumenten in C#: [So löschen Sie eSignaturen mit einem bestimmten Typ aus einem Dokument mit GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Fortgeschrittene Anwendungsfälle zum Löschen elektronischer Signaturen von Dokumenten: [So löschen Sie verschiedene Arten von eSignaturen aus einem Dokument in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Löscht die Signatur anhand ihrer spezifischen Signatur-ID aus dem Dokument.

```csharp
public bool Delete(string signatureId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureId | String | Die ID der Signatur, die aus dem Dokument entfernt werden soll. |

### Rückgabewert

Gibt true zurück, wenn die Operation erfolgreich war.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zum Löschen elektronischer Signaturen aus Dokumenten in C#: [So löschen Sie mit GroupDocs.Signature die elektronische Signatur aus einem Dokument](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Fortgeschrittene Anwendungsfälle zum Löschen elektronischer Signaturen von Dokumenten: [So löschen Sie verschiedene Arten von eSignaturen aus einem Dokument in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Löscht die übergebene Signaturliste[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) aus dem Dokument.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureIds | List`1 | Liste der Identifikatoren der Signaturen, die aus dem Dokument entfernt werden sollen. |

### Rückgabewert

Gibt DeleteResult zurück[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) mit Liste der erfolgreich gelöschten und fehlgeschlagenen Signaturen.

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zum Löschen elektronischer Signaturen aus Dokumenten in C#: [So löschen Sie mit GroupDocs.Signature die elektronische Signatur aus einem Dokument](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Fortgeschrittene Anwendungsfälle zum Löschen elektronischer Signaturen von Dokumenten: [So löschen Sie verschiedene Arten von eSignaturen aus einem Dokument in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namensraum [GroupDocs.Signature](../../signature)
* Montage [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
