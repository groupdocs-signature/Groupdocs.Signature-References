---
title: "DataMatrixEncodeMode クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "DataMatrixEncodeMode 列挙型 — GroupDocs.Signature for Python via .NET API リファレンス。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

DataMatrixEncodeMode 型は次のメンバーを公開します:

### フィールド
| フィールド | 説明 |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | DataMatrix エンコードに最適なエンコードモードを自動的に選択します |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | 1 バイトあたり 1 文字の英数字または 2 文字の数字をエンコードします |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | 8 ビット値をエンコードします |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding で指定されたエンコーディングでエンコードします |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | C40 エンコーディングを使用します。大文字の英数字、 小文字および特殊文字をエンコードします |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Text エンコーディングを使用します。小文字の英数字、大文字および特殊文字をエンコードします。 |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | EDIFACT エンコーディングを使用します。文字あたり 6 ビットを使用し、数字、大文字、 多くの句読点をエンコードしますが、小文字はサポートされていません。 |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | ANSI X12 エンコーディングを使用します。 |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | ExtendedCodetext モードは、コードテキスト内でエンコーディング方式を手動で切り替えることを可能にします。形式: \"\\Encodation_scheme_name:text\\Encodation_scheme_name:text\"。使用可能なエンコーディング方式は: EDIFACT, ANSIX12, ASCII, C40, Text, Auto。拡張コードテキスト例: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText\" すべてのバックスラッシュ (\\) はテキスト内で二重にする必要があります。 |

### 関連項目
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
