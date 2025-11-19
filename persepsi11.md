Catatan kuliah "Human peceptual model and its sytem", pertemuan ke-11.

Pitch dan pemodelannya

Pure tone 100 Hz
Peidodik kompleks stone --> Fundamental frekuensi.

Periodik kompleks tone adalah jumlahan dari tones

Misal, suatu kompleks tone terdiri dari 200, 400, 600 dan 800 Hz.
Sehingga ketika didekomposisi ada lebih dari satu frekuensi: f0, f1, f2, f3, ..., fN.
Frekuensi tersebut dinamakan harmonik. Harmonik berkaitan dengan picth.

Absolute pitch --> kemampuan telinga musisi untuk menentukan pitch/frekuensi dari suatu nada.

Harmonik
Satu diantara komponen frekuensi pembentuk kompleks tone. Harmonik tidak sama dengan formant.
Harmonik dihasilkan oleh vocal folds, sedangkan formant dihasilkan oleh vocal tract.
Harmonik selalu berulang, sedangkan formant tidak.

Teori persepsi pitch
- Teori fase
- Teori temporal

Dalam domain waktu, periode adalah cue yang penting. 
Pada domain frekuensi, bisa saja f0 tidak muncul, sebaliknya hanya frekuensi tengah yang muncul. 
Dalam hal ini, f0 bisa dihitung sebagai selish antara frekuensi pertama dengan frekuensi kedua.


Slide hal 11.
Periode sinyal dihitung dari selish antar dua puncak harmonik, misal untuk 500 Hz adalah 2 ms, sedang utuk 550 Hz adalah 1.8 detik.

limen, is expressed as a percentage of the baseline frequency
limen = 

Frekuensi diskriminan
1000 Hz dengan 1002 Hz secara sekuensial maka dapat dibedakan antara frekuensi pertama dengan frekuensi kedua.
Pada frekuensi rendah, misal 150 Hz, perbedaan frekuensi antara dua tone kecil bisa dibedakan, yakni 0.5 Hz.
Sedang pada frekuensi tinggi dibutuhkan beda frekuensi yang besar agar bisa dibedakan.


Phase locking
Penguncian frekuensi yang bisa terjadi pada stimulus dengan frekuensi rendah dan pada temporal envelope.

Missing fundamental
Secara fisis tidak ada frekuensi dasar, tapi bisa dipersepsi.

Miss tune
Memindahkan fN lebih tinggi atau lebih rendah (halaman 17). Dari gambar tersebu yang paling dominan adalah memindah f2 dan f3 agar pitch yang dipersepsi berbeda.

Apakah ada hubungan antara loudness dengan pitch?
Tidak ada, namun ada penelitian yang mengarah pada hal itu.

Bagaimana mengekstrak f0?
- autokorelasi, jika input merupakan sinyal periodik maka kita bisa mengestrak periodenya
- zerrocrossing, jika input hanya pure tone maka mengekstrak titik dimana y=0 dan mengurangi antar titiknya bisa digunakan untuk mencari f0.
- FFT + (autokorelasi)
- peak picking
- 

Namun semua metode tersebut tidak akan bekerja pada sinyal kompleks semisal, speech.
Untuk speech, metode yang baik adalah untuk mengeliminasi efek vocal tract, hanya glottis.


