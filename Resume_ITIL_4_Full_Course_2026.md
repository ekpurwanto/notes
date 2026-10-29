# Resume ITIL 4 — Full Course 2026

> Catatan belajar berdasarkan transkrip video yang diberikan. Istilah teknis dipertahankan dalam bahasa Inggris agar mudah dipakai saat belajar ITSM dan persiapan sertifikasi.

## 1. Pengertian ITIL dan ITSM

**ITIL (Information Technology Infrastructure Library)** adalah framework best practices untuk mengelola layanan IT agar selaras dengan kebutuhan bisnis dan pelanggan.

**ITSM (IT Service Management)** adalah pendekatan untuk merencanakan, merancang, memberikan, mendukung, dan mengelola layanan IT.

### Tujuan ITIL
- Meningkatkan kualitas dan keandalan layanan IT.
- Mengurangi biaya operasional dan pemborosan sumber daya.
- Meningkatkan produktivitas dan kepuasan pelanggan.
- Mengelola risiko bisnis dan mengurangi dampak gangguan layanan.
- Memastikan layanan IT menciptakan **value** bagi pelanggan dan organisasi.

## 2. Evolusi ITIL

| Versi | Tahun | Fokus utama |
|---|---:|---|
| ITIL V1 | 1989 | Standardisasi pengelolaan layanan IT. |
| ITIL V2 | 2001 | Service Support dan Service Delivery. |
| ITIL V3 | 2007 | Pendekatan Service Lifecycle. |
| ITIL V3 update | 2011 | Penyempurnaan proses dan dokumentasi. |
| ITIL 4 | 2019 | Value creation, Service Value System, serta integrasi dengan Agile, Lean, dan DevOps. |

**Perbedaan penting:** ITIL V3 menonjolkan lima tahapan service lifecycle, sedangkan ITIL 4 menggunakan pendekatan lebih fleksibel dan terintegrasi untuk menciptakan nilai.

## 3. Empat Dimensi ITIL 4

Setiap layanan perlu dianalisis dari empat dimensi:

1. **Organizations and People** — struktur, budaya, peran, tanggung jawab, dan kompetensi orang-orang yang terlibat.
2. **Information and Technology** — data, pengetahuan, aplikasi, infrastruktur, server, jaringan, dan teknologi pendukung.
3. **Partners and Suppliers** — vendor, penyedia jaringan/cloud, kontraktor, dan mitra yang mendukung layanan.
4. **Value Streams and Processes** — rangkaian aktivitas dan prosedur yang mengubah kebutuhan menjadi layanan bernilai.

Keempat dimensi dipengaruhi faktor eksternal **PESTLE**:
- Political
- Economic
- Social
- Technological
- Legal
- Environmental

## 4. Service Value System (SVS)

**Service Value System** menjelaskan bagaimana komponen dan aktivitas organisasi bekerja bersama untuk mengubah peluang dan permintaan (*opportunity and demand*) menjadi nilai.

Komponen utama SVS:

1. **Guiding Principles**
2. **Governance**
3. **Service Value Chain**
4. **Practices**
5. **Continual Improvement**

### Tujuh Guiding Principles
1. **Focus on Value** — setiap aktivitas harus menghasilkan nilai bagi stakeholder.
2. **Start Where You Are** — evaluasi kondisi yang ada sebelum membuat perubahan.
3. **Progress Iteratively with Feedback** — kerjakan secara bertahap dan gunakan umpan balik.
4. **Collaborate and Promote Visibility** — libatkan stakeholder dan buat pekerjaan transparan.
5. **Think and Work Holistically** — lihat layanan sebagai satu kesatuan, bukan komponen terpisah.
6. **Keep It Simple and Practical** — gunakan langkah minimum yang efektif.
7. **Optimize and Automate** — optimalkan proses terlebih dahulu, lalu otomatisasi bila sesuai.

### Governance
Governance memastikan pengelolaan layanan tetap sesuai arah organisasi melalui:
- **Evaluate** — mengevaluasi kebutuhan, peluang, dan kinerja.
- **Direct** — menetapkan arah dan keputusan.
- **Monitor** — memantau hasil dan kesesuaian terhadap arah yang ditetapkan.

## 5. Service Value Chain

Service Value Chain adalah rangkaian aktivitas yang saling terhubung untuk merespons permintaan dan menghasilkan nilai.

Enam aktivitasnya:

1. **Plan** — menetapkan arah, prioritas, kebijakan, arsitektur, dan rencana.
2. **Improve** — mengidentifikasi serta menjalankan peningkatan.
3. **Engage** — memahami kebutuhan dan mengelola hubungan dengan stakeholder.
4. **Design and Transition** — merancang layanan dan memastikan layanan baru/berubah memenuhi kebutuhan kualitas, biaya, dan waktu.
5. **Obtain/Build** — memperoleh, membangun, dan menguji komponen layanan.
6. **Deliver and Support** — memberikan layanan, memantau operasional, mendukung pengguna, dan menangani gangguan.

Aktivitas tersebut tidak harus dijalankan secara linear; kombinasi aktivitas bergantung pada kebutuhan layanan.

## 6. Output, Outcome, dan Value

- **Output**: produk atau hasil langsung dari suatu aktivitas.
- **Outcome**: hasil atau dampak yang dirasakan pengguna setelah memakai output.
- **Value**: manfaat, kegunaan, atau nilai yang dipersepsikan stakeholder.

Contoh dari transkrip: album foto pernikahan adalah *output*; kepuasan pelanggan saat melihat foto yang jelas adalah *outcome*. Layanan dinilai berdasarkan manfaat yang benar-benar dirasakan, bukan sekadar fitur yang disediakan.

### Utility dan Warranty
- **Utility** (*fit for purpose*): fungsi atau kemampuan layanan untuk memenuhi kebutuhan.
- **Warranty** (*fit for use*): jaminan bahwa layanan memenuhi persyaratan penggunaan, terutama availability, capacity, security, dan continuity.

## 7. Management Practices

Transkrip menjelaskan bahwa ITIL 4 memiliki **34 management practices** dalam tiga kelompok:

- **General Management Practices** — praktik yang berlaku luas di organisasi, seperti information security management, relationship management, strategic management, portfolio management, architecture management, service financial management, workforce and talent management, continual improvement, measurement and reporting, risk management, knowledge management, organizational change management, project management, dan supplier management.
- **Service Management Practices** — praktik yang berfokus pada pengelolaan dan penyampaian layanan.
- **Technical Management Practices** — praktik yang berkaitan dengan pengelolaan teknologi.

ITIL 4 menggunakan istilah *practices* karena aktivitas pengelolaan saling berhubungan dan dapat diterapkan lintas tahap layanan, bukan terbatas pada satu tahap lifecycle.

## 8. Incident, Problem, Known Error, dan Service Request

| Istilah | Pengertian dan tujuan |
|---|---|
| **Incident** | Gangguan atau penurunan kualitas layanan yang perlu ditangani untuk memulihkan layanan normal secepat mungkin. |
| **Problem** | Penyebab atau potensi penyebab satu atau lebih incident. Fokusnya menemukan akar penyebab dan mengurangi kemungkinan kejadian berulang. |
| **Known Error** | Problem yang telah dianalisis tetapi belum sepenuhnya diselesaikan; informasi workaround atau solusi yang diketahui dapat didokumentasikan. |
| **Service Request** | Permintaan pengguna, misalnya informasi, saran, akses, atau layanan standar. |
| **Change Request** | Usulan formal untuk mengubah layanan, sistem, atau komponen yang perlu dinilai dan dikendalikan sesuai prosedur. |

### Incident Management
Tujuan utamanya memulihkan layanan secepat mungkin dan mengurangi dampak terhadap pengguna serta bisnis.

Alur umum:
1. Catat incident dan informasi dampaknya.
2. Klasifikasikan dan tentukan prioritas.
3. Lakukan diagnosis awal.
4. Gunakan knowledge base atau Known Error Database bila relevan.
5. Eskalasi ke tim yang tepat jika diperlukan.
6. Pulihkan layanan, konfirmasi hasil, dan tutup catatan incident.

### Problem Management
Berfokus pada penyebab dasar, bukan hanya memulihkan layanan saat kejadian.

Aktivitas yang disebutkan dalam materi meliputi:
- Problem identification.
- Problem control.
- Error control.
- Analisis tren incident untuk menemukan pola.
- Dokumentasi workaround dan solusi yang diketahui.

### Known Error Database (KEDB)
Repositori informasi known error beserta workaround atau solusi yang diketahui. Tim incident dapat merujuknya untuk mempercepat pemulihan layanan.

### Standard Change
Perubahan yang sudah dipraotorisasi, berisiko rendah, dan berdampak rendah, dengan prosedur yang telah ditetapkan. Materi membedakannya dari perubahan yang memerlukan penilaian dan persetujuan formal.

## 9. Service Desk dan Informasi Pendukung

**Service Desk** menjadi *single point of contact* bagi pengguna untuk melaporkan incident, mengajukan service request, atau menyampaikan pertanyaan.

Materi juga menyebut repositori informasi yang mendukung pengelolaan layanan:
- **Capacity Management Information System (CMIS)** — informasi penggunaan, kapasitas, dan performa infrastruktur.
- **Availability Management Information System** — data yang mendukung pengelolaan ketersediaan layanan.
- **Known Error Database (KEDB)** — known error beserta workaround atau solusi yang diketahui.

Informasi harus tetap akurat, relevan, mutakhir, dan dapat digunakan oleh tim yang membutuhkan.

## 10. Deployment Management dan Continual Improvement

### Deployment Management
Memindahkan komponen baru atau yang berubah—seperti hardware, software, dokumentasi, atau proses—ke lingkungan yang dituju. Materi membedakannya dari **Release Management**, yang berfokus pada perencanaan dan penjadwalan release.

### Continual Improvement
Peningkatan dilakukan terus-menerus berdasarkan pengukuran, evaluasi, dan feedback.

Pertanyaan model peningkatan yang disebutkan dalam materi:
1. What is the vision?
2. Where are we now?
3. Where do we want to be?
4. How do we get there?
5. Did we get there?
6. How do we keep the momentum going?

Siklusnya memerlukan tindakan di antara pertanyaan-pertanyaan tersebut. Kinerja yang diukur dapat mencakup layanan, komponen, configuration items (CIs), teknologi, orang, dan proses.

## 11. Manfaat ITIL 4

Menurut materi, penerapan ITIL dapat membantu organisasi:
- Menekan biaya dan meningkatkan pemanfaatan sumber daya.
- Meningkatkan konsistensi serta keandalan layanan.
- Memperbaiki pengelolaan risiko dan gangguan.
- Meningkatkan kepuasan pengguna.
- Menyelaraskan investasi IT dengan tujuan bisnis.
- Mendukung kolaborasi, perubahan, dan perbaikan berkelanjutan.

ITIL dapat disesuaikan dengan skala dan kebutuhan organisasi; bukan berarti semua praktik harus diterapkan dengan cara yang sama di setiap tempat.

## 12. Sertifikasi ITIL

Transkrip memperkenalkan sertifikasi Foundation sebagai level awal dan menyebut jalur lanjutan seperti Practitioner, Intermediate, Expert, dan Master. Nama jalur tersebut mengikuti penjelasan dalam video; skema sertifikasi dapat berubah, sehingga persyaratan ujian terkini perlu diperiksa pada penyelenggara sertifikasi resmi.

## 13. Contoh Penerapan untuk IT Support / System Engineer / NOC

**Kasus: server aplikasi tidak dapat diakses.**

1. Pengguna melapor melalui Service Desk.
2. Tim mencatat incident, dampak, dan prioritas.
3. Engineer memeriksa monitoring, konektivitas, resource server, dan log.
4. Jika ada workaround di KEDB, tim menggunakannya bila sesuai.
5. Layanan dipulihkan dan hasil dikonfirmasi.
6. Jika akar penyebab belum diketahui atau berpotensi berulang, Problem Management melakukan analisis lanjutan.
7. Jika dibutuhkan perubahan konfigurasi, perubahan diproses melalui mekanisme Change Control yang sesuai.
8. Setelah kejadian, tim meninjau data incident, waktu pemulihan, dan peluang perbaikan.

Pembedaan yang penting:
- **Incident Management:** memulihkan layanan.
- **Problem Management:** memahami dan mengatasi penyebab.
- **Change Control:** menilai dan mengendalikan perubahan.
- **Continual Improvement:** meningkatkan layanan dan proses berdasarkan bukti.

## 14. Ringkasan Hafalan Cepat

- **ITIL** = framework best practices untuk ITSM.
- **4 Dimensions** = Organizations and People; Information and Technology; Partners and Suppliers; Value Streams and Processes.
- **SVS** = Guiding Principles + Governance + Service Value Chain + Practices + Continual Improvement.
- **7 Guiding Principles** = Focus on Value; Start Where You Are; Progress Iteratively with Feedback; Collaborate and Promote Visibility; Think and Work Holistically; Keep It Simple and Practical; Optimize and Automate.
- **6 Service Value Chain activities** = Plan; Improve; Engage; Design and Transition; Obtain/Build; Deliver and Support.
- **Output** = hasil langsung; **Outcome** = dampak; **Value** = manfaat yang dirasakan.
- **Utility** = fit for purpose; **Warranty** = fit for use.
- **Incident** = gangguan; **Problem** = penyebab; **Known Error** = problem yang sudah dianalisis tetapi belum terselesaikan sepenuhnya.
- **Service Desk** = single point of contact.
- **Continual Improvement** = pengukuran, evaluasi, tindakan, dan feedback berulang.

---
**Catatan:** Resume ini merangkum isi transkrip yang tersedia dan mempertahankan istilah yang digunakan sumber. Ini adalah catatan belajar, bukan pengganti silabus resmi atau materi ujian terbaru.
