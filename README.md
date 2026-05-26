# 💼 PitchPolish

> AI startup pitch critique

Get brutal investor-grade feedback on your startup pitch — clarity, market fit, traction signals, financial logic, and red flags.

## ✨ Features

- VC-grade pitch evaluation 0-100
- Strengths, weaknesses, and red flags with severity
- Verdict: pass / maybe / take-the-meeting / term-sheet
- Sharp questions a VC will ask
- Stage-aware feedback (idea → growth)
- Multi-language UI (English / 中文)
- BYOK Xiaomi MiMo API support with free Pollinations fallback
- Zero dependencies, single-file HTML

## 🚀 Quick Deploy

### Vercel (drag-drop, paling cepat)
1. Buka [vercel.com/new](https://vercel.com/new)
2. Drag folder `pitchpolish/` ke area drop
3. Klik Deploy. URL hidup dalam 30 detik.

### Local
```bash
cd pitchpolish
python3 -m http.server 8000
# buka http://localhost:8000
```

## 🔑 Setup MiMo API Key (recommended)

1. Klik **⚙** di header
2. Paste API key dari [api.xiaomimimo.com](https://api.xiaomimimo.com)
3. Test Connection → Save

Tanpa API key, app pakai Pollinations free endpoint (terbatas, demo only).

## 🏗️ Stack

- Single-file HTML, vanilla JS, zero dependencies
- Xiaomi MiMo V2.5 (primary) → Pollinations (fallback)
- localStorage untuk settings, no server

## 📦 Built for

[**MiMo 100T Creator Program**](https://100t.xiaomimimo.com)

## 📄 License

MIT — fork, modify, gunakan komersial bebas.

---

Made by [@Fikrizz](https://github.com/Fikrizz) · Powered by Xiaomi MiMo
