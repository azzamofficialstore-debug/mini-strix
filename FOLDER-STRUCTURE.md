# Folder Structure Mini Strix

## Visual Tree

```
mini-strix/
├── README.md                          # Onboarding pembeli playbook
├── SKILL.md                           # Definisi skill + 3 capability + guardrails redirect
├── SYSTEM-PROMPT.md                   # Persona detail + prinsip kerja + anti-pattern
├── FOLDER-STRUCTURE.md                # File ini
├── standards/
│   └── humanize-writing-guide.md      # Protokol humanize zero tolerance (copy persis dari Strix full)
└── references/
    ├── research-approach-picker.md    # Capability 1: opsi pendekatan + outline langkah
    ├── self-check-lensa.md            # Capability 2: 5 lensa scan + cara flag stoplight
    └── diagnostic-6-dimensi.md        # Capability 3: tabel skor 6 dimensi + level mapping
```

**Total: 8 file.** Tidak lebih, tidak kurang. Disiplin scope berarti disiplin file.

---

## Konstanta Upsell, Tersebar di Semua File

**Link Strix full:** `https://nakama-creative-lab.myscalev.com/strix-ai`

Link ini muncul di semua file yang berhubungan dengan output user. File yang mengandung link:
- `SKILL.md` (konstanta upsell + 9 baris di tabel guardrails redirect + template sapaan + capability descriptions).
- `SYSTEM-PROMPT.md` (konstanta upsell + 3 mode kerja flow 3 fase + anti-pattern 6+7 + section hubungan Strix full).
- `README.md` (header + tips + section upgrade).
- `references/research-approach-picker.md` (template diskovery + template bridging + tabel kontras).
- `references/self-check-lensa.md` (template diskovery + template bridging conditional + tabel kontras).
- `references/diagnostic-6-dimensi.md` (template diskovery + template bridging per level + tabel kontras + special case).

Kalau link Strix full berubah di kemudian hari, find-replace `https://nakama-creative-lab.myscalev.com/strix-ai` di seluruh folder akan tuntas.

---

## Filosofi Interaksi: Tripwire Konsultatif (Flow 3 Fase)

Mini Strix tidak langsung upsell setelah deliver output. Tiap capability punya flow 3 fase:

**Fase 1: Deliver output capability** (sesuai struktur capability masing-masing).

**Fase 2: Closing diskovery** (1 pertanyaan open-ended tentang kondisi atau kendala user di area riset yang relevan dengan capability). Mini Strix STOP setelah tanya, tunggu user jawab.

**Fase 3: Bridging konsultatif + tabel kontras + offering** (setelah user jawab). Mini Strix acknowledge jawaban, hubungkan kendala user dengan kapabilitas Strix full dengan tone "kakak ngenalin adik", tampilkan tabel kontras spesifik untuk capability ini, lalu offering ke Strix full + link.

Pendekatan ini bikin upsell terasa **respon natural** dari obrolan dengan user, jauh dari kesan iklan template di akhir output.

---

## Knowledge Discipline: Cuma Pakai Framework Strix + Playbook

Mini Strix punya batasan keilmuan tegas:
- **HARUS** pakai knowledge dari framework Strix induk + 18 bab playbook + file referensi internal Mini Strix.
- **TIDAK BOLEH** ambil dari pengetahuan umum AI, blog post, framework non-Strix populer (AIDA, PAS, AARRR funnel, RACE, dll), atau best practice industri mainstream.

Alasan: Strix punya pendekatan keilmuan yang berbeda atau bahkan bertentangan dengan mainstream. Kalau Mini Strix ngarang dari knowledge umum, user bisa dapat saran yang merusak integritas keilmuan Strix.

Kalau user tanya hal di luar framework, Mini Strix jujur bilang dan offering ke Strix full.

---

## Perbandingan dengan Strix Full

### File yang Sama Persis (Inheritance)

Hanya satu file di-copy persis dari Strix full ke Mini Strix:

| File | Lokasi di Strix Full | Lokasi di Mini Strix |
|---|---|---|
| Humanize Writing Guide | `standards/_FINAL-AI-humanize-writing-guide.md` | `standards/humanize-writing-guide.md` |

Alasan: protokol humanize (zero tolerance em dash, antitesis) berlaku universal di semua output, tidak ada versi ringan untuk humanize.

### File yang Diturunkan (Subset / Simplified)

File-file ini di Mini Strix adalah subset ringkas dari file Strix full yang lebih lengkap:

| Mini Strix File | Sumber di Strix Full | Cara Disederhanakan |
|---|---|---|
| `references/research-approach-picker.md` | `frameworks/data-to-insight-framework.md` + 5 standar riset (`standards/standar-riset-*.md`) + `references/strategy-research-structure.md` | Diambil hanya 9 opsi pendekatan dengan kapan-cocok + trade-off, tanpa metodologi detail per jenis riset. |
| `references/self-check-lensa.md` | `frameworks/evaluasi-review-checklist.md` + `standards/standar-penulisan-insight.md` + `standards/standar-penulisan-rekomendasi.md` + `standards/anti-generik-rules.md` | Diambil 5 lensa inti (kedalaman, spesifisitas, mekanisme, gap, actionability), tanpa template feedback dengan rewrite. |
| `references/diagnostic-6-dimensi.md` | Bab 03 playbook (Self-Assessment) | Diambil 6 dimensi + tabel skor + level mapping, tanpa roadmap upgrade detail multi-bulan. |
| `SKILL.md` | `SKILL.md` Strix full | Diciutkan dari 9 mode kerja jadi 3 capability sempit, no Brand Profile system. |
| `SYSTEM-PROMPT.md` | `SYSTEM-PROMPT.md` Strix full | Diciutkan dari 17 prinsip jadi 5 prinsip + 6 anti-pattern eksplisit. |

### File Eksklusif Mini Strix (Tidak Ada di Strix Full)

Tidak ada. Semua file Mini Strix adalah turunan dari Strix full atau playbook companion. Ini sengaja, untuk pertahankan konsistensi cara berpikir.

### File Strix Full yang TIDAK Diturunkan ke Mini Strix

File-file ini ada di Strix full tapi sengaja **tidak** dibawa ke Mini Strix:

| File Strix Full | Alasan Tidak Diturunkan |
|---|---|
| `standards/standar-riset-audiens.md` | Eksekusi riset audiens di luar scope Mini Strix. |
| `standards/standar-riset-kompetitor.md` | Eksekusi riset kompetitor di luar scope. |
| `standards/standar-riset-kreator.md` | Eksekusi riset kreator di luar scope. |
| `standards/standar-riset-kata-kunci.md` | Eksekusi riset kata kunci di luar scope. |
| `standards/standar-riset-trend.md` | Eksekusi riset trend di luar scope. |
| `standards/standar-deskripsi-konten.md` | 10 layer deskripsi konten di luar scope. |
| `standards/standar-penulisan-insight.md` | Penulisan insight tajam di luar scope (Mini Strix cuma flag, tidak rewrite). |
| `standards/standar-penulisan-rekomendasi.md` | Rekomendasi Level 3 briefable di luar scope. |
| `standards/standar-evaluasi-konten.md` | Evaluasi konten brand di luar scope. |
| `standards/anti-generik-rules.md` | Diintegrasikan inline ke `references/self-check-lensa.md` Lensa 2 (Spesifisitas), tidak butuh file terpisah. |
| `frameworks/data-to-insight-framework.md` | Konsep diintegrasikan ke `references/self-check-lensa.md` Lensa 1 (Kedalaman). |
| `frameworks/pattern-recognition.md` | Pattern recognition lintas data di luar scope. |
| `frameworks/gap-analysis-framework.md` | Konsep diintegrasikan ke `references/self-check-lensa.md` Lensa 4 (Gap Analysis). |
| `references/case-pattern-library.md` | Library pola lintas kasus di luar scope. |
| `references/trend-research-structure.md` | Riset trend periodic di luar scope. |
| `references/strategy-research-structure.md` | Strategy research komprehensif di luar scope. |

Total: **16 file Strix full tidak diturunkan ke Mini Strix.** Ini gambaran nyata seberapa sempit scope Mini Strix dibanding Strix full.

---

## Perbandingan Volume

| Aspek | Strix Full | Mini Strix |
|---|---|---|
| Total file | 19 | 8 |
| Mode kerja / capability | 9 | 3 |
| File standar riset | 5 (per jenis) | 0 |
| File framework analitis | 4 | 0 |
| File reference besar | 3 | 3 (subset) |
| Brand Profile onboarding | 10 pertanyaan, wajib | 3-5 hal singkat per capability |
| Output deliverable | Laporan multi-section + file | Chat 1 layar |
| Iterasi konsultatif | Ya, multi-mode dalam 1 session | Tidak, one-shot per capability |

Mini Strix kira-kira **40% volume file** Strix full dengan **30% capability**, dan output deliverable **maksimal 5% volume** laporan Strix full.

Pembagian ini membuat:
- Mini Strix tetap kerja dengan disiplin Strix (humanize, anti-generik, anchor playbook).
- Strix full tetap punya value pembeda yang jelas (kedalaman + brand profile + laporan + iterasi konsultatif).
- Tidak ada kanibalisasi yang signifikan.
