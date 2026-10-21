---
title: "GroupDocs.Signature.Domain.Extensions"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Namespace menyediakan ekstensi untuk tampilan tanda tangan dan fungsionalitas tambahan."
type: docs
weight: 30
url: /id/net/groupdocs.signature.domain.extensions/
---
Namespace menyediakan ekstensi untuk tampilan tanda tangan dan fungsionalitas tambahan.

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [Address](./address) | Mewakili alamat untuk kontak. |
| [Brush](./brush) | Mewakili kelas dasar untuk berbagai kuas. |
| [CryptoCurrencyTransfer](./cryptocurrencytransfer) | Mewakili transfer Cryptocurrency (menerima atau mengirim) untuk QR-Code. |
| [DigitalVBA](./digitalvba) | Mewakili tanda tangan digital untuk proyek VBA Spreadsheet. Ini menyediakan kemampuan untuk menandatangani proyek VBA pada format dokumen Spreadsheet tertentu seperti Xlsm atau Xltm. Jika beberapa ekstensi DigitalVBA ditambahkan ke DigitalSignOptions.Extensions, hanya yang pertama yang terlibat dalam penandatanganan dokumen. |
| [Email](./email) | Mewakili format Email untuk QR-Code. |
| [EPC](./epc) | Mewakili European Payments Council Quick Response Code. |
| [Event](./event) | Mewakili detail Acara QR-Code standar. |
| [FormatAttribute](./formatattribute) | Menginstruksikan serialisasi objek untuk menyerialisasi anggota dengan nama dan format yang ditentukan. |
| [HIBCLICCombinedData](./hibcliccombineddata) | Kelas untuk menyimpan data gabungan HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) dengan entitas data primer dan sekunder. |
| [HIBCLICPrimaryData](./hibclicprimarydata) | Kelas untuk menyimpan data primer HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code). |
| [HIBCLICSecondaryAdditionalData](./hibclicsecondaryadditionaldata) | Kelas untuk menyimpan data sekunder dan tambahan HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code). |
| [HIBCPASData](./hibcpasdata) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord) | Kelas untuk menyimpan Rekaman HIBC (Healthcare Industry Bar Code Council) PAS (Provider Applications Standard). |
| [LinearGradientBrush](./lineargradientbrush) | Mewakili kuas gradien linier. |
| [Mailmark2D](./mailmark2d) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam Royal Mail 2D Mailmark. |
| [MaxiCodeMode2](./maxicodemode2) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode untuk mode. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage) | Kelas untuk mengkodekan dan mendekode pesan kedua standar untuk barcode MaxiCode. |
| [MeCard](./mecard) | Mewakili detail kontak standar MeCard. |
| [RadialGradientBrush](./radialgradientbrush) | Mewakili kuas gradien radial. |
| [SignatureExtension](./signatureextension) | Mewakili kelas dasar untuk ekstensi tanda tangan. |
| [SkipSerializationAttribute](./skipserializationattribute) | Menginstruksikan serialisasi untuk melewati anggota. |
| [SMS](./sms) | Mewakili detail layanan pesan singkat SMS. |
| [SolidBrush](./solidbrush) | Mewakili kuas padat. Bisa digunakan sebagai pengganti properti warna latar belakang. |
| [SpreadsheetPosition](./spreadsheetposition) | Mendefinisikan posisi tanda tangan untuk dokumen Spreadsheet. |
| [SwissAddress](./swissaddress) | Mewakili alamat kreditur atau debitur. Anda dapat mengatur jalan, nomor rumah, kode pos, dan kota (tipe alamat terstruktur) atau baris alamat 1 dan 2 (tipe elemen alamat gabungan). |
| [SwissQR](./swissqr) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode SwissQR. |
| [SymmetricEncryption](./symmetricencryption) | Mengimplementasikan algoritma simetris standar untuk enkripsi data dengan kunci tunggal dan kata sandi (garam). |
| [SymmetricEncryptionAttribute](./symmetricencryptionattribute) | Menginstruksikan serialisasi instance untuk mengenkripsi / mendekripsi string serialisasi objek. |
| [TextShadow](./textshadow) | Mewakili properti bayangan teks untuk tanda tangan teks. Hasilnya dapat bervariasi tergantung pada tipe tanda tangan dan format dokumen. TextShadow direkomendasikan untuk digunakan dengan tanda tangan TextAsImage untuk semua tipe dokumen yang didukung, juga dengan TextSignature sederhana dan TextSignature sebagai watermark untuk Spreadsheet (.xslx) dan Presentasi (.pptx). TextSignature sederhana untuk Word (.docx) juga direkomendasikan, namun memiliki fungsionalitas terbatas. |
| [TextureBrush](./texturebrush) | Mewakili kuas tekstur. |
| [VCard](./vcard) | Mewakili detail kontak standar Kartu Bisnis Elektronik. |
| [WiFi](./wifi) | Mewakili detail koneksi jaringan WiFi. |
## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [IDataEncryption](./idataencryption) | Antarmuka enkripsi untuk menyediakan metode pengkodean dan dekode objek. |
| [IDataSerializer](./idataserializer) | Antarmuka serialisasi untuk menyediakan metode serialisasi dan deserialisasi objek. |
## Enumerasi

| Enumerasi | Deskripsi |
| --- | --- |
| [CryptoCurrencyType](./cryptocurrencytype) | Mewakili tipe Cryptocurrency. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Mode pengkodean encoder DataMatrix, default ke Auto. |
| [HIBCLICDateFormat](./hibclicdateformat) | Menentukan berbagai tipe format tanggal untuk HIBC (Healthcare Industry Bar Code) LIC (Licensed Identification Code). |
| [HIBCPASDataLocation](./hibcpasdatalocation) | Menentukan tipe lokasi data HIBC PAS. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard. |
| [HIBCPASDataType](./hibcpasdatatype) | Menentukan berbagai tipe data rekaman HIBC PAS. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard. |
| [Mailmark2DType](./mailmark2dtype) | Tipe Mailmark 2D menentukan ukuran kode batang Data Matrix. |
| [SymmetricAlgorithmType](./symmetricalgorithmtype) | Mewakili tipe algoritma enkripsi simetris. |
| [WiFiEncryptionType](./wifiencryptiontype) | Mewakili tipe Enkripsi WiFi. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
