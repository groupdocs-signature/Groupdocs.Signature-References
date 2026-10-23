---
title: "load_digital_signatures मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "सभी सिस्टम X509 प्रमाणपत्र स्टोर्स से डिजिटल हस्ताक्षर लोड करें।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

सभी सिस्टम X509 प्रमाणपत्र स्टोर्स से डिजिटल हस्ताक्षर लोड करें।

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

प्रमाणपत्र संग्रह से डिजिटल हस्ताक्षर लोड करें।

```python
def load_digital_signatures(cls, store_name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | प्रमाणपत्रों को रखने वाले डिजिटल स्टोरेज का नाम. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

प्रमाणपत्र संग्रह से डिजिटल हस्ताक्षर लोड करें।

```python
def load_digital_signatures(cls, store_name):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| store_name | `str` | प्रमाणपत्रों को रखने वाले डिजिटल स्टोरेज का कस्टम नाम. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

विशिष्ट स्थान पर रखे डिजिटल प्रमाणपत्र संग्रह से डिजिटल हस्ताक्षर लोड करें।

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | प्रमाणपत्रों को रखने वाले डिजिटल स्टोरेज का नाम. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | डिजिटल प्रमाणपत्र स्टोरेज का स्थान. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

विशिष्ट स्थान पर रखे डिजिटल प्रमाणपत्र संग्रह से डिजिटल हस्ताक्षर लोड करता है।

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| store_name | `str` | प्रमाणपत्रों को रखने वाले डिजिटल स्टोरेज का कस्टम नाम. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | डिजिटल प्रमाणपत्र स्टोरेज का स्थान. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### संबंधित देखें
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
