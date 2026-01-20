# 🏭 PLC Data Deduplication

Endüstriyel PLC cihazlarından gelen tekrarlı verileri filtreleyen algoritma

## 📊 Problem

- PLC ~1 dakika dönüyor → Aynı jant 60+ kez okunuyor
- Günlük ~25.000 gereksiz SQL insert

## 💡 Çözüm

1. PLC protokolündeki 20+ field'ı analiz
2. Unique changing field tespiti
3. In-memory deduplication filter
4. %95 DB yükü azalması

## 🛠️ Tech Stack

- C# / .NET Worker Service
- MSSQL
- PLC Integration

## 🏢 Bağlam

Döktaş - Bilgi İşlem Stajı (2025)
