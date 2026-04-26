# ClawIndonesia - Indonesian Skill Pack for OpenClaw

A comprehensive collection of OpenClaw skills specifically designed for Indonesian users and context. Covers taxation, healthcare, language, finance, and geography.

## Overview

ClawIndonesia extends OpenClaw with five specialized skills that address real Indonesian needs:

1. **Pajak** - Tax calculations and filing guidance
2. **BPJS** - Health insurance premiums and enrollment
3. **Bahasa** - Indonesian language tools and grammar
4. **Rupiah** - Currency conversion and financial calculations
5. **Wilayah** - Geographic and administrative information

## Features

### Professional Coverage
- Indonesian tax system (PPh, PPN, SPT)
- BPJS Kesehatan health insurance
- Formal/casual Bahasa Indonesia
- Currency conversion and zakat calculator
- Geographic data and timezones

### Practical Focus
- Real-world calculations
- Step-by-step guidance
- Current rates and deadlines
- Professional terminology
- Integration across skills

## Installation

### Quick Setup

1. Copy the skills folder to your OpenClaw workspace:
   ```bash
   cp -r clawindonesia/skills /path/to/openclaw/workspace/
   ```

2. Each skill is now available in OpenClaw:
   ```bash
   openclaw skill load pajak
   openclaw skill load bpjs
   openclaw skill load bahasa
   openclaw skill load rupiah
   openclaw skill load wilayah
   ```

### Manual Installation

Individual skills can be installed separately:
```bash
cp clawindonesia/skills/pajak /path/to/openclaw/workspace/skills/
cp clawindonesia/skills/bpjs /path/to/openclaw/workspace/skills/
# ... repeat for other skills
```

## Skills Overview

### 1. Pajak - Indonesian Tax Helper

**Description:** Calculate Indonesian taxes and provide filing guidance.

**Capabilities:**
- PPh Final 0.5% calculation for UMKM
- Tax deadline tracking (SPT, PPh 21, PPN)
- DJP Online (e-filing) navigation
- Tax terminology glossary

**Example Usage:**
```
User: Hitung pajak PPh Final untuk pendapatan Rp 100 juta

Bot: PPh Final 0.5% untuk Rp 100.000.000 adalah Rp 500.000 per bulan
     Total per tahun: Rp 6.000.000
     Syarat: Omzet tidak melebihi Rp 4.8 milyar dalam satu tahun
```

**Key Features:**
- Multiple tax type calculators
- Current deadline calendar
- Step-by-step DJP Online guide
- Glossary of tax terms

### 2. BPJS - Health Insurance Helper

**Description:** Calculate BPJS Kesehatan premiums and guide enrollment.

**Capabilities:**
- Premium calculation by class (I/II/III)
- Membership status verification
- Enrollment procedures
- Coverage and benefits information

**Example Usage:**
```
User: Berapa biaya BPJS Kelas II untuk keluarga 4 orang?

Bot: BPJS Kesehatan Kelas II
     Rp 121.500 per orang per bulan
     Keluarga 4 orang: Rp 486.000/bulan = Rp 5.832.000/tahun
```

**Key Features:**
- Three class comparison (I, II, III)
- Family group calculation
- Registration step-by-step
- Healthcare facility selection

### 3. Bahasa - Language Helper

**Description:** Indonesian language tools for formal/casual conversion and grammar.

**Capabilities:**
- Formal/informal register detection
- Formal to casual (gaul) conversion
- EYD spelling checker
- Abbreviation and acronym glossary

**Example Usage:**
```
User: Deteksi level formalitas teks ini: "Gimana kabar lo?"

Bot: Register: CASUAL/GAUL
     "Gimana" = kontraksi dari "bagaimana"
     "lo" = pronoun gaul untuk "kamu"
     Cocok untuk: Chat, WhatsApp, media sosial
     Tidak cocok untuk: Email profesional, presentasi
```

**Key Features:**
- Register level detection
- Bidirectional conversions
- EYD compliance checking
- Formal abbreviations guide

### 4. Rupiah - Finance Helper

**Description:** Currency conversion, zakat calculator, and financial information.

**Capabilities:**
- Currency conversion (USD, EUR, SGD to IDR)
- Zakat (Islamic alms) calculation
- Indonesian banking terminology
- BI 7-Day Repo Rate information

**Example Usage:**
```
User: 5000 dollar berapa rupiah?

Bot: USD 5.000 × Rp 15.500 = Rp 77.500.000
     (Rate dapat berubah setiap hari)
     Pertimbangkan biaya transfer 1-3%
```

**Key Features:**
- Real-time currency rates
- Zakat Mal and Zakat Penghasilan
- Banking terms glossary
- Loan calculator

### 5. Wilayah - Geography Helper

**Description:** Indonesian geographic and administrative information.

**Capabilities:**
- Province and district data
- Timezone information (WIB/WITA/WIT)
- Postal code (Kode Pos) lookup
- Address formatting guide

**Example Usage:**
```
User: Sekarang jam 14:00 WIB. Jam berapa di Makassar (WITA)?

Bot: Makassar menggunakan WITA (UTC+8)
     Perbedaan: WITA = WIB + 1 jam
     Jam di Makassar: 15:00 WITA
```

**Key Features:**
- All 34 provinces listed
- Timezone converter
- Postal code lookup system
- Address formatting guide

## Skills Comparison

| Skill | Purpose | Key Feature |
|-------|---------|------------|
| Pajak | Tax guidance | PPh Final calculation |
| BPJS | Health insurance | Premium by class |
| Bahasa | Language tools | Formal/casual conversion |
| Rupiah | Finance | Currency conversion |
| Wilayah | Geography | Timezone information |

## Integration Examples

### Tax and Finance
```
User: Saya UMKM dengan omzet Rp 50 juta/bulan. 
      Berapa total biaya pajak dan zakat?

Bot: [Using Pajak skill]
     PPh Final 0.5%: Rp 250.000/bulan = Rp 3.000.000/tahun
     
     [Using Rupiah skill + Bahasa skill]
     Jika ada tabungan Rp 200 juta selama 1 tahun:
     Zakat (2.5%): Rp 5.000.000
     
     Total per tahun: Rp 8.000.000
```

### Health and Location
```
User: Saya di Jayapura, butuh daftar BPJS Kelas II

Bot: [Using Wilayah skill]
     Jayapura menggunakan WIT (UTC+9)
     
     [Using BPJS skill]
     BPJS Kelas II: Rp 121.500/bulan
     Kantor BPJS terdekat: [lokasi Jayapura]
     Jam operasional: 08:00-17:00 WIT
```

## File Structure

```
clawindonesia/
├── skills/
│   ├── pajak/
│   │   └── SKILL.md
│   ├── bpjs/
│   │   └── SKILL.md
│   ├── bahasa/
│   │   └── SKILL.md
│   ├── rupiah/
│   │   └── SKILL.md
│   └── wilayah/
│       └── SKILL.md
├── README.md
└── LICENSE
```

## Technical Requirements

- OpenClaw installation
- Python 3.6+ (for skill execution)
- No additional dependencies required

## Usage Examples

### Example 1: Complete Tax Scenario
```
openclaw> load skill pajak
openclaw> pajak: Calculate PPh Final for Rp 300 million annual revenue
Bot: [Detailed calculation and compliance guidance]
```

### Example 2: Multi-Skill Chain
```
openclaw> Saya di Surabaya mau hitung zakat
Bot: [Wilayah] Surabaya: Jawa Timur, WIB
     [Rupiah] Berapa total aset yang ingin dihitung zakatnya?
```

### Example 3: Language Help
```
openclaw> Ubah email formal ini jadi chat: "Dengan hormat, saya..."
Bot: [Bahasa] CASUAL VERSION: "Halo, aku mau..."
     [Bahasa] GAUL VERSION: "Yo, gue pengen..."
```

## Real-World Applications

### Individual Use
- Personal tax planning
- Health insurance enrollment
- Currency conversion while traveling
- Finding postal codes for mailing
- Writing professional emails

### Small Business
- UMKM tax compliance
- Employee health insurance
- Invoice formatting
- Financial planning
- Regional market research

### Organizations
- Payroll and tax management
- Bulk BPJS enrollment
- Internal documentation
- Finance department support
- Geographic data lookups

## Current Rates and Data

All rates and deadlines are accurate as of 2025/2026:

- **PPh Final**: 0.5% (UMKM threshold: Rp 4.8 billion)
- **BPJS Class II**: Rp 121.500/person/month
- **Exchange Rates**: USD 1 = Rp 15.500 (approximate)
- **Provinces**: 34 (with latest administrative divisions)

**Note:** Always verify current rates before important transactions.

## Support and Updates

### Getting Help
- Check individual SKILL.md files for detailed guidance
- Use skill's built-in examples
- Refer to resource links provided in each skill
- Contact relevant government agencies for official information

### Updates
- Tax rates may change annually
- Exchange rates update daily
- Healthcare premiums adjust periodically
- Government procedures may be updated

Check official sources:
- Pajak: www.pajak.go.id
- BPJS: bpjs-kesehatan.go.id
- Bahasa: Kamus Besar Bahasa Indonesia
- Rupiah: bi.go.id (Bank Indonesia)
- Wilayah: Indonesia.go.id

## Contributing

Suggestions for improvements:
- Additional skill features
- More detailed examples
- Regional variations
- Updated rates and information
- Language improvements

Submit feedback through OpenClaw's skill contribution process.

## Resources

### Government Portals
- Tax Authority (Pajak): pajak.go.id
- BPJS Health: bpjs-kesehatan.go.id
- Bank Indonesia: bi.go.id
- Indonesia Portal: indonesia.go.id
- Post Office (Pos): posindonesia.co.id

### Reference Materials
- Indonesian Tax Law (UU KUP No. 8 of 1997)
- BPJS Law (UU No. 24 of 2011)
- Indonesian Language Guide (PUEBI)
- Administrative Divisions: kemendagri.go.id

## License

Evaluation License. See [LICENSE](LICENSE) file.

## Legal Disclaimer

The information provided in these skills is for general guidance only. For critical decisions:
- Consult with professional advisors (tax consultants, financial advisors)
- Verify information with official government sources
- Check current rates and regulations
- Don't rely solely on skill output for legal/financial decisions

## Roadmap

- [ ] Add more tax scenarios (PPh 21, PPN, corporate)
- [ ] Expand BPJS with claim processes
- [ ] Add advanced grammar checker
- [ ] Regional currency exchanges
- [ ] Add regency-level postal code database
- [ ] Integration with financial planning tools
- [ ] Mobile-optimized interfaces

---

**Built for Indonesia. Made by Indonesians. For Indonesian users.**

**Last Updated:** 2026
