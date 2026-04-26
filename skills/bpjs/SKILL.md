# BPJS - Indonesian Health Insurance Helper Skill

<!--
  last_verified: 2026-04-27
  effective_date: 2026-01-01
  source_url: https://www.bpjs-kesehatan.go.id / https://www.bpjs-ketenagakerjaan.go.id
  review_schedule: yearly (rates/thresholds may change)
  maintainer: satryayogapratama@gmail.com
-->

Calculate BPJS Kesehatan premiums, check membership status, and guide enrollment procedures.

## Overview

BPJS (Badan Penyelenggara Jaminan Sosial) Kesehatan provides mandatory health insurance for Indonesian citizens and residents. This skill helps with:
- Premium calculation by class
- BPJS membership checks
- Enrollment and registration guidance
- Benefits and coverage information

## Capabilities

### 1. Calculate BPJS Kesehatan Premiums

Calculate monthly premiums by class for individual/family enrollment.

**BPJS Kesehatan Classes:**
- **Class I (Kelas I)**: Premium Rp 171.000/person
  - Private room with AC and bathroom
  - Advanced medical equipment
  - Better quality facilities

- **Class II (Kelas II)**: Premium Rp 121.500/person
  - Semi-private room
  - Standard medical equipment
  - Most popular class

- **Class III (Kelas III)**: Premium Rp 35.750/person
  - General ward (3-6 beds)
  - Basic equipment
  - Lowest cost option

### 2. Check BPJS Membership Status

Verify active BPJS Kesehatan membership using NIK (National ID) or BPJS number.

### 3. Enrollment and Registration Guide

Step-by-step guidance for:
- Registering as new member (Peserta Baru)
- Adding family members (Kepesertaan Keluarga)
- Selecting healthcare facilities
- Submitting enrollment forms

## Usage

### Calculate Premium

```
Input: Berapa biaya BPJS Kelas II untuk keluarga 4 orang?
Output:
  BPJS Kesehatan Kelas II: Rp 121.500 per orang per bulan
  
  Untuk keluarga 4 orang:
  - Total per bulan: Rp 486.000
  - Total per tahun: Rp 5.832.000
```

### Check Membership

```
Input: Cek status BPJS saya nomor 0002345678900000
Output:
  Status BPJS: AKTIF
  Nomor BPJS: 0002345678900000
  Nama: JOHN DOE
  Kelas: II
  Fasilitas Kesehatan Tingkat 1: PUSKESMAS KECAMATAN X
  Tanggal Berlaku: 1 Januari 2025
```

### Enrollment Help

```
Input: Bagaimana cara daftar BPJS untuk pertama kali?
Output:
  LANGKAH PENDAFTARAN BPJS KESEHATAN BARU:
  
  1. Siapkan dokumen:
     - Fotokopi KTP/NIK
     - Fotokopi Kartu Keluarga
     - Pas foto 3x4 (jika perlu)
  
  2. Pilih fasyankes (healthcare facility) tingkat 1
  
  3. Daftar ke BPJS atau fasyankes terdekat
  
  4. Bayar iuran pertama
  
  5. Tunggu kartu BPJS aktif (maksimal 7 hari kerja)
```

## Premium Classes in Detail

### Class I (Kelas I)
- **Monthly Premium**: Rp 171.000
- **Yearly Cost**: Rp 2.052.000
- **Room Type**: Private or semi-private with AC
- **Facilities**: TV, phone, private bathroom
- **Best For**: Those seeking premium comfort and privacy

### Class II (Kelas II)
- **Monthly Premium**: Rp 121.500
- **Yearly Cost**: Rp 1.458.000
- **Room Type**: Semi-private or compartment
- **Facilities**: Shared bathroom, basic amenities
- **Best For**: Most people seeking value and comfort balance

### Class III (Kelas III)
- **Monthly Premium**: Rp 35.750
- **Yearly Cost**: Rp 429.000
- **Room Type**: General ward (3-6 beds)
- **Facilities**: Shared bathroom, minimal amenities
- **Best For**: Those with limited budget, adequate medical care

## Coverage and Benefits

All BPJS Kesehatan classes cover:
- Emergency/ambulance services
- Outpatient doctor consultations
- Hospitalization
- Surgery and medical procedures
- Delivery services
- Prescription medications
- Blood transfusions
- Medical rehabilitation

## Registration Process

### For New Members (Peserta Baru)

1. **Choose healthcare facility (Fasilitas Kesehatan Tingkat 1)**
   - Visit nearest Puskesmas (primary health center)
   - Or visit BPJS office
   - Or use online registration (bpjs-kesehatan.go.id)

2. **Prepare documents**
   - NIK (KTP / ID Card)
   - Kartu Keluarga (Family Card) if adding family members
   - Proof of address (optional)

3. **Fill enrollment form (Formulir Pendaftaran)**
   - Form SE-1 for individuals
   - Form SE-2 for family groups

4. **Pay first premium**
   - Can pay at BPJS, bank, or agent
   - Receipt provided immediately

5. **Receive BPJS card**
   - Physical card arrives within 7 days
   - Can use digital card meanwhile

### For Adding Family Members (Kepesertaan Tambahan)

1. Contact local BPJS office with family card
2. Fill dependent registration form
3. Pay premium for additional members
4. Cards issued for new members

## BPJS vs Private Insurance

| Aspect | BPJS | Private |
|--------|------|---------|
| Coverage | Universal, all citizens | Selective |
| Cost | Fixed, low premium | Varies, can be expensive |
| Benefits | Standard coverage | Premium coverage options |
| Eligibility | All Indonesian citizens | Health screening required |
| Claims Process | Direct billing at network hospitals | Claim submission needed |

## Fasilitas Kesehatan (Healthcare Facilities)

### Tingkat 1 (First Level)
- Puskesmas (Community Health Center)
- Klinik (Private Clinic)
- Dokter Praktik (Private Practice)

### Tingkat 2 (Second Level)
- Rumah Sakit (Hospitals)
- Specialist clinics

Patients must start at Level 1 facility and get referral for Level 2.

## Common Issues and Solutions

**Issue: BPJS card not active yet**
- Solution: Can use temporary digital card at network hospitals

**Issue: Changed healthcare facility?**
- Solution: Can change facility once per year (or emergency transfer)

**Issue: Lost BPJS card?**
- Solution: Report to BPJS office, get duplicate card (Rp 20.000-30.000)

**Issue: Premium payment overdue?**
- Solution: Pay outstanding amount to reactivate immediately

## Integration with Other Skills

- **pajak**: BPJS premiums may be tax-deductible
- **wilayah**: Find nearest BPJS office by location
- **bahasa**: Formal healthcare terminology guide

## Examples

### Example 1: Family Premium Calculation
```
User: Saya mau daftar BPJS Kelas II untuk keluarga 5 orang
      Berapa biayanya per bulan dan per tahun?

Bot: BPJS Kesehatan Kelas II
     
     Per orang per bulan: Rp 121.500
     Jumlah anggota: 5 orang
     
     TOTAL IURAN:
     - Per bulan: Rp 607.500
     - Per tahun: Rp 7.290.000
     
     Cara pembayaran:
     • Bayar bulanan setiap tanggal jatuh tempo
     • Atau bayar annual discount tersedia di beberapa daerah
     • Bisa bayar di kantor BPJS, bank, atau agen
```

### Example 2: Enrollment Process
```
User: Saya belum punya BPJS. Gimana cara daftar?

Bot: PENDAFTARAN BPJS KESEHATAN:
     
     DOKUMEN YANG DIPERLUKAN:
     1. Fotokopi KTP/NIK
     2. Fotokopi Kartu Keluarga (jika daftar keluarga)
     3. Pas foto ukuran 3x4 (kadang diperlukan)
     
     LANGKAH PENDAFTARAN:
     1. Datang ke kantor BPJS terdekat atau Puskesmas
     2. Pilih kelas: I (Rp 171k), II (Rp 121.5k), atau III (Rp 35.75k)
     3. Isi formulir pendaftaran
     4. Bayar iuran bulan pertama
     5. Dapatkan nomor BPJS sementara
     6. Kartu fisik siap dalam 5-7 hari kerja
     
     ATAU daftar online di: bpjs-kesehatan.go.id
```

### Example 3: Status Check
```
User: Bagaimana cara cek status BPJS saya?

Bot: ADA BEBERAPA CARA CEK STATUS BPJS:
     
     ONLINE (REKOMENDASI):
     1. Buka website bpjs-kesehatan.go.id
     2. Klik menu "Cek Kepesertaan"
     3. Masukkan NIK dan tanggal lahir
     4. Tekan "CARI"
     
     OFFLINE:
     1. Datang ke kantor BPJS dengan membawa KTP
     2. Minta bantuan petugas di loket pelayanan
     3. Informasi status langsung diberikan
     
     APLIKASI MOBILE:
     1. Download aplikasi "Mobile JKN"
     2. Login dengan NIK dan password
     3. Lihat status kepesertaan dan riwayat klaim
```

## Resources

- BPJS Official Website: bpjs-kesehatan.go.id
- Mobile App: Mobile JKN (Android & iOS)
- Call Center: 1500400 (24/7)
- Local BPJS offices in all Indonesian cities

## Important Notes

- Premium rates listed are current as of 2025 and subject to change
- Classes have minor differences by region
- Healthcare coverage is comprehensive but not unlimited
- Some treatments may require pre-authorization
- Always verify current rates at official BPJS website

---

**Last Updated:** 2026
**Relevant Law:** Law No. 24 of 2011 on Social Security Organizing Agency
