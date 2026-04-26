# Wilayah - Indonesian Geography Helper Skill

<!--
  last_verified: 2026-04-27
  effective_date: 2026-01-01
  source_url: https://www.kemendagri.go.id
  review_schedule: yearly (rates/thresholds may change)
  maintainer: satryayogapratama@gmail.com
-->

Geographic and administrative information for Indonesia, including provinces, districts, timezones, postal codes, and address formatting.

## Overview

Wilayah skill provides geographic and administrative assistance for Indonesian users:
- Province (Provinsi) and district (Kabupaten/Kota) data
- Indonesian timezone information (WIB, WITA, WIT)
- Postal code (Kode Pos) database
- Standard Indonesian address formatting
- Regional capital cities
- Geographic area codes

## Capabilities

### 1. Province and District Information

Retrieve data on Indonesia's 34 provinces and 500+ districts/municipalities.

**Provinces Include:**
- Aceh, Bali, Bangka Belitung, Banten
- Bengkulu, DI Yogyakarta, DKI Jakarta
- Gorontalo, Jambi, Jawa Barat, Jawa Tengah, Jawa Timur
- Kalimantan Barat, Kalimantan Selatan, Kalimantan Tengah, Kalimantan Timur, Kalimantan Utara
- Kepulauan Riau, Lampung, Maluku, Maluku Utara
- Nusa Tenggara Barat, Nusa Tenggara Timur
- Papua, Papua Barat, Papua Barat Daya, Papua Tengah, Papua Pegunungan, Papua Selatan
- Riau, Sulawesi Barat, Sulawesi Selatan, Sulawesi Tengah, Sulawesi Tenggara, Sulawesi Utara
- Sumatera Barat, Sumatera Selatan, Sumatera Utara

### 2. Timezone Information

Indonesia spans three main timezones:

**WIB (Waktu Indonesia Barat - Western Indonesian Time)**
- UTC+7
- Covers: Sumatra, Java, Madura, West/South Kalimantan
- Major cities: Jakarta, Bandung, Surabaya

**WITA (Waktu Indonesia Tengah - Central Indonesian Time)**
- UTC+8
- Covers: Sulawesi, Bali, East Kalimantan, West Nusa Tenggara
- Major cities: Makassar, Denpasar

**WIT (Waktu Indonesia Timur - Eastern Indonesian Time)**
- UTC+9
- Covers: Maluku, Papua
- Major cities: Jayapura, Ambon

### 3. Postal Code System

Indonesian postal code (Kode Pos) structure:
- 5-digit number
- Format: XXXXX
- First digit: Province
- Next digits: District → Sub-district → Area

### 4. Address Formatting

Standard Indonesian address structure.

### 5. Regional Information

Capital cities, population, area, and regional characteristics.

## Indonesian Provinces (34)

### Sumatra Region (6 Provinces)

| No | Province | Capital | Timezone | Notable |
|----|----------|---------|----------|---------|
| 1 | Aceh | Banda Aceh | WIB | Northernmost |
| 2 | Riau | Pekanbaru | WIB | Oil & gas |
| 3 | Sumatera Barat | Padang | WIB | Coffee producer |
| 4 | Sumatera Utara | Medan | WIB | Large population |
| 5 | Jambi | Jambi | WIB | Mineral rich |
| 6 | Bengkulu | Bengkulu | WIB | Tourism |

### Java Region (7 Provinces + Special Capital)

| No | Province | Capital | Timezone | Notable |
|----|----------|---------|----------|---------|
| 1 | DKI Jakarta | Jakarta | WIB | National capital |
| 2 | Banten | Serang | WIB | Industrial |
| 3 | Jawa Barat | Bandung | WIB | Highest pop. |
| 4 | DI Yogyakarta | Yogyakarta | WIB | Cultural center |
| 5 | Jawa Tengah | Semarang | WIB | Cultural heritage |
| 6 | Jawa Timur | Surabaya | WIB | Industrial |

### Kalimantan Region (5 Provinces)

| Province | Capital | Timezone |
|----------|---------|----------|
| Kalimantan Barat | Pontianak | WIB |
| Kalimantan Selatan | Banjarmasin | WITA |
| Kalimantan Tengah | Palangkaraya | WITA |
| Kalimantan Timur | Samarinda | WITA |
| Kalimantan Utara | Tanjung Selor | WITA |

### Sulawesi & Eastern Islands (7 Provinces)

| Province | Capital | Timezone |
|----------|---------|----------|
| Sulawesi Utara | Manado | WITA |
| Sulawesi Barat | Manado | WITA |
| Sulawesi Tengah | Palu | WITA |
| Sulawesi Selatan | Makassar | WITA |
| Sulawesi Tenggara | Kendari | WITA |
| Gorontalo | Gorontalo | WITA |
| Maluku | Ambon | WIT |

### Eastern Region (7 Provinces)

| Province | Capital | Timezone | Notes |
|----------|---------|----------|-------|
| Bali | Denpasar | WITA | Tourism |
| Nusa Tenggara Barat | Mataram | WITA | Tourist islands |
| Nusa Tenggara Timur | Kupang | WITA | Remote |
| Maluku Utara | Ternate | WITA | Historic |
| Papua | Jayapura | WIT | Largest area |
| Papua Barat | Manokwari | WIT | Development |
| Papua Tengah | Nabire | WIT | New province |

## Timezone Details

### WIB (UTC+7)

**Coverage Area:**
- Sumatra (all provinces)
- Java (all provinces)
- Madura
- Kalimantan (west and south regions)
- Brunei
- Malaysia (partial)

**Major Cities:**
- Jakarta, Bandung, Semarang, Surabaya
- Medan, Palembang, Yogyakarta, Bandung

**Business Hours (Typical):**
- Office: 08:00-17:00 WIB (lunch 12:00-13:00)
- Shopping: 10:00-22:00 WIB (malls)

### WITA (UTC+8)

**Coverage Area:**
- Sulawesi (all provinces)
- Bali
- East Kalimantan
- West Kalimantan (partially)
- West Nusa Tenggara
- East Nusa Tenggara (partially)

**Major Cities:**
- Makassar, Manado, Denpasar, Palu, Kendari

**Business Hours (Typical):**
- Office: 08:00-17:00 WITA
- Similar to WIB + 1 hour

### WIT (UTC+9)

**Coverage Area:**
- Maluku
- Papua (all regions)

**Major Cities:**
- Jayapura, Ambon

**Business Hours (Typical):**
- Office: 08:00-17:00 WIT
- Similar to WIB + 2 hours

## Postal Code Structure

### 5-Digit Format

```
X X X X X
│ │ │ │ │
└─┘ └─┘ │
  │     └─ Sub-district/Area (2 digits)
  │        Range: 00-99
  └─ District (2 digits)
     Range: 00-99
└─ Province (1 digit)
   0=Central Java, 1=E. Java, 2=Yogyakarta, etc.
```

### Example Postal Codes

| City | Postal Code | Breakdown |
|------|-------------|-----------|
| Jakarta | 12345 | 1=Jakarta, 23=Senayan, 45=Area |
| Surabaya | 60123 | 6=E. Java, 01=Surabaya, 23=Area |
| Yogyakarta | 55142 | 5=Yogyakarta, 51=District, 42=Area |

### Finding Postal Codes

- **Pos Indonesia Website**: posindonesia.co.id
- **Search by address**: Use postal code lookup
- **Mobile app**: POS Mobile
- **Or ask locally**: Kantor Pos terdekat (nearest post office)

## Standard Indonesian Address Format

### Formal Address Structure

```
[Nama Penerima]
[Nama Jalan] No. [Nomor]
RT [Number]/RW [Number]
[Kelurahan/Desa]
[Kecamatan] [Kabupaten/Kota]
[Provinsi] [Kode Pos]
[Negara] (optional for domestic)
```

### Example Address

```
Budi Santoso
Jalan Sudirman No. 45
RT 03/RW 07
Kelurahan Senayan
Kecamatan Kebayoran Baru
Kota Administrasi Jakarta Selatan
DKI Jakarta 12190
Indonesia
```

### Address Components Explained

- **Nama Penerima**: Recipient's full name
- **Jalan**: Street name (Jl. = abbreviation)
- **No.**: Street number
- **RT/RW**: Neighborhood unit (Rukun Tetangga / Rukun Warga)
  - RT: Smallest unit (typically 30-50 houses)
  - RW: Larger unit (typically 3-5 RTs)
- **Kelurahan/Desa**: Village/neighborhood name
  - Kelurahan: Urban village
  - Desa: Rural village
- **Kecamatan**: Sub-district
- **Kabupaten/Kota**: District/City
- **Provinsi**: Province
- **Kode Pos**: Postal code

## Area Codes and Phone System

### Indonesia Phone Structure

**Format:**
```
+62 [Area Code] [Local Number]
```

**Example:**
```
+62-21-XXXX-XXXX (Jakarta)
+62-31-XXXX-XXXX (Surabaya)
```

### Major Area Codes (Kode Area)

| City | Area Code | Province |
|------|-----------|----------|
| Jakarta | 21 | DKI Jakarta |
| Bandung | 22 | Jawa Barat |
| Semarang | 24 | Jawa Tengah |
| Yogyakarta | 274 | DI Yogyakarta |
| Surabaya | 31 | Jawa Timur |
| Medan | 61 | Sumatera Utara |
| Makassar | 411 | Sulawesi Selatan |
| Denpasar | 361 | Bali |

## Examples

### Example 1: Province Information
```
User: Berapa banyak kabupaten di Jawa Timur?

Bot: INFORMASI JAWA TIMUR:
     
     Ibu Kota: Surabaya
     Timezone: WIB (UTC+7)
     
     KABUPATEN & KOTA (36):
     
     Kabupaten (29):
     - Pacitan, Ponorogo, Trenggalek, Tulungagung
     - Blitar, Kediri, Malang, Lumajang, Jember
     - Banyuwangi, Bondowoso, Situbondo, Probolinggo
     - Pasuruan, Sidoarjo, Mojokerto, Jombang, Nganjuk
     - Madiun, Magetan, Ngawi, Bojonegoro, Tuban
     - Lamongan, Gresik, Bangkalan, Sampang, Pamekasan
     - Sumenep
     
     Kota (7):
     - Surabaya, Batu, Blitar, Kediri, Malang
     - Mojokerto, Pasuruan
     
     TOTAL: 36 kabupaten & kota
```

### Example 2: Timezone Difference
```
User: Sekarang jam 14:00 WIB. Jam berapa di Makassar (WITA)?

Bot: PERHITUNGAN WAKTU:
     
     Waktu di Jakarta: 14:00 WIB (UTC+7)
     Waktu di Makassar: WITA (UTC+8)
     
     Perbedaan: WITA = WIB + 1 jam
     
     Waktu di Makassar: 14:00 + 1 jam = 15:00 WITA
     
     CATATAN:
     - Jakarta & Makassar berbeda 1 jam
     - Makassar lebih maju 1 jam dari Jakarta
     - Contoh lain:
       * Jika WIB 08:00 → WITA 09:00
       * Jika WIB 17:00 → WITA 18:00
```

### Example 3: Postal Code Lookup
```
User: Apa kode pos Jakarta Pusat?

Bot: KODE POS JAKARTA PUSAT:
     
     Beberapa area di Jakarta Pusat:
     
     - Kota Tua: 12120
     - Balai Kota: 12110
     - Taman Sari: 11140
     - Sawah Besar: 10150
     - Cempaka Putih: 10520
     - Kemayoran: 10620
     
     CARA MENCARI KODE POS LENGKAP:
     1. Kunjungi: posindonesia.co.id
     2. Masukkan nama kelurahan/jalan
     3. Sistem akan menampilkan kode pos
     
     ATAU:
     - Tanya di Kantor Pos terdekat
     - Cek di peta Google Maps
```

### Example 4: Address Formatting
```
User: Bagaimana format alamat yang benar di Indonesia?

Bot: FORMAT ALAMAT INDONESIA YANG BENAR:
     
     STRUKTUR UMUM:
     [Nama Lengkap Penerima]
     [Jalan] No. [Nomor]
     RT [XX]/RW [XX]
     [Kelurahan/Desa]
     [Kecamatan] [Kabupaten/Kota]
     [Provinsi] [Kode Pos]
     
     CONTOH LENGKAP:
     
     Siti Nurhaliza
     Jalan Merdeka No. 25
     RT 05/RW 03
     Kelurahan Gondangdia
     Kecamatan Menteng
     Kota Administrasi Jakarta Pusat
     DKI Jakarta 10350
     
     PENJELASAN ELEMEN:
     ✓ Nama penerima (jelas & lengkap)
     ✓ Jalan (nama jalan resmi)
     ✓ Nomor rumah
     ✓ RT/RW (unit lingkungan)
     ✓ Kelurahan (nama desa/lingkungan)
     ✓ Kecamatan (wilayah administratif)
     ✓ Kota/Kabupaten
     ✓ Provinsi
     ✓ Kode Pos (5 digit)
```

### Example 5: Regional Information
```
User: Info Sulawesi Selatan

Bot: INFORMASI SULAWESI SELATAN:
     
     Ibu Kota: Makassar
     Timezone: WITA (UTC+8)
     Pulau Utama: Sulawesi
     
     KARAKTERISTIK:
     - Luas: 46.717 km²
     - Populasi: ~8 juta jiwa
     - Budaya: Bugis, Makassar, Toraja
     
     KOTA BESAR:
     1. Makassar (ibukota)
     2. Parepare
     3. Palopo
     
     KABUPATEN (21) & KOTA (3):
     - Bantaeng, Barru, Bone, Bulukumba
     - Enrekang, Gowa, Jeneponto, Luwu
     - Luwu Timur, Luwu Utara, Maros, Pangkajene
     - Pinrang, Sidenreng, Sinjai, Soppeng, Takalar
     - Tana Toraja, Toraja Utara, Wajo
     - Kota: Makassar, Parepare, Palopo
     
     KARAKTERISTIK REGIONAL:
     ✓ Pelabuhan penting
     ✓ Sejarah maritim
     ✓ Keragaman budaya
     ✓ Pariwisata berkembang
```

## Resources

- **Administrative Maps**: www.indonesia.go.id
- **Postal Code Lookup**: posindonesia.co.id
- **Maps & Geography**: maps.google.com, maps.go.id
- **Phone Directory**: indotelecommunications.net
- **Regional Information**: Bappenas.go.id

## Important Notes

- Indonesia has 34 provinces (as of latest administrative division)
- Three main timezones, always check local time in business
- Postal codes are managed by Pos Indonesia (national post office)
- Address format is important for mail delivery
- Regional dialects and customs vary significantly
- Always use official government names for provinces/districts

## Integration with Other Skills

- **pajak**: Regional tax office locations
- **bpjs**: Find BPJS offices by region
- **bahasa**: Regional dialect variations
- **rupiah**: Regional banking branches
- **pajak**: Identify tax jurisdiction by region

---

**Last Updated:** 2026
**Reference:** Ministry of Interior (Kemendagri), BPS (Statistics), Pos Indonesia
