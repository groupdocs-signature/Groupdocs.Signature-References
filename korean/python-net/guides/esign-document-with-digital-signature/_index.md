---
title: "디지털 서명으로 문서 서명"
linkTitle: "Digital Signature"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "디지털 서명을 사용하여 문서를 안전하게 서명하는 이점에 대해 알아보세요. 단계별 안내를 통해 Python에서 프로그래밍 방식으로 디지털 서명을 추가하는 방법을 확인하십시오."
type: docs
url: /ko/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

오늘날 디지털 시대에 전자 문서의 진위와 무결성을 보장하는 것은 매우 중요합니다. 이를 달성하는 가장 효과적인 방법 중 하나는 디지털 서명을 사용하는 것입니다. 이 가이드에서는 디지털 서명의 개념, 필요성 및 GroupDocs.Signature for Python via .NET을 활용하여 문서를 원활하게 전자 서명(eSign)하는 방법을 살펴봅니다.

## What is a Digital Signature?

디지털 서명은 전자 문서의 진위와 무결성을 검증하기 위한 암호화 메커니즘입니다. 이는 문서가 알려진 발신자에 의해 생성되었으며 무단으로 변조되지 않았음을 강력히 보장합니다. 디지털 서명은 일반적으로 서명을 위한 개인 키와 검증을 위한 공개 키를 포함하는 인증서 형태로 제공됩니다. PFX 형식과 같은 다양한 공개 키 암호화 표준이 이 목적에 흔히 사용됩니다.
아래 그림은 기본적으로 PDF 문서 페이지에 디지털 서명이 어떻게 표시되는지 보여줍니다.

![Digital](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-digital-signature.png)

## Why Use Digital Signatures?

- **Enhanced Security:** Digital signatures provide a higher level of document security, making it extremely challenging for unauthorized parties to alter the content.
- **Authentication:** They offer a reliable way to verify the identity of the document sender.
- **Non-repudiation:** Digital signatures prevent senders from denying the authenticity of the signed document.

## How to Sign a Document with a Digital Signature

**[GroupDocs.Signature for Python via .NET](https://products.groupdocs.com/signature/python-net)** supports the creation of digital signatures based on existing PFX certificates. To specify various settings the library provides the [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) class that allows adjusting digital signature properties in the document:

* The [certificate_file_path](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) or [certificate_stream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) properties define the certificate source;
* The [password](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) property specifies the certificate password;
* The [contact](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/), [reason](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) and [location](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) properties specify additional descriptions;
* The [visible](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) property specifies whether the signature should be visible on the document page or not;
* The [xad_es_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) property defines whether the e-signature should be of an XML Advanced Electronic Signature type (supported for spreadsheet documents).

만료되었거나 아직 유효하지 않은 인증서는 거부됩니다: `sign`은 [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/)을 발생시키며, 예를 들어 "The signing certificate expired on ..."와 같은 메시지를 표시합니다. 그래도 해당 인증서로 서명하려면 `allow_expired` 또는 `allow_not_yet_valid`를 `True`로 설정하십시오.

### Follow these steps to sign your documents with a digital signature

1. pip를 사용하여 GroupDocs.Signature 패키지를 설치합니다:
```bash
pip install groupdocs-signature-net
```

2. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) 클래스를 새 인스턴스로 생성하고 소스 문서 경로를 생성자 매개변수로 전달합니다.
3. 필요한 인증서와 비밀번호를 사용하여 [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) 객체를 인스턴스화합니다.
4. [Signature] 클래스 인스턴스의 [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) 메서드를 호출하고 [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/)를 전달합니다.

아래 예제는 Python을 사용하여 PDF 문서에 디지털 전자 서명을 적용하는 방법을 보여줍니다. 동일한 방식으로 다른 지원되는 문서 형식도 서명할 수 있습니다.

{{< tabs \"sign_with_digital_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # 인증서 파일로 디지털 서명 옵션을 생성합니다.
        options = DigitalSignOptions("certificate.pfx")

        # 인증서 비밀번호를 설정합니다.
        options.password = "1234567890"

        # 옵션: 페이지에 서명을 표시하는 이미지
        options.image_file_path = "signature.jpg"

        # 서명 위치를 설정합니다.
        options.left = 100
        options.top = 400

        # 문서에 서명하고 결과를 저장합니다
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx`는 이 예제에 사용된 샘플 인증서입니다 (비밀번호 `1234567890`). 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx)를 클릭하십시오.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg)를 클릭하십시오.

{{< /tab >}}
{{< tab \"signed_digital.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

디지털 서명을 추가 옵션으로 더 맞춤 설정할 수 있습니다: 페이지에서 서명의 크기, 그리고 서명에 저장된 연락처, 이유 및 위치입니다:

{{< tabs \"sign_with_digital_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # 생성자에 인증서와 외관 이미지를 전달합니다.
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # 페이지에 서명을 표시하고, 지정된 위치와 크기로 나타냅니다.
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # 서명에 저장된 정보
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx`는 이 예제에 사용된 샘플 인증서입니다 (비밀번호 `1234567890`). 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx)를 클릭하십시오.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg)를 클릭하십시오.

{{< /tab >}}
{{< tab \"signed_digital_advanced.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

스트림에서 인증서를 로드할 수도 있습니다. `sign`이 반환될 때까지 스트림을 열어 두세요:

{{< tabs \"sign_with_certificate_from_stream\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # 스트림에서 인증서를 로드합니다.
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # 서명의 위치와 크기를 설정합니다
            options.left = 100
            options.top = 400
            options.width = 200
            options.height = 60

            result = signature.sign("signed_digital_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_certificate_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx`는 이 예제에 사용된 샘플 인증서입니다 (비밀번호 `1234567890`). 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx)를 클릭하십시오.

{{< /tab >}}
{{< tab \"signed_digital_stream.pdf\" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
이 가이드는 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net)를 사용하여 디지털 서명으로 문서를 서명하는 방법을 보여줍니다. 문서를 로드하고, 인증서 기반 서명을 구성하며, 서명된 파일을 안전하게 저장하는 방법을 설명합니다. 서명 모양 및 서명에 저장된 정보와 같은 고급 기능도 다룹니다. 디지털 서명 워크플로에 대한 자세한 내용은 관련 리소스를 참조하십시오.

## More Resources

### GitHub Examples

위 코드를 쉽게 실행하여 GitHub 예제에서 기능이 작동하는 모습을 확인할 수 있습니다:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

전체 기능을 갖춘 Python 라이브러리와 함께, 간단하지만 강력한 무료 온라인 앱을 제공합니다.

PDF, Word, Excel, PowerPoint 및 기타 문서에 서명하려면 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**의 온라인 앱을 사용할 수 있습니다.
