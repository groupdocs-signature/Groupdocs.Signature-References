---
title: "Υπογραφή"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Υπογράφει το έγγραφο με SignOptionsgroupdocs.signature.options/signoptions και αποθηκεύει το αποτέλεσμα σε μια ροή."
type: docs
weight: 160
url: /el/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Υπογράφει το έγγραφο με [`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή εξόδου του εγγράφου. |
| signOptions | SignOptions | Οι επιλογές της υπογραφής. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα των νεοδημιουργημένων υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Υπογράφει το έγγραφο με [`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή με προορισμένες [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή εξόδου του εγγράφου. |
| signOptions | SignOptions | Οι επιλογές της υπογραφής. |
| saveOptions | SaveOptions | Οι επιλογές αποθήκευσης. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα των νεοδημιουργημένων υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Υπογράφει το έγγραφο με συλλογή από [`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή εξόδου του εγγράφου. |
| signOptionsList | List`1 | Η λίστα των επιλογών υπογραφής. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα των νεοδημιουργημένων υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Υπογράφει το έγγραφο με συλλογή των [`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή με προεπιλεγμένες [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ροή εξόδου του εγγράφου. |
| signOptionsList | List`1 | Η λίστα των επιλογών υπογραφής. |
| saveOptions | SaveOptions | Οι επιλογές αποθήκευσης. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα των νεοδημιουργημένων υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Υπογράφει το έγγραφο με [`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή εξόδου του αρχείου. |
| signOptions | SignOptions | Οι επιλογές της υπογραφής. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα των νεοδημιουργημένων υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Υπογράφει το έγγραφο με [`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου με προεπιλεγμένες [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή εξόδου του αρχείου. |
| signOptions | SignOptions | Οι επιλογές της υπογραφής. |
| saveOptions | SaveOptions | Οι επιλογές αποθήκευσης. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα των νεοδημιουργημένων υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Υπογράφει το έγγραφο με συλλογή των [`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή εξόδου του αρχείου. |
| signOptionsList | List`1 | Η λίστα των επιλογών υπογραφής. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα των νεοδημιουργημένων υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Υπογράφει το έγγραφο με συλλογή των [`SignOptions`](../../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου με προεπιλεγμένες [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή εξόδου του αρχείου. |
| signOptionsList | List`1 | Η λίστα των επιλογών υπογραφής. |
| saveOptions | SaveOptions | Οι επιλογές αποθήκευσης. |

### Τιμή Επιστροφής

Επιστρέφει ένα στιγμιότυπο του [`SignResult`](../../../groupdocs.signature.domain/signresult) με λίστα των νεοδημιουργημένων υπογραφών.

### Παρατηρήσεις

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Δείτε επίσης

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
