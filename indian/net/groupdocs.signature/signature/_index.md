---
title: "हस्ताक्षर"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "दस्तावेज़ हस्ताक्षर प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास दर्शाता है।"
type: docs
weight: 2170
url: /hi/net/groupdocs.signature/signature/
---
## Signature class

दस्तावेज़ हस्ताक्षर प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास दर्शाता है।

```csharp
public class Signature : IDisposable
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [Signature](signature#constructor)(Stream) | स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ के साथ [`Signature`](../signature) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [Signature](signature#constructor_4)(string) | फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ [`Signature`](../signature) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और लोड विकल्प LoadOptions के साथ [`Signature`](../signature) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और [`SignatureSettings`](../signaturesettings) के साथ [`Signature`](../signature) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [Signature](signature#constructor_5)(string, LoadOptions) | फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ और LoadOptions के साथ [`Signature`](../signature) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [Signature](signature#constructor_7)(string, SignatureSettings) | फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ और [`SignatureSettings`](../signaturesettings) के साथ [`Signature`](../signature) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़, लोड विकल्प LoadOptions और सेटिंग्स [`SignatureSettings`](../signaturesettings) के साथ [`Signature`](../signature) क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़, LoadOptions और [`SignatureSettings`](../signaturesettings) के साथ [`Signature`](../signature) क्लास का नया इंस्टेंस प्रारंभ करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | दस्तावेज़ से पास किया गया हस्ताक्षर [`BaseSignature`](../../groupdocs.signature.domain/basesignature) को हटाता है। |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | दस्तावेज़ से पास की गई हस्ताक्षरों की सूची [`BaseSignature`](../../groupdocs.signature.domain/basesignature) को हटाता है। |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | दस्तावेज़ से निर्दिष्ट प्रकारों की सूची [`SignatureType`](../../groupdocs.signature.domain/signaturetype) के हस्ताक्षरों को हटाता है। केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए थे और Signatures [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) के रूप में चिह्नित हैं, हटाए जाएंगे। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | दस्तावेज़ से पास की गई हस्ताक्षरों की सूची [`BaseSignature`](../../groupdocs.signature.domain/basesignature) को हटाता है। |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | दस्तावेज़ से निर्दिष्ट प्रकार [`SignatureType`](../../groupdocs.signature.domain/signaturetype) के हस्ताक्षरों को हटाता है। केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए थे और Signatures [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) के रूप में चिह्नित हैं, हटाए जाएंगे। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | दस्तावेज़ से उसके विशिष्ट हस्ताक्षर Id द्वारा हस्ताक्षर को हटाता है। |
| [Dispose](../../groupdocs.signature/signature/dispose)() | आंतरिक संसाधनों को साफ़ करने के लिए IDisposable इंटरफ़ेस को लागू करें |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | दस्तावेज़ पृष्ठों का पूर्वावलोकन उत्पन्न करता है। |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | दस्तावेज़ पृष्ठों के बारे में जानकारी प्राप्त करता है: उनका आकार, अधिकतम पृष्ठ ऊँचाई, अधिकतम ऊँचाई वाले पृष्ठ की चौड़ाई। |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | दस्तावेज़ में सभी उपलब्ध खोज विकल्पों का उपयोग करके हस्ताक्षरों की खोज करता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है। |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | दस्तावेज़ में हस्ताक्षरों को [`SearchOptions`](../../groupdocs.signature.options/searchoptions) सूची द्वारा खोजता है। |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | दस्तावेज़ में निर्दिष्ट हस्ताक्षर प्रकारों को [`SignatureType`](../../groupdocs.signature.domain/signaturetype) मान द्वारा खोजता है। |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | प्रदान किए गए खोज विकल्पों का उपयोग करके दस्तावेज़ में हस्ताक्षरों को खोजता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है। |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | दस्तावेज़ में हस्ताक्षरों को [`SearchOptions`](../../groupdocs.signature.options/searchoptions) विकल्पों द्वारा खोजता है। |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | दस्तावेज़ में हस्ताक्षरों के सटीक प्रकार को [`SignatureType`](../../groupdocs.signature.domain/signaturetype) मान द्वारा खोजता है। |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | [`SignOptions`](../../groupdocs.signature.options/signoptions) संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को एक स्ट्रीम में सहेजता है। |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | [`SignOptions`](../../groupdocs.signature.options/signoptions) के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को एक स्ट्रीम में सहेजता है। |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | [`SignOptions`](../../groupdocs.signature.options/signoptions) संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है। |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | [`SignOptions`](../../groupdocs.signature.options/signoptions) के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है। |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | [`SignOptions`](../../groupdocs.signature.options/signoptions) संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को पूर्वनिर्धारित [`SaveOptions`](../../groupdocs.signature.options/saveoptions) के साथ एक स्ट्रीम में सहेजता है। |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | [`SignOptions`](../../groupdocs.signature.options/signoptions) के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को पूर्वनिर्धारित [`SaveOptions`](../../groupdocs.signature.options/saveoptions) के साथ एक स्ट्रीम में सहेजता है। |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | [`SignOptions`](../../groupdocs.signature.options/signoptions) संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को पूर्वनिर्धारित [`SaveOptions`](../../groupdocs.signature.options/saveoptions) के साथ निर्दिष्ट फ़ाइल पथ पर सहेजता है। |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | [`SignOptions`](../../groupdocs.signature.options/signoptions) के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को पूर्वनिर्धारित [`SaveOptions`](../../groupdocs.signature.options/saveoptions) के साथ निर्दिष्ट फ़ाइल पथ पर सहेजता है। |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | दस्तावेज़ में पास किए गए हस्ताक्षर [`BaseSignature`](../../groupdocs.signature.domain/basesignature) को अपडेट करता है। |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | दस्तावेज़ में पास किए गए हस्ताक्षरों [`BaseSignature`](../../groupdocs.signature.domain/basesignature) को अपडेट करता है। |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | VerifyOptions डेटा की सूची के साथ दस्तावेज़ के हस्ताक्षरों को सत्यापित करता है। |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | दिए गए VerifyOptions डेटा के साथ दस्तावेज़ के हस्ताक्षरों को सत्यापित करता है। |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | सभी उपलब्ध सत्यापन विकल्पों का उपयोग करके दस्तावेज़ के हस्ताक्षरों को सत्यापित करता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है। यह विधि पहले सत्यापन विकल्पों से मेल खाने वाले हस्ताक्षरों को खोजती है, उन्हें प्रेडिकेट द्वारा फ़िल्टर करती है, और फिर केवल उन फ़िल्टर किए गए हस्ताक्षरों को सत्यापित करती है। |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | प्रदान किए गए सत्यापन विकल्पों का उपयोग करके दस्तावेज़ के हस्ताक्षरों को सत्यापित करता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है। यह विधि पहले सत्यापन विकल्पों से मेल खाने वाले हस्ताक्षरों को खोजती है, उन्हें प्रेडिकेट द्वारा फ़िल्टर करती है, और फिर केवल उन फ़िल्टर किए गए हस्ताक्षरों को सत्यापित करती है। |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | दिए गए SignOptions के आधार पर हस्ताक्षर पूर्वावलोकन उत्पन्न करता है। [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | हस्ताक्षर खोज प्रक्रिया पूर्ण होने पर होता है। |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | हस्ताक्षर खोज प्रक्रिया की प्रगति बदलने पर होता है। |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | हस्ताक्षर खोज प्रक्रिया शुरू होने पर होता है। |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | दस्तावेज़ हस्ताक्षर प्रक्रिया पूर्ण होने पर होता है। |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | दस्तावेज़ साइनिंग प्रक्रिया की प्रगति बदलने पर होता है। |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | दस्तावेज़ साइनिंग प्रक्रिया शुरू होने पर होता है। |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | हस्ताक्षर सत्यापन प्रक्रिया पूर्ण होने पर होता है। |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | हस्ताक्षर सत्यापन प्रक्रिया की प्रगति बदलने पर होता है। |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | हस्ताक्षर सत्यापन प्रक्रिया शुरू होने पर होता है। |

### टिप्पणियाँ

**Learn more**

GroupDocs.Signature सुविधाओं के बारे में अधिक: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### संबंधित देखें

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
