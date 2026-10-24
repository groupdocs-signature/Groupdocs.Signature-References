---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "스트림으로 제공된 문서로 새로운 Signature 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

스트림으로 제공된 문서로 새로운 Signature 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 문서 콘텐츠 스트림. |

## __init__ {#document-load_options}

문서 스트림과 로드 옵션으로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다.

자세히 알아보기

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 문서 콘텐츠 스트림. |
| load_options | `LoadOptions` | 문서 로드 옵션. |

## __init__ {#document-settings}

스트림으로 제공된 문서와 선택적 [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)으로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다.

자세히 보기:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 문서 콘텐츠 스트림. |
| settings | `SignatureSettings` | 서명 설정. |

## __init__ {#document-load_options-settings}

문서 스트림, 로드 옵션 및 서명 설정으로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| document | `io.RawIOBase` | 문서 콘텐츠 스트림. |
| load_options | `LoadOptions` | 문서 로드 옵션. |
| settings | `SignatureSettings` | 서명 설정. |

## __init__ {#file_path}

파일 경로로 제공된 문서로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 절대 또는 상대 파일 경로. |

### 예시

```python
from groupdocs.signature import Signature

# 서명, 검색 또는 검증을 위해 문서를 엽니다
with Signature("sample.pdf") as signature:
    # 서명 객체와 작업합니다
    pass
```

## __init__ {#file_path-load_options}

파일 경로와 로드 옵션으로 제공된 문서로 새로운 Signature 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 절대 또는 상대 파일 경로. |
| load_options | `LoadOptions` | 문서 로드 옵션. |

### 예시

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # 서명, 검색 또는 검증 작업을 수행합니다
    pass
```

## __init__ {#file_path-settings}

파일 경로로 제공된 문서와 선택적 [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)으로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 절대 또는 상대 파일 경로. |
| settings | `SignatureSettings` | 서명 설정. |

### 예시

```python
from groupdocs.signature import Signature

# 서명 또는 검증을 위해 PDF 문서를 엽니다
with Signature("sample.pdf") as signature:
    # 여기에서 서명 인스턴스를 사용합니다 (예: 서명, 검증, 검색)
    pass
```

## __init__ {#file_path-load_options-settings}

파일 경로, 로드 옵션 및 서명 설정으로 제공된 문서로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다.

자세히 보기:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 절대 또는 상대 파일 경로. |
| load_options | `LoadOptions` | 문서 로드 옵션. |
| settings | `SignatureSettings` | 서명 설정. |

### 예시

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # 서명, 검증 또는 검색 작업을 수행합니다
    pass
```

### 또 보기
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
