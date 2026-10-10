# FTTH Documentation

Dokumentasi publik untuk pembelajaran dan referensi operasional jaringan Fiber To The Home (FTTH). Repository ini menggunakan **data dummy** dan ditujukan untuk panduan umum, bukan sebagai inventaris jaringan produksi.

## Daftar isi

- [Arsitektur FTTH](docs/architecture.md)
- [Komponen jaringan](docs/components.md)
- [Panduan instalasi pelanggan](docs/customer-installation.md)
- [Pengukuran redaman optik](docs/optical-power.md)
- [Troubleshooting](docs/troubleshooting.md)
- [Checklist teknisi](docs/technician-checklists.md)
- [Template inventaris ODC/ODP](templates/odc-odp-inventory.csv)
- [Template tiket gangguan](templates/incident-ticket.md)
- [Template laporan instalasi](templates/installation-report.md)
- [Glosarium](docs/glossary.md)
- [Keamanan publikasi](SECURITY.md)

## Gambaran alur FTTH

`Core/POP → OLT → ODF → Feeder → ODC → Distribution Fiber → ODP → Drop Cable → Roset/OTP → ONT/ONU → Router/Wi-Fi`

Topologi nyata dapat berbeda tergantung desain jaringan dan kebijakan operator.

## Struktur repository

```text
ftth-documentation-public/
├── README.md
├── SECURITY.md
├── CONTRIBUTING.md
├── LICENSE
├── docs/
│   ├── architecture.md
│   ├── components.md
│   ├── customer-installation.md
│   ├── optical-power.md
│   ├── troubleshooting.md
│   └── glossary.md
├── checklists/
│   ├── pre-installation.md
│   ├── installation.md
│   └── maintenance.md
├── templates/
│   ├── odc-odp-inventory.csv
│   ├── incident-ticket.md
│   └── installation-report.md
└── diagrams/
    └── topology-example.mmd
```

## Catatan keselamatan

- Semua ID, nama lokasi, port, dan nilai pada template adalah contoh.
- Jangan unggah alamat pelanggan, nomor telepon, koordinat, serial number ONT produksi, kredensial, IP manajemen, konfigurasi perangkat mentah, atau peta jaringan internal.
- Ikuti SOP keselamatan kerja, aturan operator, dan standar yang berlaku di wilayah Anda.
- Nilai redaman dan batas penerimaan harus mengikuti desain optik, kelas perangkat, panjang gelombang, dan standar operator. Contoh pada dokumentasi bukan ambang kelulusan universal.

## Penggunaan

Silakan gunakan sebagai bahan pembelajaran atau sesuaikan untuk dokumentasi publik. Periksa lisensi dan kebijakan organisasi sebelum memakai materi di lingkungan kerja.
