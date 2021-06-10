# REPOSITORY SERTIFIKAT BERSAMA FISIKA ITS 2020

Repository ini bertujuan untuk mempermudah pencarian sertifikat-sertifikat
bersama yang telah didapat selama masa kuliah ini.

## How We Did This??

Tentu bukan manual, tidak mungkin kita melakukannya manual dan tentu akan
memakan waktu yang panjang. Kita memiliki list nama mahasiswa yang lengkap,
dan dari situ kita bisa memilih secara otomatis, mana saja yang dari Fisika
2020.

#### GNU/Linux

Ekstrak file zip, pindahkan `list.txt` ke dalam folder ekstraksi tersebut.
Setelah itu, jalankan perintah ini di dalam folder ekstraksi dengan `cd
<nama folder>`.

```bash
mkdir fisika && sed 's/^ *//' < list.txt | xargs -d '\n' mv -t fisika/
```

Script one-line ini bertujuan untuk
1. `mkdir fisika` - Membuat folder dengan nama `fisika`
2. `sed 's/^ *//' < list.txt` - membaca list nama mahasiswa
3. Output dari no.2 dimasukkan ke command GNU mv, `mv -t fisika/` di mana
   ini akan memasukkan seluruh file dengan nama yang sama ke dalam folder
   baru yang dibuat pada perintah no.1

#### Windows Powershell

YNTKTS

## Something Goes Wrong?

Jika nama anda belum tercantum, bisa chat pribadi kepada **Jhagas (017),
Andyra (066) atau Harda (104).**

## Have Something to Add?

Hubungi saja kontak di atas beserta dengan link sertifikat. Kita akan
proses dan memasukkannya ke dalam daftar secepat mungkin

Cheers!!
