---
title: "EXTENDED_CODETEXT フィールド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ExtendedCodetext モードでは、コードテキスト内でエンコーディング方式を手動で切り替えることができます。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/
is_root: false
weight: 3090
---


## EXTENDED_CODETEXT field

ExtendedCodetext モードは、コードテキスト内でエンコーディング方式を手動で切り替えることを可能にします。形式: \"\\Encodation_scheme_name:text\\Encodation_scheme_name:text\"。使用可能なエンコーディング方式は: EDIFACT, ANSIX12, ASCII, C40, Text, Auto。拡張コードテキスト例: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText\" すべてのバックスラッシュ (\\) はテキスト内で二重にする必要があります。

### 値
`12`

### 関連項目
* class [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/)
