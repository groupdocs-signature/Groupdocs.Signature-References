---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "PresentationSaveOptions 인스턴스를 기본값으로 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/presentationsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

PresentationSaveOptions 인스턴스를 기본값으로 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

PresentationSaveOptions의 새 인스턴스를 지정된 출력 파일 형식으로 초기화합니다.

```python
def __init__(self, file_format):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_format | `PresentationSaveFileFormat` | 출력 파일 형식. |

## __init__ {#overwrite_existing_file}

PresentationSaveOptions의 새 인스턴스를 지정된 출력 유형 및 덮어쓰기 플래그와 함께 초기화합니다.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| overwrite_existing_file | `bool` | 같은 파일로 서명된 파일을 덮어쓸지 여부를 나타내는 플래그. |

## __init__ {#file_format-overwrite_existing_file}

PresentationSaveOptions의 새 인스턴스를 지정된 출력 파일 형식 및 덮어쓰기 플래그와 함께 초기화합니다.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_format | `PresentationSaveFileFormat` | 출력 파일 형식 `PresentationSaveFileFormat`. |
| overwrite_existing_file | `bool` | 기존 서명된 파일을 덮어쓸지 여부를 나타내는 플래그. |

### 또 보기
* class [`PresentationSaveOptions`](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/)
