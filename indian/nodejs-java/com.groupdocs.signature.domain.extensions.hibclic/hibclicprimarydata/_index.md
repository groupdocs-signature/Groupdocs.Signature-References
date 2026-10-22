---
title: "HIBCLICPrimaryData"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "HIBC हेल्थकेयर इंडस्ट्री बारकोड काउंसिल LIC लाइसेंस्ड आइडेंटिफिकेशन कोड प्राथमिक डेटा संग्रहीत करने के लिए क्लास।"
type: docs
weight: 12
url: /hi/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

HIBC (हेल्थकेयर इंडस्ट्री बार कोड काउंसिल) LIC (लाइसेंस्ड आइडेंटिफिकेशन कोड) प्राथमिक डेटा संग्रहीत करने के लिए क्लास।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | डिफ़ॉल्ट ctor() |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | लेबलर पहचान कोड की तिथि की पहचान करता है। |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | लेबलर पहचान कोड की तिथि की पहचान करता है। |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | उत्पाद या कैटलॉग नंबर की पहचान करता है। |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | उत्पाद या कैटलॉग नंबर की पहचान करता है। |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | माप इकाई ID की पहचान करता है। |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | माप इकाई ID की पहचान करता है। |
| [deepClone()](#deepClone--) | इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है। |
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


डिफ़ॉल्ट ctor()

### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


लेबलर पहचान कोड की तिथि की पहचान करता है। लेबलर पहचान कोड 4 अक्षरों का अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए, जिसमें पहला अक्षर हमेशा अक्षरात्मक होना चाहिए।

**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


लेबलर पहचान कोड की तिथि की पहचान करता है। लेबलर पहचान कोड 4 अक्षरों का अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए, जिसमें पहला अक्षर हमेशा अक्षरात्मक होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


उत्पाद या कैटलॉग नंबर की पहचान करता है। उत्पाद या कैटलॉग नंबर 18 अक्षरों तक की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


उत्पाद या कैटलॉग नंबर की पहचान करता है। उत्पाद या कैटलॉग नंबर 18 अक्षरों तक की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


माप इकाई ID की पहचान करता है। माप इकाई ID 0 से 9 के बीच पूर्णांक मान होना चाहिए।

**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


माप इकाई ID की पहचान करता है। माप इकाई ID 0 से 9 के बीच पूर्णांक मान होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है।

**Returns:**
java.lang.Object
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
