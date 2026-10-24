---
title: "sign 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "SignOptions를 사용해 문서에 서명하고 결과를 스트림에 저장합니다."
type: docs
url: /ko/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)로 문서를 서명하고 결과를 스트림에 저장합니다.

```python
def sign(self, document, sign_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 출력 문서 스트림. |
| sign_options | `SignOptions` | 서명 옵션. |

**Returns:** SignResult: Instance containing list of newly created signatures.

비고:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#document-sign_options-save_options}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)로 문서를 서명하고 미리 정의된 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)를 사용하여 결과를 스트림에 저장합니다.

자세히 알아보기
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 출력 문서 스트림. |
| sign_options | `SignOptions` | 서명 옵션. |
| save_options | `SaveOptions` | 저장 옵션. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 컬렉션으로 문서를 서명하고 결과를 스트림에 저장합니다.

자세히 알아보기

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 출력 문서 스트림. |
| sign_options_list | `List[SignOptions]` | 서명 옵션 목록. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 컬렉션으로 문서를 서명하고 미리 정의된 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)를 사용하여 결과를 스트림에 저장합니다.

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 출력 문서 스트림. |
| sign_options_list | `List[SignOptions]` | 서명 옵션 목록. |
| save_options | `SaveOptions` | 저장 옵션. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

비고:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # 서명하고 결과를 새 파일에 저장합니다; 원본은 변경되지 않습니다.
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

SignOptions로 문서를 서명하고 결과를 지정된 파일 경로에 저장합니다.

자세히 알아보기

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 출력 파일 경로. |
| sign_options | `SignOptions` | 서명 옵션. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options-save_options}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)로 문서를 서명하고 미리 정의된 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)와 함께 결과를 지정된 파일 경로에 저장합니다.

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 출력 파일 경로. |
| sign_options | `SignOptions` | 서명 옵션. |
| save_options | `SaveOptions` | 저장 옵션. |

**Returns:** SignResult: Instance with list of newly created signatures.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # 문서를 엽니다; with 블록은 종료될 때 파일을 해제합니다.
    with Signature("sample.pdf") as signature:
        # 첫 페이지의 왼쪽 및 위쪽 가장자리에서 100픽셀 떨어진 텍스트 서명
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # 서명하고 결과를 새 파일에 저장합니다; 원본은 변경되지 않습니다.
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 컬렉션으로 문서를 서명하고 결과를 지정된 파일 경로에 저장합니다.

자세히 보기:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 출력 파일 경로. |
| sign_options_list | `List[SignOptions]` | 서명 옵션 목록. |

**Returns:** SignResult: Instance with list of newly created signatures.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    options.left = 100
    options.top = 100
    result = signature.sign("signed_sample.pdf", options)
    print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list-save_options}

문서를 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 컬렉션으로 서명하고 미리 정의된 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)를 사용하여 결과를 지정된 파일 경로에 저장합니다.

자세히 보기:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 출력 파일 경로. |
| sign_options_list | `List[SignOptions]` | 서명 옵션 목록. |
| save_options | `SaveOptions` | 저장 옵션. |

**Returns:** SignResult: Instance with list of newly created signatures.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### 또 보기
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
