---
title: "Delete"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Διαγράφει την παρεχόμενη υπογραφή BaseSignaturegroupdocs.signature.domain/basesignature από το έγγραφο."
type: docs
weight: 110
url: /el/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Διαγράφει την παρεχόμενη υπογραφή [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) από το έγγραφο.

```csharp
public bool Delete(BaseSignature signature)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| υπογραφή | BaseSignature | Αντικείμενο υπογραφής που θα αφαιρεθεί από το έγγραφο. |

### Τιμή Επιστροφής

Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.

### Παρατηρήσεις

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Διαγράφει την παρεχόμενη λίστα υπογραφών [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) από το έγγραφο.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| υπογραφές | List`1 | Λίστα υπογραφών για αφαίρεση από το έγγραφο. |

### Τιμή Επιστροφής

Επιστρέφει το DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) με λίστα των υπογραφών που διαγράφηκαν επιτυχώς και των αποτυχημένων.

### Παρατηρήσεις

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Διαγράφει υπογραφές συγκεκριμένου τύπου [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) από το έγγραφο. Μόνο οι υπογραφές που προστέθηκαν με τη μέθοδο Sign και έχουν χαρακτηριστεί ως Υπογραφές [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) θα αφαιρεθούν. Οι ακόλουθοι τύποι υπογραφών υποστηρίζονται: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureType | SignatureType | Ο τύπος των υπογραφών που θα αφαιρεθούν από το έγγραφο. |

### Τιμή Επιστροφής

Επιστρέφει το DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) με λίστα των υπογραφών που διαγράφηκαν επιτυχώς και των αποτυχημένων.

### Παρατηρήσεις

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Διαγράφει τις υπογραφές της λίστας συγκεκριμένων τύπων [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) από το έγγραφο. Μόνο οι υπογραφές που προστέθηκαν με τη μέθοδο Sign και έχουν χαρακτηριστεί ως Υπογραφές [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) θα αφαιρεθούν. Οι ακόλουθοι τύποι υπογραφών υποστηρίζονται: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureTypes | List`1 | Η λίστα των τύπων υπογραφών που θα αφαιρεθούν από το έγγραφο. |

### Τιμή Επιστροφής

Επιστρέφει το DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) με λίστα των υπογραφών που διαγράφηκαν επιτυχώς και των αποτυχημένων.

### Παρατηρήσεις

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Διαγράφει την υπογραφή με το συγκεκριμένο αναγνωριστικό υπογραφής από το έγγραφο.

```csharp
public bool Delete(string signatureId)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureId | String | Το Id της υπογραφής που πρέπει να αφαιρεθεί από το έγγραφο. |

### Τιμή Επιστροφής

Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.

### Παρατηρήσεις

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Διαγράφει την παρεχόμενη λίστα υπογραφών [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) από το έγγραφο.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureIds | List`1 | Λίστα των ταυτοτήτων των υπογραφών που πρέπει να αφαιρεθούν από το έγγραφο. |

### Τιμή Επιστροφής

Επιστρέφει το DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) με λίστα των υπογραφών που διαγράφηκαν επιτυχώς και των αποτυχημένων.

### Παρατηρήσεις

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
