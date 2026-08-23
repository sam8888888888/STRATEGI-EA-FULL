# EA31337 Strategies — Full Collection (Rapi)

Koleksi lengkap strategi EA dari proyek [EA31337](https://github.com/EA31337/EA31337-strategies), disusun rapi untuk arsip & pengembangan.

> **Sumber asli:** https://github.com/EA31337/EA31337-strategies (GPLv3)
> **Versi:** snapshot lengkap (strategi + framework + indikator)

## Struktur

```
ea31337-strategies-full/
├── strategies/     ← 69 strategi EA (tiap folder = 1 strategi)
│   ├── RSI/        → Stg_RSI.mq5, Stg_RSI.mq4, Stg_RSI.mqh, config/, sets/
│   ├── MACD/       → Stg_MACD.mq5, ...
│   ├── Stochastic/ → ...
│   └── ...66 lainnya
├── framework/      ← EA31337-classes (library MQL untuk strategi)
├── indicators/     ← indikator pendukung
│   ├── common/     → EA31337-indicators-common
│   └── other/      → EA31337-indicators-other
└── README.md
```

## Daftar Strategi (69)

AC, AD, ADX, AMA, ASI, ATR, ATR_MA_Trend, Alligator, Arrows, Awesome, BWMFI, Bands, BearsPower, BullsPower, CCI, Chaikin, DEMA, DPO, DeMarker, Demo, ElliottWave, Envelopes, Force, Fractals, Gator, HeikenAshi, Ichimoku, Indicator, MA, MACD, MA_Breakout, MA_Cross_Pivot, MA_Cross_Shift, MA_Cross_Sup_Res, MA_Cross_Timeframe, MA_Trend, MFI, Momentum, OBV, OsMA, Oscillator, Oscillator_Cross, Oscillator_Cross_Shift, Oscillator_Cross_Timeframe, Oscillator_Cross_Zero, Oscillator_Divergence, Oscillator_Martingale, Oscillator_Multi, Oscillator_Overlay, Oscillator_Range, Oscillator_Trend, Pattern, Pinbar, Pivot, RSI, RVI, Retracement, SAR, SAWA, SVE_Bollinger_Bands, StdDev, Stochastic, SuperTrend, TMAT_SVEBB, TMA_CG, TMA_True, WPR, ZigZag

## Cara Compile (biar siap pakai di MT5)

1. Salin isi `framework/` ke `MQL5\Include\` (folder library EA31337)
2. Salin isi `indicators/common/` dan `indicators/other/` ke `MQL5\Indicators\` (atau Include, sesuai referensi masing-masing strategi)
3. Salin folder strategi yang mau dipakai (misal `strategies/RSI/`) ke `MQL5\Experts\`
4. Compile di MetaEditor (F7)

> Catatan: tiap strategi butuh dependency framework/indikator yang sesuai. Lihat README di folder strategi masing-masing untuk referensi lengkap.

## Lisensi

Kode asli: GNU GPLv3 — © EA31337 Ltd. (kenorb). Modifikasi/penataan ulang arsip ini tetap tunduk GPLv3.

## Disclaimer

Koleksi ini untuk edukasi & riset. Trading mengandung risiko tinggi — backtest & demo dulu sebelum live. Pastikan strategi yang dipakai sudah divalidasi.
