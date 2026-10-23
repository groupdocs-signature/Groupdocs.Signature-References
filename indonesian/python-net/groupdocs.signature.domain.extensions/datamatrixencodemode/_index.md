---
title: "Kelas DataMatrixEncodeMode"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Enum DataMatrixEncodeMode — GroupDocs.Signature untuk Python via .NET API reference."
type: docs
url: /id/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

Tipe DataMatrixEncodeMode menampilkan anggota-anggota berikut:

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | Secara otomatis memilih mode enkode terbaik untuk enkoding DataMatrix |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Mengenkripsi satu karakter alfanumerik atau dua karakter numerik per byte |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | Enkode nilai 8 bit |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | Enkode dengan pengkodean yang ditentukan dalam BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | Menggunakan pengkodean C40. Mengkodekan alfanumerik huruf besar, huruf kecil, dan karakter khusus |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Menggunakan pengkodean Text. Mengkodekan alfanumerik huruf kecil, huruf besar, dan karakter khusus. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | Menggunakan pengkodean EDIFACT. Menggunakan enam bit per karakter, mengkodekan digit, huruf besar, dan banyak tanda baca, tetapi tidak mendukung huruf kecil. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | Menggunakan pengkodean ANSI X12. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | Mode ExtendedCodetext memungkinkan untuk secara manual beralih skema pengkodean dalam code-text. Format : \"\\Encodation_scheme_name:text\\Encodation_scheme_name:text\". Skema pengkodean yang diizinkan adalah: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Contoh code-text yang diperluas: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText\" Semua backslash (\\) harus digandakan dalam teks. |

### Lihat Juga
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
