# 🛡️ Credit Card Fraud Detection Dashboard

[English Version](#english-version) | [Wersja Polska](#wersja-polska)

---

## English Version
### 📊 Project Overview
Analysis of 284,807 credit card transactions (Kaggle dataset - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) to detect fraud patterns. The project was built in **Power BI**, focusing on visualizing anomalies in PCA-transformed features (V1-V28).

### 📑 Report Structure (4 Pages)
1. **Executive Risk Overview**: Key Performance Indicators (492 fraud incidents) and general security statistics.
2. **Fraud Behavior Patterns**: Time and amount analysis. Using scatter charts to identify fraud clusters.
3. **Technical Signal Analysis**: Deep dive into **V17, V14, and V12** variables. Demonstrating significant mean deviations for fraudulent transactions.
4. **Investigator Case Tool**: An interactive forensic tool with raw data, utilizing conditional formatting for rapid risk identification.

### 🛠️ Technical Implementation
* **DAX**: Aggregation measures, averages, and context filters.
* **Data Modeling**: Optimized `creditcard` table with high-precision decimal formatting (4 places).
* **UX/UI**: Overlay techniques and custom marker formatting for better visibility.

### [📷 See screnshots](./Screenshots/)
---

## Wersja Polska
### 📊 O projekcie
Analiza 284,807 transakcji kartowych (zbiór danych Kaggle - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) w celu wykrycia wzorców oszustw. Projekt wykonany w **Power BI**, skupiający się na wizualizacji anomalii w zmiennych po transformacji PCA (V1-V28).

### 📑 Struktura Raportu (4 Strony)
1. **Executive Risk Overview**: Główne wskaźniki KPI (492 incydenty) i ogólna statystyka bezpieczeństwa.
2. **Fraud Behavior Patterns**: Analiza czasowa i kwotowa. Wykorzystanie wykresu punktowego do identyfikacji skupisk oszustw.
3. **Technical Signal Analysis**: Głęboka analiza techniczna zmiennych **V17, V14 i V12**. Wykazanie drastycznych różnic w średnich wartościach dla transakcji typu Fraud.
4. **Investigator Case Tool**: Interaktywne narzędzie śledcze z surowymi danymi, wykorzystujące formatowanie warunkowe dla szybkiej identyfikacji ryzyka.

### 🛠️ Wykorzystane techniki
* **DAX**: Miary sumujące, średnie i filtry kontekstowe.
* **Modelowanie danych**: Optymalizacja tabeli `creditcard` i ustawienie precyzji (4 miejsca po przecinku).
* **UX/UI**: Techniki nakładania warstw (Overlay) oraz autorskie formatowanie znaczników dla lepszej czytelności.

### [📷 Zobacz zrzuty ekranu raportu](./Screenshots/)


---
*Created as a demonstration of data analysis and visualization skills in Power BI.*
