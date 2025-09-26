# Econometrics Term Paper Project 📊

Bu proje, **Yıldız Teknik Üniversitesi - İstatistik Bölümü** için hazırlanmış 
Ekonometrik analiz çalışmasını, kullanılan veri setini ve ek dosyaları içerir.  

## İçindekiler
- `econometrics.docx` → Term paper (rapor)
- `economics.csv` → Veri seti
- `ekler/` → Görseller ve ek materyaller
- `.gitignore` → Gereksiz dosyaları dışlamak için
- `README.md` → Proje açıklaması

## Analiz Özeti
Çalışmada **tüketim (PCE)** ile **işsizlik göstergeleri** arasındaki ilişki 
incelenmiştir. Farklı model denemeleri yapılmış, en iyi sonuç **Log-Lin model** ile elde edilmiştir.

- 📈 **R² = 0.90** → Çok güçlü açıklama gücü  
- ❗ **DW ≈ 0.33** → Pozitif otokorelasyon tespit edildi  
- 📉 **PSAVERT (tasarruf oranı)** ↑ **Tüketim** ↓  
- 👥 **UEMPMED ve UNEMPLOY** ↑ **Tüketim** ↑ 

## Kullanılan Yöntemler ve Yazılımlar
**EViews** (ekonometrik analizler için)
- Regresyon Modelleri: Lin-Lin, Log-Lin, Log-Log
- Birim kök testleri (ADF)
- Heteroskedastisite testleri (White, Park, Goldfeld-Quandt)
- Otokorelasyon testleri (Durbin-Watson, h-test)
- Yapısal kırılma testi (Chow Test, 2008 krizi)

## Nasıl Kullanılır
1. `economics.csv` dosyasını indir.
2. Veri seti **EViews** yazılımında veya Python/R ortamında analiz edilebilir.  
   - Python örneği:
     ```python
     import pandas as pd
     df = pd.read_csv("economics.csv")
     print(df.head())
     ```
3. Rapor (`.docx`) içeriği ve EViews çıktıları karşılaştırılarak incelenebilir.

## Lisans
📌 Bu proje eğitim amaçlıdır.
