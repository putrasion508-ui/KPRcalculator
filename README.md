# Kalkulator KPR PWA v1.7

## 🔥 What's New v1.7

- ✨ **Mode A/B selector** untuk actual partials — pilih bagaimana bank memproses pelunasan
- ✨ **Timeline Lunas dinamis** — auto-update ke "Lunas (Proyeksi, X bln lebih cepat)" kalau Mode A
- ✨ **Cicilan dinamis** — auto-update ke nilai baru kalau Mode B (cicilan turun setelah parsial)
- ✨ **Tombol "Masukan ke Kondisi Aktual"** di Skenario D — workflow lebih natural: simulasi → confirm → aktualkan
- 🔧 Refactor accounting jadi single source of truth (`calcCurrentState`)
- 🔧 `projectLunas()` factor in past partials + their modes

## 🧪 Testing
- 133/133 tests passed:
  - 15/15 Python ↔ JS cross-validation (Rp 0 diff)
  - 54/54 functional regression
  - 25/25 layered tests (simple to complex)
  - 13/13 Smart Plan, 19/19 logic, 7/7 Mode/Format
- 0 runtime errors

## ✨ Key Features

- 📊 Dashboard dengan timeline yang reflect kondisi aktual
- 🧮 6 Skenario Simulator
- 💡 Smart Plan recommender + Mode A/B toggle
- 📅 Jadwal Amortisasi
- ⚙️ **Pelunasan Parsial Aktual** dengan Mode A/B selector (Settings) atau via tombol di Skenario D

## 🚀 Deploy
Upload 9 file ke GitHub repo, Settings → Pages → Deploy from main/root.
