# 📊 Funds Dashboard (Python + Power BI)

Projekt do analizy i wizualizacji rentowności funduszy inwestycyjnych.  
Dane źródłowe pochodzą z plików Excel/CSV oraz kart funduszu (PDF), które następnie są przetwarzane i wizualizowane w Power BI.  
Część informacji jest pozyskiwana automatycznie z plików PDF za pomocą **Gemini API**.

---

## 📂 Struktura projektu

- **fundusze_get_data.ipynb** – główny notebook Jupyter  
- **1. Aktywa netto/**
  - `aktywa.xlsx`  
- **2. Benchmark/**
  - `benchmark.xlsx`  
- **3. Struktura aktywow/**
  - `struktura_aktywow.xlsx`  
- **4. Struktura geograficzna/**
  - `struktura_geograficzna.xlsx`  
- **5. Najwieksze pozycje w portfelu/**
  - `najw_poz_w_porfelu.xlsx`  
- **6. Alokacja sektorowa/**
  - `alokacja_sektorowa.xlsx`  
- **7. Waluty/**
  - `waluty.xlsx`  
- **Additional Tables/**
  - `extraInfo.csv`  
- **Karty funduszu/** – podfoldery = tickery funduszy  
  - `MIL27/2025-04-30.pdf`  
  - `ING43/2025-07-31.pdf`
  - `.../....pdf`
- **Notowania/**
  - `dane.csv` 
- **Zwrot od Gemini/** – odpowiedzi Gemini (per ticker)  
  - `MIL27/...`  
  - `ING43/...`
  - `.../...`
