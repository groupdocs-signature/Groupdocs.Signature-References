---
title: EPC
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: यूरपय भुगतन परषद त्वरत प्रतक्रय कड क प्रतनधत्व करत है
type: docs
weight: 230
url: /hi/net/groupdocs.signature.domain.extensions/epc/
---
## EPC class

यूरोपीय भुगतान परिषद त्वरित प्रतिक्रिया कोड का प्रतिनिधित्व करता है।

```csharp
public sealed class EPC
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [EPC](epc)() | नई ईपीसी वस्तु का दृष्टांत देता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Amount](../../groupdocs.signature.domain.extensions/epc/amount) { get; set; } | राशि प्राप्त या सेट करता है। |
| [BIC](../../groupdocs.signature.domain.extensions/epc/bic) { get; set; } | लाभार्थी के बीआईसी को 11 वर्णों तक की लंबाई के साथ प्राप्त या सेट करता है। |
| [Charset](../../groupdocs.signature.domain.extensions/epc/charset) { get; } | ईपीसी / एसईपीए क्यूआर-कोड चार सेट कार्यान्वयन। डिफ़ॉल्ट रूप से यह मान 1 पर सेट होता है |
| [Code](../../groupdocs.signature.domain.extensions/epc/code) { get; set; } | अधिकतम 4 वर्णों का व्यवसाय कोड प्राप्त या सेट करता है. |
| [IBAN](../../groupdocs.signature.domain.extensions/epc/iban) { get; set; } | लाभार्थी का खाता (IBAN) प्राप्त या सेट करता है। IBAN में अधिकतम 34 अक्षरांकीय वर्ण होते हैं. |
| [Identification](../../groupdocs.signature.domain.extensions/epc/identification) { get; } | ईपीसी / एसईपीए क्यूआर-कोड पहचान। डिफ़ॉल्ट रूप से यह मान SCT पर सेट है |
| [Information](../../groupdocs.signature.domain.extensions/epc/information) { get; set; } | संकेत जानकारी प्राप्त या सेट करता है। अधिकतम 70 वर्ण. |
| [Name](../../groupdocs.signature.domain.extensions/epc/name) { get; set; } | लाभार्थी का नाम प्राप्त या सेट करता है। अधिकतम लंबाई 70 वर्ण है. |
| [Reference](../../groupdocs.signature.domain.extensions/epc/reference) { get; set; } | भुगतान संदर्भ प्राप्त या सेट करता है (अधिकतम 35 वर्ण)। यह फ़ील्ड और प्रेषण सूचना फ़ील्ड परस्पर अनन्य हैं। |
| [Remittance](../../groupdocs.signature.domain.extensions/epc/remittance) { get; set; } | प्रेषण सूचना प्राप्त या सेट करता है (अधिकतम 140 वर्ण)। यह फ़ील्ड और भुगतान संदर्भ फ़ील्ड परस्पर अनन्य हैं. |
| [Version](../../groupdocs.signature.domain.extensions/epc/version) { get; } | ईपीसी / एसईपीए क्यूआर-कोड संस्करण कार्यान्वयन। डिफ़ॉल्ट रूप से यह मान 002. पर सेट होता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Equals](../../groupdocs.signature.domain.extensions/epc/equals)(object) | ईपीसी गुणों की तुलना करने के लिए बराबर विधि को ओवरराइट करता है |
| override [GetHashCode](../../groupdocs.signature.domain.extensions/epc/gethashcode)() | GetHashCode method को ओवरराइड करता है |

### यह सभी देखें

* नाम स्थान [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
