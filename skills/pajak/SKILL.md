# Pajak - Indonesian Tax Helper Skill

Calculate taxes, explain deadlines, and guide Indonesian tax filing procedures.

## Overview

Pajak skill helps Indonesian users understand and calculate various Indonesian taxes including:
- PPh Final 0.5% for UMKM (Usaha Mikro Kecil Menengah)
- Tax deadlines and filing requirements
- Navigation of DJP Online (Direktorat Jenderal Pajak)

## Capabilities

### 1. Calculate PPh Final 0.5% for UMKM

Calculate final income tax for small businesses with gross income under 4.8 billion rupiah.

**Formula:** PPh Final = Gross Income × 0.5%

**Example:**
```
User: Hitung pajak PPh Final untuk pendapatan Rp 100 juta
Bot: PPh Final 0.5% untuk Rp 100.000.000 adalah Rp 500.000 per bulan
```

### 2. Tax Deadlines and Schedules

Provide current tax deadlines for:
- SPT (Surat Pemberitahuan / Tax Return) - annually
- PPh 21 (Personal Income Tax) - monthly
- PPh 23 (Service Income Tax) - monthly
- PPh 25 (Corporate Tax Installment) - monthly
- PPN (Value Added Tax) - monthly
- Annual SPT deadline

### 3. DJP Online Guide

Guide users through filing on efiling.pajak.go.id including:
- Registration process
- SPT filing steps
- Document requirements
- Submission and receipt

## Usage

### Calculate PPh Final

```
Input: Hitung PPh Final untuk omzet 500 juta
Output: 
  Omzet: Rp 500.000.000
  PPh Final (0.5%): Rp 2.500.000 per bulan / Rp 30.000.000 per tahun
  Syarat: Omzet ≤ Rp 4.8 milyar dalam satu tahun buku
```

### Check Tax Deadline

```
Input: Kapan deadline SPT 2024?
Output:
  SPT Tahunan 2024 (Orang Pribadi): 29 Maret 2025
  SPT Tahunan 2024 (Badan): 30 April 2025
  Extension: Dapat diperpanjang hingga 3 bulan
```

### DJP Online Help

```
Input: Bagaimana cara lapor SPT di DJP Online?
Output:
  1. Kunjungi efiling.pajak.go.id
  2. Login dengan NPSN dan password Anda
  3. Pilih menu "SPT"
  4. Pilih tahun pajak dan jenis SPT
  5. Isi data penghasilan sesuai dengan bukti dokumen
  6. Verifikasi dan submit
  7. Cetak bukti penerimaan
```

## Key Rates and Thresholds

### PPh Final UMKM
- Rate: 0.5% per month
- Applies to: Businesses with gross annual income ≤ Rp 4.8 billion
- Method: Based on total monthly revenue
- Benefit: Simplified reporting, no deductions allowed

### Income Tax Rates (PPh 21)
- Personal income tax on salary/wages
- Progressive rates from 5% to 30%
- Non-taxable income (PTKP):
  - Individual: Rp 54 million/year
  - Married: Rp 58.5 million/year
  - Dependent: +Rp 4.5 million per dependent

### Other Key Deadlines
- Monthly tax reporting: 20th of following month
- Annual SPT filing: End of March following year
- Advance tax (PPh 25): 15th of following month

## Tax Terms Glossary

- **SPT**: Surat Pemberitahuan (Annual Tax Return)
- **NPWP**: Nomor Pokok Wajib Pajak (Tax Identification Number)
- **NPSN**: NomerSeri Sertifikat Pengamanan (Security Certificate Number for e-filing)
- **PPh**: Pajak Penghasilan (Income Tax)
- **PPh 21**: Personal income tax on salaries
- **PPh 23**: Tax on services, rent, interest
- **PPh 25**: Corporate advance tax
- **PPh Final 0.5%**: Fixed tax for UMKM
- **PPN**: Pajak Pertambahan Nilai (Value Added Tax, 11%)
- **DJP**: Direktorat Jenderal Pajak (Tax Directorate)

## Integration Points

This skill can integrate with:
- **rupiah**: Convert income amounts for calculation
- **wilayah**: Identify location-specific tax offices
- **bahasa**: Translate formal tax terminology

## Examples

### Example 1: UMKM Tax Calculation
```
User: Saya punya bisnis kuliner dengan omzet Rp 200 juta per bulan
      Berapa PPh Final yang harus saya bayar?

Bot: Untuk usaha kuliner dengan omzet Rp 200.000.000:
     
     PPh Final 0.5% = Rp 200.000.000 × 0.5% = Rp 1.000.000
     
     Pembayaran per bulan: Rp 1.000.000
     Pembayaran per tahun: Rp 12.000.000
     
     Catatan: Anda hanya wajib PPh Final jika omzet tidak melebihi 
              Rp 4.8 milyar dalam satu tahun buku.
```

### Example 2: Deadline Information
```
User: Kapan saya harus bayar PPh 21 karyawan?

Bot: PPh 21 harus dibayar paling lambat tanggal 10 bulan berikutnya
     setelah bulan pajak berakhir.
     
     Contoh:
     - PPh 21 bulan Januari → bayar 10 Februari
     - PPh 21 bulan Februari → bayar 10 Maret
     
     Pelaporan SPT PPh 21 dilakukan setiap bulan ke DJP.
```

### Example 3: DJP Online Navigation
```
User: Saya baru pertama kali mau lapor SPT online. Bagaimana caranya?

Bot: Berikut langkah-langkah lapor SPT di DJP Online:
     
     PERSIAPAN:
     1. Siapkan NPWP Anda
     2. Buat akun di efiling.pajak.go.id (jika belum punya)
     3. Kumpulkan dokumen pendukung (invoice, bukti transfer, dll)
     
     FILING:
     1. Login ke efiling.pajak.go.id
     2. Pilih menu "SPT" → "SPT Tahunan"
     3. Pilih jenis SPT (1770 untuk OP, 1771 untuk OP usaha, dll)
     4. Isi data sesuai dokumen (penghasilan, potongan, hutang pajak)
     5. Cek kembali semua data
     6. Submit SPT
     
     SELESAI:
     7. Catat nomor referensi
     8. Cetak bukti penerimaan (akan dikirim email)
```

## Resources

- DJP Website: www.pajak.go.id
- E-Filing: efiling.pajak.go.id
- Tax Calculator: Tax Identification Number (NPWP) lookup and verification
- Forms: Semua formulir SPT tersedia di portal DJP

## Accuracy Note

This skill provides general guidance. For complex tax situations:
- Consult with a professional tax consultant (konsultan pajak)
- Contact local tax office (Kantor Pelayanan Pajak)
- Visit official DJP website for latest regulations

Tax laws change frequently. Always verify current rates and deadlines.

---

**Last Updated:** 2026
**Relevant Regulation:** Law No. 8 of 1997 (KUP), Law No. 6 of 1983 (PPh)
