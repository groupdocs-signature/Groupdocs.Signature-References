---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "PdfSaveOptions의 새 인스턴스를 기본값으로 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

PdfSaveOptions의 새 인스턴스를 기본값으로 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

PdfSaveOptions의 새 인스턴스를 지정된 출력 파일 형식으로 초기화합니다.

```python
def __init__(self, file_format):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | 출력 파일 형식 `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

PdfSaveOptions의 새 인스턴스를 덮어쓰기 플래그와 함께 초기화합니다.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| overwrite_existing_file | `bool` | 같은 파일로 서명된 파일을 덮어쓸지 여부를 나타내는 플래그. |

## __init__ {#file_format-overwrite_existing_file}

PdfSaveOptions의 새 인스턴스를 지정된 출력 파일 형식 및 덮어쓰기 플래그와 함께 초기화합니다.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | 출력 파일 형식. |
| overwrite_existing_file | `bool` | 같은 파일로 서명된 파일을 덮어쓸지 여부를 나타내는 플래그. |

### 예시

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# PDF 형식으로 저장 옵션을 생성하고 기존 파일을 덮어쓰기를 허용합니다
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### 또 보기
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
