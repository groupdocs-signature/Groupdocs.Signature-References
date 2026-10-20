---
title: "Επαλήθευση"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Επαληθεύει τις υπογραφές του εγγράφου με τα δεδομένα VerifyOptions που δόθηκαν."
type: docs
weight: 180
url: /el/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Επαληθεύει τις υπογραφές του εγγράφου με τα δεδομένα VerifyOptions που δόθηκαν.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Οι επιλογές επαλήθευσης της υπογραφής. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Η ιδιότητα VerificationResult.IsValid επιστρέφει true εάν η διαδικασία επαλήθευσης ήταν επιτυχής.

### Παρατηρήσεις

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Δείτε επίσης

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Επαληθεύει τις υπογραφές του εγγράφου χρησιμοποιώντας τις παρεχόμενες επιλογές επαλήθευσης και φιλτράρει τα αποτελέσματα βάσει της καθορισμένης συνθήκης. Αυτή η μέθοδος πρώτα αναζητά υπογραφές που ταιριάζουν με τις επιλογές επαλήθευσης, τις φιλτράρει με τη συνθήκη και στη συνέχεια επαληθεύει μόνο τις φιλτραρισμένες υπογραφές.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Οι επιλογές επαλήθευσης της υπογραφής. |
| predicate | Func`2 | Η συνθήκη φίλτρου για τον καθορισμό ποιες υπογραφές πρέπει να επαληθευτούν. |

### Τιμή Επιστροφής

Επιστρέφει μια λίστα από αντικείμενα του [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) που ικανοποιούν την παρεχόμενη προδιαγραφή.

### Παρατηρήσεις

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Δείτε επίσης

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Επαληθεύει τις υπογραφές του εγγράφου με λίστα δεδομένων VerifyOptions.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| verifyOptionsList | List`1 | Η συλλογή επιλογών επαλήθευσης της υπογραφής. Στιγμιότυπο του VerifyOptionsCollection. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Η ιδιότητα VerificationResult.IsValid επιστρέφει true εάν η διαδικασία επαλήθευσης ήταν επιτυχής.

### Παρατηρήσεις

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Δείτε επίσης

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Επαληθεύει τις υπογραφές του εγγράφου χρησιμοποιώντας όλες τις διαθέσιμες επιλογές επαλήθευσης και φιλτράρει τα αποτελέσματα βάσει της καθορισμένης συνθήκης. Αυτή η μέθοδος πρώτα αναζητά υπογραφές που ταιριάζουν με τις επιλογές επαλήθευσης, τις φιλτράρει με τη συνθήκη και στη συνέχεια επαληθεύει μόνο τις φιλτραρισμένες υπογραφές.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| verifyOptionsList | List`1 | Η συλλογή επιλογών επαλήθευσης της υπογραφής. Στιγμιότυπο του VerifyOptionsCollection. |
| predicate | Func`2 | Η συνθήκη φίλτρου για τον καθορισμό ποιες υπογραφές πρέπει να επαληθευτούν. |

### Τιμή Επιστροφής

Επιστρέφει μια λίστα από αντικείμενα του [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) που ικανοποιούν την παρεχόμενη προδιαγραφή.

### Παρατηρήσεις

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Δείτε επίσης

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
