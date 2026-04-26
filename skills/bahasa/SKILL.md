# Bahasa - Bahasa Indonesia Language Helper Skill

<!--
  last_verified: 2026-04-27
  effective_date: 2026-01-01
  source_url: https://ejaan.kemdikbud.go.id
  review_schedule: yearly (rates/thresholds may change)
  maintainer: satryayogapratama@gmail.com
-->

Formal/informal language detection, translation between formal and casual Bahasa, EYD checking, and abbreviation guides.

## Overview

This skill assists users with Indonesian language matters:
- Detecting formal vs informal language register
- Converting between formal Bahasa Indonesia and casual/gaul language
- Checking spelling (EYD - Ejaan Yang Disempurnakan)
- Explaining common abbreviations and acronyms

## Capabilities

### 1. Formal/Informal Language Detection

Analyze text and determine language register (formal, informal, or casual).

**Formal (Bahasa Baku)**
- Used in: Official documents, business, presentations, news
- Characteristics: Complete sentences, formal pronouns, proper grammar

**Informal (Bahasa Santai)**
- Used in: Casual conversations, social media, chat
- Characteristics: Contractions, friendly tone, relaxed grammar

**Casual/Gaul (Bahasa Gaul)**
- Used in: Very casual settings, youth communication, slang
- Characteristics: Slang, abbreviations, playful language

### 2. Formal to Casual Conversion

Transform formal text into casual/gaul language for social media and informal communication.

### 3. Casual to Formal Conversion

Improve casual text for professional use, presentations, and official documents.

### 4. EYD Spelling Checker

Check spelling according to EYD (Ejaan Yang Disempurnakan - Enhanced Spelling Rules):
- Identify spelling errors
- Suggest corrections
- Explain common mistakes

### 5. Abbreviations Guide

Explain common Indonesian abbreviations and acronyms:
- Formal abbreviations (dst, dkk, dll)
- Institutional abbreviations (KTP, NPwp, etc.)
- Modern abbreviations (TKA, WNI, etc.)

## Language Registers

### Formal Register (BAKU)

**Characteristics:**
- Complete sentences with proper structure
- Formal pronouns: Saya, Anda (not gue, elo, lo)
- No contractions
- Proper punctuation
- Subject-Verb-Object word order

**Example:**
```
"Saya dengan hormat meminta informasi mengenai produk Anda 
yang berkualitas tinggi. Bisakah Anda memberikan penjelasan 
lebih detail?"
```

### Informal Register (SANTAI)

**Characteristics:**
- Can drop subjects
- Mix of formal and casual
- Some contractions possible
- Relaxed punctuation
- More natural flow

**Example:**
```
"Mau tanya dong tentang produk lu. Bisa kasih penjelasan 
yang lebih detail nggak?"
```

### Casual/Gaul Register (GAUL)

**Characteristics:**
- Heavy use of slang
- Abbreviations and acronyms
- Dropped grammatical elements
- Playful tone
- Emoticons often included

**Example:**
```
"Eh bro, produk lu gmn sih? Kasih info dong, yg jelas2 ya!"
```

## EYD Rules

### Common Spelling Rules

1. **Prefixes (Awalan)**
   - "me-" used before most verbs: menulis, makan, melompat
   - "ber-" for plural or reciprocal: berjalan, bermain
   - "pe-" for agent: penulis, pemain

2. **Suffixes (Akhiran)**
   - "-kan" for transitive verbs: lihat → lihatkan (show)
   - "-i" for locative: mandi → mandikan (bathe someone)
   - "-an" for noun formation: main → mainan (toy)

3. **Consonant Doubling**
   - Keep single consonant after short vowel
   - But "tt", "ss", "kk" are rare in Indonesian

4. **Common Mistakes**
   - "mau" (want) ≠ "mo" (gaul)
   - "tidak" (not) ≠ "ndak" (gaul)
   - "kenapa" (why) ≠ "knapa" (incorrect spelling)

5. **Capital Letters**
   - Start of sentences
   - Proper nouns (names, places)
   - Names of months, days
   - Acronyms: KTP, BPJS, DJP

### Common EYD Errors

| Error | Correct | Explanation |
|-------|---------|------------|
| gw | saya | Avoid slang in formal writing |
| lo | Anda | Use formal "you" |
| ndak | tidak | Proper spelling |
| yg | yang | Avoid abbreviations |
| u | Anda | Full word required |
| mau | mau | Correct, but "ingin" is more formal |

## Common Abbreviations

### Formal Abbreviations

| Abbr | Stands For | Meaning | Example |
|------|-----------|---------|---------|
| dst | dan seterusnya | and so on | Apel, jeruk, mangga, dst. |
| dkk | dan kawan-kawan | and colleagues | Sukarno, dkk. |
| dll | dan lain-lain | and others | Buku, pensil, dll. |
| et al | et alii (Latin) | and others (academic) | Smith et al. (2020) |

### Institution Abbreviations

| Abbr | Full Form | Translation |
|------|-----------|------------|
| KTP | Kartu Tanda Penduduk | National ID Card |
| NPWP | Nomor Pokok Wajib Pajak | Tax ID Number |
| NIK | Nomor Induk Kependudukan | National ID Number |
| BPJS | Badan Penyelenggara Jaminan Sosial | Social Security Agency |
| DJP | Direktorat Jenderal Pajak | Tax Directorate |
| BPN | Badan Pertanahan Nasional | National Land Agency |

### Modern Abbreviations

| Abbr | Indonesian | Translation |
|------|-----------|------------|
| TKA | Tenaga Kerja Asing | Foreign Worker |
| WNI | Warga Negara Indonesia | Indonesian Citizen |
| WNA | Warga Negara Asing | Foreign Citizen |
| DT | Daerah Tertinggal | Disadvantaged Area |
| UMKM | Usaha Mikro Kecil Menengah | Small Business |

### Reference Abbreviations

| Abbr | Meaning | Usage |
|------|---------|-------|
| hlm | halaman | page |
| no | nomor | number |
| ed | edisi | edition |
| jil | jilid | volume |
| vol | volume | volume |
| thn | tahun | year |

## Pronoun Guide

### Formal Pronouns

- **Saya** - I (formal, respectful)
- **Kami** - We (exclusive, formal)
- **Anda** - You (formal, singular)
- **Dia** - He/She (formal)
- **Mereka** - They (formal)

### Informal Pronouns

- **Aku** - I (intimate)
- **Kita** - We (inclusive)
- **Kamu** - You (familiar)
- **Dia** - He/She (common)
- **Mereka** - They (common)

### Casual/Gaul Pronouns

- **Gue/Gw** - I (very casual)
- **Elu/Lo** - You (very casual)
- **Dia** - He/She (all registers)
- **Mereka** - They (all registers)

## Examples

### Example 1: Register Detection
```
User: Deteksi level formalitas teks ini: "Gimana kabar lo?"

Bot: ANALISIS REGISTER BAHASA:
     
     Teks: "Gimana kabar lo?"
     
     Register Terdeteksi: CASUAL/GAUL
     
     Alasan:
     - "Gimana" = kontraksi dari "bagaimana" (casual)
     - "lo" = pronoun gaul untuk "kamu/Anda"
     - Struktur kalimat informal
     
     Saran penggunaan:
     - Chat/WhatsApp ✓ (cocok)
     - Email profesional ✗ (tidak cocok)
     - Presentasi bisnis ✗ (tidak cocok)
```

### Example 2: Formal to Casual Conversion
```
User: Ubah ke bahasa gaul:
      "Saya dengan hormat meminta bantuan Anda 
       untuk menyelesaikan proyek ini."

Bot: KONVERSI FORMAL → GAUL:
     
     FORMAL (BAKU):
     "Saya dengan hormat meminta bantuan Anda 
      untuk menyelesaikan proyek ini."
     
     CASUAL (SANTAI):
     "Tolong bantu gue dong untuk selesain proyek ini."
     
     GAUL (VERY CASUAL):
     "Eh, bisa bantu gw selesain proyek ini nggak?"
     
     Tingkat informalitas:
     Formal ─────── Santai ─────── Gaul
```

### Example 3: EYD Spelling Check
```
User: Cek EYD: "kami mau mlakukan survey di 5 kota yg brbeda"

Bot: PEMERIKSAAN EYD:
     
     ✗ mau → ACCEPTABLE (informal)
     ✗ mlakukan → SALAH (seharusnya "melakukan")
     ✗ survey → ACCEPTABLE (loanword, also: survei)
     ✗ yg → SALAH (singkatan, seharusnya "yang")
     ✗ brbeda → SALAH (seharusnya "berbeda")
     
     KALIMAT YANG BENAR (BAKU):
     "Kami akan melakukan survei di 5 kota yang berbeda."
     
     KALIMAT SANTAI (ACCEPTABLE):
     "Kami mau melakukan survey di 5 kota yang beda."
```

### Example 4: Abbreviation Explanation
```
User: Apa arti "dst" dan "dll"? Bedanya apa?

Bot: PENJELASAN SINGKATAN:
     
     DST (dan seterusnya):
     - Untuk melanjutkan deret/urutan
     - Contoh: "Hari Senin, Selasa, Rabu, dst."
     - Lebih akademik, teratur
     
     DLL (dan lain-lain):
     - Untuk item yang tidak berurutan
     - Contoh: "Buku, pensil, penghapus, dll."
     - Lebih umum, casual
     
     PERBEDAAN:
     - dst = untuk urutan/seri
     - dll = untuk daftar umum
     
     BONUS:
     - dkk = dan kawan-kawan (untuk orang)
       Contoh: "Sukarno, Hatta, dkk."
```

### Example 5: Casual to Formal Conversion
```
User: Ubah jadi formal:
      "Halo bro! Gue pengen tanya soal harga produk lu"

Bot: KONVERSI GAUL → FORMAL:
     
     CASUAL/GAUL:
     "Halo bro! Gue pengen tanya soal harga produk lu"
     
     FORMAL (BAKU):
     "Selamat pagi. Dengan hormat, saya ingin menanyakan 
      informasi mengenai harga produk Anda."
     
     PERUBAHAN:
     - Halo → Selamat pagi
     - bro → (dihapus)
     - Gue → Saya
     - pengen → ingin
     - tanya → menanyakan
     - soal → mengenai
     - harga produk lu → harga produk Anda
     
     SARAN PENGGUNAAN:
     - Formal: Email, surat resmi, proposal
     - Casual: Chat, media sosial, percakapan santai
```

## Integration with Other Skills

- **pajak**: Formal abbreviations for tax documents
- **bpjs**: Health terminology and official abbreviations
- **rupiah**: Currency and numerical notation in Indonesian
- **wilayah**: Regional dialect variations and place names

## Resources

- Kamus Besar Bahasa Indonesia (KBBI): kbbi.web.id
- EYD Guide: Official Indonesian spelling rules
- Pusat Bahasa: Language center resources
- Indonesian Grammar: Tata Bahasa Indonesia Baku

## Important Notes

- EYD is the official standard for formal Indonesian
- Casual/gaul is acceptable in informal contexts but not in professional writing
- Modern Indonesian uses many loanwords (from English, Arabic, Dutch)
- Regional dialects exist but don't replace standard Indonesian
- Abbreviations should match formality level of text

---

**Last Updated:** 2026
**Reference:** Pedoman Umum Ejaan Bahasa Indonesia yang Disempurnakan (PUEBI)
