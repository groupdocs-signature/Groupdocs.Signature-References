---
title: "QrCodeTypes 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "QR 코드 유형 컨테이너입니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

QR 코드 유형 컨테이너입니다.

QrCodeTypes 형식은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | QR 코드 유형 이름을 구문 분석하고 해당 QRCodeType 인스턴스를 반환합니다. |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | 주어진 구문 분석 유형 이름과 일치하는 QRCode 유형을 반환하며, 이름을 알 수 없을 경우 None을 반환합니다. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | 모든 QRCode 유형. |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Aztec QR-Code 유형 객체. |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | DataMatrix QR-Code 유형 객체. |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | QR QR-Code 유형 객체. |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | GS1 DataMatrix QR-Code 유형 객체. |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | GS1 QR-Code 유형 객체. |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | HIBC LIC QR-Code 유형 객체. |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | HIBC LIC Data Matrix QR-Code 유형 객체. |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | HIBC LIC Aztec QR-Code 유형 객체. |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | HIBC PAS QR-Code 유형 객체. |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | HIBC PAS Data Matrix QR-Code 유형 객체. |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | HIBC PAS Aztec QR-Code 유형 객체. |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Han Xin QR-Code 유형 객체. |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | GS1 Han Xin QR-Code 유형 객체. |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | RectMicroQR 유형 객체. |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | MicroQR 유형 객체. |

### 예시

```python
from groupdocs.signature.domain import QrCodeTypes

# 서명 옵션을 만들 때 QR 코드 유형 열거형을 사용하십시오
print(QrCodeTypes.QR)
```

### Guides
`QrCodeTypes`를 사용하는 작업 가이드:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
