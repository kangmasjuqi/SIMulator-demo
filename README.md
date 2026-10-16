# SIMulator-demo

https://www.awesomescreenshot.com/video/57499005?key=37ab77e123cf41d058be1a19bc43597c

Screenshots:
<img width="1770" height="2008" alt="screencapture-file-Users-marjuqi-Downloads-siap-sim-html-2026-10-16-08_47_47" src="https://github.com/user-attachments/assets/8339575f-4938-4741-ae9c-c279ad1596a6" />
<img width="1770" height="1798" alt="screencapture-file-Users-marjuqi-Downloads-siap-sim-html-2026-10-16-08_48_03" src="https://github.com/user-attachments/assets/13a1d825-220c-48cb-9b94-d0892f741522" />
<img width="1770" height="1798" alt="screencapture-file-Users-marjuqi-Downloads-siap-sim-html-2026-10-16-08_48_16" src="https://github.com/user-attachments/assets/f8b8f1bb-83e2-43ae-8856-c6efa1427b0d" />
<img width="1770" height="2008" alt="screencapture-file-Users-marjuqi-Downloads-siap-sim-html-2026-10-16-08_48_29" src="https://github.com/user-attachments/assets/0d60d36e-531d-4195-aa3b-b4e7dfffe475" />
<img width="1770" height="1966" alt="screencapture-file-Users-marjuqi-Downloads-siap-sim-html-2026-10-16-08_48_41" src="https://github.com/user-attachments/assets/323e4b10-ce18-4c14-8484-d65550f27fef" />
<img width="1770" height="2008" alt="screencapture-file-Users-marjuqi-Downloads-siap-sim-html-2026-10-16-08_48_58" src="https://github.com/user-attachments/assets/0205eea9-75df-470b-8f9f-97ff9537ffe2" />
<img width="1770" height="2052" alt="screencapture-file-Users-marjuqi-Downloads-siap-sim-html-2026-10-16-08_49_27" src="https://github.com/user-attachments/assets/411462ca-dd47-4f89-a715-5432f62b1640" />


# 🏍️🚗 Siap SIM

Aplikasi web untuk **berlatih pengetahuan dan pengambilan keputusan berlalu lintas** bagi calon pemohon SIM di Indonesia. Satu aplikasi untuk dua golongan SIM: **SIM C** (sepeda motor) dan **SIM A** (mobil). Aplikasi ini memadukan **kuis teori** (rambu, marka, aturan prioritas) dengan **simulasi interaktif** situasi jalan yang nyata sehari-hari, misalnya pindah lajur, putar balik, keluar gang, atau melewati zebra cross.

> ⚠️ **Penafian.** Proyek ini adalah alat belajar independen. Aplikasi ini **bukan** bagian dari sistem ujian resmi Polri dan **tidak menggantikan** ujian teori maupun praktik SIM yang sebenarnya. Isi soal dan aturan masih dalam tahap peninjauan (lihat [Status](#status)).

## Latar belakang

Ujian praktik SIM menguji keterampilan mengendalikan kendaraan, tetapi banyak kecelakaan terjadi karena **keputusan di jalan raya** yang keliru: tidak menengok bahu sebelum pindah lajur, menerobos keluar dari gang, atau memutar balik sembarangan. Aplikasi ini melatih bagian yang jarang dilatih itu: **mengamati, memberi isyarat, memberi jalan, dan menunggu celah yang aman.**

Target pengguna: semua pemegang KTP, terutama calon pemohon SIM yang belajar mandiri.

## Prinsip

- **Menilai proses, bukan hanya hasil.** Pindah lajur tanpa menengok bahu tetap dianggap salah walau tidak terjadi tabrakan, lengkap dengan penjelasan alasannya.
- **Ringan dan mudah dipakai.** Berjalan di peramban HP biasa tanpa perlu instal atau unduhan besar.
- **Tidak mengajarkan kebiasaan salah.** Kebiasaan di lapangan yang melanggar aturan tidak dijadikan "benar" hanya karena umum dilakukan.
- **Skenario mudah diubah.** Skenario SIM C dan SIM A disimpan sebagai data terpisah dari mesin simulasinya, sehingga bisa disesuaikan per golongan.

## Fitur

**Kuis teori**
- 30 soal umum yang berlaku untuk SIM A dan SIM C, semuanya ditampilkan dengan urutan acak
- Penjelasan setelah setiap jawaban
- Soal bergambar untuk rambu dan marka

**Simulasi keputusan (tampak atas, 2D)**

Di awal simulasi Anda memilih **SIM C (motor)** atau **SIM A (mobil)**, dan kendaraan serta skenarionya menyesuaikan. Kendaraan yang tertutup tidak terlihat sebelum Anda melihat ke arahnya. Anda mengatur sein, melihat kiri, kanan, atau belakang, memilih kecepatan (berhenti, pelan, normal), lalu memutuskan kapan jalan. Beberapa skenario dibagi dua tahap (mendekati dan berhenti dulu, lalu memutuskan melanjutkan), dan penilaian mencakup kecepatan saat mendekati, sein, serta melihat ulang tepat sebelum bergerak. Hasilnya berupa skor dan daftar langkah yang benar serta terlewat.

| Skenario | SIM C | SIM A |
|---|:-:|:-:|
| Pindah lajur | ✅ | ✅ |
| Putar balik di bukaan median | ✅ | ✅ |
| Keluar gang ke jalan raya | ✅ | ✅ |
| Mundur dari parkir minimarket | ✅ | ✅ |
| Belok kanan di perempatan | ✅ | ✅ |
| Ke lajur paling kanan untuk belok di pertigaan | ✅ | ✅ |
| Keluar dari parkir tepi jalan | | ✅ |
| Zebra cross dan pejalan kaki | | ✅ |
| Perlintasan kereta api | | ✅ |

Tampilan menyesuaikan mode terang dan gelap, dan dirancang untuk layar HP.
