---
title: "Signature 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서 서명 프로세스를 제어하는 주요 클래스를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

문서 서명 프로세스를 제어하는 주요 클래스를 나타냅니다.

GroupDocs.Signature 기능에 대해 자세히 알아보세요:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Signature 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | 스트림으로 제공된 문서로 새로운 Signature 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | 문서 스트림과 로드 옵션으로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | 스트림으로 제공된 문서와 선택적 [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)으로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | 문서 스트림, 로드 옵션 및 서명 설정으로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | 파일 경로로 제공된 문서로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | 파일 경로와 로드 옵션으로 제공된 문서로 새로운 Signature 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | 파일 경로로 제공된 문서와 선택적 [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)으로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | 파일 경로, 로드 옵션 및 서명 설정으로 제공된 문서로 새로운 [`Signature`](/signature/python-net/groupdocs.signature/signature/) 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | 문서에서 지정된 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)을 삭제합니다. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | 문서에서 제공된 서명 목록을 삭제합니다. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | 문서에서 지정된 유형의 서명을 삭제합니다. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | 문서에서 지정된 `SignatureType` 목록의 서명을 삭제합니다. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | 문서에서 특정 서명 Id로 서명을 삭제합니다. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | 문서에서 지정된 서명을 삭제합니다. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | 서명 객체가 사용한 내부 리소스를 정리합니다. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | 문서 페이지 미리보기를 생성합니다. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | 주어진 SignOptions를 기반으로 서명 미리보기를 생성합니다. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | 문서 페이지에 대한 정보를 가져옵니다: 페이지 크기, 최대 페이지 높이, 최대 높이를 가진 페이지의 너비. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | 문서에서 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) 목록을 사용하여 서명을 검색합니다. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | 제공된 검색 옵션을 사용하여 문서에서 서명을 검색하고 지정된 술어에 따라 결과를 필터링합니다. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | `SignatureType` 값으로 문서에서 지정된 서명 유형을 검색합니다. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | 사용 가능한 모든 검색 옵션을 사용하여 문서에서 서명을 검색하고 지정된 술어에 따라 결과를 필터링합니다. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)로 문서를 서명하고 결과를 스트림에 저장합니다. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)로 문서를 서명하고 미리 정의된 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)를 사용하여 결과를 스트림에 저장합니다. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 컬렉션으로 문서를 서명하고 결과를 스트림에 저장합니다. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 컬렉션으로 문서를 서명하고 미리 정의된 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)를 사용하여 결과를 스트림에 저장합니다. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | SignOptions로 문서를 서명하고 결과를 지정된 파일 경로에 저장합니다. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)로 문서를 서명하고 미리 정의된 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)와 함께 결과를 지정된 파일 경로에 저장합니다. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 컬렉션으로 문서를 서명하고 결과를 지정된 파일 경로에 저장합니다. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | 문서를 [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) 컬렉션으로 서명하고 미리 정의된 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)를 사용하여 결과를 지정된 파일 경로에 저장합니다. |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | 문서에서 전달된 서명 BaseSignature를 업데이트합니다. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | 문서에서 전달된 서명 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)을 업데이트합니다. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | 주어진 VerifyOptions 데이터로 문서 서명을 검증합니다. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | 제공된 검증 옵션을 사용하여 문서 서명을 검증하고 지정된 술어에 따라 결과를 필터링합니다. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | VerifyOptions 데이터 목록으로 문서 서명을 검증합니다. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | 제공된 검증 옵션을 사용하여 문서 서명을 확인하고, 주어진 프레디케이트로 결과를 필터링합니다. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

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

### Guides
`Signature`를 사용하는 작업 가이드:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)
* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)
* [Delete signatures of the certain type](/signature/python-net/guides/delete-signatures-of-the-certain-type/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)
* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### 또 보기
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
