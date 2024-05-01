---
title: BarcodeTypes
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Barcode Types container.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.signature.domain.barcodes/barcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeTypes
```

Barcode Types container.
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeTypes()](#BarcodeTypes--) |  |
## Fields

| Field | Description |
| --- | --- |
| [AustralianPosteParcel](#AustralianPosteParcel) | Australian Post eParcel Barcode Type object. |
| [AustralianPost](#AustralianPost) | Australian Post Barcode Type object. |
| [Codabar](#Codabar) | Codabar Barcode Type object. |
| [CodablockF](#CodablockF) | CodablockF Barcode Type object. |
| [Code11](#Code11) | Code11 Barcode Type object. |
| [Code128](#Code128) | Code128 Barcode Type object. |
| [Code16K](#Code16K) | Code16K Barcode Type object. |
| [Code32](#Code32) | Code32 Barcode Type object. |
| [Code39Extended](#Code39Extended) | Code39Extended Barcode Type object. |
| [Code39Standard](#Code39Standard) | Code39Standard Barcode Type object. |
| [Code93Extended](#Code93Extended) | Code93Extended Barcode Type object. |
| [Code93Standard](#Code93Standard) | Code93Standard Barcode Type object. |
| [DatabarExpanded](#DatabarExpanded) | DatabarExpanded Barcode Type object. |
| [DatabarExpandedStacked](#DatabarExpandedStacked) | DatabarExpandedStacked Barcode Type object. |
| [DatabarLimited](#DatabarLimited) | DatabarLimited Barcode Type object. |
| [DatabarOmniDirectional](#DatabarOmniDirectional) | DatabarOmniDirectional Barcode Type object. |
| [DatabarStacked](#DatabarStacked) | DatabarStacked Barcode Type object. |
| [DatabarStackedOmniDirectional](#DatabarStackedOmniDirectional) | DatabarStackedOmniDirectional Barcode Type object. |
| [DatabarTruncated](#DatabarTruncated) | DatabarTruncated Barcode Type object. |
| [DataLogic2of5](#DataLogic2of5) | DataLogic2of5 Barcode Type object. |
| [DeutschePostIdentcode](#DeutschePostIdentcode) | DeutschePostIdentcode Barcode Type object. |
| [DeutschePostLeitcode](#DeutschePostLeitcode) | DeutschePostLeitcode Barcode Type object. |
| [DotCode](#DotCode) | DotCode Barcode Type object. |
| [DutchKIX](#DutchKIX) | DutchKIX Barcode Type object. |
| [EAN8](#EAN8) | EAN8 Barcode Type object. |
| [EAN13](#EAN13) | EAN13 Barcode Type object. |
| [EAN14](#EAN14) | EAN14 Barcode Type object. |
| [GS1CodablockF](#GS1CodablockF) | GS1CodablockF Barcode Type object. |
| [GS1Code128](#GS1Code128) | GS1 Code128 Barcode Type object. |
| [GS1CompositeBar](#GS1CompositeBar) | GS1 Composite Barcode Type object. |
| [IATA2of5](#IATA2of5) | IATA2of5 Barcode Type object. |
| [Interleaved2of5](#Interleaved2of5) | Interleaved2of5 Barcode Type object. |
| [ISBN](#ISBN) | ISBN Barcode Type object. |
| [ISMN](#ISMN) | ISMN Barcode Type object. |
| [ISSN](#ISSN) | ISSN Barcode Type object. |
| [ItalianPost25](#ItalianPost25) | ItalianPost25 Barcode Type object. |
| [ITF14](#ITF14) | ITF14 Barcode Type object. |
| [ITF6](#ITF6) | ITF6 Barcode Type object. |
| [MacroPdf417](#MacroPdf417) | MacroPdf417 Barcode Type object. |
| [Mailmark](#Mailmark) | Royal Mail 2D Mailmark Barcode Type object. |
| [Matrix2of5](#Matrix2of5) | Matrix2of5 Barcode Type object. |
| [MaxiCode](#MaxiCode) | MaxiCode Barcode Type object. |
| [MicroPdf417](#MicroPdf417) | MicroPdf417 Barcode Type object. |
| [MSI](#MSI) | MSI Barcode Type object. |
| [OneCode](#OneCode) | OneCode Barcode Type object. |
| [OPC](#OPC) | OPC Barcode Type object. |
| [PatchCode](#PatchCode) | Patch Code Barcode Type object. |
| [Pdf417](#Pdf417) | Pdf417 Barcode Type object. |
| [Pharmacode](#Pharmacode) | Pharma code Barcode Type object. |
| [Planet](#Planet) | Planet Barcode Type object. |
| [Postnet](#Postnet) | Postnet Barcode Type object. |
| [PZN](#PZN) | PZN Barcode Type object. |
| [RM4SCC](#RM4SCC) | RM4SCC Barcode Type object. |
| [SCC14](#SCC14) | SCC14 Barcode Type object. |
| [SingaporePost](#SingaporePost) | SingaporePost Barcode Type object. |
| [SSCC18](#SSCC18) | SSCC18 Barcode Type object. |
| [Standard2of5](#Standard2of5) | Standard2of5 Barcode Type object. |
| [SwissPostParcel](#SwissPostParcel) | SwissPostParcel Barcode Type object. |
| [UPCA](#UPCA) | UPCA Barcode Type object. |
| [UpcaGs1Code128Coupon](#UpcaGs1Code128Coupon) | UpcaGs1Code128Coupon Barcode Type object. |
| [UpcaGs1DatabarCoupon](#UpcaGs1DatabarCoupon) | UpcaGs1DatabarCoupon Barcode Type object. |
| [UPCE](#UPCE) | UPCE Barcode Type object. |
| [VIN](#VIN) | VIN Barcode Type object. |
| [HIBCCode39LIC](#HIBCCode39LIC) | HIBC LIC 39 Barcode Type object. |
| [HIBCCode128LIC](#HIBCCode128LIC) | HIBC LIC 128 Barcode Type object. |
| [HIBCCode39PAS](#HIBCCode39PAS) | HIBC PAS 39 Barcode Type object. |
| [HIBCCode128PAS](#HIBCCode128PAS) | HIBC PAS 128 Barcode Type object. |
| [GS1DotCode](#GS1DotCode) | GS1 DotCode Barcode Type object. |
## Methods

| Method | Description |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | All barcode types. |
| [parse(String parsingType)](#parse-java.lang.String-) | Returns Barcode type with pasringType name. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | Returns Barcode type with pasringType name. |
| [getDecodeTypes()](#getDecodeTypes--) | Internal list of Decode Types for extraction |
| [find(String encodeTypeName)](#find-java.lang.String-) |  |
| [isBarcodeType(String encodeTypeName)](#isBarcodeType-java.lang.String-) |  |
### BarcodeTypes() {#BarcodeTypes--}
```
public BarcodeTypes()
```


### AustralianPosteParcel {#AustralianPosteParcel}
```
public static final BarcodeType AustralianPosteParcel
```


Australian Post eParcel Barcode Type object.

### AustralianPost {#AustralianPost}
```
public static final BarcodeType AustralianPost
```


Australian Post Barcode Type object.

### Codabar {#Codabar}
```
public static final BarcodeType Codabar
```


Codabar Barcode Type object.

### CodablockF {#CodablockF}
```
public static final BarcodeType CodablockF
```


CodablockF Barcode Type object.

### Code11 {#Code11}
```
public static final BarcodeType Code11
```


Code11 Barcode Type object.

### Code128 {#Code128}
```
public static final BarcodeType Code128
```


Code128 Barcode Type object.

### Code16K {#Code16K}
```
public static final BarcodeType Code16K
```


Code16K Barcode Type object.

### Code32 {#Code32}
```
public static final BarcodeType Code32
```


Code32 Barcode Type object.

### Code39Extended {#Code39Extended}
```
public static final BarcodeType Code39Extended
```


Code39Extended Barcode Type object.

### Code39Standard {#Code39Standard}
```
public static final BarcodeType Code39Standard
```


Code39Standard Barcode Type object.

### Code93Extended {#Code93Extended}
```
public static final BarcodeType Code93Extended
```


Code93Extended Barcode Type object.

### Code93Standard {#Code93Standard}
```
public static final BarcodeType Code93Standard
```


Code93Standard Barcode Type object.

### DatabarExpanded {#DatabarExpanded}
```
public static final BarcodeType DatabarExpanded
```


DatabarExpanded Barcode Type object.

### DatabarExpandedStacked {#DatabarExpandedStacked}
```
public static final BarcodeType DatabarExpandedStacked
```


DatabarExpandedStacked Barcode Type object.

### DatabarLimited {#DatabarLimited}
```
public static final BarcodeType DatabarLimited
```


DatabarLimited Barcode Type object.

### DatabarOmniDirectional {#DatabarOmniDirectional}
```
public static final BarcodeType DatabarOmniDirectional
```


DatabarOmniDirectional Barcode Type object.

### DatabarStacked {#DatabarStacked}
```
public static final BarcodeType DatabarStacked
```


DatabarStacked Barcode Type object.

### DatabarStackedOmniDirectional {#DatabarStackedOmniDirectional}
```
public static final BarcodeType DatabarStackedOmniDirectional
```


DatabarStackedOmniDirectional Barcode Type object.

### DatabarTruncated {#DatabarTruncated}
```
public static final BarcodeType DatabarTruncated
```


DatabarTruncated Barcode Type object.

### DataLogic2of5 {#DataLogic2of5}
```
public static final BarcodeType DataLogic2of5
```


DataLogic2of5 Barcode Type object.

### DeutschePostIdentcode {#DeutschePostIdentcode}
```
public static final BarcodeType DeutschePostIdentcode
```


DeutschePostIdentcode Barcode Type object.

### DeutschePostLeitcode {#DeutschePostLeitcode}
```
public static final BarcodeType DeutschePostLeitcode
```


DeutschePostLeitcode Barcode Type object.

### DotCode {#DotCode}
```
public static final BarcodeType DotCode
```


DotCode Barcode Type object.

### DutchKIX {#DutchKIX}
```
public static final BarcodeType DutchKIX
```


DutchKIX Barcode Type object.

### EAN8 {#EAN8}
```
public static final BarcodeType EAN8
```


EAN8 Barcode Type object.

### EAN13 {#EAN13}
```
public static final BarcodeType EAN13
```


EAN13 Barcode Type object.

### EAN14 {#EAN14}
```
public static final BarcodeType EAN14
```


EAN14 Barcode Type object.

### GS1CodablockF {#GS1CodablockF}
```
public static final BarcodeType GS1CodablockF
```


GS1CodablockF Barcode Type object.

### GS1Code128 {#GS1Code128}
```
public static final BarcodeType GS1Code128
```


GS1 Code128 Barcode Type object.

### GS1CompositeBar {#GS1CompositeBar}
```
public static final BarcodeType GS1CompositeBar
```


GS1 Composite Barcode Type object.

### IATA2of5 {#IATA2of5}
```
public static final BarcodeType IATA2of5
```


IATA2of5 Barcode Type object.

### Interleaved2of5 {#Interleaved2of5}
```
public static final BarcodeType Interleaved2of5
```


Interleaved2of5 Barcode Type object.

### ISBN {#ISBN}
```
public static final BarcodeType ISBN
```


ISBN Barcode Type object.

### ISMN {#ISMN}
```
public static final BarcodeType ISMN
```


ISMN Barcode Type object.

### ISSN {#ISSN}
```
public static final BarcodeType ISSN
```


ISSN Barcode Type object.

### ItalianPost25 {#ItalianPost25}
```
public static final BarcodeType ItalianPost25
```


ItalianPost25 Barcode Type object.

### ITF14 {#ITF14}
```
public static final BarcodeType ITF14
```


ITF14 Barcode Type object.

### ITF6 {#ITF6}
```
public static final BarcodeType ITF6
```


ITF6 Barcode Type object.

### MacroPdf417 {#MacroPdf417}
```
public static final BarcodeType MacroPdf417
```


MacroPdf417 Barcode Type object.

### Mailmark {#Mailmark}
```
public static final BarcodeType Mailmark
```


Royal Mail 2D Mailmark Barcode Type object.

### Matrix2of5 {#Matrix2of5}
```
public static final BarcodeType Matrix2of5
```


Matrix2of5 Barcode Type object.

### MaxiCode {#MaxiCode}
```
public static final BarcodeType MaxiCode
```


MaxiCode Barcode Type object.

### MicroPdf417 {#MicroPdf417}
```
public static final BarcodeType MicroPdf417
```


MicroPdf417 Barcode Type object.

### MSI {#MSI}
```
public static final BarcodeType MSI
```


MSI Barcode Type object.

### OneCode {#OneCode}
```
public static final BarcodeType OneCode
```


OneCode Barcode Type object.

### OPC {#OPC}
```
public static final BarcodeType OPC
```


OPC Barcode Type object.

### PatchCode {#PatchCode}
```
public static final BarcodeType PatchCode
```


Patch Code Barcode Type object.

### Pdf417 {#Pdf417}
```
public static final BarcodeType Pdf417
```


Pdf417 Barcode Type object.

### Pharmacode {#Pharmacode}
```
public static final BarcodeType Pharmacode
```


Pharma code Barcode Type object.

### Planet {#Planet}
```
public static final BarcodeType Planet
```


Planet Barcode Type object.

### Postnet {#Postnet}
```
public static final BarcodeType Postnet
```


Postnet Barcode Type object.

### PZN {#PZN}
```
public static final BarcodeType PZN
```


PZN Barcode Type object.

### RM4SCC {#RM4SCC}
```
public static final BarcodeType RM4SCC
```


RM4SCC Barcode Type object.

### SCC14 {#SCC14}
```
public static final BarcodeType SCC14
```


SCC14 Barcode Type object.

### SingaporePost {#SingaporePost}
```
public static final BarcodeType SingaporePost
```


SingaporePost Barcode Type object.

### SSCC18 {#SSCC18}
```
public static final BarcodeType SSCC18
```


SSCC18 Barcode Type object.

### Standard2of5 {#Standard2of5}
```
public static final BarcodeType Standard2of5
```


Standard2of5 Barcode Type object.

### SwissPostParcel {#SwissPostParcel}
```
public static final BarcodeType SwissPostParcel
```


SwissPostParcel Barcode Type object.

### UPCA {#UPCA}
```
public static final BarcodeType UPCA
```


UPCA Barcode Type object.

### UpcaGs1Code128Coupon {#UpcaGs1Code128Coupon}
```
public static final BarcodeType UpcaGs1Code128Coupon
```


UpcaGs1Code128Coupon Barcode Type object.

### UpcaGs1DatabarCoupon {#UpcaGs1DatabarCoupon}
```
public static final BarcodeType UpcaGs1DatabarCoupon
```


UpcaGs1DatabarCoupon Barcode Type object.

### UPCE {#UPCE}
```
public static final BarcodeType UPCE
```


UPCE Barcode Type object.

### VIN {#VIN}
```
public static final BarcodeType VIN
```


VIN Barcode Type object.

### HIBCCode39LIC {#HIBCCode39LIC}
```
public static final BarcodeType HIBCCode39LIC
```


HIBC LIC 39 Barcode Type object.

### HIBCCode128LIC {#HIBCCode128LIC}
```
public static final BarcodeType HIBCCode128LIC
```


HIBC LIC 128 Barcode Type object.

### HIBCCode39PAS {#HIBCCode39PAS}
```
public static final BarcodeType HIBCCode39PAS
```


HIBC PAS 39 Barcode Type object.

### HIBCCode128PAS {#HIBCCode128PAS}
```
public static final BarcodeType HIBCCode128PAS
```


HIBC PAS 128 Barcode Type object.

### GS1DotCode {#GS1DotCode}
```
public static final BarcodeType GS1DotCode
```


GS1 DotCode Barcode Type object.

### getAllTypes() {#getAllTypes--}
```
public static BarcodeType[] getAllTypes()
```


All barcode types.

**Returns:**
com.groupdocs.signature.domain.barcodes.BarcodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static BarcodeType parse(String parsingType)
```


Returns Barcode type with pasringType name. If name of Barcode is unknown - Exception will be thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Source string of barcode type name. |

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) - BarcodeType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static BarcodeType tryParse(String parsingType)
```


Returns Barcode type with pasringType name. If name of Barcode is unknown - no Exception will be thrown but method will return null value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Source string of barcode type name. |

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) - BarcodeType instance.
### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Internal list of Decode Types for extraction

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### find(String encodeTypeName) {#find-java.lang.String-}
```
public static BarcodeType find(String encodeTypeName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encodeTypeName | java.lang.String |  |

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### isBarcodeType(String encodeTypeName) {#isBarcodeType-java.lang.String-}
```
public static boolean isBarcodeType(String encodeTypeName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encodeTypeName | java.lang.String |  |

**Returns:**
boolean
