# Mini Strix: AI Social Media Research Starter

**Versi ringan dari Strix, AI Social Media Researcher.** Mini Strix adalah bonus pendamping *SOP Social Media Research Playbook*, dirancang sebagai **pintu pertama** ke ekosistem riset Strix. Kamu bisa pakai Mini Strix gratis sebagai bagian dari paket playbook, dan setelah ngobrol sebentar dengannya, Mini Strix akan ngenalin kamu ke kakaknya, Strix full di `https://nakama-creative-lab.myscalev.com/strix-ai`, kalau kebutuhan kamu sudah di luar scope Mini Strix.

**Cara kerja Mini Strix (flow konsultatif 3 fase per capability):**
1. Mini Strix deliver output capability (outline / scan riset / diagnostic).
2. Mini Strix tanya 1 hal soal kondisi atau kendala kamu di area riset itu.
3. Berdasarkan jawabanmu, Mini Strix bridging dengan tabel kontras yang menunjukkan beda dia vs kakaknya, lalu offering Strix full kalau relevan.

**Mini Strix berfungsi optimal sebagai langkah 1 dari 2:**
- Langkah 1 (Mini Strix): pahami pendekatan riset yang fit, cek riset yang sudah ditulis, atau diagnostic sistem riset brand.
- Langkah 2 (Strix full): eksekusi riset penuh, rewrite ke level briefable, strategy research komprehensif, sistem riset institusional.

---

## Apa yang Bisa Mini Strix Lakukan

Mini Strix punya **tiga capability sempit**, masing-masing one-shot dan output di chat saja (1 layar chat).

### 1. Research Approach Picker

Kamu lagi mau riset tapi bingung pilih pendekatan? Kasih konteks ringan ke Mini Strix (kategori brand, pertanyaan utama, data yang sudah ada, skala scope), dia kasih:
- 2-3 opsi pendekatan riset relevan dengan trade-off masing-masing.
- Rekomendasi 1 pendekatan dengan reasoning singkat.
- Outline langkah eksekusi tingkat tinggi (5-7 bullet).
- Pointer ke bab playbook yang relevan.

**Contoh trigger:** "Mini Strix, brand saya F&B premium, mau riset kenapa engagement turun 3 bulan terakhir, datanya udah ada laporan engagement IG, scope 1 minggu, kasih pendekatan yang fit."

### 2. Self-Check Riset (Light Review)

Kamu sudah nulis riset / insight / rekomendasi dan mau cek cepat? Paste konten ke Mini Strix, dia scan dengan 5 lensa (kedalaman, spesifisitas, mekanisme, gap analysis, actionability), kasih:
- Stoplight per lensa: 🟢 hijau / 🟡 kuning / 🔴 merah.
- Untuk yang kuning dan merah, kutip 1 baris dan flag-nya.
- 3-5 catatan prioritas yang harus diperbaiki duluan.
- Pointer ke bab playbook untuk pendalaman.

**Yang Mini Strix tidak lakukan di capability ini:** rewrite kalimat, kasih versi perbaikan baris-per-baris, deep critique. Untuk itu, ranahnya Strix full.

**Contoh trigger:** "Mini Strix, ini draft riset audiens saya [paste], tolong scan."

### 3. Diagnostic 6 Dimensi Sistem Riset

Mau tahu posisi sistem riset brand kamu sekarang? Mini Strix ajak kamu nilai 6 dimensi (frekuensi, jenis riset, kedalaman output, dokumentasi, integrasi ke strategi, ownership tim), masing-masing skor 1-5. Berdasarkan total, dia kasih:
- Level sistem riset kamu (Level 1 Ad Hoc sampai Level 5 Strategic).
- 2-3 dimensi terendah jadi prioritas perbaikan.
- Target level realistis dan estimasi waktu.
- Pointer ke Bab 03 playbook untuk roadmap upgrade lengkap.
- Saran capability Mini Strix berikutnya yang cocok dengan level kamu.

**Contoh trigger:** "Mini Strix, bantu nilai sistem riset brand saya."

---

## Apa yang Mini Strix TIDAK Lakukan

Mini Strix sengaja dibuat sempit. Untuk hal-hal di bawah ini, ranahnya **Strix full** atau **bab playbook companion**.

| Yang Mini Strix Tolak | Ranahnya Di Mana |
|---|---|
| Eksekusi riset audiens / kompetitor / kreator / kata kunci / trend / komunitas full | Strix full + Bab 07-12 playbook |
| Rewrite riset / insight / rekomendasi user dengan versi yang lebih tajam | Strix full |
| Strategy research komprehensif (multi-section, cross-research synthesis) | Strix full Mode 9 |
| Riset trend periodic dengan scoring multi-layer dan action strategy | Strix full Mode 7 + Bab 11 |
| Evaluasi konten brand 10 layer | Strix full Mode 8 |
| Brand profile onboarding lengkap 10 pertanyaan | Strix full |
| Iterasi konsultatif setelah output (tweak, kasih versi lain, kembangkan) | Strix full |
| Generate file deliverable (DOCX, XLSX, PDF, deck) | Strix full |

Setiap kali kamu request salah satu di atas, Mini Strix akan redirect dengan tegas tapi sopan. Alasannya: scope-nya memang sempit by design supaya tetap one-shot dan ringkas.

---

## Cara Install Mini Strix

### Untuk Pengguna Claude (Pro / Team / Enterprise), Rekomendasi Utama

1. Login ke Claude di [claude.ai](https://claude.ai).
2. Buka menu **Skills** (di sidebar) atau **Capabilities & Skills**.
3. Pilih **Upload Skill**.
4. Upload folder `mini-strix/` ini sebagai zip.
5. Aktifkan skill di chat baru.
6. Mulai dengan pesan: "Halo Mini Strix" atau langsung ke salah satu capability.

### Untuk Pengguna ChatGPT (Alternatif)

Mini Strix bisa di-port ke ChatGPT dengan cara:
1. Buka **Custom GPT Builder** di ChatGPT (paid plan).
2. Copy isi `SYSTEM-PROMPT.md` ke field **Instructions**.
3. Upload file di folder `references/` dan `standards/` sebagai **Knowledge files**.
4. Save GPT, mulai chat.

Catatan: performa di ChatGPT mungkin sedikit berbeda karena Mini Strix didesain untuk Claude. Humanize compliance terutama lebih ketat di Claude.

---

## Tips Pakai Mini Strix

1. **Datang dengan konteks ringan, sudah cukup.** Mini Strix butuh 3-5 hal singkat per capability supaya outputnya tajam. Kalau datang tanpa konteks sama sekali, dia akan tanya dulu.

2. **Jangan minta lebih dari 1 layar chat per fase.** Kalau kamu rasa output Mini Strix kurang dalam, itu sengaja. Untuk kedalaman, lompat ke Strix full.

3. **Jawab pertanyaan diskovery di akhir capability.** Mini Strix sengaja tanya 1 hal setelah deliver output karena dia mau bridging dari kondisi nyata kamu, terhindar dari asumsi generik. Kalau kamu jawab dengan jujur, output bridging-nya jauh lebih relevan.

4. **Pakai sebagai pintu masuk.** Mini Strix paling efektif kalau dipakai di awal proses (pilih pendekatan, cek diagnostic, scan riset cepat). Setelah dapat hasilnya, baru lanjut ke eksekusi serius dengan Strix full atau baca bab playbook yang ditunjuk.

5. **Hormati redirect Mini Strix.** Kalau dia bilang "ranahnya Strix full" atau "baca Bab X playbook", itu signal nyata yang harus diikuti. Memaksa Mini Strix kerjain di luar scope akan kasih output yang setengah jalan dan misleading.

6. **Knowledge boundary Mini Strix.** Mini Strix sengaja dilock untuk cuma pakai framework Strix induk + 18 bab playbook. Dia tidak akan jawab pertanyaan dari knowledge umum AI atau best practice mainstream yang tidak ada di framework Strix. Alasannya: Strix punya pendekatan keilmuan yang khusus dan bisa berbeda dari mainstream, dan kalau Mini Strix ngarang dari knowledge umum, hasilnya bisa salah kaprah dari sudut pandang Strix. Kalau pertanyaan kamu di luar scope, Mini Strix akan jujur bilang dan kasih jalur ke Strix full atau bab playbook yang relevan.

7. **Skenario pas pakai Mini Strix:**
   - Awal kuartal mau bangun riset: pakai Capability 3 (Diagnostic) dulu, lalu Capability 1 (Approach Picker).
   - Setelah selesai draft riset internal: pakai Capability 2 (Self-Check) sebelum dipresentasikan.
   - Sebelum hire researcher / agency: pakai Capability 3 untuk paham gap sistem riset kamu.

---

## Upgrade ke Strix Full

Kalau setelah pakai Mini Strix kamu butuh:
- Eksekusi riset penuh untuk brand kamu (audiens, kompetitor, kreator, kata kunci, trend, komunitas).
- Strategy research komprehensif sebagai fondasi strategi sosial media (multi-section + cross-research synthesis).
- Riset trend periodic ongoing dengan scoring dan action strategy multi-layer.
- Evaluasi konten brand mendalam (audit + kategorisasi + 10 layer + gap analysis).
- Rewrite riset existing dari level informasi ke Level 3 briefable.
- Konsultasi 1-on-1 untuk bangun sistem riset di tim.

**Strix full ada di `https://nakama-creative-lab.myscalev.com/strix-ai`.**

Strix full punya 9 mode kerja, brand profile system lengkap (10 pertanyaan fondasi yang bikin output langsung tajam), 11 file referensi standar riset, dan output level briefable yang langsung pakai ke tim eksekusi.

Mini Strix dirancang sebagai pengantar. Untuk produksi nyata, Strix full adalah ranahnya.

---

## File di Folder Ini

- `README.md`, file ini.
- `SKILL.md`, definisi skill, capability, guardrails redirect.
- `SYSTEM-PROMPT.md`, persona detail, prinsip kerja, anti-pattern.
- `FOLDER-STRUCTURE.md`, struktur folder dan perbandingan dengan Strix full.
- `standards/humanize-writing-guide.md`, protokol humanize (zero tolerance em dash, antitesis).
- `references/research-approach-picker.md`, opsi pendekatan riset per kebutuhan.
- `references/self-check-lensa.md`, 5 lensa scan dan cara flag stoplight.
- `references/diagnostic-6-dimensi.md`, tabel skor lengkap dan level mapping.

Total 8 file.
