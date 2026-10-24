---
title: "이미지 서명이 포함된 전자 서명 문서"
linkTitle: "Image Signature"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 문서에서는 .NET을 통해 Python용 GroupDocs.Signature를 사용하여 문서 페이지에 서명 이미지를 추가하는 방법을 보여줍니다."
type: docs
url: /ko/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

**image**를 서명으로 사용하는 것은 데이터를 시각적인 형태로 표시하는 대체 방법입니다. 이 전자 서명 유형을 사용하면 회사 로고, 발신자 이니셜, 이름 등으로 맞춤 이미지를 만들 수 있습니다.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

문서 페이지에 이미지 서명을 생성하는 단계는 다음과 같습니다:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

이 예제는 Python을 사용하여 이미지 서명으로 PDF 문서에 서명하는 방법을 보여줍니다:

{{< tabs \"sign_with_image_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # 이미지 파일로 이미지 서명 옵션을 생성합니다
        options = ImageSignOptions("signature.jpg")

        # 서명의 위치와 크기를 설정합니다
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # 문서에 서명하고 결과를 저장합니다
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"signed_image.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

이미지 서명을 추가 옵션으로 더 맞춤 설정할 수 있습니다: 정렬 및 여백, 회전, 투명도 및 테두리. 정렬을 설정하면 `left` 또는 `top` 좌표를 대체하고, `margin`은 서명을 페이지 가장자리에서 떨어뜨립니다.

{{< tabs \"sign_with_image_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # 페이지 오른쪽 하단에 서명을 배치하십시오.
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # 이미지를 회전하고 20% 투명하게 만드십시오.
        options.rotation_angle = 10
        options.transparency = 0.2

        # 이미지 주위에 점선 테두리를 그리십시오.
        border = Border()
        border.color = Color.dark_green
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border

        result = signature.sign("signed_image_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"signed_image_advanced.pdf\" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

스트림에서 서명 이미지를 로드할 수도 있습니다. `sign`이 반환될 때까지 스트림을 열어 두십시오:

{{< tabs \"sign_with_image_from_stream\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # 스트림에서 서명 이미지를 로드하십시오.
        with open("signature.jpg", "rb") as image_stream:
            options = ImageSignOptions(image_stream)
            options.left = 100
            options.top = 400
            options.width = 120
            options.height = 100

            result = signature.sign("signed_image_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) 를 클릭하십시오.

{{< /tab >}}
{{< tab \"signed_image_stream.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
이 가이드는 [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net)를 사용하여 문서에 이미지 기반 서명을 추가하는 방법을 보여줍니다. 문서 로드, 이미지 서명의 속성(크기, 위치, 투명도 등) 구성 및 서명된 문서 저장에 대해 다룹니다. 이미지 외관 조정 및 서명 정렬과 같은 고급 맞춤 옵션도 논의됩니다. 추가 정보를 원하면 관련 문서 서명 리소스를 살펴보십시오.

## More Resources

### GitHub Examples

위 코드를 쉽게 실행하여 GitHub 예제에서 기능이 작동하는 모습을 확인할 수 있습니다:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

전체 기능을 갖춘 Python 라이브러리와 함께, 간단하지만 강력한 무료 온라인 앱을 제공합니다.

이미지 서명을 생성하거나 파일에 무료로 서명하려면 [Generate Image](https://products.groupdocs.app/signature/generate/image) 온라인 앱을 사용할 수 있습니다.

PDF, Word, Excel, PowerPoint 및 기타 문서에 서명하려면 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**의 다른 온라인 앱을 사용할 수 있습니다.
