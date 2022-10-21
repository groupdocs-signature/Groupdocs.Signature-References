---
title: PreviewSignatureOptions
second_title: Справочник по API GroupDocs.Signature для .NET
description: Инициализирует объект PreviewSignatureOptions.
type: docs
weight: 10
url: /ru/net/groupdocs.signature.options/previewsignatureoptions/previewsignatureoptions/
---
## PreviewSignatureOptions(SignOptions, CreateSignatureStream) {#constructor}

Инициализирует объект PreviewSignatureOptions.

```csharp
public PreviewSignatureOptions(SignOptions signOptions, CreateSignatureStream createSignatureStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signOptions | SignOptions | Параметры подписи, для которых создается предварительный просмотр. |
| createSignatureStream | CreateSignatureStream | Делегат, определяющий метод создания потока предварительного просмотра выходной подписи. |

### Смотрите также

* class [SignOptions](../../signoptions)
* delegate [CreateSignatureStream](../../createsignaturestream)
* class [PreviewSignatureOptions](../../previewsignatureoptions)
* пространство имен [GroupDocs.Signature.Options](../../previewsignatureoptions)
* сборка [GroupDocs.Signature](../../../)

---

## PreviewSignatureOptions(SignOptions, CreateSignatureStream, ReleaseSignatureStream) {#constructor_1}

Инициализирует объект PreviewSignatureOptions.

```csharp
public PreviewSignatureOptions(SignOptions signOptions, 
    CreateSignatureStream createSignatureStream, ReleaseSignatureStream releaseSignatureStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signOptions | SignOptions | Параметры подписи, для которых создается предварительный просмотр. |
| createSignatureStream | CreateSignatureStream | Делегат, определяющий метод создания потока предварительного просмотра выходной подписи. |
| releaseSignatureStream | ReleaseSignatureStream | Делегат, определяющий метод выпуска выходного потока предварительного просмотра подписи. |

### Смотрите также

* class [SignOptions](../../signoptions)
* delegate [CreateSignatureStream](../../createsignaturestream)
* delegate [ReleaseSignatureStream](../../releasesignaturestream)
* class [PreviewSignatureOptions](../../previewsignatureoptions)
* пространство имен [GroupDocs.Signature.Options](../../previewsignatureoptions)
* сборка [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->