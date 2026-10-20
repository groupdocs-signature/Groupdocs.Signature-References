---
title: "ライセンス"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "コンポーネントにライセンスを付与するメソッドを提供します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

コンポーネントのライセンス付与のためのメソッドを提供します。ライセンスについて詳しく学ぶ
[here](../https://purchase.groupdocs.com/faqs/licensing)
.

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [License()](#License--) | ライセンスをインスタンス化する |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | コンポーネントにライセンスを付与します。 |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | コンポーネントにライセンスを付与します。 |
|
### License() {#License--}
```
public License()
```


ライセンスをインスタンス化する


### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


コンポーネントにライセンスを付与します。

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set a license
>  passing a path to the license file.
>   string licensePath = "GroupDocs.Signature.lic";
>  GroupDocs.Signature.License lic = new GroupDocs.Signature.License();
>  lic.SetLicense(licensePath);
>  
>  
> ```

<br />



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | licensePath | java.lang.String | ライセンスパスです。 |
|

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


コンポーネントにライセンスを付与します。

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set a license
>  passing Stream of the license file.
>   using (FileStream licenseStream = new FileStream("GroupDocs.Signature.lic", FileMode.Open))
>  {
>      GroupDocs.Signature.License lic = new GroupDocs.Signature.License();
>      lic.SetLicense(licenseStream);
>  }
>  
>  
> ```

<br />



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | ライセンスストリームです。 |
|

