---
title: Delete
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Διαγράφει την υπογραφή που έχει περάσειBaseSignaturegroupdocs.signature.domain/basesignature από το έγγραφο.
type: docs
weight: 110
url: /el/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Διαγράφει την υπογραφή που έχει περάσει[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) από το έγγραφο.

```csharp
public bool Delete(BaseSignature signature)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signature | BaseSignature | Αντικείμενο υπογραφής που πρέπει να αφαιρεθεί από το έγγραφο. |

### Επιστρεφόμενη Αξία

Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο διαγραφής ηλεκτρονικής υπογραφής από έγγραφο σε C#: [Τρόπος διαγραφής eSignature από έγγραφο με GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Προηγμένες περιπτώσεις διαγραφής εγγράφων eSignatures: [Πώς να διαγράψετε διαφορετικούς τύπους ηλεκτρονικών υπογραφών από έγγραφο σε C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Διαγράφει τη λίστα υπογραφών που έχει περάσει[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) από το έγγραφο.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatures | List`1 | Λίστα υπογραφών προς κατάργηση από το έγγραφο. |

### Επιστρεφόμενη Αξία

Επιστρέφει το DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) με λίστα επιτυχώς διαγραμμένων υπογραφών και αποτυχημένων υπογραφών.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο διαγραφής ηλεκτρονικής υπογραφής από έγγραφο σε C#: [Τρόπος διαγραφής eSignature από έγγραφο με GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Προηγμένες περιπτώσεις διαγραφής εγγράφων eSignatures: [Πώς να διαγράψετε διαφορετικούς τύπους ηλεκτρονικών υπογραφών από έγγραφο σε C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Διαγράφει υπογραφές συγκεκριμένου τύπου[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) από το έγγραφο. Μόνο υπογραφές που προστέθηκαν με τη μέθοδο Sign και επισημάνθηκαν ως υπογραφές[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) θα αφαιρεθεί. Υποστηρίζονται οι ακόλουθοι τύποι υπογραφών: Κείμενο, Εικόνα, Ψηφιακός, Γραμμωτός κώδικας, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureType | SignatureType | Ο τύπος των υπογραφών που πρέπει να αφαιρεθούν από το έγγραφο. |

### Επιστρεφόμενη Αξία

Επιστρέφει το DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) με λίστα επιτυχώς διαγραμμένων υπογραφών και αποτυχημένων υπογραφών.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο διαγραφής ηλεκτρονικής υπογραφής από έγγραφο σε C#: [Πώς να διαγράψετε eSignatures με συγκεκριμένο τύπο από έγγραφο με GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Προηγμένες περιπτώσεις διαγραφής εγγράφων eSignatures: [Πώς να διαγράψετε διαφορετικούς τύπους ηλεκτρονικών υπογραφών από έγγραφο σε C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Διαγράφει τις υπογραφές της λίστας ορισμένων τύπων[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) από το έγγραφο. Μόνο υπογραφές που προστέθηκαν με τη μέθοδο Sign και επισημάνθηκαν ως υπογραφές[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) θα αφαιρεθεί. Υποστηρίζονται οι ακόλουθοι τύποι υπογραφών: Κείμενο, Εικόνα, Ψηφιακός, Γραμμωτός κώδικας, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureTypes | List`1 | Η λίστα των τύπων υπογραφών που πρέπει να αφαιρεθούν από το έγγραφο. |

### Επιστρεφόμενη Αξία

Επιστρέφει το DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) με λίστα επιτυχώς διαγραμμένων υπογραφών και αποτυχημένων υπογραφών.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο διαγραφής ηλεκτρονικής υπογραφής από έγγραφο σε C#: [Πώς να διαγράψετε eSignatures με συγκεκριμένο τύπο από έγγραφο με GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Προηγμένες περιπτώσεις διαγραφής εγγράφων eSignatures: [Πώς να διαγράψετε διαφορετικούς τύπους ηλεκτρονικών υπογραφών από έγγραφο σε C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Διαγράφει την υπογραφή με το αναγνωριστικό της συγκεκριμένης υπογραφής από το έγγραφο.

```csharp
public bool Delete(string signatureId)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureId | String | Το αναγνωριστικό της υπογραφής που πρέπει να αφαιρεθεί από το έγγραφο. |

### Επιστρεφόμενη Αξία

Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο διαγραφής ηλεκτρονικής υπογραφής από έγγραφο σε C#: [Τρόπος διαγραφής eSignature από έγγραφο με GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Προηγμένες περιπτώσεις διαγραφής εγγράφων eSignatures: [Πώς να διαγράψετε διαφορετικούς τύπους ηλεκτρονικών υπογραφών από έγγραφο σε C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Διαγράφει τη λίστα υπογραφών που έχει περάσει[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) από το έγγραφο.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureIds | List`1 | Λίστα με τα αναγνωριστικά των υπογραφών που πρέπει να αφαιρεθούν από το έγγραφο. |

### Επιστρεφόμενη Αξία

Επιστρέφει το DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) με λίστα επιτυχώς διαγραμμένων υπογραφών και αποτυχημένων υπογραφών.

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τον τρόπο διαγραφής ηλεκτρονικής υπογραφής από έγγραφο σε C#: [Τρόπος διαγραφής eSignature από έγγραφο με GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Προηγμένες περιπτώσεις διαγραφής εγγράφων eSignatures: [Πώς να διαγράψετε διαφορετικούς τύπους ηλεκτρονικών υπογραφών από έγγραφο σε C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Δείτε επίσης

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* χώρος ονομάτων [GroupDocs.Signature](../../signature)
* συνέλευση [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
