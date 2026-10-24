---
title: "allow_expired 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "유효 기간이 끝난 인증서로 서명할 수 있게 하는 플래그입니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

유효 기간이 만료된 인증서로 서명하도록 허용하는 플래그입니다. 기본값은 False이며, 만료된 인증서로 서명하면 `GroupDocsSignatureException`이 발생하고 문서는 서명되지 않습니다.

검증자는 만료된 인증서로 만든 서명을 유효하지 않다고 보고합니다. 이러한 서명이 필요할 경우에만, 예를 들어 오래된 인증서로 테스트하려는 경우에만 이 속성을 True로 설정하십시오. 그러면 문서가 서명되고, [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)에 설정된 로거에 경고가 기록됩니다.

인증서는 UTC 현재 시간과 비교되며, [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/)와는 비교되지 않습니다. 이 플래그는 [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) 또는 [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/)에 지정된 인증서에 적용되며, 스프레드시트에 서명할 경우 첫 번째 [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) 확장자의 인증서에도 적용됩니다. 이미지의 디지털 서명은 인증서를 사용하지 않으며 검증되지 않습니다. 아직 유효 기간이 시작되지 않은 인증서는 [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/)에 의해 제어됩니다.

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### 또 보기
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
