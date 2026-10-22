---
title: "Tanda Tangan"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili kelas utama yang mengontrol proses penandatanganan dokumen."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Mewakili kelas utama yang mengontrol proses penandatanganan dokumen.

--------------------

**Learn more**

 *  More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide][]


[GroupDocs.Signature Developer Guide]: https://docs.groupdocs.com/display/signaturenet/Developer+Guide
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Signature(InputStream document)](#Signature-java.io.InputStream-) | Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui stream. |
| [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui stream dan opsi pemuatan LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)). |
| [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui stream dan [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui stream, opsi pemuatan LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) dan pengaturan [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(String filePath)](#Signature-java.lang.String-) | Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui jalur file. |
| [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui jalur file dan LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)). |
| [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui jalur file dan [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui jalur file, LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) dan [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Menandatangani dokumen dengan [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke dalam stream. |
| [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Menandatangani dokumen dengan [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke aliran dengan [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) yang telah ditentukan sebelumnya. |
| [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Menandatangani dokumen dengan koleksi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke aliran. |
| [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Menandatangani dokumen dengan koleksi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke aliran dengan [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) yang telah ditentukan sebelumnya. |
| [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Menandatangani dokumen dengan [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke jalur file yang ditentukan. |
| [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Menandatangani dokumen dengan [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) yang telah ditentukan sebelumnya. |
| [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Menandatangani dokumen dengan koleksi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke jalur file yang ditentukan. |
| [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Menandatangani dokumen dengan koleksi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) yang telah ditentukan sebelumnya. |
| [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Memverifikasi tanda tangan dokumen dengan data VerifyOptions yang diberikan. |
| [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Memverifikasi tanda tangan dokumen dengan daftar data VerifyOptions. |
| [getDocumentInfo()](#getDocumentInfo--) | Mendapatkan informasi tentang halaman dokumen: ukuran mereka, tinggi maksimum halaman, lebar halaman dengan tinggi maksimum. |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Menghasilkan pratinjau halaman dokumen. |
| [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Mencari tanda tangan dalam dokumen berdasarkan daftar [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
| [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Mencari tanda tangan dalam dokumen dengan opsi [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
| [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Mencari tipe tepat tanda tangan dalam dokumen berdasarkan nilai [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
| [search(int[] signatureTypes)](#search-int...-) | Mencari tipe tanda tangan yang ditentukan dalam dokumen berdasarkan nilai [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
| [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Memperbarui tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dalam dokumen. |
| [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Memperbarui tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dalam dokumen. |
| [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Memperbarui tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dalam dokumen. |
| [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Memperbarui tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dalam dokumen. |
| [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Menghapus tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dari dokumen. |
| [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Menghapus daftar tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dari dokumen. |
| [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Menghapus tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dari dokumen. |
| [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Menghapus daftar tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dari dokumen. |
| [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Menghapus tanda tangan dengan tipe tertentu [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dari dokumen. |
| [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Menghapus tanda tangan dengan daftar tipe tertentu [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dari dokumen. |
| [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Menghapus tanda tangan dengan tipe tertentu [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dari dokumen. |
| [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Menghapus tanda tangan dengan daftar tipe tertentu [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dari dokumen. |
| [delete(String signatureId)](#delete-java.lang.String-) | Menghapus tanda tangan berdasarkan Id tanda tangan spesifiknya dari dokumen. |
| [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Menghapus daftar tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dari dokumen. |
| [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Menghasilkan pratinjau Signature berdasarkan SignOptions yang diberikan. |
| [dispose()](#dispose--) | Implementasikan antarmuka IDisposable untuk membersihkan sumber daya internal |
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui stream.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Aliran konten dokumen. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui stream dan opsi pemuatan LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.InputStream | Aliran konten dokumen. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Opsi pemuatan dokumen. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui stream dan [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.InputStream | Aliran konten dokumen. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Pengaturan tanda tangan. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui stream, opsi pemuatan LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) dan pengaturan [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.InputStream | Aliran konten dokumen. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Opsi pemuatan dokumen. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Pengaturan tanda tangan. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui jalur file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file absolut atau relatif. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui jalur file dan LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file absolut atau relatif. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Opsi pemuatan dokumen. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui jalur file dan [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file absolut atau relatif. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Pengaturan tanda tangan. |

--------------------

 **Learn more** 

 *  
 *   |

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


Menginisialisasi instance baru dari kelas [Signature](../../com.groupdocs.signature/signature) dengan dokumen yang disediakan melalui jalur file, LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) dan [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file absolut atau relatif. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Opsi pemuatan dokumen. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Pengaturan tanda tangan. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


Menandatangani dokumen dengan [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke dalam stream.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen keluaran. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Opsi tanda tangan. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


Menandatangani dokumen dengan [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke aliran dengan [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) yang telah ditentukan sebelumnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen keluaran. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Opsi tanda tangan. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Opsi penyimpanan. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


Menandatangani dokumen dengan koleksi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen keluaran. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Daftar opsi tanda tangan. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Menandatangani dokumen dengan koleksi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke aliran dengan [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) yang telah ditentukan sebelumnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen keluaran. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Daftar opsi tanda tangan. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Opsi penyimpanan. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


Menandatangani dokumen dengan [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke jalur file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file keluaran. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Opsi tanda tangan. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


Menandatangani dokumen dengan [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) yang telah ditentukan sebelumnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file keluaran. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Opsi tanda tangan. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Opsi penyimpanan. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


Menandatangani dokumen dengan koleksi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke jalur file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file keluaran. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Daftar opsi tanda tangan. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Menandatangani dokumen dengan koleksi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) yang telah ditentukan sebelumnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file keluaran. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Daftar opsi tanda tangan. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Opsi penyimpanan. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


Memverifikasi tanda tangan dokumen dengan data VerifyOptions yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | Opsi verifikasi tanda tangan. |

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.
### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


Memverifikasi tanda tangan dokumen dengan daftar data VerifyOptions.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | Koleksi opsi verifikasi tanda tangan. Instansi dari [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Mendapatkan informasi tentang halaman dokumen: ukuran mereka, tinggi maksimum halaman, lebar halaman dengan tinggi maksimum.

**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

--------------------

**Learn more**

 *  Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java][]


[How to get document properties in Java]: https://docs.groupdocs.com/signature/java/get-document-information/
### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Menghasilkan pratinjau halaman dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | Opsi pratinjau. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature][]


[How to generate document pages preview using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/generate-document-pages-preview/ |

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


Mencari tanda tangan dalam dokumen berdasarkan daftar [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Koleksi opsi pencarian. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.
### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


Mencari tanda tangan dalam dokumen dengan opsi [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Opsi pencarian. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - Mengembalikan daftar tanda tangan yang ditemukan.
### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Mencari tipe tepat tanda tangan dalam dokumen berdasarkan nilai [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | Jenis tanda tangan yang akan dicari. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - Mengembalikan daftar tanda tangan yang ditemukan dengan tipe tepat.
### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Mencari tipe tanda tangan yang ditentukan dalam dokumen berdasarkan nilai [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | signatureTypes | int[] | Satu atau beberapa jenis tanda tangan untuk ditemukan. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.
### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


Memperbarui tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dalam dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen keluaran. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Objek tanda tangan yang akan diperbarui dalam dokumen. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - Mengembalikan true jika operasi berhasil.
### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Memperbarui tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dalam dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen keluaran. |
|  | tanda tangan | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Daftar tanda tangan untuk diperbarui dalam dokumen. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


Memperbarui tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dalam dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file keluaran. |
|  | tanda tangan | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Daftar tanda tangan untuk diperbarui dalam dokumen. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


Memperbarui tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dalam dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file keluaran. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Objek tanda tangan yang akan diperbarui dalam dokumen. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - Mengembalikan UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) dengan daftar tanda tangan yang berhasil diperbarui dan yang gagal.
### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Menghapus tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dari dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen keluaran. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Objek tanda tangan yang akan dihapus dari dokumen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - Mengembalikan true jika operasi berhasil.
### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Menghapus daftar tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dari dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen keluaran. |
|  | tanda tangan | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Daftar tanda tangan untuk dihapus dari dokumen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


Menghapus tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dari dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file keluaran. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Objek tanda tangan yang akan dihapus dari dokumen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - Mengembalikan true jika operasi berhasil.
### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Menghapus daftar tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dari dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file keluaran. |
|  | tanda tangan | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Daftar tanda tangan untuk dihapus dari dokumen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


Menghapus tanda tangan dari tipe tertentu [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan oleh metode Sign dan ditandai sebagai Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) yang akan dihapus. Tipe tanda tangan berikut didukung: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen keluaran. |
|  | signatureType | int | Tipe tanda tangan yang akan dihapus dari dokumen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


Menghapus tanda tangan dari daftar tipe tertentu [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan oleh metode Sign dan ditandai sebagai Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) yang akan dihapus. Tipe tanda tangan berikut didukung: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen keluaran. |
|  | signatureTypes | java.util.List<java.lang.Integer> | Daftar tipe tanda tangan yang akan dihapus dari dokumen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


Menghapus tanda tangan dari tipe tertentu [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan oleh metode Sign dan ditandai sebagai Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) yang akan dihapus. Tipe tanda tangan berikut didukung: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file keluaran. |
|  | signatureType | int | Tipe tanda tangan yang akan dihapus dari dokumen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


Menghapus tanda tangan dari daftar tipe tertentu [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan oleh metode Sign dan ditandai sebagai Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) yang akan dihapus. Tipe tanda tangan berikut didukung: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file keluaran. |
|  | signatureTypes | java.util.List<java.lang.Integer> | Daftar tipe tanda tangan yang akan dihapus dari dokumen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


Menghapus tanda tangan berdasarkan Id tanda tangan spesifiknya dari dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | signatureId | java.lang.String | Id tanda tangan yang akan dihapus dari dokumen. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
boolean - Mengembalikan true jika operasi berhasil.
### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Menghapus daftar tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang diberikan dari dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Daftar pengidentifikasi tanda tangan yang akan dihapus dari dokumen. |

--------------------

**Learn more** ///  ///  /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature][] ///  ///  /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C] ///  ///  ///


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


Menghasilkan pratinjau Tanda Tangan berdasarkan SignOptions yang diberikan. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | Pratinjau tanda tangan dengan SignOptions yang diberikan. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

--------------------

**Learn more**

 *  Learn more about how to generate previews of the signatures: |

### dispose() {#dispose--}
```
public final void dispose()
```


Implementasikan antarmuka IDisposable untuk membersihkan sumber daya internal

