---
title: "DataMatrixEncodeMode sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "DataMatrixEncodeMode enum — GroupDocs.Signature for Python via .NET API referansı."
type: docs
url: /tr/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

DataMatrixEncodeMode türü aşağıdaki üyeleri ortaya çıkarır:

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | DataMatrix kodlaması için en iyi kodlama modunu otomatik olarak seçer |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Her bayt için bir alfanümerik veya iki sayısal karakter kodlar |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | 8 bit değerleri kodla |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding içinde belirtilen kodlamayla kodla |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | C40 kodlamasını kullanır. Büyük harf alfanümerik, küçük harf ve özel karakterleri kodlar |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Metin kodlamasını kullanır. Küçük harf alfanümerik, büyük harf ve özel karakterleri kodlar. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | EDIFACT kodlamasını kullanır. Karakter başına altı bit kullanır, rakamları, büyük harfleri ve birçok noktalama işaretini kodlar, ancak küçük harfleri desteklemez. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | ANSI X12 kodlamasını kullanır. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | ExtendedCodetext modu, kod‑metninde kodlama şemalarını manuel olarak değiştirmeye izin verir. Biçim: "\Encodation_scheme_name:text\Encodation_scheme_name:text". İzin verilen kodlama şemaları şunlardır: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Extended code‑text örneği: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" Metindeki tüm ters eğik çizgiler (\) iki kez yazılmalıdır. |

### Ayrıca Bakınız
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
