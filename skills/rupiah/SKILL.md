# Rupiah - Indonesian Finance Helper Skill

<!--
  last_verified: 2026-04-27
  effective_date: 2026-01-01
  source_url: https://www.bi.go.id
  review_schedule: yearly (rates/thresholds may change)
  maintainer: satryayogapratama@gmail.com
-->

Currency conversion, zakat calculator, banking terminology, and financial rate information.

## Overview

Rupiah skill provides financial assistance for Indonesian users:
- Currency conversion (USD, EUR, SGD to IDR)
- Zakat calculation (Islamic alms)
- Indonesian banking glossary and terms
- BI 7-Day Repo Rate information
- Income and savings calculations

## Capabilities

### 1. Currency Conversion

Convert major currencies to Indonesian Rupiah (IDR).

**Supported Currencies:**
- USD (US Dollar)
- EUR (Euro)
- SGD (Singapore Dollar)
- AUD (Australian Dollar)
- MYR (Malaysian Ringgit)
- THB (Thai Baht)
- GBP (British Pound)
- JPY (Japanese Yen)

Exchange rates updated daily from reliable sources.

### 2. Zakat Calculator

Calculate Zakat (Islamic mandatory alms) for:
- Savings/wealth (Zakat Mal)
- Annual income (Zakat Penghasilan)
- Gold and silver
- Livestock
- Business inventory

Zakat rate: 2.5% of eligible savings above Nisab threshold.

### 3. Banking Terminology

Explain common Indonesian banking terms:
- Account types
- Loan products
- Interest rates
- Fee structures
- Transfer methods

### 4. BI 7-Day Repo Rate

Information about Bank Indonesia's policy rate:
- Current rate
- Recent changes
- Impact on banking
- Inflation relationship

### 5. Financial Calculations

Calculate:
- Monthly savings targets
- Compound interest
- Loan amortization
- Investment returns

## Currency Conversion

### Current Exchange Rates (Indicative)

Note: Rates update daily. These are approximate reference rates.

| Currency | Code | Rate to IDR (approx) |
|----------|------|---------------------|
| US Dollar | USD | 15,500 |
| Euro | EUR | 16,800 |
| Singapore Dollar | SGD | 11,500 |
| Australian Dollar | AUD | 10,200 |
| Malaysian Ringgit | MYR | 3,400 |
| Thai Baht | THB | 430 |
| British Pound | GBP | 19,500 |
| Japanese Yen | JPY | 105 |

### Conversion Formula

IDR = Foreign Amount × Exchange Rate

**Example:**
```
USD 1,000 × 15,500 = Rp 15.500.000
```

### Where to Check Current Rates

- Bank Indonesia: bi.go.id
- OJK (Otoritas Jasa Keuangan): ojk.go.id
- Major Indonesian banks' websites
- XE.com or OANDA (reference rates)

## Zakat Calculation

### Zakat Mal (Wealth Zakat)

**Eligibility:**
- Have savings ≥ Nisab for 1 lunar year
- Nisab: Approximately Rp 87 million (varies with gold price)

**Calculation:**
- Zakat = Qualifying wealth × 2.5%
- Only assets held for 1 year trigger Zakat

**What Counts:**
- Cash/savings
- Gold and silver
- Stocks and bonds
- Business inventory
- Receivables

**What Doesn't Count:**
- Personal belongings
- Primary residence
- Work tools
- Vehicles for personal use
- Debts owed

**Formula:**
```
Zakat = (Total Assets - Debts) × 2.5%
(if amount held ≥ 1 lunar year)
```

### Zakat Penghasilan (Income Zakat)

**Eligibility:**
- Income from employment or business
- Can be paid upon receipt
- More flexible timing than Zakat Mal

**Calculation:**
- Zakat = Gross income × 2.5%
- OR: Zakat = (Income - Essential expenses) × 2.5%

**Due Date:**
- Can be paid anytime during Islamic year
- Or paid upon receiving income

### Nisab Values

**Gold Nisab:**
- 20 mithqal (87.48 grams)
- Current value ≈ Rp 87 million (updates with gold price)

**Silver Nisab:**
- 200 dirham (612 grams)
- Current value ≈ Rp 9 million

**Cash Nisab:**
- Usually follows gold nisab (Rp 87 million)
- Or use silver nisab if lower (more lenient)

### Zakat Recipients (Asnaf)

Zakat can be given to:
1. **Fuqara** - Poor people
2. **Masakin** - Needy people
3. **Amil** - Zakat collectors
4. **Muallaf** - New converts
5. **Riqab** - Slaves (historical)
6. **Gharimin** - Debt-ridden people
7. **Fisabilillah** - Islamic causes
8. **Ibnu Sabil** - Travelers in need

### Where to Pay Zakat

**Official channels:**
- BAZNAS (National Zakat Agency)
- LAZ (Accredited Zakat Agencies)
- Mosques and Islamic organizations
- Licensed Zakat foundations

**Website:** baznas.go.id

## Banking Terminology

### Account Types

| Type | Purpose | Minimum |
|------|---------|---------|
| Tabungan | Savings account | Rp 100,000 |
| Giro | Current/checking account | Rp 250,000 |
| Deposito | Fixed deposit | Rp 10 million |

### Loan Products

| Product | Purpose | Rate | Term |
|---------|---------|------|------|
| KPR | Home mortgage | ~3-5% | 1-20 years |
| KKB | Car loan | ~4-6% | 1-7 years |
| KTA | Personal loan | ~6-12% | 1-5 years |
| KKBB | Business loan | ~5-10% | 1-10 years |

### Key Terms

- **Bunga** (Interest): Cost of borrowing money
- **Suku Bunga** (Interest Rate): Percentage charged
- **Cicilan** (Installment): Monthly payment amount
- **BI Rate** (BI 7-Day Repo): Bank Indonesia's policy rate
- **Inflasi** (Inflation): Rise in prices over time
- **Margin** (Spread): Difference between lending and deposit rates
- **Tenor** (Term): Loan duration in months/years
- **Agunan** (Collateral): Asset pledged as security

### Fees and Charges

- **Biaya Admin** (Admin Fee): Monthly account maintenance
- **Biaya Transfer** (Transfer Fee): For inter-bank transfers
- **Biaya Tarik Tunai** (Cash Withdrawal Fee): ATM usage fee
- **Biaya Asuransi** (Insurance Premium): Loan insurance cost
- **Biaya Denda** (Penalty): Late payment fees

## BI 7-Day Repo Rate

### What Is It?

The BI 7-Day Repo Rate is Bank Indonesia's main policy rate used to:
- Control inflation
- Influence lending rates
- Manage money supply
- Signal monetary policy stance

### Current Information

Check BI.go.id for latest rate information.

### How It Works

1. **Rate Set** - BI announces new rate
2. **Banks Adjust** - Commercial banks adjust lending rates
3. **Economy Impact** - Higher rates = more expensive credit
4. **Inflation Control** - Rate hikes fight rising prices

### Relationship to Savings/Loans

- **Higher BI Rate** → Banks offer higher savings rates → Depositors earn more
- **Lower BI Rate** → Banks charge lower loan rates → Borrowers pay less

## Examples

### Example 1: Currency Conversion
```
User: 5000 dollar berapa rupiah?

Bot: KONVERSI MATA UANG:
     
     Jumlah: USD 5.000
     Kurs USD/IDR: 1 USD = Rp 15.500 (estimasi)
     
     PERHITUNGAN:
     USD 5.000 × Rp 15.500 = Rp 77.500.000
     
     HASIL: USD 5.000 = Rp 77.500.000
     
     CATATAN:
     - Kurs ini estimasi dan berubah setiap hari
     - Untuk transaksi nyata, periksa bank Anda
     - Biasanya ada komisi transfer 1-3%
     
     SARAN:
     1. Cek kurs real-time di bi.go.id
     2. Bandingkan rate di beberapa bank
     3. Pertimbangkan biaya transfer
```

### Example 2: Zakat Calculation
```
User: Saya punya tabungan Rp 200 juta selama 1 tahun.
      Berapa zakat yang harus saya keluarkan?

Bot: PERHITUNGAN ZAKAT MAL:
     
     Data:
     - Total tabungan: Rp 200.000.000
     - Durasi pengalaman: 1 tahun penuh ✓
     - Nisab (2025): ~Rp 87.000.000 ✓
     
     STATUS WAJIB ZAKAT: YA (melebihi nisab)
     
     PERHITUNGAN:
     Zakat = Total Aset × 2.5%
     Zakat = Rp 200.000.000 × 2.5%
     Zakat = Rp 5.000.000
     
     HASIL: Anda wajib mengeluarkan zakat Rp 5.000.000
     
     CARA PEMBAYARAN:
     1. Bayar langsung ke BAZNAS (baznas.go.id)
     2. Atau ke lembaga zakat terakreditasi
     3. Atau langsung ke yang berhak (fakir miskin)
     
     TIPS: Hitung setiap tahun (sama dengan tanggal 
     pertama kali nabung)
```

### Example 3: Loan Interest Calculation
```
User: Saya mau pinjam KTA Rp 50 juta dengan bunga 9% 
      selama 2 tahun. Berapa cicilan bulanannya?

Bot: PERHITUNGAN CICILAN KTA:
     
     Data:
     - Pokok pinjaman: Rp 50.000.000
     - Suku bunga: 9% per tahun
     - Tenor: 24 bulan (2 tahun)
     
     PERHITUNGAN BUNGA TOTAL:
     Bunga = Rp 50.000.000 × 9% × 2
     Bunga = Rp 9.000.000
     
     TOTAL YANG HARUS DIBAYAR:
     Rp 50.000.000 + Rp 9.000.000 = Rp 59.000.000
     
     CICILAN BULANAN:
     Rp 59.000.000 ÷ 24 bulan = Rp 2.458.333/bulan
     
     PERKIRAAN BIAYA TAMBAHAN:
     - Asuransi kredit: ~Rp 500.000-1.000.000
     - Biaya admin: ~Rp 300.000
     - Total cicilan aktual: ~Rp 2.800.000/bulan
     
     TIPS: Bandingkan dengan bank lain untuk bunga lebih rendah
```

### Example 4: Banking Terms
```
User: Apa beda KPR dan KTA?

Bot: PERBANDINGAN KPR vs KTA:
     
     KPR (Kredit Pemilikan Rumah):
     - Untuk: Membeli rumah/properti
     - Tenor: 1-20 tahun
     - Bunga: 3-5% per tahun
     - Agunan: Sertifikat rumah
     - Jumlah: Bisa sangat besar
     - Admin: Lebih kompleks
     
     KTA (Kredit Tanpa Agunan):
     - Untuk: Kebutuhan personal apa saja
     - Tenor: 1-5 tahun
     - Bunga: 6-12% per tahun
     - Agunan: TIDAK diperlukan
     - Jumlah: Lebih terbatas
     - Admin: Proses lebih cepat
     
     PILIH KPR JIKA:
     ✓ Membeli rumah
     ✓ Jumlah besar
     ✓ Bisa menunggu approval
     
     PILIH KTA JIKA:
     ✓ Butuh cepat
     ✓ Jumlah tidak terlalu besar
     ✓ Tidak punya aset untuk agunan
```

## Resources

- Bank Indonesia: bi.go.id
- OJK (Financial Services Authority): ojk.go.id
- BAZNAS (Zakat Agency): baznas.go.id
- Indonesian Banks Directory: Check official bank websites
- Indonesian Chamber of Commerce (KADIN)

## Important Notes

- Exchange rates shown are approximate and update daily
- Always verify current rates before large transactions
- Banks often charge additional fees (1-3%)
- Zakat rates and regulations follow Islamic principles
- BI Rate changes affect entire economy
- Consult with financial advisor for major decisions

## Integration with Other Skills

- **pajak**: Track taxable income for zakat calculations
- **bpjs**: Include health insurance in expense planning
- **bahasa**: Indonesian banking terminology explanations
- **wilayah**: Regional bank locations and branches

---

**Last Updated:** 2026
**Reference:** Bank Indonesia, OJK, BAZNAS, Islamic Finance Standards
