# Kalkulator KPR PWA v1.8

## 🔥 v1.8 Changes

- ✅ **Tombol "Masukan ke Aktual" selalu visible** kalau ada event di Skenario D — UX lebih jelas
- ✅ Disabled state dengan label informatif kalau event masih masa depan
- ✅ Default bulan diubah dari 125 → 60 (lebih realistic untuk testing)
- ✅ Help text di bawah Skenario D jelaskan workflow

## 🔄 Auto-Update Cicilan Bulanan
App pakai `tanggal akad` + `hari ini` untuk hitung bulan ke berapa. Setiap tanggal 12 (atau setelahnya), bulan ticks ke +1, OS recompute otomatis. Tidak perlu manual input cicilan bulanan.

## 🧪 Testing
- 25/25 layered tests (simple → complex)
- 54/54 functional regression
- 15/15 Python ↔ JS cross-validation (Rp 0 diff)
- 0 runtime errors

## 🚀 Deploy
Upload 9 file ke GitHub repo → Pages settings → Deploy.
