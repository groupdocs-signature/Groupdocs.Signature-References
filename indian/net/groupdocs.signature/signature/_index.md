---
title: Signature
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: मुख्य वर्ग क प्रतनधत्व करत है ज दस्तवेज़ पर हस्तक्षर करने क प्रक्रय क नयंत्रत करत है
type: docs
weight: 1880
url: /hi/net/groupdocs.signature/signature/
---
## Signature class

मुख्य वर्ग का प्रतिनिधित्व करता है जो दस्तावेज़ पर हस्ताक्षर करने की प्रक्रिया को नियंत्रित करता है।

```csharp
public class Signature : IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Signature](signature#constructor)(Stream) | का नया उदाहरण शुरू करता है[`Signature`](../signature) स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ के साथ वर्ग। |
| [Signature](signature#constructor_4)(string) | का नया उदाहरण शुरू करता है[`Signature`](../signature) फ़ाइल पथ. द्वारा प्रदान किए गए दस्तावेज़ के साथ वर्ग उदाहरण |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | का नया उदाहरण शुरू करता है[`Signature`](../signature) क्लास स्ट्रीम और लोड विकल्पों द्वारा प्रदान किए गए दस्तावेज़ के साथLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | का नया उदाहरण शुरू करता है[`Signature`](../signature)स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ के साथ क्लास इंस्टेंस और[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | का नया उदाहरण शुरू करता है[`Signature`](../signature) फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ वर्ग उदाहरण औरLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | का नया उदाहरण शुरू करता है[`Signature`](../signature) फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ वर्ग उदाहरण और[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | का नया उदाहरण शुरू करता है[`Signature`](../signature) स्ट्रीम, लोड विकल्पों द्वारा प्रदान किए गए दस्तावेज़ के साथ वर्ग उदाहरणLoadOptions और सेटिंग्स[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | का नया उदाहरण शुरू करता है[`Signature`](../signature) फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ वर्ग उदाहरण,LoadOptions और[`SignatureSettings`](../signaturesettings) . |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | पारित हस्ताक्षर हटाता है[`BaseSignature`](../../groupdocs.signature.domain/basesignature) दस्तावेज़ से. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | उत्तीर्ण हस्ताक्षरों की सूची हटाता है[`BaseSignature`](../../groupdocs.signature.domain/basesignature) दस्तावेज़ से. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | विशिष्ट प्रकार की सूची के हस्ताक्षर हटाता है[`SignatureType`](../../groupdocs.signature.domain/signaturetype) दस्तावेज़ से. केवल हस्ताक्षर जो साइन विधि द्वारा जोड़े गए थे और हस्ताक्षर के रूप में चिह्नित किए गए थे[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) हटा दिया जाएगा। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: पाठ, छवि, डिजिटल, बारकोड, क्यूआर-कोड |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | उत्तीर्ण हस्ताक्षरों की सूची हटाता है[`BaseSignature`](../../groupdocs.signature.domain/basesignature) दस्तावेज़ से. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | निश्चित प्रकार के हस्ताक्षर हटाता है[`SignatureType`](../../groupdocs.signature.domain/signaturetype) दस्तावेज़ से. केवल हस्ताक्षर जो साइन विधि द्वारा जोड़े गए थे और हस्ताक्षर के रूप में चिह्नित किए गए थे[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) हटा दिया जाएगा। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: पाठ, छवि, डिजिटल, बारकोड, क्यूआर-कोड |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | दस्तावेज़ से अपने विशिष्ट हस्ताक्षर आईडी द्वारा हस्ताक्षर हटाता है। |
| [Dispose](../../groupdocs.signature/signature/dispose)() | आंतरिक संसाधनों को साफ करने के लिए IDisposable इंटरफ़ेस लागू करें |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | दस्तावेज़ पृष्ठों का पूर्वावलोकन बनाता है. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | दस्तावेज़ पृष्ठों के बारे में जानकारी प्राप्त करता है: उनके आकार, अधिकतम पृष्ठ ऊंचाई, अधिकतम ऊंचाई वाले पृष्ठ की चौड़ाई। |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | द्वारा दस्तावेज़ में हस्ताक्षर की खोज करता है[`SearchOptions`](../../groupdocs.signature.options/searchoptions) सूची. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | द्वारा दस्तावेज़ में निर्दिष्ट हस्ताक्षर प्रकारों की खोज करता है[`SignatureType`](../../groupdocs.signature.domain/signaturetype) मान. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | द्वारा दस्तावेज़ में हस्ताक्षर की खोज करता है[`SearchOptions`](../../groupdocs.signature.options/searchoptions) विकल्प. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | द्वारा दस्तावेज़ में सटीक प्रकार के हस्ताक्षरों की खोज करता है[`SignatureType`](../../groupdocs.signature.domain/signaturetype) मान. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../groupdocs.signature.options/signoptions) और परिणाम को स्ट्रीम में सहेजता है। |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../groupdocs.signature.options/signoptions) और परिणाम को स्ट्रीम में सहेजता है। |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../groupdocs.signature.options/signoptions) और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../groupdocs.signature.options/signoptions) और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../groupdocs.signature.options/signoptions)और परिणाम को पूर्वनिर्धारित स्ट्रीम में सहेजता है[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../groupdocs.signature.options/signoptions)और परिणाम को पूर्वनिर्धारित स्ट्रीम में सहेजता है[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../groupdocs.signature.options/signoptions) और परिणाम को पूर्वनिर्धारित के साथ निर्दिष्ट फ़ाइल पथ में सहेजता है[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../groupdocs.signature.options/signoptions) और परिणाम को पूर्वनिर्धारित के साथ निर्दिष्ट फ़ाइल पथ में सहेजता है[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | पास हुए हस्ताक्षर को अपडेट करता है[`BaseSignature`](../../groupdocs.signature.domain/basesignature) दस्तावेज़ में. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | पास हुए हस्ताक्षरों को अपडेट करता है[`BaseSignature`](../../groupdocs.signature.domain/basesignature) दस्तावेज़ में. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | VerifyOptions डेटा की सूची के साथ दस्तावेज़ हस्ताक्षर सत्यापित करता है। |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | दिए गए VerifyOptions डेटा के साथ दस्तावेज़ हस्ताक्षर सत्यापित करता है। |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | दिए गए साइनऑप्शन के आधार पर सिग्नेचर प्रीव्यू जेनरेट करता है।[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## आयोजन

| नाम | विवरण |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | तब होता है जब हस्ताक्षर खोज प्रक्रिया पूरी हो जाती है। |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | तब होता है जब हस्ताक्षर खोज प्रक्रिया की प्रगति बदल जाती है। |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | तब होता है जब हस्ताक्षर खोज प्रक्रिया शुरू होती है। |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | तब होता है जब दस्तावेज़ पर हस्ताक्षर करने की प्रक्रिया पूरी हो जाती है। |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | तब होता है जब दस्तावेज़ पर हस्ताक्षर करने की प्रक्रिया की प्रगति बदल जाती है। |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | तब होता है जब दस्तावेज़ पर हस्ताक्षर करने की प्रक्रिया शुरू होती है। |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | तब होता है जब हस्ताक्षर सत्यापन प्रक्रिया पूरी हो जाती है। |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | तब होता है जब हस्ताक्षर सत्यापन प्रक्रिया की प्रगति बदल जाती है। |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | तब होता है जब हस्ताक्षर सत्यापन प्रक्रिया शुरू होती है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs.हस्ताक्षर सुविधाओं के बारे में अधिक: [GroupDocs.Signature डेवलपर गाइड](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### यह सभी देखें

* नाम स्थान [GroupDocs.Signature](../../groupdocs.signature)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
