# Arsitektur FTTH

FTTH membawa layanan komunikasi melalui serat optik hingga lokasi pelanggan. Desain sebenarnya bergantung pada teknologi PON, kapasitas, anggaran optik, topologi, dan kebijakan penyedia layanan.

## Alur umum

1. **POP/STO** — lokasi peralatan dan agregasi layanan.
2. **OLT** — Optical Line Terminal yang mengelola sisi jaringan akses optik.
3. **ODF** — Optical Distribution Frame untuk terminasi dan pengelolaan serat.
4. **Kabel feeder** — menghubungkan sisi sentral dengan titik distribusi.
5. **ODC** — Optical Distribution Cabinet, titik distribusi dan pemisahan serat sesuai desain.
6. **Kabel distribusi** — menghubungkan ODC ke area distribusi.
7. **ODP** — Optical Distribution Point, titik akses distribusi dekat pelanggan.
8. **Drop cable** — kabel dari ODP menuju lokasi pelanggan.
9. **OTP/roset** — titik terminasi di sisi pelanggan, sesuai desain instalasi.
10. **ONT/ONU** — perangkat terminasi optik pelanggan.
11. **Router/Wi-Fi** — menyediakan konektivitas jaringan lokal jika terpisah dari ONT.

## Contoh topologi dummy

```text
POP-DEMO
   |
  OLT-DEMO
   |
  ODF-DEMO
   |
 FEEDER-DEMO
   |
 ODC-DEMO-01
   |
 DISTRIBUTION-DEMO
   |
 ODP-DEMO-01
   |
 DROP-CABLE-DEMO
   |
 OTP-DEMO -- ONT-DEMO -- ROUTER-DEMO
```

## Catatan desain

- Tentukan rasio split dan jalur berdasarkan perencanaan jaringan yang disetujui.
- Perhitungkan redaman serat, konektor, sambungan, splitter, dan margin desain.
- Dokumentasikan jalur dan port dengan ID non-sensitif pada materi publik.
- Jangan menggunakan diagram contoh ini sebagai gambar kerja lapangan tanpa survei dan persetujuan teknis.
